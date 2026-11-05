# Projektkontext: KI-gestütztes Variantenmanagement

**Stand der Zusammenfassung:** 05.11.2026  
**Modul:** Projekt- und Innovationsmanagement  
**Projektgruppe:** 6  
**Teamgröße:** 7 Personen  
**Projektleitung:** Nutzer  
**Projektbetreuer:** Steffen Feld

Diese Datei ist der Einstiegspunkt für Teammitglieder und spätere Assistenz. Sie bündelt den belegten Projektstand, hält offene Punkte sichtbar und zeigt, woher die Informationen stammen. Bei Abweichungen gilt die jeweils neueste dokumentierte Teamentscheidung; Planungen und Entwürfe sind keine Beschlüsse.

## Kurzüberblick

- **Thema:** Variantenmanagement. Untersucht wird, wie ein KI-Agent Unternehmen dabei unterstützen kann, ein wirtschaftlich sinnvolles Produktportfolio zu gestalten.
- **Zielkonflikt:** Genügend marktgerechte, kundennützliche Varianten anbieten, ohne durch interne Teile- und Fertigungsvielfalt Wettbewerbsfähigkeit und Skaleneffekte zu verlieren.
- **Aufgabenidee:** Produktgruppe anhand von Merkmalen, Merkmalsausprägungen, Portfolio- und Stücklisteninformationen analysieren und ein begründetes Variantenoptimum erarbeiten.
- **Wichtig:** Das Projekt zielt nicht auf eine pauschale Reduktion der Variantenanzahl. Marktbeitrag und interne Komplexität müssen gemeinsam betrachtet werden.
- **Aktueller Reifegrad:** Anforderungs- und Planungsphase. Produktgruppe, Datenzugang, Bewertungskriterien und erwarteter technischer Umfang sind in den vorhandenen Notizen noch nicht verbindlich entschieden.

## Status und nächste Termine

Stand 05.11.2026: Die Aufgabenstellung wurde besprochen, ein erster Fragenkatalog und Grundlagen zur Variantenmanagement-Methodik liegen vor. Ein Gespräch mit Steffen Feld ist angefragt, ein bestätigter Termin ist in den Notizen nicht dokumentiert. Die Zuständigkeiten und Kontaktdaten sollten laut KW45-Bericht bereits an den Dozenten zurückgemeldet worden sein; Beleg dafür ist der Wochenbericht.

| Termin | Bedeutung laut Planung |
| --- | --- |
| 06.11.2026 | Interne Vorbereitung bzw. erster Entwurf der Präsentation und Roadmap laut KW45-To-dos und Wochenbericht |
| 11.11.2026, 18:00 Uhr | Abgabe der ersten Projektpräsentation per E-Mail an den Dozenten |
| KW 46 | Betreuergespräch und Projektabgrenzung geplant; Gesprächsergebnis noch nicht dokumentiert |
| 06.12.2026 | Deadline Konzeptentwicklung laut Timeline |
| 17.12.2026 | Abschlusspräsentation laut Timeline |
| 15.01.2027 | Abgabe der Hausarbeit laut Timeline |

Termine nach dem Standdatum sind Plantermine und sollten bei jeder Aktualisierung geprüft werden. Der Termin 16.01.2026 aus der fremden Beispielarbeit gehört nicht zu diesem Projekt.

## Was ist offen?

Diese Punkte müssen vor einer belastbaren Agenten- oder Bewertungslogik geklärt werden:

1. **Ergebnisumfang:** Konzept, demonstrierbarer Prototyp oder funktionsfähiger Agent?
2. **Agentenaufgabe:** Bestehende Varianten bewerten, neue Varianten vorschlagen oder beides?
3. **Produktgruppe:** Noch nicht ausgewählt. Kartonagen/Verpackungen sind lediglich als Frage für das Betreuergespräch notiert, nicht als Entscheidung.
4. **Daten:** Reale, anonymisierte oder synthetische Daten? Welche Merkmale, Stücklisten, Nachfrage-, Kunden-, Wettbewerbs- und Kostendaten sind verfügbar und zulässig?
5. **Bewertung:** Wie werden Kundennutzen/Marktabdeckung, Wettbewerb, Deckungsbeitrag und Fertigungskomplexität gemessen und gegeneinander gewichtet?
6. **Ausgabe und Validierung:** Erwartetes Ausgabeformat, Sonderfälle, Plausibilitätsprüfung und Rolle der menschlichen Fachentscheidung.

