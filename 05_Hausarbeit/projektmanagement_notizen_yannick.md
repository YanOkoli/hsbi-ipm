# Hausarbeitsentwurf: Kapitel 2 Projektmanagement

> **Arbeitsstand:** Entwurf auf Grundlage der Lehrbriefe und der bisher dokumentierten Projektunterlagen. Geplante oder noch nicht bestätigte Inhalte sind entsprechend gekennzeichnet.

## 2 Projektmanagement

Dieses Kapitel beschreibt, wie das Projekt „KI-gestütztes Variantenmanagement“ initialisiert, strukturiert und gesteuert wird. Im Mittelpunkt stehen der Projektauftrag und die Zielsetzung, die Organisation eines siebenköpfigen Teams, die Planung der Arbeitspakete und Meilensteine sowie das Vorgehen zur Fortschritts- und Risikokontrolle.

Die Lehrbriefe beschreiben Projektmanagement als die Planung, Durchführung, Überwachung und Steuerung eines zeitlich begrenzten, einmaligen Vorhabens. Für das vorliegende Projekt ist insbesondere wichtig, die zunächst breite Aufgabenstellung so abzugrenzen, dass ein fachlich nachvollziehbares und im verfügbaren Semesterzeitraum bearbeitbares Ergebnis entsteht. Da Produktgruppe, Datenzugang und technischer Reifegrad zum dokumentierten Stand noch nicht verbindlich festgelegt waren, ist die Planung teilweise als Arbeitsvorschlag zu verstehen.

## 2.1 Projektauftrag und Zielsetzung

Ausgangspunkt ist die Aufgabenstellung „Thema 6 – Variantenmanagement“. Sie fordert, einen möglichen KI-Agenten zu betrachten, der anhand von Stücklisten, Portfolioübersichten sowie Merkmalsanforderungen und -ausprägungen wirtschaftlich sinnvolle Varianten generiert. Dabei sollen ausreichende Marktvarianz und Kundenerwartungen mit wettbewerbsfähiger Fertigung und der Begrenzung interner Komplexität in Einklang gebracht werden.

Das Team hat daraus als zentrale Problemstellung abgeleitet, dass eine hohe Zahl kundenrelevanter Varianten die Marktabdeckung verbessern kann, zugleich aber zusätzliche Teile-, Beschaffungs-, Lager- und Fertigungskomplexität verursachen kann. Das Ziel ist deshalb nicht die pauschale Verringerung der Variantenzahl. Untersucht werden soll vielmehr, wie Varianten nach ihrem Beitrag für Kunden und Markt sowie nach ihrer Wirtschaftlichkeit und ihren Auswirkungen auf die Fertigung beurteilt werden können.

Als Arbeitsziel wird ein begründetes Konzept für eine KI-gestützte Entscheidungshilfe verfolgt. Der aktuelle technische Vorschlag ist ein Wrapper um ein bestehendes KI-Modell; ein eigenes Modelltraining ist nicht vorgesehen. Dieser Ansatz und der erwartete Reifegrad des Ergebnisses müssen noch mit dem Projektbetreuer abgestimmt werden. Die fachliche Verantwortung für Portfolioentscheidungen soll bei den zuständigen Personen verbleiben.

Nach den Lehrbriefen sollen Projektziele präzise, überprüfbar, realistisch, priorisiert und möglichst lösungsneutral formuliert werden. Für dieses Projekt sind die fachlichen Zielrichtungen klar, konkrete Messgrößen jedoch noch festzulegen. Vor allem müssen die Produktgruppe, die verfügbare Datenbasis sowie Kriterien und mögliche Gewichtungen für die Bewertung abgestimmt werden. Erst danach lässt sich ein belastbares Abnahmekriterium für den Demonstrator definieren.

| Zielgröße des magischen Dreiecks | Bedeutung für das Projekt |
| --- | --- |
| Leistung und Qualität | Ein fachlich nachvollziehbares Variantenmanagement-Konzept mit geeignetem Produktfall, Bewertungslogik und gegebenenfalls Demonstrator |
| Zeit | Erste Projektpräsentation am 11.11.2026, Abschlusspräsentation am 17.12.2026 und Hausarbeitsabgabe am 15.01.2027 laut Planung |
| Ressourcen | Arbeitszeit des siebenköpfigen Teams, Zugang zu geeigneten Daten und verfügbare Werkzeuge bzw. Modellzugänge; ein bestätigtes Budget ist nicht dokumentiert |

Änderungen an einer Zielgröße können die übrigen beeinflussen. Beispielsweise kann ein größerer technischer Umfang angesichts der festen Präsentations- und Abgabetermine zusätzlichen Aufwand verursachen. Deshalb soll der Projektumfang nach dem Betreuergespräch an die verfügbare Zeit, Datenlage und Teamkapazität angepasst werden.

