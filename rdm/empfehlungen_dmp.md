<button><a href="javascript:(function(){window.hypothesisConfig=function(){return{showHighlights:true,appType:'bookmarklet'};};var d=document,s=d.createElement('script');s.setAttribute('src','https://hypothes.is/embed.js');d.body.appendChild(s)})();">Dieses Dokument mit hypothes.is annotieren</a></button>

# Empfehlungen der AG Greening DH zum ressourcenschonenden Umgang mit Forschungsdaten

Ein strategisches und umsichtiges Forschungsdatenmanagement (FDM) gehört zum zentralen Kern der guten wissenschaftlichen Praxis [Deutsche Forschungsgemeinschaft, Leitlinien zur Sicherung guter wissenschaftlicher Praxis, Bonn 2019. DOI:10.5281/zenodo.3923601](https://zenodo.org/records/6472827). Es dient dem planvollen und methodischen Erfassen, Aufbereiten, Sichern und Bereitstellen von projektbezogenen Daten zur transparenten Nachvollziehbarkeit von Forschungsergebnissen und sichert deren Nachnutzung. Dadurch werden ressourcenintensive Doppelarbeiten vermieden. Das FDM ist damit nicht nur forschungspolitisch gewollt und ohnehin Voraussetzung für jegliche Förderung, sondern zugleich verantwortungsvolles Handeln im Umgang mit Ressourcen. Allerdings ist das FDM selbst ressourcenintensiv, so dass eine sorgfältige Abwägung zwischen den genannten Zielen und dem dafür erforderlichen Ressourceneinsatz erforderlich ist. 

Die folgenden Empfehlungen haben zum Ziel, Forschenden zu helfen, typische Fragen in Forschunsdatenmanagementplänen im Hinblick auf den ökologischen Fußabdruck von Daten, Hardware und Software zu beantworten und diese Fragen als Ansporn zu nutzen, sich für Lösungen zu entscheiden, die unter Berücksichtigung der Ziele des FDM so wenig ressourcenintensiv sind wie möglich. Die Empfehlungen sind in die sechs Bereiche Formate/Interoperabilität, Versionierung, Metadaten, Nutzungsszenarien und Speicherplatz/Langzeitarchivierung aufgeteilt. Die genannten Kategorien sind im Rahmen des Workshops "Der Weg zum grünen Forschungsdatenmanagementplan" bei der Jahrestagung des DHd 2024 entstanden. [Anja Gerber, Lisa Rosendahl, Der Weg zum grünen Forschungsdatenmanagementplan, Passau 2024. DOI: 10.5281/zenodo.10698392](https://zenodo.org/records/10698392).

## Formate und Interoperabilität

Folgende Fragen sind üblicherweise in einem FDMPlan-Template mit Bezug auf Formate und Interoperabilität zu finden: 

- In welchem Format liegen die Daten vor?
- Sind die Datensätze interoperabel?
- Werden offene Softwares verwendet?

Diese drei Fragen sind zentral für die Umsetzung von Speicher- und vor allem (Nach-)Nutzungsszenarien, die wiederum wesentlich für die Reduzierung des ökologischen Fußabdrucks der genutzten digitalen Ressourcen sind (siehe unten Abschnitt Nachnutzung).

**Offene, nicht binäre Formate** sind der Interoperabilität förderlich (d.h.: Die Datensätze sind für den Datenaustausch geeignet). Interoperable Daten und offene Software können **leichter nachgenutzt werden**. Eine breitere Nutzung digitaler Ressourcen (Daten, Software, Hardware, Infrastruktur) reduziert ihren ökologischen Gesamt-Fussabdruck, da dieser auf die Systeme, Individuen und Institutionen aufgeteilt wird, die darauf zurückgreifen. Insofern ist **das ideale Projekt eines, das keine Daten und Software erzeugt, sondern bereits vorhandene nachnutzt**.

Um Daten und Software besser mit der Community teilen zu können, kann man sich an folgenden Prinzipien orientieren:

- Beim ausgewählten Datenformat/bei den ausgewählten Datenformaten (für jeweils Text, Bild, Ton,...) **anerkannte und langlebige Standards** verwenden.

- Zeigen, wie der Datensatz ohne großen Aufwand mit verschiedenen anderen Datensätzen aus unterschiedlichen Quellen kombiniert werden kann. Schwachstellen in der Interoperabilität lassen sich über das Erstellen von konkreten Nachnutzungsszenarien identifizieren (etwa im Sinne der Zusammenarbeit mit anderen Projekten). Neben Format und Software spielen hier **Metadaten** eine wichtige Rolle (siehe unten Metadaten).

- Das oder die ausgesuchte/n Datenformat/e sollen **mit einer offenen Software** (bzw. mit in der jeweiligen Community etablierter und vielgenutzter Software) bearbeitet werden können.

Fazit: Datenformate und Software sollen **Reproduzierbarkeit und Nachnutzung** begünstigen – diesen liegt Interoperabilität zugrunde. Je mehr Personen damit arbeiten, desto geringer der Fussabdruck.

## Versionierung

Folgende Fragen sind üblicherweise in einem FDMPlan-Template mit Bezug auf Versionierung zu finden:

- Werden verschiedene Versionen des Datensatzes erzeugt? 
- Welche Versionierungsstrategie wird für diesen Datensatz angewandt? 
- Welche Technologie bzw. welches Tool wird zur Versionierung verwendet?

Mit der Versionierung eines Datensatzes in manueller oder automatisierter Form mithilfe von Versionenkontrollsystemen ist die Speicherung von Zwischenständen im Laufe des Arbeitsprozesses gemeint. Während die Versionierung von Dokumenten für das Erstellen von Daten (z.B. projektinterne Richtlinien) – insbesondere für die Zusammenarbeit in einem größeren Team – sehr hilfreich und wichtig sein kann, ist es in den meisten Fällen nicht notwendig, sämtliche Versionen eines Dokuments langfristig zu speichern. Die Historie kann in diesen Fällen gelöscht und nur die für das Forschungsziel benötigte Version gespeichert und publiziert werden. Informationen über die Entstehung der Daten wie Datum, Autor*innen und genutzte Tools sollten aus den Metadaten und/oder der Dokumentation hervorgehen.

Innerhalb eines Projekts sollte je nach Dateityp entschieden werden, ob eine **Versionierung** notwendig ist oder ob es genügt, nur die aktuelle Datei vorzuhalten. Bereits während des Arbeitsprozesses kann Speicherplatz gespart werden, indem **lediglich inkrementelle Backups** durchgeführt werden, bei denen nicht vollständige Dateien, sondern nur jeweils die Änderungen gespeichert werden. Nicht mehr benötigte ältere Versionen können zudem **regelmäßig gelöscht werden**. Es muss ebenso entschieden werden, welches System dafür am besten genutzt werden kann und wie häufig Backups durchgeführt werden sollten. Diese Punkte sollten im Arbeitsplan bzw. **im Workflow des Projekts integriert werden**. Dabei zu dokumentieren sind Entscheidungsprozesse, feste Termine zur Einschätzung des Bedarfs, zuständige Personen, Beschreibung der durchgeführten Löschmassnahmen in einem ressourcenschonenden, einfachen Textformat.

## Metadaten
Folgende Fragen sind üblicherweise in einem FDMPlan-Template mit Bezug auf Metadaten zu finden:

- Welche Informationen sind für Außenstehende notwendig, um die Daten zu verstehen? Das betrifft Informationen über ihre Erhebung bzw. Entstehung, Analyse sowie die auf ihrer Basis gewonnenen Forschungsergebnisse. Hier gehören Informationen zu Ort, Inhalt, Methodik, Erzeugungsprozess, Technologie, Dokumentation der zur Nutzung notwendigen Software, Zeit, Quellen, Akteure, Identifikatoren.
- Welche Standards, Ontologien, Klassifikationen etc. werden zur Beschreibung der Daten und Kontextinformation genutzt?
- Werden Metadaten und Kontextinformation auf Korrektheit und Vollständigkeit geprüft? Wer ist verantwortlich für die Dokumentation und Prüfung der Metadaten und Kontextinformationen auf Richtigkeit und Vollständigkeit?

Metadaten sind Daten über (digitale) Objekte und Ressourcen jeglicher Art. Sie beschreiben **Inhalt, Form,  Zugangsbedingungen**  in strukturierter und einheitlicher Form, was der Verbesserung der Erschließung, Auffindbarkeit und Nutzung von (digitalen) Dokumenten dient. Es ist dadurch ebenfalls möglich, Beziehungen zu bzw. zwischen anderen Objeken und auch Datenbeständen anderer Institutionen herzustellen, so dass die Einordnung in größere Zusammenhänge abgebildet werden kann. Metadaten erleichtern ebenfalls den Austausch über Schnittstellen. Die Einteilung von Metadaten kann in vier Kategorien erfolgen: Beschreibende bzw. deskriptive, strukturelle, Verwaltungs- bzw. administrative sowie technische Metadaten.

Die Speicherung der Metadaten im Format JSON (JavaScript Object Notation) oder XML (Extensible Markup Language) ermöglicht eine Langfristsicherung der Metadaten in einem menschen- und maschinenlesbaren Format und den Datenaustausch mit anderen Institutionen. Zudem sind die Daten schnell abrufbar und verursachen keine hohen Ladezeiten. Für eine nachnutzbare Erfassung, Zusammenführung und Durchsuchbarkeit heterogener Datenbestände ist es sinnvoll, **sich an bereits vorhandenen und etablierten Spezifikationen und Standards zu orientieren** und ein minimales Set an erforderlichen Metadatenelementen vorzugeben. Sollte von etablierten Standards abgewichen werden, so ist **eine Dokumentation der verwendeten Datenfelder und der in ihnen erhobenen Informationen notwendig**. Hierzu gehört die Vorgabe bestimmter Pflichtfelder für die Annotation der Daten, insbesondere für den Identifier, um eine eindeutige Referenzierung sicherzustellen, weiterhin Titel, um das digitale Objekt zu benennen, sowie Rechteangaben (Urheber, Rechtsangabe, Lizenz), um eine zweifelsfreie Nachnutzung der Dateien zu ermöglichen. Eine Versionierung der Metadaten ist inbesondere bei Datenpublikationen sehr wichtig, um den jeweiligen Bearbeitungszustand der Daten anzueigen. Das ist vor allem dann von Bedeutung, wenn Daten rein digital erzeugt (3D-Rekonstruktionen, digitale Editionen und Objektbiografien auf Basis nachgenutzter Daten) oder nachnutzbar für Dritte in Portalen oder über Wissensgraphen angeboten werden.

## Nutzungsszenarien (im Projekt)

Folgende Fragen sind üblicherweise in einem FDMPlan-Template mit Bezug auf Nutzungszenarien zu finden:

- Wozu / wie wird dieser Datensatz während des Projektes genutzt?
- Wie häufig wird dieser Datensatz genutzt?
- In welchem Umfang werden Infrastrukturressourcen benötigt (CPU-Stunden, Bandbreite, Speicherplatz etc.)?
- Gibt es beabsichtigte (ggf. auch potentielle) Nutzungsszenarien, für die die Unterstützung durch Datenmanagement- oder IT-ExpertInnen sinnvoll oder notwendig ist?

Diese Fragen dienen der Einschätzung, welche Ressourcen für die **geplante Nutzung der Daten während der Projektlaufzeit** nötig sind. Einschlägig für die Einschätzung des ökologischen Fussabdrucks der Arbeit an Datensätzen sind entsprechend den drei Phasen der Lebenszyklusanalyse die folgenden Aspekte:

- im Bereich Produktion: Wahl der Endgeräte und des Formats bzw. der Auflösung. Auch die Wahl des Ortes der Datenaufnahme kann durch Transport von Geräten, Personen oder Material (z.B. analog vorliegende Quellen) ein wichtiger Faktor sein.

- im Bereich Nutzung: Erzeugung des genutzten Stroms (vor Ort sowie für Datentausch), Fußabdruck der ausgesuchten Speicherplätze (bezogen auf CO2, Wasser, Biodiversität) und Differenzierung von Daten, die lokal, zentral, im Cache, auf Hot- oder Cold-Storage gehalten werden sollten, Form des Netz-Anschlusses, Wahl der Software.

- im Bereich Wiederverwendung: Daten über Schnittstellen beziehen, die eine passgenaue Auswahl von Daten und Formaten ermöglichen. Bei Daten, die häufig genutzt werden (zum Beispiel zentrale Metadaten, Transkriptionen oder andere Textdaten), können diese ggf. lokal vorgehalten werden.

- im Bereich Lebensende: Verlängerung der Nutzung bzw. Recycling der verwendeten Endgeräte und der Gesamtinfrastruktur.

Um diese Fragen zu beantworten, muss der Projekt-Workflow klar umreißen, wer wann welchen Zugriff zu welchen Daten braucht. Ein sparsamer Umgang bedeutet, **einerseits das Gesamtdatenvolumen gering zu halten, andererseits den Datentausch zu minimieren**, und dies sowohl im täglichen Arbeitsablauf als auch in den Speicherung- und Langzeitarchivierungsstrategien. 

## Weitergabe und Veröffentlichung

Folgende Fragen sind üblicherweise in einem FDMPlan-Template mit Bezug auf Weitergabe und Veröffentlichung zu finden:

- Soll dieser Datensatz veröffentlicht oder geteilt werden?
- Wenn nicht, begründen Sie dies bitte und unterscheiden Sie dabei zwischen rechtlichen und/oder vertraglichen Gründen und freiwilligen Einschränkungen.
- Wenn ja, unter welchen Nutzungsbedingungen oder welcher Lizenz sollen die Daten veröffentlicht bzw. geteilt werden?
- Sollte die Nachnutzung dieses Datensatzes Einschränkungen unterliegen, erläutern Sie bitte die Gründe.

Die Nachnutzung von Forschungsdaten gehört zu den Hauptzwecken des FDM. Ihre dauerhafte Veröffentlichung in einem qualitätsgesicherten offenen Repository ist damit zentraler Bestandteil eines jeden Forschungsdatenmanagementplan. Ein Zielkonflikt beim grünen FDM kann sich daraus ergeben, dass einerseits möglichst alle erhobenen Daten in möglichst hoher Qualität (z.B. Auflösung bei Bildern), in unterschiedlichen Formaten und mit umfangreichen Metadaten ausführlich dokumentiert der Forschung für die Nachnutzung zur Verfügung gestellt werden sollen. Andererseits sind jedoch gerade diese Tendenzen zu Quantität, Qualität, Vollständigkeit sowie Medien- und Formatvielfalt ressourcenintensiv. Es gilt daher abzuwägen zwischen den möglichen Nachnutzungsszenarien und daraus erwarteten Erkenntnissen auf der einen Seite und dem dafür aufgewandten Ressourcenverbrauch auf der anderen Seite.

Ist die Veröffentlichung der Daten geplant, so empfehlen wir im Sinne eines ressourcenschonenden FDM zu entscheiden, **wann und wie oft die Daten publiziert werden sollen**. Kann mit der Publikation bis zum Abschluss der Arbeit an den Daten gewartet werden? Es ist ressourcenschonend, wenn nicht mehrfach Versionen der Daten in ein Repository überspielt werden, sondern erst dann, wenn die Arbeit an den Daten tatsächlich abgeschlossen ist. Um dennoch Doppelarbeit zu vermeiden, sollten Projekte früh darüber kommunizieren, welche Daten erhoben, bearbeitet und zukünftig publiziert werden. Bei der Frage der Lizenzen sollte **eine möglichst freie CC-Lizenz gewählt werden**, um eine uneingeschränkte Form der Nachnutzung der Daten zu ermöglichen und zu vermeiden, dass diese erneut erhoben werden.

Zu überlegen ist darüber hinaus, welche **Nachnutzungsszenarien** erwartbar sind und wie die Daten, ihre Metadaten und die begleitende Dokumentation dafür beschaffen sein müssen (Formate, Auflösung). Kann eine **Auswahl** getroffen werden und genügt etwa die **Bereitstellung in einem einzigen Format**, von dem durch die Nachnutzenden – bei Bedarf – die Daten in andere Formate umgewandelt werden können (z.B. von .csv nach Excel oder nach MySQL) oder sollen Daten in verschiedenen Formaten angeboten werden? Die Verwendung einer DOI oder anderer permanenter Identifiern und Adressen erhöht die Wahrscheinlichkeit, dass die Daten an anderer Stelle verlinkt und nicht stattdessen dupliziert werden.

Wenn die Daten aus rechtlichen, ethischen oder anderen Gründen nicht veröffentlicht werden können, dann sollte im Sinne der Nachhaltigkeit: 
- eine **Dokumentation** erstellt und veröffentlicht werden, warum die Daten nicht publiziert/nachgenutzt werden können;
- die **Metadaten** veröffentlicht werden, so dass ggf. eine konkrete Kontaktaufnahme oder Anfrage für eine interne Nutzung durch andere möglich ist;
- **Verantwortlichkeiten** für die Daten festgelegt werden, z.B. in einem "Datentestament", so dass nach Ausscheiden einer Person klar ist, wer die Verantwortung für die Pflege der Daten übernimmt und als Kontaktperson nach außen fungiert.

## Speicherplatz und Langzeitarchivierung

Folgende Fragen sind üblicherweise in einem FDMPlan-Template mit Bezug auf Speicherplatz und Langzeitarchivierung zu finden:

- Muss dieser Datensatz langfristig aufbewahrt werden? 
- Aus welchen Gründen müssen die Daten langfristig aufbewahrt werden? 
- Wie lange müssen die Daten aufbewahrt werden? 
- Wie lang sollen die Daten nach Projektende (nach)nutzbar sein? 
- Wo werden die Daten nach Projektende gespeichert bzw. archiviert? 

Zu Beginn der Frage nach der Langzeitarchivierung sollte stets die Frage stehen, **ob und ggf. wie lange** ein Datensatz überhaupt aufbewahrt werden muss. In einigen Fällen mag es reichen, die Ergebnisse in Form von Aufsätzen zu veröffentlichen, in anderen Fällen können Datensätze für andere Projekte hilfreich sein und damit Mehrarbeit ersparen bzw. können sie andere Forschungsfragen überhaupt ermöglichen.

Für die Langzeitarchivierung sollten **bestehende institutionelle Strukturen und Workflows** genutzt werden. Infrastrukturen und **personelle Zuständigkeiten sollten möglichst früh geklärt werden**, um einen reibungslosen Ablauf bei Projektende sicherzustellen. Womöglich sollten gezielt energieeffiziente Server gewählt werden. Dabei gilt zu berücksichigen, dass auch bei Servern die Nutzung von bereits vorhandenem Material generell der Anschaffung von neuem Material vorzuziehen ist.

Vor der Übergabe der Daten müssen sie entsprechend vorbereitet werden, indem sie bereinigt (z. B. Duplikate und ältere Versionen beseitigt), passende Datenformate (z. B. TXT, XML oder TIFF) ausgewählt und die Dateien komprimiert werden (nach Abwägung des Verhältnisses zwischen Datenverlustrisko, Speicherverbrauch und Rechenleistung). Innerhalb eines Projektes können **je nach Datenformat unterschiedliche Qualitätsanforderungen an zu archivierende Datensätze gestellt werden**. Neben der Entscheidung über die langfristige Speicherung der Daten muss auch darüber entschieden werden, wie diese verfügbar gemacht werden sollen: Reicht es etwa, die Daten auf Nachfrage bereitzustellen oder sollten sie online leicht zugänglich verfügbar sein? Hierbei sollte das zu erwartende Interesse aus den Fachcommunities (und der Öffentlichkeit) berücksichtigt werden.

--

Unsere Empfehlungen beziehen sich überwiegend auf Daten als Endprodukte und nicht auf Generierungs- und Bearbeitungsprozesse, bei denen besonders ressourcenintensive Verfahren wie Künstliche Intelligenz (KI) oder Large Language Models (LLM) zum Einsatz kommen. Deren katastrophaler ökologischer Fussabdruck, sei es mit Blick auf ihren CO2-Ausstoß, Wasserverbrauch oder Einfluss auf die Biodiversität, ist nachgewiesen. Wie bei allen anderen Forschungsprozessen gilt es vor dem Einsatz solcher ressourcenintensiven Methoden genau abzuwägen, wie **Erkenntnismehrwert und Zerstörungspotential zu gewichten sind**. Dazu gibt es momentan keine verpflichtenden Massgaben. Hier ist kritisches, vernunftgeleitetes Denken vonseiten der Forschenden und Forschungseinrichtungen gefordert.
Gegebenenfalls werden wir den Bereich ressourcenschonende Empfehlungen zum Einsatz von Künstlicher Intelligenz in der geisteswissenschaftlichen Forschung in einem anderen Papier ausführlicher behandeln.


