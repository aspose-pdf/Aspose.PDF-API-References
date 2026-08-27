---
title: "ExcelSaveOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Speicheroptionen für den Export in das Excel-Format"
type: docs
weight: 330
url: /de/python-net/aspose.pdf/excelsaveoptions/
---

## ExcelSaveOptions class

Speicheroptionen für den Export in das Excel-Format

Der Typ ExcelSaveOptions stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| ExcelSaveOptions() | Initialisiert eine neue Instanz der Klasse ExcelSaveOptions |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| warning_handler | Rückruf zur Behandlung aller erzeugten Warnungen. <br/>            Der WarningHandler gibt ein ReturnAction‑Enum‑Element zurück, das entweder Continue oder Abort angibt. <br/>            Continue ist die Standardaktion und das Save operation wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, wodurch das Save operation beendet werden soll. |
| save_format | Format der Datenspeicherung. |
| close_response | Liest oder setzt den booleschen Wert, der angibt, ob das Response‑Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| extract_ocr_sublayer_only | Dieses Attribut aktiviert die Funktionalität zum Extrahieren von Bild oder Text <br/>            für PDF‑Dokumente mit OCR‑Unterschicht. |
| try_merge_adjacent_same_background_images | Manchmal enthalten PDFs Hintergrundbilder (von Seiten oder Tabellenzellen)<br/>              die aus mehreren gleichen Kachel‑Hintergrundbildern nebeneinander erstellt wurden.<br/>              In einem solchen Fall erzeugen Renderer der Zielformate (z. B. MsWord für das DOCS‑Format) manchmal<br/>              sichtbare Grenzen zwischen Teilen der Hintergrundbilder,<br/>              da ihre Techniken zur Kantenglättung (Anti‑Aliasing) von denen des Acrobat Reader abweichen.<br/>               Wenn es so aussieht, als enthielte das exportierte Dokument solche sichtbaren Grenzen zwischen <br/>              Teilen gleicher Hintergrundbilder, versuchen Sie bitte, diese Einstellung zu verwenden, um den<br/>              unerwünschten Effekt zu entfernen. <br/>                ACHTUNG! Diese Qualitätsoptimierung verlangsamt die Konvertierung in der Regel erheblich,<br/>              daher bitte diese Option nur verwenden, wenn sie wirklich notwendig ist. |
| minimize_the_number_of_worksheets | Setzen Sie true, wenn Sie die Anzahl der Arbeitsblätter in der resultierenden Arbeitsmappe minimieren müssen.<br/>            Der Standardwert ist false; das bedeutet, dass jede PDF-Seite als separates Arbeitsblatt gespeichert wird. |
| insert_blank_column_at_first | Setzen Sie true, wenn Sie eine leere Spalte als erste Spalte des Arbeitsblatts einfügen müssen.<br/>            Der Standardwert ist false; das bedeutet, dass keine leere Spalte eingefügt wird. |
| uniform_worksheets | Setzen Sie true, um eine einheitliche Spaltenaufteilung im gesamten Dokument zu verwenden. <br/>            Der Standardwert ist false; das bedeutet, dass die Spaltenaufteilung für jede Seite unabhängig ist. |
| format | Ausgabeformat |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

