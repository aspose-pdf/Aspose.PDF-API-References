---
title: PdfAnnotationEditor
second_title: Aspose.PDF för .NET API Referens
description: Representerar en klass för arbete med PDF-dokumentkommentarer kommentarer.
type: docs
weight: 2420
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor class

Representerar en klass för arbete med PDF-dokumentkommentarer (kommentarer).

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor#constructor)() | Initierar ny[`PdfAnnotationEditor`](../pdfannotationeditor) objekt. |
| [PdfAnnotationEditor](pdfannotationeditor#constructor_1)(Document) | Initierar ny[`PdfAnnotationEditor`](../pdfannotationeditor) objekt på basen av*document* . |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document) { get; } | Får dokumentfasaden arbetar på. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Document) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(Stream) | Initierar fasaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf)(string) | Initierar fasaden. |
| virtual [Close](../../aspose.pdf.facades/facade/close)() | Kastar Aspose.Pdf.Dokument bunden med en fasad. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation)(string) | Tar bort anteckningen med angivet anteckningsnamn. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations)() | Tar bort alla kommentarer i dokumentet. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations#deleteannotations_1)(string) | Tar bort alla anteckningar av den angivna typen i dokumentet. |
| [Dispose](../../aspose.pdf.facades/facade/dispose)() | Disponerar fasaden. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf)(Stream) | Exporterar kommentarer till stream. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Exporterar innehållet i de angivna anteckningstyperna till XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf#exportannotationsxfdf_1)(Stream, int, int, string[]) | Exporterar innehållet i de angivna anteckningstyperna till XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations)(int, int, AnnotationType[]) | Hämtar listan över anteckningar av de angivna typerna. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations#extractannotations_1)(int, int, string[]) | Hämtar listan över anteckningar av de angivna typerna. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations)() | Plattar ut alla kommentarer i dokumentet. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_1)(FlattenSettings) | Plattar ut alla kommentarer i dokumentet. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations#flatteningannotations_2)(int, int, AnnotationType[]) | Plattar ut kommentarerna för de angivna typerna. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Importerar de angivna anteckningarna från XFDF-dataström. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf#importannotationfromxfdf_3)(string, AnnotationType[]) | Importerar de angivna anteckningarna från XFDF-filen. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations)(Stream[]) | Importerar kommentarer till dokument från en mängd andra PDF-dokumentströmmar. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_2)(string[]) | Importerar kommentarer till dokument från en mängd andra PDF-dokument. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_1)(Stream[], AnnotationType[]) | Importerar de angivna anteckningarna till dokument från en rad andra PDF-dokumentströmmar. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations#importannotations_3)(string[], AnnotationType[]) | Importerar de angivna anteckningarna till dokument från en rad andra PDF-dokument. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf)(Stream) | Importerar alla kommentarer från XFDF-dataström. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf#importannotationsfromxfdf_1)(string) | Importerar alla kommentarer från XFDF-fil. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations#modifyannotations)(int, int, Annotation) | Modifierar anteckningarna av den angivna typen på det angivna sidintervallet. Det stöder att ändra nästa anteckningsegenskaper: Modifierad, Titel, Innehåll, Färg, Ämne och Öppna. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor)(int, int, string, string) | Ändrar författaren till anteckningar på det angivna sidintervallet. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea)(int, Rectangle, Color) | Redagerar område på den angivna sidan. Allt innehåll tas bort. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save)(string) | Sparar PDF-dokumentet till den angivna filen. |

### Se även

* class [SaveableFacade](../saveablefacade)
* namnutrymme [Aspose.Pdf.Facades](../../aspose.pdf.facades)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
