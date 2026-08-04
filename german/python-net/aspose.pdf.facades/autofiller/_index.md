---
title: "AutoFiller"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Klasse dar, die Daten aus einer Datenbank oder anderen Datenquellen empfängt, sie in die entworfenen Felder der Vorlagen‑PDF einfügt und schließlich eine neue PDF‑Datei oder einen Stream erzeugt.<br/>             Sie unterstützt zwei Eingabemodi für die Vorlagendatei: Eingabe als Stream oder als PDF‑Datei.<br/>             Sie unterstützt vier Ausgabemodi: einen zusammengeführten Stream, eine zusammengeführte Datei, viele kleine Streams, viele kleine Dateien.<br/>             Sie kann literal enthaltene Daten aus einem System.Data.DataTable empfangen."
type: docs
weight: 20
url: /de/python-net/aspose.pdf.facades/autofiller/
---

## AutoFiller class

Stellt eine Klasse dar, die Daten aus einer Datenbank oder anderen Datenquellen empfängt, sie in die entworfenen Felder der Vorlagen‑PDF einfügt und schließlich eine neue PDF‑Datei oder einen Stream erzeugt.<br/>             Sie unterstützt zwei Eingabemodi für die Vorlagendatei: Eingabe als Stream oder als PDF‑Datei.<br/>             Sie unterstützt vier Ausgabemodi: einen zusammengeführten Stream, eine zusammengeführte Datei, viele kleine Streams, viele kleine Dateien.<br/>             Sie kann literal enthaltene Daten aus einem System.Data.DataTable empfangen.

Der AutoFiller-Typ stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| AutoFiller() | Initialisiert eine neue Instanz der AutoFiller-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| output_stream | Liest oder legt fest den OutputStream. Einer von vier Ausgabemodi. Sein klassischer Anwendungsfall ist Response.OutputStream.<br/>            Bitte beziehen Sie sich auf die Online-Demo. |
| output_streams | Liest oder legt fest die vielen Output Streams. Einer von vier Ausgabemodi. |
| input_stream | Liest oder legt fest den Eingabevorlagen-Stream. Einer von zwei Eingabemodi. |
| input_file_name | Liest oder legt fest die Eingabevorlagendatei. Einer von zwei Eingabemodi. |
| output_file_name | Liest oder legt fest die eine große zusammengeführte Ausgabedatei. Einer von vier Ausgabemodi. |
| generating_path | Liest oder legt fest den Generating Path der kleinen PDF-Dateien, wenn viele kleine PDF-Dateien erzeugt werden sollen. Sie funktioniert zusammen mit einer anderen Eigenschaft [basic_file_name](/pdf/python-net/aspose.pdf.facades/autofiller/)BasicFileName.<br/>            Einer von vier Ausgabemodi. |
| basic_file_name | Liest oder legt fest den Basisdateinamen, wenn viele kleine Dateien erzeugt werden. Die erzeugte Datei wird z. B. "BasicFileName0","BasicFileName1",... heißen<br/>            Sie funktioniert zusammen mit einer anderen Eigenschaft [generating_path](/pdf/python-net/aspose.pdf.facades/autofiller/)GeneratingPath. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| save() | Speichert alle PDFs. |
| save(dest_file) | Speichert alle PDFs. |
| save(dest_stream) | Speichert alle PDFs. |
| bind_pdf(src_file) | Bindet eine PDF-Datei. |
| bind_pdf(src_stream) | Bindet eine PDF-Datei. |
| bind_pdf(src_doc) | Bindet ein PDF-Dokument. |
| close() | Schließt das Objekt und die Ausgabeströme. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