## 2.2 Projektorganisation und Rollenverteilung

Das Projektteam besteht nach aktueller Angabe aus sieben Personen; die Nummer 6 bezeichnet die Projektgruppe. Die Projektleitung liegt bei mir. Zu den Aufgaben der Projektleitung gehören die übergreifende Koordination, die Termin- und Fortschrittsverfolgung, die Vorbereitung von Abstimmungen, die Dokumentation von Entscheidungen und Risiken sowie die Zusammenführung der Teilprojektergebnisse.

Die Timeline schlägt vier miteinander verbundene Teilprojekte vor. Diese Aufteilung berücksichtigt, dass fachliche Bewertungsmethodik, Produktfall, Datenmodell und KI-Workflow voneinander abhängen.

| Teilprojekt | Schwerpunkt und Ergebnis |
| --- | --- |
| TP 1: Projektkoordination | Termine, Teamabstimmungen, Statusberichte, Risiken und Präsentationskoordination |
| TP 2: Variantenmanagement und Methodik | Fachgrundlagen, Zielkonflikt, Kennzahlen und begründetes Bewertungsmodell |
| TP 3: KI-Agent und Datenlogik | Daten- und Merkmalsmodell, Wrapper-Workflow, Eingabe- und Ausgabeformat sowie gegebenenfalls Demonstrator |
| TP 4: Produktfall und Wirtschaftlichkeit | Auswahl der Produktgruppe, Kunden- und Marktsicht, Wettbewerb sowie Fertigungs- und Wirtschaftlichkeitsbetrachtung |

Für einzelne Aufgaben nennt der KW45-Bericht vorläufige Zuständigkeiten: Lukas H. für die Roadmap, David W. für die methodische Vorbereitung und Jonas F. für die erste Projektpräsentation. Yannick O. ist dort für die Abstimmung mit dem Betreuer vorgesehen. Die dauerhafte Verteilung der Rollen ist noch nicht bestätigt; drei weitere Teammitglieder sind in den vorhandenen Notizen nicht namentlich aufgeführt. Die Rollenverteilung ist daher nach dem Betreuergespräch gemeinsam festzulegen.

Da die Teilprojekte Schnittstellen besitzen, sollen Zwischenergebnisse regelmäßig abgeglichen werden. Insbesondere hängen die Auswahl der Bewertungsmethode und die Entwicklung des Datenmodells von der Produktgruppe und der Datenverfügbarkeit ab. Die Projektleitung koordiniert diese Abhängigkeiten, während fachliche Annahmen und Bewertungen durch die jeweils zuständigen Teammitglieder geprüft werden.

## 2.3 Projektstrukturplanung und Vorgehensmodell

Der Projektstrukturplan zerlegt das Gesamtvorhaben hierarchisch in Teilprojekte, Aufgaben und Arbeitspakete. Er beantwortet die Frage, welche Arbeiten für das Projekt erforderlich sind. Darauf aufbauend können Verantwortlichkeiten, Termine, Ressourcen, Abhängigkeiten und Risiken geplant werden.

Der für das Team erstellte PSP-Entwurf umfasst vier Teilprojekte: Projektkoordination und Dokumentation, Variantenmanagement und Bewertungsmethodik, Datenmodell und KI-Wrapper sowie Produktfall und Wirtschaftlichkeit. Er führt unter anderem die Klärung von Projektziel und Umfang, die Auswahl einer Produktgruppe, die Definition von Merkmalen und Kennzahlen, die Entwicklung des Wrapper-Workflows sowie die Demonstration und Validierung auf.

Ein Arbeitspaket soll nach den Lehrbriefen eine klar abgegrenzte Aufgabe mit einem überprüfbaren Ergebnis sein. Für die weitere Planung sollten je Arbeitspaket mindestens Ziel, verantwortliche Person, Beteiligte, Termin, Ergebnis, Voraussetzungen, Schnittstellen und Abnahmekriterium festgehalten werden. Beispielhaft kann das Arbeitspaket „Bewertungsmodell entwickeln“ als abgeschlossen gelten, wenn die Kriterien definiert, Datenquellen oder Annahmen dokumentiert, Gewichtungen begründet und die Methode an einem Beispiel angewendet wurden. Die konkrete Ausgestaltung ist noch mit dem Team abzustimmen.

Das geplante Vorgehen folgt den Projektphasen aus den Lehrbriefen und der vorhandenen Timeline:

