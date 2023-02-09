# Daten Management (ETL)

Version: 1.0 | Datum: 1.0

## 1 Metainformationen

### 1.1 Dokument

| Inhalte               | Wert                                                     |
| --------------------- | -------------------------------------------------------- |
| Autor(en)             | Andre Baumgart<br />Moanes Ben Amour<br />Martin Laplans |
| Name des Dokuments    | Daten Management                                         |
| Version des Dokuments | 1.0                                                      |
| Datum des Dokuments   | 2023-01-23                                               |
| Status des Dokuments  |                                                          |

***Tabelle:*** Dokument

### 1.2 Produkt 

| Parameter                                 | Wert                   |
| ----------------------------------------- | ---------------------- |
| Produkt / Use Case (Name, Identifikation) | Use Case PreHab        |
| Version                                   |                        |
| Entwicklungsstand                         | Ausarbeitung Use Cases |
|                                           |                        |
|                                           |                        |

***Tabelle:*** Produkt / Use Case

### 1.3 Zweck

Dieses Dokument hat das Ziel,

- eine Übersicht über alle Datenflüsse im Use Case oder dem Produt / System aufzuzeigen
- die Informationen bereitzustellen, die für eine Bewertung der Daten und Informationsflüsse aus Sicht des Datenschutzes, Entwicklung und Security notwendig sind und
- als "Input" für die Entwicklungsarbeiten

zu dienen.

### 1.4 Adressaten

Dieses Dokument richtet sich an:

- Datenschützbeauftragte
- Sicherheitsengineure
- Entwickluner
- Produkt
- Projektmanager
- Weitere Interessierte der Use Cases

## 2 Beschreibung Use Case

### 2.1 Zweck und Ziele


> Folgenden Aspekte sollten adressiert werden:
>
> - Medizinischer Zweck
>
>   - Diagnose, Therapie, Überwachung, Vorhersage
>   - Indikationen, Kontraindikationen
>   - Nutzen, Vorteile
>   - Unmet Need
> - Patienten
>
>   - Erkrankungen, Begleiterkrankungen
>   - Ggf. demographische Angabe wie Alter, Geschlecht
>   - Einschränkungen, Limitationen
> - Nutzungsumgebung u.a. physikalische Umgebung und soziale Umgebung (z.B. Stress, Schichtbetrieb)
> - ...

### 2.2 Klinischer Kontext

> Hier einen kurzen Hintergrund zur Relevanz des Use Cases im medizinischen bzw. diagnostischen Kontext geben (Dabei kann z.B. der medizinische Stand der Technik (s. klinische Bewertung/Leistungsbewertung) zuhilfe genommen werden.), z.B.
>
> - relevantes medizinisches/diagnostisches Feld
> - Anzahl der betroffenen Patienten, Häufigkeit der Erkrankung in der Allgemeinbevölkerung bzw. in Anhängigkeit bestimmter Kriterien (z.B. Altersgruppe, Geschlecht, familiäre Prädisposition, genetische Apsekte)
> - Krankheitsverläufe, relevante medizinische Sachverhalte, verschiedene Formen/Stadien/Schweregrade der Erkrankung
> - besondere medizinische und ökonomische Problemstellungen
> - ...



### 2.3 Einbettung der Daten und des Algorithmus in das Gesamtsystem

> Hier z.B. mit Komponentendiagramm oder SysMLDiagramm beschreiben, wie der Algorithmus in das Gesamtsystem eingebettet ist.
>
> ![](./media/SW-TPL-07-DE_ComponentDiagram.png)
>
> ***Abb. 1***: Komponentendiagramm, das die Einbettung der Algorithmus-/ML-Komponente ins Gesamtsystem zeigt
>
> Kurze Beschreibung der Inputs und Outputs der Komponente einfügen. Eine genauere Beschreibung folgt im Kapitel 3.2)



### 2.4 Risikoanalyse

> Hier die wichtigsten Risiken beschreiben, die sich ergeben würden, wenn die Algorithmus-/ML-Komponente nicht die spezifizierten Gütekriterien erfüllt.



## 3 Anforderungen - Daten Management

### 3.1 Kriterien der Datenqualität

> Die Wahl dieser Qualitätskriterien begründen, z.B. auf Basis von:
>
> - Stand der Wissenschaft z.B. Gold-Standard
> - Stand der Technik z.B. alternative Use Cases oder Produkte (z.B. Wettbewerber) oder Verfahren (z.B. konventionelle Diagnostik)
> - zu erzielender Nutzen
> - Unmet Need
>
> Es kann sinnvoll sein, zu begründen, weshalb man bestimmte Gütekriterien **nicht** gewählt hat.
>
> Der Vergleich mit dem Stand der Technik ist auch für die Festlegung der Risikobewertung bedeutend.
>
> Beispiele für Gütekriterien sind:
>
> - Minimalität
> - Informationswert
> - Datenschutz
> - Sicherheit
> - ...

