## Incident bearbeiten

[**Link zum Prozessmodell in ADONIS**](https://adonis.lhs.stuttgart.de/) [Aktualisierung mit individuellem Link]

### Festlegung von Prozessrahmen und Prozesseckdaten

#### Prozessrollen

- **Prozessmanager/in:** [GZ, Name]
- **Prozesseigner/in:** [GZ, Name]
- **Dezentrale Modellierung (konkrete Person):** [GZ, Name]
- **(Technische) Rolle Prozessanalyst/-modellierer:** [*40 Prozessanalyse/-modellierung*](https://adonis.lhs.stuttgart.de:8443/adonisnp?repoid=c0e28474-6a25-42ee-950b-dee17574158e&id=76487fcc-6e3f-4172-bc39-93d08bfa03d8&libObjID=38c98349-4425-40f7-8712-2d90e014228c&at=0&rid=76487fcc-6e3f-4172-bc39-93d08bfa03d8&t=nb&scenarioID=anp_scenario_1_design_and_document&lang=de) *(bei allen Prozessen im SVA)*
- **Rolle Methodischer Prüfer** (bei allen Prozessen der LHS): [*17-3.4 ADONIS-Team*](https://adonis.lhs.stuttgart.de:8443/adonisnp?repoid=c0e28474-6a25-42ee-950b-dee17574158e&id=fe39853e-01ad-432a-9a41-ed184283316d&libObjID=38c98349-4425-40f7-8712-2d90e014228c&at=0&rid=fe39853e-01ad-432a-9a41-ed184283316d&t=nb&scenarioID=anp_scenario_1_design_and_document&lang=de)

#### Ziel und Zweck des Prozesses

- Ziel ist die schnellstmögliche Wiederherstellung einer gestörten IT-Leistung im Umfeld des Schulverwaltungsamtes und die nachvollziehbare Dokumentation der Störungsbearbeitung.
- Kurzbeschreibung: Eine meldende Stelle (z.B. Schule oder Mitarbeitende des Schulverwaltungsamtes) meldet eine IT-Störung beim Servicedesk. Der Servicedesk erfasst, kategorisiert und priorisiert den Incident und übergibt ihn an die IT-Fachbetreuung. Diese analysiert die Ursache, setzt die Lösung um und testet sie. Der Servicedesk dokumentiert und schließt den Incident ab und informiert die meldende Stelle, die die Störungsbehebung prüft.
- **Gewünschte Detailtiefe („Flughöhe“) der Prozessdarstellung:** Regulärer Ablaufpfad (Happy Path) auf Ebene der fachlichen Aktivitäten je Rolle; Ausnahme- und Eskalationspfade sind nicht dargestellt.

#### Wann und wie wird der Prozess gestartet (= Startereignis)?

- Startereignis Kunde: „Stoerung festgestellt“. Die meldende Stelle stellt eine Störung einer IT-Leistung fest und meldet diese mit der Aktivität „Incident melden“ an den Servicedesk (Nachricht „Incident-Meldung mit Fehlerbeschreibung, betroffenem System und Kontaktdaten“).
- Startereignis Organisation: „Incident-Meldung eingegangen“ (Nachrichtenstart im Servicedesk).

#### Wann und wie endet der Prozess (= Endereignis)?

- Endereignis Kunde: „Stoerungsbehebung erhalten“, nachdem die meldende Stelle die Lösungsmitteilung erhalten und die Störungsbehebung geprüft hat.
- Endereignis Organisation: „Incident abgeschlossen“, nachdem der Servicedesk die meldende Stelle über die Lösung informiert hat.

#### Welche Personen/Rollen (GZ) sind am Prozess beteiligt (= Schwimmbahnen)?

- **Kunde:** Meldende Stelle [GZ]
- **Organisation:** Servicedesk [GZ]
- **Organisation:** IT-Fachbetreuung [GZ]

#### Zusammenstellung der Prozessgruppe für diesen Prozess

- [Name und GZ je Schwimmbahn (Meldende Stelle, Servicedesk, IT-Fachbetreuung) hier eintragen]
- Prozessgruppenmitglieder in dieses Unterprojekt aufnehmen

#### Welche IT-Anwendungen/-Lösungen werden genutzt?

- Ticketsystem zur Erfassung, Zuweisung, Dokumentation und zum Abschluss von Incidents [Produktname eintragen]
- [Weitere Anwendungen hier eintragen, z.B. Kommunikationskanal für Meldung und Lösungsmitteilung]

#### Bereits vorhandene Unterlagen / Materialien / Beschreibungen

- **Welche Dokumente, Materialien und sonstige Arbeitsmittel werden verwendet?**
  - [Bereitstellen/Hochladen der jeweiligen Dokumente/Dateien in dieses Unterprojekt, z.B. Kategorien- und Prioritätenmatrix]
- **Gibt es bereits Beschreibungen, Modelle oder sonstige Verschriftlichungen/Visualisierungen des Prozesses?**
  - [Bereitstellen/Hochladen/Verlinken in dieses Unterprojekt]

#### Prozessvarianten; vor- und nachgelagerte Prozesse

- **Gibt es Prozessvarianten, die für die Betrachtung dieses Modells relevant sind?**
  - [Link einfügen]
- **Gibt es vor- und nachgelagerte Prozesse, die sich auf dieses Modell relevant auswirken?**
  - [Link einfügen]

#### Teilprozesse / Übergeordnete/r Prozess/e

- [Falls TP vorhanden: Angabe und Verlinkung auf jeden einzelnen Teilprozess bzw. dessen Seite als Unterprojekt dieses Projekts in OpenProject]
- [Falls Darstellung eines Prozesses, der als Teilprozess verwendet wird: Angabe und Verlinkung jedes einzelnen (übergeordneten) Prozesses bzw. dessen Seite in OpenProject, in dem dieser Teilprozess aufgerufen wird]

### Key Performance Indicators (KPIs)

Die folgenden Kennzahlen dienen der Messung der Prozessleistung und werden in Prozess-KPIs (Gesamtbetrachtung) und Aktivitäts-KPIs (Schrittbetrachtung) unterteilt. Die Zielwerte sind Vorschläge und mit dem Prozessmanager abzustimmen.

#### 1. Prozess-KPIs (Ebene Gesamtprozess)

| KPI-ID | Kennzahl | Beschreibung | Zielwert | Messmethode |
| :--- | :--- | :--- | :--- | :--- |
| **P-KPI-01** | **Durchlaufzeit (Time-to-Resolution)** | Gesamtzeitdauer vom Eingang der Incident-Meldung bis zur Lösungsmitteilung an die meldende Stelle | Median < 1 Arbeitstag | Timestamp(Lösungsmitteilung versendet) – Timestamp(Ticket erfasst), ausgewertet je Priorität |
| **P-KPI-02** | **Prozessqualität (Erstlösungsquote)** | Anteil der Incidents, die ohne Wiedereröffnung oder erneute Meldung gelöst werden | > 90 % | Anzahl(Incidents ohne Wiedereröffnung) / Gesamtanzahl abgeschlossener Incidents |
| **P-KPI-03** | **Service-Level (SLA-Einhaltung)** | Anteil der Incidents, die innerhalb der für die jeweilige Priorität vereinbarten Lösungszeit gelöst werden | > 90 % | Anzahl(Lösungszeit eingehalten) / Gesamtanzahl abgeschlossener Incidents |
| **P-KPI-04** | **Dokumentationsquote** | Anteil der abgeschlossenen Incidents mit vollständig dokumentierter Ursache und Lösung | 100 % | Anzahl(Tickets mit befüllten Pflichtfeldern Ursache und Lösung) / Gesamtanzahl abgeschlossener Incidents |

#### 2. Aktivitäts-KPIs (Ebene Prozessschritte)

| Zugeordnete Aktivität(en) | KPI-Name | Beschreibung & Relevanz | Zielwert |
| :--- | :--- | :--- | :--- |
| **Incident melden** (Meldende Stelle) → **Incident erfassen** (Servicedesk) | **Time-to-Registration** | Zeit von der Meldung bis zur Ticketanlage. Frühe Erfassung ist Voraussetzung für jede weitere Bearbeitung und SLA-Messung. | Median < 30 Minuten (Servicezeit) |
| **Incident erfassen** → **Incident kategorisieren und priorisieren** (Servicedesk) | **Datenqualität der Erfassung** | Anteil der Tickets, bei denen Kategorie und Priorität bei der Erstbearbeitung korrekt vergeben werden, ohne spätere Korrektur durch die IT-Fachbetreuung. Falsche Einstufung verzögert die Bearbeitung. | > 95 % |
| **Incident kategorisieren und priorisieren** (Servicedesk) → **Incident an IT-Fachbetreuung uebergeben** | **Time-to-Assignment** | Zeit von der Erfassung bis zur Zuweisung an die IT-Fachbetreuung. Kritische Schnittstelle zwischen den Lanes mit Wartezeitrisiko. | Median < 1 Stunde (Servicezeit) |
| **Incident an IT-Fachbetreuung uebergeben** (Servicedesk) → **Ursache analysieren** (IT-Fachbetreuung) | **Time-to-Start-of-Analysis** | Zeit von der Zuweisung bis zum Beginn der Ursachenanalyse. Zeigt Wartezeiten durch Kapazitätsengpässe in der Fachbetreuung. | Median < 2 Stunden (Servicezeit) |
| **Ursache analysieren** → **Loesung umsetzen** (IT-Fachbetreuung) | **Time-to-Fix** | Bearbeitungszeit von Analysebeginn bis zur umgesetzten Lösung. Größter Zeitanteil im Prozess und wesentlicher Treiber der Durchlaufzeit. | Median < 4 Stunden (Servicezeit) |
| **Loesung umsetzen** → **Loesung testen** (IT-Fachbetreuung) | **Testerfolgsquote** | Anteil der Lösungen, die den Test im ersten Durchlauf bestehen. Zeigt die Qualität der Lösungsumsetzung und vermeidet Rückfragen der meldenden Stelle. | > 90 % |
| **Incident dokumentieren und abschliessen** → **Kunde ueber Loesung informieren** (Servicedesk) | **Time-to-Notification** | Zeit von der bereitgestellten Lösung bis zur Lösungsmitteilung an die meldende Stelle. Bestimmt, wie schnell die Störungsbehebung beim Kunden ankommt. | Median < 1 Stunde (Servicezeit) |
