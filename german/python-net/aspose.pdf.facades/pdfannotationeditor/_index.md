---
title: "PdfAnnotationEditor"
second_title: "Aspose.PDF für Python via .NET API‑Referenz"
description: "Stellt eine Klasse für die Arbeit mit PDF‑Dokumentannotation (Kommentare) dar."
type: docs
weight: 170
url: /de/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

Stellt eine Klasse für die Arbeit mit PDF‑Dokumentannotation (Kommentare) dar.

Der Typ PdfAnnotationEditor stellt die folgenden Mitglieder bereit:
## Konstruktoren
| Name | Beschreibung |
| :- | :- |
| PdfAnnotationEditor() | Initialisiert ein neues [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/) Objekt. |
| PdfAnnotationEditor(document) | Initialisiert eine neue Instanz der PdfAnnotationEditor-Klasse |
## Eigenschaften
| Name | Beschreibung |
| :- | :- |
| Dokument | Ermittelt das Dokument, auf dem die Fassade arbeitet. |
## Methoden
| Name | Beschreibung |
| :- | :- |
| bind_pdf(src_file) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_stream) | Bindet PDF-Dokument zur Bearbeitung. |
| bind_pdf(src_doc) | Bindet PDF-Dokument zur Bearbeitung. |
| save(dest_file) | Speichert das PDF-Dokument in die angegebene Datei. |
| save(dest_stream) | Speichert das PDF-Dokument in den angegebenen Stream. |
| import_annotations_from_xfdf(xfdf_file) | Importiert alle Anmerkungen aus einer XFDF-Datei. |
| import_annotations_from_xfdf(xfdf_stream) | Importiert alle Anmerkungen aus einem XFDF-Datenstrom. |
| import_annotation_from_xfdf(xfdf_file) | Importiert alle Anmerkungen aus einer XFDF-Datei. |
| import_annotation_from_xfdf(xfdf_file, annot_type) | Importiert die angegebenen Anmerkungen aus einer XFDF-Datei. |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | Importiert die angegebenen Anmerkungen aus einem XFDF-Datenstrom. |
| import_annotation_from_xfdf(xfdf_stream) | Importiert die angegebenen Anmerkungen aus einem XFDF-Datenstrom. |
| import_annotations(annot_file, annot_type) | Importiert die angegebenen Anmerkungen in das Dokument aus einem Array anderer PDF-Dokumente. |
| import_annotations(annot_file) | Importiert die angegebenen Anmerkungen in das Dokument aus einem Array anderer PDF-Dokumente. |
| import_annotations(annot_file_stream, annot_type) | Importiert die angegebenen Anmerkungen in das Dokument aus einem Array anderer PDF-Dokument-Streams. |
| import_annotations(annot_file_stream) | Importiert die angegebenen Anmerkungen in das Dokument aus einem Array anderer PDF-Dokument-Streams. |
| flattening_annotations() | Flacht alle Anmerkungen im Dokument ab. |
| flattening_annotations(flatten_settings) | Flacht alle Anmerkungen im Dokument ab. |
| flattening_annotations(start, end, annot_type) | Flacht die Anmerkungen der angegebenen Typen ab. |
| delete_annotations() | Löscht alle Anmerkungen im Dokument. |
| delete_annotations(annot_type) | Löscht alle Anmerkungen des angegebenen Typs im Dokument. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Exportiert den Inhalt der angegebenen Anmerkungstypen nach XFDF |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Exportiert den Inhalt der angegebenen Anmerkungstypen nach XFDF |
| extract_annotations(start, end, annot_types) | Gibt die Liste der Anmerkungen der angegebenen Typen zurück. |
| extract_annotations(start, end, annot_types) | Gibt die Liste der Anmerkungen der angegebenen Typen zurück. |
| close() | Gibt alle mit der aktuellen Fassade verbundenen Ressourcen frei. |
| modify_annotations_author(start, end, src_author, des_author) | Ändert den Autor der Anmerkungen im angegebenen Seitenbereich. |
| delete_annotation(annot_name) | Löscht alle Anmerkungen des angegebenen Typs im Dokument. |
| export_annotations_to_xfdf(xml_output_stream) | Exportiert Anmerkungen in den Stream. |
| modify_annotations(start, end, annotation) | Ändert die Anmerkungen des angegebenen Typs im angegebenen Seitenbereich.<br/>            Unterstützt das Ändern folgender Anmerkungs‑Eigenschaften: Modified, Title, Contents, Color, Subject und Open. |
| redact_area(page_index, rect, color) | Redigiert den Bereich auf der angegebenen Seite. Alle Inhalte werden entfernt. |

### Siehe auch

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

