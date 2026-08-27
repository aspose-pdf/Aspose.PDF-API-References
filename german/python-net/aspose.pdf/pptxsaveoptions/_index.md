---
title: "PptxSaveOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Speicheroptionen für den Export in das SVG-Format"
type: docs
weight: 1290
url: /de/python-net/aspose.pdf/pptxsaveoptions/
---

## PptxSaveOptions class

Speicheroptionen für den Export in das SVG-Format

Der Typ PptxSaveOptions stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PptxSaveOptions() | Initialisiert eine neue Instanz der Klasse PptxSaveOptions |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| warning_handler | Rückruf zur Behandlung aller erzeugten Warnungen. <br/>            Der WarningHandler gibt ein ReturnAction‑Enum‑Element zurück, das entweder Continue oder Abort angibt. <br/>            Continue ist die Standardaktion und das Save operation wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, wodurch das Save operation beendet werden soll. |
| save_format | Format der Datenspeicherung. |
| close_response | Liest oder setzt den booleschen Wert, der angibt, ob das Response‑Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| extract_ocr_sublayer_only | Dieses Attribut aktiviert die Funktionalität zum Extrahieren von Bild oder Text <br/>            für PDF‑Dokumente mit OCR‑Unterschicht. |
| try_merge_adjacent_same_background_images | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen)<br/>              die aus mehreren gleichen Kachel‑Hintergrundbildern nebeneinander erstellt wurden.<br/>              In einem solchen Fall erzeugen Renderer der Zielformate (z. B. MsWord für das DOCS‑Format) manchmal<br/>              sichtbare Grenzen zwischen Teilen der Hintergrundbilder,<br/>              da ihre Techniken zur Kantenglättung (Anti‑Aliasing) von denen des Acrobat Reader abweichen.<br/>               Wenn es so aussieht, als enthielte das exportierte Dokument solche sichtbaren Grenzen zwischen <br/>              Teilen gleicher Hintergrundbilder, versuchen Sie bitte, diese Einstellung zu verwenden, um den<br/>              unerwünschten Effekt zu entfernen. <br/>                ACHTUNG! Diese Qualitätsoptimierung verlangsamt die Konvertierung in der Regel erheblich,<br/>              daher bitte diese Option nur verwenden, wenn sie wirklich notwendig ist. |
| slides_as_images | Wenn auf true gesetzt, wird der gesamte Inhalt als Bilder erkannt (ein Bild pro Seite) |
| image_resolution | Liest oder setzt die Bildauflösung (dpi). Standard ist 192 dpi. |
| separate_images | Wenn auf true gesetzt, werden Bilder von allen anderen Grafiken getrennt. |
| optimize_text_boxes | Schaltet die Erkennung von Textspalten um. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