### 3.2 Anforderungen der Prozesse

> Hier beschreiben, ob wie der Ablauf des Prozesses und der Patientenreise ist.

### 3.3 Anforderungen an den Nutzungskontext

> Hier beschreiben, ob es spezielle Anforderungen an den Nutzugnskontext gibt.

### 3.4 Weitere "nicht-funktionale" Anforderungen

> Hier auf die Übersicht über die wichtigsten Anforderungen sonstige Anforderungen stellen:
>
> - Anforderungen an die Laufzeitumgebung
>   - Hardware, z.B. Bildschirmauflösung, -größe, -ausrichtung, Prozessor, zur Verfügung stehender Speicher. Hier können auch Produkte genannt werden wie "iPhone 11 oder neuer"
>   - Betriebssystem
>   - Run-times wie Browser, JRE, .NET
>   - andere Software-Anwendungen
>   - Cloud-Plattformen
> - Zu verwendende Bibliotheken und Frameworks
> - Performanz, insbesondere Antwortzeiten
> - Interoperabilität: API, Datei- und Datenformate, Protokolle, Verschlüsselung, semantische Standards (Klassifikationen, Nomenklaturen, Kodiersysteme, Taxonomien)
> - Robustheit, z.B. Verhalten bei Fehleingaben, falschen Datentypen und -formaten, Überlast

## 4 Qualitätsanforderungen an die Datenverarbeitung

> Organisationen, Personen und Akteure und Systeme

### 4.1 Stakeholder: Organisationen, Qualifikationen und Kompetenzen

> Nur die Personen und Rollen aufführen, die für die Entwicklung des Algorithmus bzw. das ML relevant sind. Für Nachweise auf entsprechende Aufzeichnungen verweisen (so vorhanden).
>
> | Organisation / Person | Aufgabe | Notwendige Anforderungen und Kompetenzen | Nachweis | Type |
> | --------------------- | ------- | ---------------------------------------- | -------- | ---- |
> |                       |         |                                          |          |      |
> |                       |         |                                          |          |      |
> |                       |         |                                          |          |      |
> |                       |         |                                          |          |      |
> |                       |         |                                          |          |      |
> |                       |         |                                          |          |      |
> |                       |         |                                          |          |      |
> |                       |         |                                          |          |      |
> |                       |         |                                          |          |      |
>
> ***Tabelle:*** Organisationen und Anforderungen

### 4.2 Angewendete Verfahrens- und Arbeitsanweisungen

> Hier Vorgabedokumente referenzieren, die bei der Entwicklung und Bewertung der Algorithmus-/ML-Komponenten beachtet wurden.
>
> - Verfahrensanweisungen, Prozessbeschreibungen
> - Arbeitsanweisungen
> - Pläne (Entwicklungsplan, Risikomanagementplan, V&V-Pläne)
> - Weitere Vorgabedokumente beispielsweise zu den folgenden Themen:
>   - Dokumentenlenkung (das betrifft auch die Daten!)
>   - Entwicklung (SW allgemein, Entwicklung, Training und Validierung von ML-Modellen)
>   - Risikomanagement
>   - Klinische Bewertung/Leistungsbewertung
>   - Computerized Systems Validation (CSV)
>   - Überwachung nach dem Inverkehrbringen (Post-Market Surveillance)
>   - Produktion, Betrieb
>
> Diese Dokumentation kann auch tabellarisch erfolgen:
>
> | ID | Verfahren / Prozesse (eindeutige Identifikation) | Beschreibung der Anforderungen | Verantwortliche | Version |
> | -- | :----------------------------------------------- | :----------------------------- | :-------------- | :------ |
> |    |                                                  |                                |                 |         |
> |    |                                                  |                                |                 |         |
> |    |                                                  |                                |                 |         |
>
> ***Tabelle:*** Verfahren

### 4.3 Bill-of-Systems: Systeme

> Hier die Systeme aufzählen, die am Use Case beteiligt sind
>
> - Software zum Sammeln der Daten
> - Software zur Vorverarbeitung der Daten
> - Software zur statistischen Auswertung der Daten
> - Platformen: ML-Frameworks und Bibliotheken (sofern nicht Teil des Medizinprodukts)
> - Werkzeuge zum Verifizieren und Validieren z.B.
>   - zum Testen, zur statischen Code-Analyse, zum Dokumententieren von Code-Reviews
>   - zum Bewerten und Interpretieren der Modelle, z.B. für das Erstellen von Partial Dependency und ICE-Plots
>
> Diese Dokumentation kann auch tabellarisch erfolgen:
>
> | ID | Name System und Werkzeuge (eindeutige Identifikation) | Beschreibung der Anforderungen | Hersteller | Version |
> | -- | :---------------------------------------------------- | :----------------------------- | :--------- | :------ |
> |    |                                                       |                                |            |         |
> |    |                                                       |                                |            |         |
> |    |                                                       |                                |            |         |
>
> ***Tabelle:*** Systeme

