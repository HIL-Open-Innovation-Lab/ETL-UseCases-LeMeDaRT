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

### 1.2 Produkt, das Algorithmus- bzw. Machine-Learning-Komponente enthält

| Parameter                                 | Wert                                                                   |
| ----------------------------------------- | ---------------------------------------------------------------------- |
| Produkt / Use Case (Name, Identifikation) | Use Case PreHab<br />Use Case Praevention<br />Use Case Atemwegsinfekt |
| Version                                   |                                                                        |
| Entwicklungsstand                         | Ausarbeitung Use Cases                                                 |
|                                           |                                                                        |
|                                           |                                                                        |

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

### 3.2 Prozess und Nutzungskontext

> Hier beschreiben, ob wie der Ablauf des Prozesses und der Patientenreise ist.
>

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
> | Organisation / Person | Aufgabe | Notwendige Anforderungen und Kompetenzen | Nachweis |
> | --------------------- | ------- | ---------------------------------------- | -------- |
> |                       |         |                                          |          |
> |                       |         |                                          |          |
> |                       |         |                                          |          |
> |                       |         |                                          |          |
> |                       |         |                                          |          |
> |                       |         |                                          |          |
> |                       |         |                                          |          |
> |                       |         |                                          |          |
> |                       |         |                                          |          |
>
> ***Tabelle 4:*** Aufgaben-Checkliste

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
>
> Diese Dokumentation kann auch tabellarisch erfolgen:
>
> | ID | Verfahren / Prozesse (eindeutige Identifikation) | Beschreibung der Anforderungen | Verantwortliche | Version |
> | -- | :----------------------------------------------- | :----------------------------- | :-------------- | :------ |
> |    |                                                  |                                |                 |         |
> |    |                                                  |                                |                 |         |
> |    |                                                  |                                |                 |         |
>
> ***Tabelle 5:*** CSV
>

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

## 5 Trainingsdaten

### 5.1 Datenquellen

#### Übersicht über die Datenquellen

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

#### Deskriptive Statistik

> Hier z.B. mit Hilfe einer deskriptiven Statistik eine Übersicht über die Datensätze geben, z.B. für die einzelnen Feature
>
> - Lagemaße: Mittelwert, Median, ...
> - Histogramme
> - Anzahl fehlender Werte
> - Korrelation der Attribute (Feature) untereinander
>
> So sinnvoll, sollten diese Statistiken für die verschiedenen Datenquellen getrennt erstellt werden, um den Einfluss der Datenquelle auf die Datensätze bewerten zu können.

#### Bewertung der Daten

> Der Hersteller sollte kurz begründen, weshalb die Daten, die für das Training verwendet werden,
>
> - repräsentativ für die Patientenpopulation bzw. angestrebte Zweckbestimmung und
> - quantitativ und qualitativ ausreichend / geeignet sind.
>
> Für diese Begründung ist die Unterstützung durch einen Statistiker hilfreich.

### 5.2 Datenvorverarbeitung ("Pre-Processing")

> Hier sollte der Hersteller beschreiben, wie die Daten vorverarbeitet werden. Zu diesen Verarbeitungsschritten zählen beispielsweise:
>
> - Umgang mit fehlenden Werten: Datensatz löschen, fehlenden Wert durch Mittelwert ersetzen usw.
> - Umgang mit "Outliern": Datensatz löschen, Wert durch einen anderen Ersetzen, Wert löschen usw.
> - Umwandlung von numerischen Werten in Kategorien
> - Konvertierung von Einheiten
> - Rundungen
> - Umwandlung von (Daten-)Formaten
> - Löschen von Elementen (z.B. Stop-Wörter beim NLP)
> - Zusammenfassen mehrerer Datensätze (z.B. durch JOINS)
> - Anonymisieren und Pseudonymisieren von Daten
>
> Hinweis: Diese Datenverarbeitung muss validiert sein (siehe oben "CSV").

### 5.3 Labeling

> Hier sollte der Hersteller bei Verfahren des "Supervised Machine Learnings" das Labeling beschreiben:
>
> - Anforderungen an die Personen, die das Labeling durchführen (Auswahlkriterien, spezifische Schulung, Prüfung)
> - Personen, die das Labeling tatsächlich durchgeführt haben (Kompetenz, Ausbildung, Ergebnis der Prüfung)
> - Protokoll und Kriterien, die für das Labeling zu verwenden waren (ggf. Referenz auf andere Dokumente)
> - Überprüfung der Korrektheit des Labelings
> - Wahl des Gold-Standards (inkl. Begründung)

## 6 Algorithmus, Modell, Modellbildung und Bewertung

### 6.1 Architektur

> Hier den Modelltyp (ML, hardkodiert) bzw. dessen Architektur beschreiben. Das kann auch grafisch erfolgen wie in der folgenden Abbildung gezeigt:
>
> ![](./media/SW-TPL-07-DE_Modell-Architecture.png)
>
> ***Abb. 2***: Beispiel für eine grafische Darstellung einer ML-Architektur
>
> Beispiele für ML-Modelltypen sind:
>
> - Neuronale Netzwerke, Convolutional Neural Networks
> - Support Vector Machines
> - Entscheidungsbäume
> - Tree Ensembles wie Random Forrest, XGBoost
> - Logistische Regression
>
> Verwendete Bibliotheken und Frameworks beschreiben. Ggf. Software-Architektur und SOUP-Liste referenzieren.