Der Gesprächsfragenkatalog in [01_Projektgrundlagen/gespraechsfragen_steffen_feld.md](01_Projektgrundlagen/gespraechsfragen_steffen_feld.md) deckt diese Klärung ab. Nach dem Gespräch sollten Antworten als Entscheidungen mit Datum und Quelle ergänzt werden.

Der [Entwurf des Pflichtenhefts](01_Projektgrundlagen/entwurf_pflichtenheft_ki_variantenmanagement.md) schlägt einen Wrapper um ein bestehendes KI-Modell ohne Training oder Fine-Tuning vor. Er ist eine Gesprächsgrundlage; die Produktgruppe, Datenfreigabe, Bewertungslogik und der erwartete Demonstrationsumfang bleiben offen.

## Arbeitsannahmen und mögliche Methodik

Die folgenden Punkte sind Recherche- und Konzeptideen, keine ausgewählten Verfahren:

- Produkt- und Merkmalsstruktur erfassen; kundenwahrnehmbare Vielfalt von interner Teile- und Prozessvielfalt unterscheiden.
- Varianten nach Absatz/Volumen, Deckungsbeitrag und Komplexität analysieren, zum Beispiel mit ABC/Pareto oder ABC/XYZ.
- Gleichteile, modulare Baukästen, Plattformen und Postponement als mögliche Hebel untersuchen.
- Variantenkosten bzw. Komplexitätskosten sichtbar machen und Szenarien einer Portfolioänderung vergleichen.
- Ein transparentes Scoring oder ein Operations-Research-Modell nur wählen, wenn Daten und Kriterien das tragen; Gewichtungen und Annahmen offenlegen.
- Association Rules und Merkmalsklassifikation stehen als Rechercheansätze in den frühen To-dos, wurden aber weder spezifiziert noch bestätigt.
- Eine mögliche KI-Lösung sollte nachvollziehbar unterstützen, statt ohne fachliche Prüfung autonom über das Portfolio zu entscheiden. Diese Ausrichtung ist ein Vorschlag aus dem persönlichen Hausarbeitsentwurf und muss mit dem Betreuer abgeglichen werden.

Die Recherche hebt als Grundlagen Modularisierung, Mass Customization, Entkopplungspunkt/Postponement, Variantenkosten und regelbasierte Konfiguration hervor. Sie benennt zudem Datenqualität, Transparenz, Datenschutz und fachliche Validierung als Grenzen bzw. Voraussetzungen.

## Team und Organisation

Die Timeline schlägt vier Teilprojekte vor. Ein dazu passender [PSP-Entwurf](02_Planung/projektstrukturplan_entwurf.md) ergänzt Arbeitspakete, Ergebnisse und einen Verteilungsvorschlag für sieben Personen. Die Besetzung ist noch nicht vom Team bestätigt.

| Teilprojekt (Vorschlag) | Aufgabenbereich |
| --- | --- |
| Projektkoordination | Termine, One-Pager, Wochenberichte, Meetings und Präsentationskoordination |
| Variantenmanagement und Methodik | Fachgrundlagen, Zielkonflikt, Kennzahlen und Bewertungsmodell |
| KI-Agent und Datenlogik | Datenmodell, Ein-/Ausgaben, Prompt oder Workflow, Demonstrator |
| Produktfall und Wirtschaftlichkeit | Produktgruppe, Markt- und Kundensicht, Fertigung und Wirtschaftlichkeit |

Im KW45-Bericht stehen vorläufige Aufgaben für einzelne nächste Schritte: Yannick O. für Betreuerabstimmung, Lukas H. für die Roadmap, Jonas F. für die erste Präsentation und David W. für die methodische Vorbereitung. Drei weitere Namen und die dauerhafte Rollenverteilung sind noch zu ergänzen bzw. zu bestätigen.

## Quellenkarte

