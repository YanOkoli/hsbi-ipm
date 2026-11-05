# Entwurf Pflichtenheft: KI-gestütztes Variantenmanagement

> **Status:** Diskussionsentwurf für die Anforderungsanalyse, noch nicht mit Steffen Feld abgestimmt.

**Version:** 0.3  
**Stand:** 05.11.2026  
**Projektteam:** 6

## 1. Ziel

- Ein wirtschaftlich sinnvolles Produktvarianten-Portfolio unterstützen.
- Kundennutzen und Marktabdeckung gegen Wirtschaftlichkeit und Fertigungskomplexität abwägen.
- Varianten oder Portfolio-Szenarien nachvollziehbar bewerten und vorschlagen.
- Die fachliche Prüfung und endgültige Entscheidung beim Menschen belassen.

## 2. Lösungsvorschlag: Wrapper um ein bestehendes KI-Modell

- **Kein eigenes Training oder Fine-Tuning:** Ein bestehendes, vortrainiertes Modell wird eingebunden.
- **Wrapper:** Prüft und strukturiert Eingaben, ergänzt Regeln und Kontext, steuert den Modellaufruf und kontrolliert die Ausgabe.
- **KI-Modell:** Unterstützt bei Einordnung und verständlicher Erklärung; es erfindet keine fehlenden Daten.
- **Bewertungen:** Kennzahlen und Regeln werden soweit möglich nachvollziehbar berechnet, nicht vom Sprachmodell geschätzt.
- **Ablauf:** Daten prüfen → Varianten bewerten → Ergebnisse erklären → fachlich freigeben.
- **Noch offen:** Externer Modellanbieter oder lokaler Betrieb. Reale Unternehmensdaten erst nach Klärung von Datenschutz, Vertraulichkeit und Freigabe verwenden.

## 3. Vorgesehener Umfang

- Ein mit dem Betreuer abgestimmter Produktfall.
- Strukturierte Daten zu Varianten, Merkmalen und, soweit verfügbar, Stücklisten.
- Bewertung von Markt/Kundennutzen, Wirtschaftlichkeit und Fertigungskomplexität.
- Vergleich des bestehenden Portfolios mit mindestens einem Alternativszenario, sofern die Daten es zulassen.
- Ein demonstrierbarer Workflow oder Prototyp; der erwartete Reifegrad ist noch zu bestätigen.

**Nicht vorgesehen:** eigenes Modelltraining, autonome Portfolioentscheidungen oder eine produktive ERP-/PLM-Integration. Ein globales mathematisches Optimum wird nicht behauptet, solange Zielfunktion, Nebenbedingungen und Daten nicht festgelegt sind.

## 4. Funktionale Anforderungen

Prioritäten und Umfang sind Vorschläge zur Abstimmung:

- **Muss:** Produktvarianten, Merkmale und freigegebene Stücklisten in einem abgestimmten Format verarbeiten.
- **Muss:** Fehlende, ungültige oder widersprüchliche Eingaben markieren.
- **Muss:** Markt/Kundennutzen, Wirtschaftlichkeit und Fertigungskomplexität getrennt bewerten.
- **Muss:** Empfehlungen mit Kennzahlen, Regeln, Annahmen und Datenlücken begründen.
- **Soll:** Ausgangsportfolio und Alternativszenarien vergleichen; neue Varianten nur aus erlaubten Merkmalskombinationen ableiten.
- **Kann:** Anforderungen dialogbasiert aufnehmen und vor der Bewertung bestätigen lassen.

## 5. Daten und Bewertungslogik

**Benötigte Daten, soweit verfügbar:**

- Varianten-ID, Produktfamilie, Merkmale und erlaubte Ausprägungen.
- Stücklisten, Teile-IDs, Gleichteile und Sonderteile.
- Fertigungsinformationen, etwa Prozessschritte, Rüstaufwand oder Engpässe.
- Nachfrage-/Absatzdaten, Kundenanforderungen und Marktindikatoren.
- Preise, Deckungsbeiträge oder abgestimmte Wirtschaftlichkeitskennzahlen.
- Technische, regulatorische oder produktionsbezogene Einschränkungen.

**Freigabe:** Datenverfügbarkeit und Nutzungsrechte sind offen. Reale Unternehmensdaten nur mit Freigabe nutzen; anonymisierte oder synthetische Beispieldaten mit Steffen abstimmen.

**Vorgeschlagene Bewertung:**

- Harte Anforderungen und unzulässige Kombinationen zuerst regelbasiert prüfen.
- Varianten anhand getrennter Kriterien für Markt/Kunde, Wirtschaftlichkeit und Fertigung vergleichen.
- Kriterien, Skalen, Gewichtungen und fehlende Werte offenlegen; Gewichtungen nicht vom Modell erfinden lassen.
- Rangfolge oder Szenarien samt Einzelwirkungen ausgeben, nicht nur einen Gesamtscore.
- Die konkrete Methode erst nach Auswahl der Produktgruppe und Prüfung der Datenbasis festlegen.

## 6. Qualitätsanforderungen

- **Nachvollziehbar:** Eingaben, Regeln und Berechnungsschritte zu jeder Empfehlung anzeigen.
- **Reproduzierbar:** Identische Daten und Kriterien ergeben identische Kennzahlen.
- **Unsicherheit kenntlich machen:** Fehlende Daten und Annahmen markieren.
- **Datenschutz beachten:** Nur notwendige Daten verarbeiten; externe Übermittlung nur nach Freigabe.
- **Wartbar halten:** Daten, Bewertungsregeln und Modellanbindung getrennt halten.
- **Menschliche Kontrolle:** Ergebnisse sind Empfehlungen und werden fachlich geprüft.

## 7. Vorgeschlagene Abnahmekriterien

- Beispieldaten werden eingelesen und auf Datenprobleme geprüft.
- Mindestens zwei Varianten oder Szenarien werden anhand dokumentierter Kriterien verglichen.
- Markt/Kunde, Wirtschaftlichkeit und Fertigung werden getrennt ausgewiesen, soweit die Daten reichen.
- Die Ausgabe enthält Begründungen, Annahmen und Datenlücken.
- Die Einbindung des bestehenden Modells über den Wrapper wird demonstriert; es gibt kein Modelltraining.
- Empfehlungen werden nicht als verbindliche oder garantiert optimale Entscheidungen ausgegeben.

Die Zahl der Varianten, Testfälle und quantitativen Erfolgsschwellen ist festzulegen, sobald Produktgruppe und Datenbasis bekannt sind.

## 8. Im ersten Meeting mit Steffen zu klären

- Ist der Wrapper-Ansatz geeignet, und welcher Reifegrad wird erwartet: Konzept, Mock-up oder Demonstrator?
- Soll das System bestehende Varianten bewerten, neue vorschlagen oder beides?
- Welche Produktgruppe und welche Daten sind geeignet und freigegeben? Reichen synthetische oder anonymisierte Daten?
- Welche Kriterien und Gewichtungen sollen Markt/Kunde, Wirtschaftlichkeit und Fertigung abbilden?
- Welche Vorgaben gelten für Modellanbieter, Datenschutz, Sonderfälle und fachliche Freigabe?

## 9. Kurzvorstellung

> Wir möchten kein eigenes Modell trainieren, sondern einen Wrapper um ein bestehendes KI-Modell bauen. Der Wrapper prüft die Daten und wendet nachvollziehbare Bewertungsregeln an; die KI unterstützt bei Einordnung und Erklärung. Heute möchten wir Produktfall, Datenfreigabe und erwarteten Demonstrationsumfang abstimmen.