## 5 Daten und Datenfluss

### 5.1 Datenquellen

#### Übersicht über die Datenquellen

##### Auslistung der Bill-of-Data-Sources

Diese Dokumentation kann auch tabellarisch erfolgen:

| ID | Datenquelle | Organisation | Type | System / Hersteller |
| -- | :---------- | :----------- | :--- | :------------------ |
|    |             |              |      |                     |
|    |             |              |      |                     |
|    |             |              |      |                     |

***Tabelle:*** Datenquellen

> Hier die Datenquellen auflisten, z.B. Kliniken, Medizinprodukte, Fragebögen, Labore, Mobiltelefone usw.
>
> Es kann notwendig sein, zu beschreiben, wie die Datensätze gewonnen wurden (z.B. Protokoll bei Befragungen, Gerätetypen, Aufnahmeverfahren und -parameter).
>
> Für jede Datenquelle beschreiben
>
> - Anzahl der Datensätze
> - Datensätze z.B. anhand von
>   - Typ: Bilddaten, tabellarische Daten, Freitext
>   - Attribute: Name, Bedeutung, Datentyp, Kodiersystem, Einheit usw.
> - Datenlieferant (z.B. Patient) anhand relevanter Parameter wie Alter, Geschlecht, Erkrankung, Diagnosen, Begleiterkrankungen, Vitalparameter, Laborparameter

#### Details zu den Datenquellen

Beschreibung der Datenquellen

Diese Dokumentation kann auch tabellarisch erfolgen:

| ID | Datenquelle | Beschreibung | Technische Details | Interoperabilität | Link |
| -- | :---------- | :----------- | :----------------- | :----------------- | ---- |
|    |             |              |                    |                    |      |
|    |             |              |                    |                    |      |
|    |             |              |                    |                    |      |

***Tabelle:*** Datenquellen

> Hier z.B. eine Übersicht über die Datensätze geben, z.B. für die einzelnen Details
>
> Soweit sinnvoll, sollten diese Informationen für die verschiedenen Datenquellen getrennt erstellt werden, um den Einfluss der Datenquelle auf die Datensätze bewerten zu können.

#### Bewertung der Daten

Die Bewertung der Dokumentation kann auch tabellarisch erfolgen:

| ID | Datenquelle | Beschreibung | Bewertung | Offen Punkte | Sonstiges |
| -- | :---------- | :----------- | :-------- | :----------- | --------- |
|    |             |              |           |              |           |
|    |             |              |           |              |           |

***Tabelle:*** Datenquellen

> Hier sollte kurz begründet werden, weshalb die Daten, für den Use Case verwendet werden,
>
> - repräsentativ für die Patientenpopulation bzw. angestrebten Zweck und
> - quantitativ und qualitativ ausreichend / geeignet sind.
>
> Für diese Begründung ist die Unterstützung durch einen Kliniker, Bioinformatiker und Machine Learning Engineer hilfreich.

### 5.2 Datenverarbeitung ("Processing")

Die Bewertung der Dokumentation kann auch tabellarisch erfolgen:

| ID | Datenquelle | Beschreibung der Verarbeitung | Bewertung | Anmerkungen |
| -- | :---------- | :---------------------------- | :-------- | ----------- |
|    |             |                               |           |             |
|    |             |                               |           |             |

***Tabelle:*** Datenverarbeitung

> Hier sollten wir beschreiben, wie die Daten verarbeitet werden. Zu diesen Verarbeitungsschritten zählen beispielsweise:
>
> - Umgang mit fehlenden Werten: Datensatz löschen, fehlenden Wert durch Mittelwert ersetzen, "Outliern": Datensatz löschen, Wert durch einen anderen Ersetzen, Wert löschen
> - Umwandlung von numerischen Werten in Kategorien und von (Daten-)Formaten
> - Löschen von Elementen (z.B. Stop-Wörter beim NLP)
> - Zusammenfassen mehrerer Datensätze (z.B. durch JOINS)
> - Anonymisieren und Pseudonymisieren von Daten
>
> Hinweis: Die Datenverarbeitung muss idealerweise   sein.

### 5.3 Signierung der Daten

Die Bewertung der Dokumentation kann auch tabellarisch erfolgen:

| ID | Datenquelle | Beschreibung der Signierung | Signierungsverfahren | Link | Sonstiges |
| -- | :---------- | :-------------------------- | :------------------- | :--- | --------- |
|    |             |                             |                      |      |           |
|    |             |                             |                      |      |           |