1. **Initialisierung und Abgrenzung:** Aufgabenstellung analysieren, Ergebnisumfang, Produktgruppe und Datenrahmen mit dem Betreuer klären.
2. **Planung und Modellierung:** Teamorganisation und PSP festlegen; Merkmale, Kennzahlen und Bewertungsanforderungen bestimmen.
3. **Konzeption:** Bewertungsmethode und Wrapper-Workflow für ein bestehendes KI-Modell ausarbeiten.
4. **Demonstration und Überprüfung:** Konzept mit geeigneten Beispiel-, anonymisierten oder synthetischen Daten erproben, Ergebnisse plausibilisieren und Grenzen dokumentieren.
5. **Abschluss:** Präsentation, Hausarbeit und Lessons Learned erstellen.

Die Phasen bauen fachlich aufeinander auf. Eine verspätete Auswahl der Produktgruppe oder eine ungeklärte Datenfreigabe kann deshalb die Modellierung, Demonstration und Ergebnisvalidierung verzögern.

## 2.4 Terminplanung und Meilensteine

Die Roadmap strukturiert die Arbeit von KW45 bis zur Hausarbeitsabgabe. Die dort aufgeführten Termine sind Plantermine; sie belegen nicht, dass die jeweiligen Ergebnisse bereits erreicht wurden.

| Zeitraum | Geplante Arbeit und Ergebnis |
| --- | --- |
| KW45–46 | Projektstart, Betreuerabstimmung und Projektabgrenzung; erste Präsentation am 11.11.2026 bis 18:00 Uhr |
| KW47 | Produkt- und Datenmodell, Merkmale und Bewertungskriterien |
| KW48 | Auswahl und Begründung der Methodik sowie Konzept des KI-Workflows |
| KW49, bis 06.12.2026 | Demonstrierbarer Workflow bzw. Mock-up, Variantenbewertung und mindestens ein Szenariovergleich laut Planung |
| KW50 | Plausibilitätsprüfung, Dokumentation von Annahmen und Grenzen, Präsentationsentwurf und Gliederung der Hausarbeit |
| KW51, 17.12.2026 | Abschlusspräsentation und Review |
| KW52 bis KW2, bis 15.01.2027 | Rohfassung, Finalisierung und Abgabe der Hausarbeit |

Die Ablaufplanung soll zusätzlich die sachlogischen Abhängigkeiten sichtbar machen: Erst nach der Projektabgrenzung können Produktgruppe und Datenmodell verbindlich bearbeitet werden; Bewertungsmodell und Datenmodell bilden anschließend die Grundlage für den Wrapper-Workflow und die Demonstration. Die Teamleitung soll Fortschritt und Terminprognosen regelmäßig prüfen und die Roadmap aktualisieren, falls sich Umfang oder Voraussetzungen ändern.

## 2.5 Projektsteuerung und Kommunikation

Projektcontrolling vergleicht den geplanten Stand mit dem tatsächlichen Fortschritt, analysiert Abweichungen und leitet bei Bedarf Maßnahmen ein. Die Lehrbriefe unterscheiden dabei Plan, Soll, Ist und Trend. Für das Projekt bedeutet das: Die Roadmap bildet den groben Plan, konkrete Arbeitspakete erhalten Soll-Termine, der Wochenbericht dokumentiert den Ist-Stand und eine Einschätzung des Trends macht drohende Verzögerungen frühzeitig sichtbar.

Der KW45-Bericht dokumentiert die Anforderungs- und Planungsphase, die erste Erkenntnis zum Zielkonflikt sowie offene Fragen zu Produktgruppe, Daten, Bewertung und technischem Umfang. Als mögliche Steuerungsroutine sieht die Projektplanung regelmäßige Teamabstimmungen und One-Pager bzw. Wochenberichte vor. Im weiteren Projektverlauf sollte jeder Bericht kurz festhalten:

- erledigte Ergebnisse und deren Abnahmestatus,
- Arbeitspaket, verantwortliche Person und nächsten Zieltermin,
- Plan-Ist-Abweichungen und erwarteten Trend,
- Risiken, Blockaden und benötigte Entscheidungen,
- beschlossene Änderungen mit Datum und Verantwortlichkeit.

Ein wöchentlicher Arbeitszyklus mit Aufgabenplanung, kurzem Status, Ergebnisreview und Retrospektive wäre für das Semesterprojekt geeignet. Er ist als Vorschlag zu verstehen, solange die tatsächliche Meetingfrequenz und Kommunikationsroutine nicht dokumentiert ist. Entscheidungen des Betreuers und Änderungen am Projektumfang sollten schriftlich festgehalten werden, damit die Teammitglieder mit demselben Informationsstand arbeiten.

## 2.6 Ressourcen- und Risikomanagement