| Datei | Inhalt und Verlässlichkeit |
| --- | --- |
| [01_Projektgrundlagen/aufgabenstellung.md](01_Projektgrundlagen/aufgabenstellung.md) | Primärquelle für den Auftrag „Thema 6 – Steffen Feld“; der überlieferte Text endet mitten im Satz. Fehlenden Wortlaut nicht ergänzen, sondern gegebenenfalls Original-Aufgabenstellung beschaffen. |
| [01_Projektgrundlagen/modul_aufgabenstellung.md](01_Projektgrundlagen/modul_aufgabenstellung.md) | Allgemeine Modul-Aufgabenstellung mit Rahmen, Abgabekriterien und vollständigem Wortlaut von Thema 6. |
| [01_Projektgrundlagen/gespraechsfragen_steffen_feld.md](01_Projektgrundlagen/gespraechsfragen_steffen_feld.md) | Fragen für die Projektabgrenzung; die Fragen sind nicht selbst Antworten oder Entscheidungen. |
| [01_Projektgrundlagen/entwurf_pflichtenheft_ki_variantenmanagement.md](01_Projektgrundlagen/entwurf_pflichtenheft_ki_variantenmanagement.md) | Diskussionsentwurf mit Wrapper-Ansatz, Anforderungen und offenen Punkten für das Betreuergespräch; noch nicht abgestimmt. |
| [02_Planung/roadmap_und_meilensteine.md](02_Planung/roadmap_und_meilensteine.md) | Projektphasen, geplante Meilensteine und Vorschlag für vier Teilprojekte. Planungsdokument, kein Nachweis erledigter Arbeit. |
| [02_Planung/projektstrukturplan_entwurf.md](02_Planung/projektstrukturplan_entwurf.md) | PSP-Entwurf mit Arbeitspaketen, Ergebnissen, vorläufiger Sieben-Personen-Verteilung und grober Terminzuordnung. |
| [02_Planung/todos_2026-10-30.md](02_Planung/todos_2026-10-30.md) | Frühe, teilweise unsortierte To-dos und methodische Ideen. |
| [02_Planung/todos_2026-11-06.md](02_Planung/todos_2026-11-06.md) | Ursprüngliche Datei war leer; enthält derzeit keine Aufgaben oder Beschlüsse. |
| [04_Statusberichte/kw45.md](04_Statusberichte/kw45.md) | Wochenbericht 27.10.–05.11.2026 mit Status, vorläufigen Zuständigkeiten und nächsten Schritten. Aktuellste dokumentierte Statusquelle im Bestand. |
| [04_Statusberichte/kw46_notizen.md](04_Statusberichte/kw46_notizen.md) | Beginnt mit „Anforderungsanalyse / Projektstrukturplan“ und enthält sonst keinen ausgearbeiteten Kontext. |
| [03_Recherche/variantenmanagement.md](03_Recherche/variantenmanagement.md) | Fachliche Einführung und Methodenübersicht zum Variantenmanagement sowie mögliche KI-Unterstützung. Literaturangaben und Aussagen vor Verwendung in der Hausarbeit prüfen und belastbar nachweisen. |
| [05_Hausarbeit/projektmanagement_notizen_yannick.md](05_Hausarbeit/projektmanagement_notizen_yannick.md) | Persönlicher Entwurf für einen Projektmanagement-Beitrag zur Hausarbeit. Enthält ausformulierte, teils prospektive Aussagen; nicht automatisch als bestätigter Projektverlauf übernehmen. |
| [99_Referenzen/beispielarbeit_chatbot_andere_gruppe.md](99_Referenzen/beispielarbeit_chatbot_andere_gruppe.md) | Vollständige Beispielarbeit zu einem HSBI-Einschreibungs-Chatbot aus einem anderen Semester und Projektteam. Nur Struktur-/Formatreferenz; sämtliche Projektfakten, Personen, Ergebnisse und Quellen sind fremd. |

## Vorsicht bei der Weiterverwendung

- Quellenstatus stets mitführen: **belegt**, **geplant**, **Vorschlag**, **offen** oder **erledigt**.
- In der fremden Beispielarbeit unter `99_Referenzen/` geht es um einen Chatbot zur Einschreibung, Zulassungsregeln, ECTS und Marketing. Das ist nicht das Variantenmanagement-Projekt.
- Der persönliche Entwurf in `05_Hausarbeit/` ist nützlich für eine mögliche Gliederung des Projektmanagement-Kapitels, aber Aussagen über Rollen, erreichte Ergebnisse oder Projektverlauf müssen mit den tatsächlichen Teamentscheidungen und späteren Berichten abgeglichen werden.
- Recherchetexte sind keine ausreichenden wissenschaftlichen Belege an sich. Originalquellen, genaue bibliografische Angaben und zitierte Aussagen prüfen.
- Dokumentiere neue Entscheidungen möglichst mit Datum, Ergebnis, Verantwortlichkeit und Verweis auf Protokoll oder Betreuerfeedback.