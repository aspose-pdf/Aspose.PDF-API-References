---
title: "SvgSaveOptions"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Speicheroptionen für den Export in das SVG-Format"
type: docs
weight: 1460
url: /de/python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

Speicheroptionen für den Export in das SVG-Format

Der Typ SvgSaveOptions stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| SvgSaveOptions() | Initialisiert eine neue Instanz der Klasse SvgSaveOptions |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| warning_handler | Rückruf zur Behandlung aller erzeugten Warnungen. <br/>            Der WarningHandler gibt ein ReturnAction‑Enum‑Element zurück, das entweder Continue oder Abort angibt. <br/>            Continue ist die Standardaktion und das Save operation wird fortgesetzt, der Benutzer kann jedoch auch Abort zurückgeben, wodurch das Save operation beendet werden soll. |
| save_format | Format der Datenspeicherung. |
| close_response | Liest oder setzt den booleschen Wert, der angibt, ob das Response‑Objekt nach dem Speichern des Dokuments in die Antwort geschlossen wird. |
| extract_ocr_sublayer_only | Keine |
| try_merge_adjacent_same_background_images | Keine |
| treat_target_file_name_as_directory | Diese Option definiert, ob ein Zielverzeichnis (falls noch nicht vorhanden) mit demselben Namen wie die angeforderte Ausgabedatei<br/>             erstellt wird, anstatt der angeforderten Ausgabedatei selbst.<br/>             Dadurch enthält das Verzeichnis alle ausgegebenen SVG‑Bilder der Seiten (wie unten beschrieben).<br/>               Wenn nein, werden Ausgabedateien der Seiten, die nicht die erste sind, genau im angeforderten Verzeichnis<br/>            als Hauptausgabedatei erstellt, jedoch mit dem Suffix _[2...n] im Dateinamen, das<br/>             durch die Seitennummer definiert ist, z. B. wenn Sie die Ausgabedatei \"C:\\AsposeTests\\output.svg\" festlegen<br/>             und die Ausgabe mehrere SVG‑Dateien der Seiten enthält,<br/>             dann werden die Seiten‑Dateien ebenfalls im Verzeichnis \"C:\\AsposeTests\\\" erstellt und haben die Namen 'output.svg', 'output_2.svg', 'output_3.svg' usw. |
| compress_output_to_zip_archive | Legt fest, ob die Ausgabe als ein ZIP‑Archiv erstellt wird.<br/>             Bitte beziehen Sie sich auf den Kommentar zur Option 'TreatTargetFileNameAsDirectory', um die Benennungsregeln<br/>             für SVG‑Dateien der Seiten eines mehrseitigen Quelldokuments zu sehen, die ebenfalls auf das gezippte Set von Ausgabedateien angewendet werden. |
| scale_to_pixels | Legt fest, ob das Ausgabedokument von typografischen Punkten in Pixel skaliert werden soll. |

### Siehe auch

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