***Tabelle:*** Signieren

> Hier sollte der Use Case bei Verfahren der Signierung detailliert beschreiben, wie es :
>
> - Anforderungen an die Personen, die das Labeling durchführen (Auswahlkriterien, spezifische Schulung, Prüfung)
> - Personen, die das Labeling tatsächlich durchgeführt haben (Kompetenz, Ausbildung, Ergebnis der Prüfung)
> - Protokoll und Kriterien, die für das Labeling zu verwenden waren (ggf. Referenz auf andere Dokumente)
> - Überprüfung der Korrektheit des Labelings
> - Wahl des Gold-Standards (inkl. Begründung)

## 6 Use Case Systemarchitektur und Datenmodell

### 6.1 Systemarchitektur

> Hier die System-Architektur beschreiben. Das kann grafisch erfolgen auf Basis eines Architekturdiagramms,.
>
> Beispiele für Systeme und verwendete Produkte sind:
>
> - Cloud-Betrieb: Openstack und Kubernetes
> - Applikation: DiGA von Hersteller in Finnland mit Daten in der Azure Cloud
> - ...
>
> Verwendete Frameworks sind zu beschreiben.

### 6.2 Datenmodell

> Hier das Datenmodell zu beschreiben in Form eines ERD und Verteilungsdiagramms.
>
> - ERD
> - Verteilungsdiagramm
> - APIs

### 6.3 Datenfluss

Der Datenfluss im Use Case wird auf Basis der Prozesse und Ereignisse im Use Case dargestellt:

> Beschreiben, wie der Datenfluss innerhalb des Use Cases anhand der Prozesse und klinischen Fragen

### 6.4 Zusammenfassende Bewertung

> Hier schreiben, ob bzw. dass der Datenfluss
>
> - die spezifizierten Qualitätsriterien erreicht,
> - geeignet ist, die Zwecke und Unmet need des Use Case zu erfüllen,
> - bessere Ergebnisse liefert als der Stand der heutigen Versorgung und andere moderne Lösungsansätze — ggf. erwähnen, welche alternativen Ansätze man ausprobiert hat oder existieren
> - ein besseres Nutzen-Risiko-Verhältnis bietet als einfachere Ansätze,
> - eine Limitierungen hat, die für die spezifizierte Zwecke (z.B. Patientenpopulation) dieses Nutzen-Risiko-Verhältnis in Frage stellt.
>
> Ggf. müssen weitere Aspekte diskutiert werden, wie die IT-Sicherheit und die Vertraulichkeit von Daten.
>
> Ggf. klinische Vewertung und Risikoaspekte referenzieren.
>
> Ggf. auch noch offene Aspekte ansprechen, die dann im operativen Betreib untersucht werden müssen.

## 7 Nächste Entwicklungsarbeiten und Phases

### 7.1 Datenschutz

> Ziele des Datenschutzes und der
>
> - Organisationen benennen
> - System definieren
> - Interkationen festlegen
> - Daten definieren
> - Verträge aufführen
> - ...

### 7.2 System- / Produktentwicklung

> Hier spezifizieren
>
> - Welche Schritte für die Systementwicklung verwendet werden.
> - Notwendige weitere Inputs aus der Datenflow Betrachtung
> - ...

### 7.3 Security

> Hier spezifizieren
>
> - Informationssicherheit
> - Systemsicherheit
> - Kommunikationssicherheit (Netzwerk)

## 8 Anhang

### 8.1 Mitgeltende Dokumente

Die folgenden Dokumente sind für dieses Dokument relevant:

| **Nr.** | **Dokumenten-ID** | **Dokumententitel** | Beschreibung |
| ------------- | ----------------------- | ------------------------- | ------------ |
|               |                         |                           |              |
|               |                         |                           |              |
|               |                         |                           |              |

***Tabelle:*** Weitere Dokumente

### 8.2 Versionskontrolle

#### Verantwortliche

| Rolle       | Datum      | Vor- und Nachname | Unterschrift |
| ----------- | ---------- | ----------------- | ------------ |
| Autoren     | 2023-01-20 | Andre Baumgart    | ABA          |
| Autoren     |            |                   |              |
| Prüfende   | JJJJ-MM-TT |                   | ...          |
| Prüfende   |            |                   |              |
| Prüfende   |            |                   |              |
| Freigebende |            |                   |              |

***Tabelle:*** Verantworliche

#### Historie

| Version | Datum      | Autor           | Status        | Beschreibung der Änderung |
| :------ | :--------- | :-------------- | :------------ | :------------------------- |
| 1.0     | 2023-01-20 | André Baumgart | Erste Version | Erstellung erste Version   |
|         |            |                 |               |                            |

***Tabelle:*** Änderungen
