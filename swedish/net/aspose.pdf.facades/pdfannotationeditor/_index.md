---
title: "Klass PdfAnnotationEditor"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Facades.PdfAnnotationEditor-klass. Representerar en klass för arbete med PDF-dokumentets Annotation‑kommentarer."
type: docs
weight: 4530
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

Representerar en klass för arbete med PDF document-anteckningar (kommentarer).

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | Initierar ett nytt `PdfAnnotationEditor`‑objekt. |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | Initierar ett nytt `PdfAnnotationEditor`‑objekt baserat på *document*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar den dokumentfacade som arbetet sker på. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar fasaden. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Rensar Aspose.Pdf.Document som är bunden till en fasad. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | Tar bort Annotation med angivet Annotation‑namn. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | Tar bort alla Annotation i Document. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | Tar bort alla Annotation av den angivna typen i Document. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar fasaden. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | Exporterar Annotation till en ström. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Exporterar innehållet för de angivna Annotation‑typerna till XFDF. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | Exporterar innehållet för de angivna Annotation‑typerna till XFDF. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | Hämtar listan över Annotation av de angivna typerna. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | Hämtar listan över Annotation av de angivna typerna. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | Plattar till alla Annotation i Document. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | Plattar till alla Annotation i Document. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | Plattar till Annotation av de angivna typerna. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Importerar de angivna Annotation från XFDF‑datastreamen. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | Importerar de angivna Annotation från XFDF‑filen. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | Importerar Annotation till Document från en array av strömmar från ett annat PDF Document. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | Importerar annotationer till dokument från en array av andra PDF-dokument. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | Importerar de specificerade annotationerna till dokument från en array av andra PDF-dokumentströmmar. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | Importerar de specificerade annotationerna till dokument från en array av andra PDF-dokument. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | Importerar alla annotationer från en FDF-fil. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importerar alla annotationer från en XFDF-dataström. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importerar alla annotationer från en XFDF-fil. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | Modifierar annotationerna av den angivna typen på det angivna sidintervallet. Det stöder att ändra följande annotationsegenskaper: Modified, Title, Contents, Color, Subject och Open. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | Modifierar författaren till annotationerna på det angivna sidintervallet. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | Raderar område på den angivna sidan. Allt innehåll tas bort. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Sparar PDF-dokumentet till den angivna filen. |

### Se även

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