### 6.2 Training

> Hier den Trainingsprozess kurz beschreiben:
>
> - Aufteilung der Daten in Trainings-, Validierungs- und Testdaten
> - Infrastruktur, auf der das Training stattfand
> - Falls das Training mit einem vortrainierten Modell erfolgt, sollte das ebenfalls erwähnt werden
> - Wahl der wichtigsten Hyperparameter
>   - Lernrate
>   - Anzahl Epochen
>   - Loss-Function
>   - Optimizer
>   - bei neuronalen Netzwerken: Anzahl und Typ der Layer, Art der Verknüpfung der Layer, Anzahl der Neuronen pro Layer, Aktivierungsfunktionen
>   - Wahrscheinlichkeiten, ab denen ein Datensatz als einer Klasse zugehörig bewertet wird
> - Getestete aber als weniger erfolgreich bewertete Ansätze (Modelltypen, Hyperparameter)

### 6.3 Bewertung der Leistung des Modells

> Beschreiben, wie das Modell verifiziert und validiert wurde. Dazu zählt eine Beschreibung, mit welchen bzw. wie vielen Daten das Modell getestet wurde.
>
> Die erreichten Gütemaße auflisten (s.o. "Gütekriterien"). Bei Klassifizierungsaufgaben wäre eine Vierfeldertafel zu empfehlen. Üblich sind auch visuelle Darstellungen wie bei ROC-Kurven.
>
> Begründungen geben, weshalb die Ergebnisse als korrekt angenommen werden können. Dazu bieten sich Ansätze an wie:
>
> - Erklärung am Ergebnis z.B.[LIME](https://christophm.github.io/interpretable-ml-book/lime.html)
> - Erklärung anhand von[Couterfacturals](https://christophm.github.io/interpretable-ml-book/counterfactual.html)
> - Darstellung der Abhängigkeiten (Stärke und Richtung) der Vorhersagen von den Feature (z.B. Sharpley-Values,[ICE-Plots](https://christophm.github.io/interpretable-ml-book/ice.html),[Partial Dependency Plots PDP](https://christophm.github.io/interpretable-ml-book/pdp.html) (s.u.))
> - Synthetisierung und/oder Visualisierung von Datensätzen, die das Modell besonders aktivieren
> - [Surrogat-Modelle](https://christophm.github.io/interpretable-ml-book/global.html)
>
> Aussagen über die Verlässlichkeit und Limitierung der Ergebnisse einfügen. Dazu können sich Hersteller beispielsweise bedienen an
>
> - Datensätze<n, bei denen das Modell die Ergebnisse besonders schlecht vorhergesagt hat,
> - der Anzahl der Datenpunkte pro Feature-Wert (kann mit PDPs kombiniert werden, wie in der folgenden Abbildung zu sehen)
>
> ![](./media/SW-TPL-07-DE_pdp-cervical-1.png)
>
> ***Abb. 3:*** Die [PDPs aus dem Buch von Christoph Molnar](https://christophm.github.io/interpretable-ml-book/pdp.html) zeigt auch, wieviele Datenpunkte in den Wertebereichen vorliegen
>
> Verweis auf weitere Software-Tests einfügen.

### 6.4 Input für die Gebrauchsanweisung

> Hier auflisten, was die Gebrauchsanweisung beschreiben muss. Beispiele sind:
>
> - Kurze Beschreibung des Modells (auch, ob dieses kontinuierlich weiterlernt)
> - Gütekriterien ggf. abhängig von Feature
> - Voraussetzungen
>   - z.B. Patientenpopulation
>   - Art derDatengewinnung (z.B. Mess- und Medizingeräte)
>   - Laufzeitumgebung
> - Sonstige Limitierungen , Kontraindikationen
> - Warnungen
> - Möglichkeiten, um die Korrektheit zu überprüfen und Fehler zu erkennen
> - Informationen darüber, wie das Modell trainiert und getestet wurde
> - Anforderungen an die Anwender (Ausbildung, Kompetenzen, spezielle Schulung)
> - Weiterführende Literatur
> - Lizenzrechte

### 6.5 Zusammenfassende Bewertung

> Hier schreiben, ob bzw. dass das Modell
>
> - die spezifizierten Gütekriterien erreicht,
> - geeignet ist, die Zweckbestimmung zu erfüllen,
> - bessere Ergebnisse liefert als der Stand der Technik und andere ML-Modelle (Typen, Hyperparameter) — ggf. erwähnen, welche alternativen Modelle man ausprobiert hat.
> - trotz möglicherweise schlechterer Interpretierbarkeit ein besseres Nutzen-Risiko-Verhältnis bietet als einfachere ML-Modelle oder klassische Algorithmen,
> - keine Limitierungen hat, die für die spezifizierte Zweckbestimmung (z.B. Patientenpopulation) dieses Nutzen-Risiko-Verhältnis in Frage stellt.
>
> Ggf. müssen weitere Aspekte diskutiert werden, wie die IT-Sicherheit und die Vertraulichkeit von Daten.
>
> Ggf. klinische Bewertung/Leistungsbewertung und Risikomanagementakte referenzieren.
>
> Ggf. auch noch offene Aspekte ansprechen, die dann in der Post-Market-Phase untersucht werden müssen.

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

### 7.2 Systementwicklung

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
>

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