Die wichtigste Ressource des Projekts ist die verfügbare Arbeitszeit der sieben Teammitglieder. Weitere Voraussetzungen sind ein geeigneter Produktfall, eine verwendbare Datenbasis sowie Zugang zu einem bestehenden KI-Modell oder einer zulässigen Alternative. Ein finanzieller Budgetrahmen ist in den vorliegenden Unterlagen nicht dokumentiert. Deshalb sollten Modellzugang, mögliche Kosten und Datenschutzanforderungen vor einer technischen Demonstration geprüft werden.

Die wichtigsten Risiken in der aktuellen Planungsphase ergeben sich aus noch offenen Anforderungen und Abhängigkeiten:

| Risiko | Mögliche Auswirkung | Vorgeschlagene Maßnahme |
| --- | --- | --- |
| Produktgruppe oder Ergebnisumfang wird zu spät festgelegt | Datenmodell und Demonstration verzögern sich | Entscheidungen im Betreuergespräch priorisieren und protokollieren |
| Geeignete Daten sind nicht verfügbar oder nicht freigegeben | Bewertungsmodell lässt sich nicht realitätsnah prüfen | Synthetische oder anonymisierte Beispieldaten als Alternative abstimmen |
| Bewertungskriterien oder Gewichtungen bleiben unklar | Empfehlungen sind schwer nachvollziehbar | Kriterien, Skalen, Annahmen und Freigabe gemeinsam festlegen |
| Umfang wächst über die verfügbare Zeit hinaus | Präsentations- und Abgabetermine geraten unter Druck | Mindestumfang definieren und Erweiterungen nach Priorität zurückstellen |
| Modellanbieter kann Daten nicht zulässig verarbeiten oder verursacht unerwarteten Aufwand | Wrapper-Demonstration wird blockiert | Anbieter, Datenschutz, Nutzungsbedingungen und lokale Alternativen früh prüfen |
| Aufgaben oder Wissen konzentrieren sich auf einzelne Personen | Ausfall oder Verzögerung an einer Schnittstelle | Ergebnisse dokumentieren und Review bzw. Vertretung im Team organisieren |

Die Tabelle stellt eine erste qualitative Risikoübersicht dar, keine abschließend bewertete Risikomatrix. Eintrittswahrscheinlichkeit, Auswirkung, verantwortliche Person und Status sollten in den regelmäßigen Projektberichten ergänzt und aktualisiert werden.

## 2.7 Vorläufige Reflexion und Lessons Learned

Zum dokumentierten Stand befindet sich das Team noch am Anfang der Anforderungs- und Planungsphase. Eine abschließende Bewertung der Projektorganisation oder des Projekterfolgs wäre daher verfrüht. Bereits erkennbar ist jedoch, dass die Aufgabenstellung mehrere Perspektiven verbindet: Markt- und Kundennutzen, Wirtschaftlichkeit, Datenqualität und Fertigungskomplexität müssen gemeinsam betrachtet werden.

Eine wichtige frühe Erkenntnis ist, dass Variantenmanagement nicht mit einer pauschalen Reduzierung des Sortiments gleichgesetzt werden kann. Vor der Auswahl einer technischen Methode müssen zunächst Produktgruppe, Daten und Kriterien konkretisiert werden. Das entspricht dem in den Lehrbriefen beschriebenen Vorgehen, zuerst Problem, Ziele und Projektumfang zu klären und erst darauf aufbauend Lösungen und Arbeitspakete zu planen.

Die eigentlichen Lessons Learned sollten während des Projekts und nach den Meilensteinen ergänzt werden. Dafür bieten sich regelmäßige Retrospektiven mit den Fragen an, was gut funktioniert hat, welche Hindernisse auftraten, wodurch sie verursacht wurden und welche konkrete Maßnahme mit Verantwortlichkeit und Termin folgt. Die Abschlussreflexion sollte erst nach der Präsentation und Validierung der Ergebnisse formuliert werden.

## Hinweise zur Fertigstellung des Kapitels

Vor Abgabe dieses Entwurfs sind noch tatsächliche Ergebnisse einzutragen: Betreuergespräch und Entscheidungen, endgültige Teamrollen und Namen, gewählte Produktgruppe, freigegebene Datenbasis, beschlossene Methode, tatsächliche Meeting- und Berichtsroutine, Plan-Ist-Abweichungen sowie Lessons Learned. Außerdem müssen die Lehrbriefe nach den formalen Zitierregeln des Moduls vollständig bibliografiert und im Text belegt werden; die vorliegende Zusammenfassung allein enthält keine ausreichenden bibliografischen Angaben oder Seitenzahlen.
