---
title: "PdfAnnotationEditor"
second_title: "Aspose.PDF för Python via .NET API‑referens"
description: "Representerar en klass för arbete med PDF‑dokumentanteckningar (kommentarer)."
type: docs
weight: 170
url: /sv/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

Representerar en klass för arbete med PDF‑dokumentanteckningar (kommentarer).

Typen PdfAnnotationEditor exponerar följande medlemmar:
## Konstruktörer
| Namn | Beskrivning |
| :- | :- |
| PdfAnnotationEditor() | Initierar ett nytt [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/)‑objekt. |
| PdfAnnotationEditor(document) | Initierar en ny instans av klassen PdfAnnotationEditor |
## Egenskaper
| Namn | Beskrivning |
| :- | :- |
| document | Hämtar dokumentfacaden som den arbetar med. |
## Metoder
| Namn | Beskrivning |
| :- | :- |
| bind_pdf(src_file) | Binder PDF-dokument för redigering. |
| bind_pdf(src_stream) | Binder PDF-dokument för redigering. |
| bind_pdf(src_doc) | Binder PDF-dokument för redigering. |
| save(dest_file) | Sparar PDF-dokumentet till den angivna filen. |
| save(dest_stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| import_annotations_from_xfdf(xfdf_file) | Importerar alla annotationer från XFDF‑filen. |
| import_annotations_from_xfdf(xfdf_stream) | Importerar alla anteckningar från XFDF-datastream. |
| import_annotation_from_xfdf(xfdf_file) | Importerar alla annotationer från XFDF‑filen. |
| import_annotation_from_xfdf(xfdf_file, annot_type) | Importerar de angivna anteckningarna från en XFDF-fil. |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | Importerar de angivna anteckningarna från en XFDF-datastream. |
| import_annotation_from_xfdf(xfdf_stream) | Importerar de angivna anteckningarna från en XFDF-datastream. |
| import_annotations(annot_file, annot_type) | Importerar de angivna anteckningarna till dokumentet från en matris av andra PDF-dokument. |
| import_annotations(annot_file) | Importerar de angivna anteckningarna till dokumentet från en matris av andra PDF-dokument. |
| import_annotations(annot_file_stream, annot_type) | Importerar de angivna anteckningarna till dokumentet från en matris av andra PDF-dokumentströmmar. |
| import_annotations(annot_file_stream) | Importerar de angivna anteckningarna till dokumentet från en matris av andra PDF-dokumentströmmar. |
| flattening_annotations() | Plattar till alla anteckningar i dokumentet. |
| flattening_annotations(flatten_settings) | Plattar till alla anteckningar i dokumentet. |
| flattening_annotations(start, end, annot_type) | Plattar till anteckningarna av de angivna typerna. |
| delete_annotations() | Tar bort alla anteckningar i dokumentet. |
| delete_annotations(annot_type) | Tar bort alla anteckningar av den angivna typen i dokumentet. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Exporterar innehållet för de angivna anteckningstyperna till XFDF |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Exporterar innehållet för de angivna anteckningstyperna till XFDF |
| extract_annotations(start, end, annot_types) | Hämtar listan över annotationer av de angivna typerna. |
| extract_annotations(start, end, annot_types) | Hämtar listan över annotationer av de angivna typerna. |
| close() | Frigör alla resurser som är associerade med den aktuella fasaden. |
| modify_annotations_author(start, end, src_author, des_author) | Modifierar författaren till annotationer på det angivna sidintervallet. |
| delete_annotation(annot_name) | Tar bort alla anteckningar av den angivna typen i dokumentet. |
| export_annotations_to_xfdf(xml_output_stream) | Exporterar annotationer till ström. |
| modify_annotations(start, end, annotation) | Modifierar annotationerna av den angivna typen på det angivna sidintervallet.<br/>            Den stöder att ändra följande annotationsegenskaper: Modified, Title, Contents, Color, Subject och Open. |
| redact_area(page_index, rect, color) | Raderar område på den angivna sidan. Allt innehåll tas bort. |

### Se även

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

