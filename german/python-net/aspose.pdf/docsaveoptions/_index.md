---
title: "DocSaveOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Speicheroptionen für den Export ins Doc‑Format"
type: docs
weight: 220
url: /de/python-net/aspose.pdf/docsaveoptions/
---

## DocSaveOptions class

Speicheroptionen für den Export ins Doc‑Format

Der Typ DocSaveOptions stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| DocSaveOptions() | Initialisiert eine neue Instanz der Klasse DocSaveOptions |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| warning_handler | Rückruf zur Behandlung aller erzeugten Warnungen. <br/>            Der WarningHandler gibt ein ReturnAction‑Enum‑Element zurück, das entweder Continue oder Abort angibt. <br/>            Continue ist die Standardaktion und das Save operation wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, wodurch das Save operation beendet werden soll. |
| save_format | Format der Datenspeicherung. |
| close_response | Liest oder setzt den booleschen Wert, der angibt, ob das Response‑Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| extract_ocr_sublayer_only | Dieses Attribut aktiviert die Funktionalität zum Extrahieren von Bild oder Text <br/>            für PDF‑Dokumente mit OCR‑Unterschicht. |
| try_merge_adjacent_same_background_images | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen)<br/>              die aus mehreren gleichen Kachel‑Hintergrundbildern nebeneinander erstellt wurden.<br/>              In einem solchen Fall erzeugen Renderer der Zielformate (z. B. MsWord für das DOCS‑Format) manchmal<br/>              sichtbare Grenzen zwischen Teilen der Hintergrundbilder,<br/>              da ihre Techniken zur Kantenglättung (Anti‑Aliasing) von denen des Acrobat Reader abweichen.<br/>               Wenn es so aussieht, als enthielte das exportierte Dokument solche sichtbaren Grenzen zwischen <br/>              Teilen gleicher Hintergrundbilder, versuchen Sie bitte, diese Einstellung zu verwenden, um den<br/>              unerwünschten Effekt zu entfernen. <br/>                ACHTUNG! Diese Qualitätsoptimierung verlangsamt die Konvertierung in der Regel erheblich,<br/>              daher bitte diese Option nur verwenden, wenn sie wirklich notwendig ist. |
| mode | Erkennungsmodus. |
| relative_horizontal_proximity | Im PDF können Wörter intern durch Operatoren dargestellt werden, die Wörter<br/> drucken, indem sie ihre Buchstaben oder Silben unabhängig voneinander ausgeben. Daher müssen wir zum Erkennen von Wörtern manchmal Gruppen<br/> unabhängiger Zeichen erkennen, die tatsächlich Wörter sind.<br/> Diese Einstellung definiert die Breite des Abstands zwischen Textelementen (Buchstaben, Silben) <br/> der als Abstand zwischen Wörtern während der Erkennung von Wörtern im Quell‑PDF behandelt werden muss.<br/> (Das Vorhandensein eines leeren Raums von mindestens dieser Breite zwischen Buchstaben bedeutet, dass <br/> Textelemente zu unterschiedlichen Wörtern gehören).<br/> Sie ist an die Schriftgröße normiert – 1,0 bedeutet 100 % der angenommenen Schriftgröße des Wortes.<br/> ACHTUNG! Sie wird nur in Fällen verwendet, wenn das Quell‑PDF spezifische, selten genutzte Schriften enthält<br/>, für die ein optimaler Wert nicht aus der Schriftart berechnet werden kann. <br/> In der überwiegenden Mehrheit der Fälle ändert dieser Parameter nichts am Ergebnisdokument. |
| max_distance_between_text_lines | Dieser Parameter wird verwendet, um Textzeilen zu Absätzen zu gruppieren.<br/>            Bestimmt, wie weit zwei relative Textzeilen voneinander entfernt sein können. Angegeben in Hundertprozent der Höhe der Textzeilen. |
| recognize_bullets | Schaltet die Erkennung von Aufzählungszeichen ein |
| add_return_to_line_end | Verwende Absatz- oder Zeilenumbrüche |
| image_resolution_x | X‑Auflösung der konvertierten Bilder. |
| image_resolution_y | Y‑Auflösung der konvertierten Bilder. |
| format | Ausgabeformat |
| batch_size | Definiert die Batch‑Größe, wenn das Attribut 'SplitOnPages=false' ist, wird das gesamte HTML, das alle Eingabe‑PDF‑Seiten darstellt, nicht<br/>            in verschiedene HTML‑Seiten aufgeteilt, sondern in einer großen Ergebnis‑HTML‑Datei zusammengefasst.<br/>            Jede Quell‑PDF‑Seite wird jedoch mit ihrem eigenen <br/>            rechteckigen Bereich in HTML dargestellt (falls nötig können diese Bereiche mit dem speziellen Attribut 'PageBorderIfAny' begrenzt werden, um die Kanten des Papierblatts zu zeigen).<br/>            Dieser Parameter definiert die Breite des Randes, der zwingend um die Ausgab‑HTML‑Bereiche, die die Seiten des Quell‑PDF‑Dokuments repräsentieren, gelassen wird.<br/>            Im Wesentlichen definiert er das garantierte Intervall zwischen den HTML‑Darstellungen der PDF‑„Papier“‑Seiten bei dieser Konvertierungsart. |
| memory_save_mode_path | Definiert den Pfad (Dateiname oder Verzeichnisname), in dem<br/> temporäre Daten im Speicher‑Spar‑Modus abgelegt werden. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

