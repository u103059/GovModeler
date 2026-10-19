## Schule an weiterführender Schule anmelden

[**Link zum Prozessmodell in ADONIS**](https://adonis.lhs.stuttgart.de/) [Aktualisierung mit individuellem Link]

### Festlegung von Prozessrahmen und Prozesseckdaten

#### Prozessrollen

- **Prozessmanager/in:** [GZ, Name]
- **Prozesseigner/in:** [GZ, Name]
- **Dezentrale Modellierung (konkrete Person):** [GZ, Name]
- **(Technische) Rolle Prozessanalyst/-modellierer:** [*40 Prozessanalyse/-modellierung*](https://adonis.lhs.stuttgart.de:8443/adonisnp?repoid=c0e28474-6a25-42ee-950b-dee17574158e&id=76487fcc-6e3f-4172-bc39-93d08bfa03d8&libObjID=38c98349-4425-40f7-8712-2d90e014228c&at=0&rid=76487fcc-6e3f-4172-bc39-93d08bfa03d8&t=nb&scenarioID=anp_scenario_1_design_and_document&lang=de) *(bei allen Prozessen im SVA)*
- **Rolle Methodischer Prüfer** (bei allen Prozessen der LHS): [*17-3.4 ADONIS-Team*](https://adonis.lhs.stuttgart.de:8443/adonisnp?repoid=c0e28474-6a25-42ee-950b-dee17574158e&id=fe39853e-01ad-432a-9a41-ed184283316d&libObjID=38c98349-4425-40f7-8712-2d90e014228c&at=0&rid=fe39853e-01ad-432a-9a41-ed184283316d&t=nb&scenarioID=anp_scenario_1_design_and_document&lang=de)

#### Ziel und Zweck des Prozesses

- Die Sorgeberechtigten erhalten für ihr Kind nach der Grundschule einen bestätigten Platz an einer weiterführenden Schule in Stuttgart. Ziel ist eine vollständige, nachvollziehbare und zügige Bearbeitung der Anmeldung mit Anmeldebestätigung.
- Die Sorgeberechtigten stellen die Anmeldeunterlagen zusammen und reichen die Anmeldung bei der Schule ein. Die Schule prüft die Unterlagen auf Vollständigkeit, erfasst die Schüler- und Anmeldedaten und meldet sie an das Schulverwaltungsamt. Das Schulverwaltungsamt prüft Schulbezirkszuordnung und Schulplatzvergabe, erfasst die Anmeldung im Schulverwaltungssystem und bestätigt der Schule die Platzzuordnung. Die Schule bestätigt die Aufnahme und versendet die Anmeldebestätigung.
- **Gewünschte Detailtiefe („Flughöhe“) der Prozessdarstellung:** Modelliert ist der regelmäßige erfolgreiche Ablauf (Happy Path) auf Ebene der Fachaktivitäten je Rolle, mit vollständigen Unterlagen und verfügbarem Schulplatz. Ablehnung, Nachforderung von Unterlagen und Fristüberschreitungen sind nicht dargestellt.

#### Wann und wie wird der Prozess gestartet (= Startereignis)?

- **Kunde (Sorgeberechtigte):** „Bedarf an Anmeldung an weiterführender Schule festgestellt“
- **Organisation (Schule):** Nachrichtenstartereignis „Anmeldung eingegangen“ (ausgelöst durch die eingereichte Anmeldung der Sorgeberechtigten)

#### Wann und wie endet der Prozess (= Endereignis)?

- **Kunde (Sorgeberechtigte):** „Anmeldebestätigung erhalten“
- **Organisation (Schule):** „Anmeldebestätigung versandt“

#### Welche Personen/Rollen (GZ) sind am Prozess beteiligt (= Schwimmbahnen)?

- Pool Kunde: Sorgeberechtigte
- Pool Organisation, Lane Schule: [GZ der Rolle]
- Pool Organisation, Lane Schulverwaltungsamt: [GZ der Rolle]

#### Zusammenstellung der Prozessgruppe für diesen Prozess

- [Name und GZ aller Prozessgruppenmitglieder hier eintragen: je Schwimmbahn Schule und Schulverwaltungsamt mindestens eine Person]
- Prozessgruppenmitglieder in dieses Unterprojekt aufnehmen

#### Welche IT-Anwendungen/-Lösungen werden genutzt?

- Schulverwaltungssystem (Erfassung der Anmeldung und der Platzzuordnung durch das Schulverwaltungsamt)
- Online-Formular „Anmeldung an weiterführender Schule“ (Formular `Schule_anmelden_Antrag.form`)
- [Weitere Anwendungen, z. B. in der Schule eingesetzte Verwaltungssoftware, hier eintragen]

#### Bereits vorhandene Unterlagen / Materialien / Beschreibungen

- **Welche Dokumente, Materialien und sonstige Arbeitsmittel werden verwendet?**
  - Anmeldeformular, Grundschulempfehlung, Geburtsurkunde des Kindes, Nachweis des Wohnsitzes
  - [Bereitstellen/Hochladen der jeweiligen Dokumente/Dateien in dieses Unterprojekt]
- **Gibt es bereits Beschreibungen, Modelle oder sonstige Verschriftlichungen/Visualisierungen des Prozesses?**
  - BPMN-Modell `CreateBPMN/40_Schule_an_weiterfuehrender_Schule_anmelden.bpmn`
  - Formular `CreateForm/Schule_anmelden_Antrag.form`
  - [Weitere Beschreibungen verlinken]

#### Prozessvarianten; vor- und nachgelagerte Prozesse

- **Gibt es Prozessvarianten, die für die Betrachtung dieses Modells relevant sind?**
  - [Link einfügen]
- **Gibt es vor- und nachgelagerte Prozesse, die sich auf dieses Modell relevant auswirken?**
  - [Link einfügen]

#### Teilprozesse / Übergeordnete/r Prozess/e

- [Falls TP vorhanden: Angabe und Verlinkung auf jeden einzelnen Teilprozess bzw. dessen Seite als Unterprojekt dieses Projekts in OpenProject]
- [Falls Darstellung eines Prozesses, der als Teilprozess verwendet wird: Angabe und Verlinkung jedes einzelnen (übergeordneten) Prozesses bzw. dessen Seite in OpenProject, in dem dieser Teilprozess aufgerufen wird]

### Key Performance Indicators (KPIs)

Die folgenden Kennzahlen dienen der Messung der Prozessleistung und werden in Prozess-KPIs (Gesamtbetrachtung) und Aktivitäts-KPIs (Schrittbetrachtung) unterteilt.

#### 1. Prozess-KPIs (Ebene Gesamtprozess)

| KPI-ID | Kennzahl | Beschreibung | Zielwert | Messmethode |
| :--- | :--- | :--- | :--- | :--- |
| **P-KPI-01** | **Durchlaufzeit** | Gesamtdauer vom Eingang der Anmeldung in der Schule bis zum Versand der Anmeldebestätigung | ≤ 10 Arbeitstage | Timestamp(Anmeldebestätigung versandt) - Timestamp(Anmeldung eingegangen) |
| **P-KPI-02** | **Prozessqualität (First-Pass-Yield)** | Anteil der Anmeldungen, die ohne Nachforderung von Unterlagen oder Rückfragen abgeschlossen werden | ≥ 90 % | Anzahl(Anmeldungen ohne Nachforderung) / Gesamtanzahl(abgeschlossene Anmeldungen) |
| **P-KPI-03** | **Service-Level (Fristeinhaltung)** | Anteil der Anmeldungen, die innerhalb der vereinbarten Bearbeitungsfrist mit Anmeldebestätigung abgeschlossen werden | ≥ 95 % | Anzahl(Anmeldungen mit Versand innerhalb Frist) / Gesamtanzahl(abgeschlossene Anmeldungen) |
| **P-KPI-04** | **Digitalisierungsgrad der Einreichung** | Anteil der Anmeldungen, die digital über das Online-Formular eingehen | ≥ 70 % | Anzahl(digital eingereichte Anmeldungen) / Gesamtanzahl(Anmeldungen) |

#### 2. Aktivitäts-KPIs (Ebene Prozessschritte)

| Zugeordnete Aktivität(en) | KPI-Name | Beschreibung & Relevanz | Zielwert |
| :--- | :--- | :--- | :--- |
| **Anmeldung entgegennehmen** (Schule) → **Anmeldeunterlagen auf Vollstaendigkeit pruefen** (Schule) | **Zeit bis Vollständigkeitsprüfung** | Zeitspanne zwischen Eingang der Anmeldung und Abschluss der Vollständigkeitsprüfung. Relevant für die schnelle Erstbearbeitung und frühe Erkennung fehlender Unterlagen. | ≤ 2 Arbeitstage |
| **Anmeldeunterlagen auf Vollstaendigkeit pruefen** (Schule) | **Quote vollständiger Unterlagen** | Anteil der Anmeldungen mit vollständig eingereichten Unterlagen. Relevant als Qualitätsindikator der Antragstellung und des Formulars. | ≥ 90 % |
| **Schueler- und Anmeldedaten erfassen** (Schule) → **Anmeldedaten an Schulverwaltungsamt melden** (Schule) | **Zeit bis Datenmeldung** | Zeitspanne von der Datenerfassung bis zur Meldung an das Schulverwaltungsamt. Relevant für den Übergang zwischen den Schwimmbahnen. | ≤ 1 Arbeitstag |
| **Anmeldedaten an Schulverwaltungsamt melden** (Schule) → **Schulbezirkszuordnung und Schulplatzvergabe pruefen** (Schulverwaltungsamt) | **Wartezeit auf Bearbeitung im Schulverwaltungsamt** | Liegezeit zwischen Meldung und Beginn der Prüfung der Schulbezirkszuordnung. Indikator für Auslastung und Engpässe an der Schnittstelle. | ≤ 2 Arbeitstage |
| **Schulbezirkszuordnung und Schulplatzvergabe pruefen** (Schulverwaltungsamt) → **Platzzuordnung an Schule bestaetigen** (Schulverwaltungsamt) | **Bearbeitungszeit Platzzuordnung** | Bearbeitungsdauer für Prüfung, Erfassung im Schulverwaltungssystem und Bestätigung der Platzzuordnung. Kernphase des Prozesses. | ≤ 3 Arbeitstage |
| **Platzzuordnung an Schule bestaetigen** (Schulverwaltungsamt) → **Aufnahme bestaetigen und Anmeldebestaetigung erstellen** (Schule) | **Zeit bis Aufnahmebestätigung** | Zeitspanne zwischen Rückmeldung der Platzzuordnung und Erstellung der Anmeldebestätigung. Relevant für die zeitnahe Information der Sorgeberechtigten. | ≤ 1 Arbeitstag |
| **Aufnahme bestaetigen und Anmeldebestaetigung erstellen** (Schule) → **Anmeldebestaetigung versenden** (Schule) | **Versanddauer** | Zeitspanne zwischen Erstellung und Versand der Anmeldebestätigung an die Sorgeberechtigten. | ≤ 1 Arbeitstag |
