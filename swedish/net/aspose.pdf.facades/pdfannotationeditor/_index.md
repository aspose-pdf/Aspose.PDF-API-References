---
title: Class PdfAnnotationEditor
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.PdfAnnotationEditor klass. Representerar en klass för arbete med PDF-dokumentanoteringar kommentarer
type: docs
weight: 4410
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/
---
## PdfAnnotationEditor klass

Representerar en klass för arbete med PDF-dokumentanoteringar (kommentarer).

```csharp
public sealed class PdfAnnotationEditor : SaveableFacade
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor)() | Initierar ett nytt `PdfAnnotationEditor`-objekt. |
| [PdfAnnotationEditor](pdfannotationeditor/#constructor_1)(Document) | Initierar ett nytt `PdfAnnotationEditor`-objekt baserat på *dokumentet*. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Hämtar dokumentfacaden som arbetas med. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initierar facaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initierar facaden. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initierar facaden. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Avslutar Aspose.Pdf.Document kopplad till en fasad. |
| [DeleteAnnotation](../../aspose.pdf.facades/pdfannotationeditor/deleteannotation/)(string) | Tar bort annoteringen med angivet annoteringsnamn. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations)() | Tar bort alla annoteringar i dokumentet. |
| [DeleteAnnotations](../../aspose.pdf.facades/pdfannotationeditor/deleteannotations/#deleteannotations_1)(string) | Tar bort alla annoteringar av den angivna typen i dokumentet. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Avslutar facaden. |
| [ExportAnnotationsToXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationstoxfdf/)(Stream) | Exporterar annoteringar till ström. |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf)(Stream, int, int, AnnotationType[]) | Exporterar innehållet av de angivna annoteringstyperna till XFDF |
| [ExportAnnotationsXfdf](../../aspose.pdf.facades/pdfannotationeditor/exportannotationsxfdf/#exportannotationsxfdf_1)(Stream, int, int, string[]) | Exporterar innehållet av de angivna annoteringstyperna till XFDF |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations)(int, int, AnnotationType[]) | Hämtar listan över annoteringar av de angivna typerna. |
| [ExtractAnnotations](../../aspose.pdf.facades/pdfannotationeditor/extractannotations/#extractannotations_1)(int, int, string[]) | Hämtar listan över annoteringar av de angivna typerna. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations)() | Plattar till alla annoteringar i dokumentet. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_1)(FlattenSettings) | Plattar till alla annoteringar i dokumentet. |
| [FlatteningAnnotations](../../aspose.pdf.facades/pdfannotationeditor/flatteningannotations/#flatteningannotations_2)(int, int, AnnotationType[]) | Plattar till annoteringarna av de angivna typerna. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_1)(Stream, AnnotationType[]) | Importerar de angivna annoteringarna från XFDF-dataström. |
| [ImportAnnotationFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationfromxfdf/#importannotationfromxfdf_3)(string, AnnotationType[]) | Importerar de angivna annoteringarna från XFDF-fil. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations)(Stream[]) | Importerar annoteringar till dokumentet från array av andra PDF-dokumentströmmar. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_2)(string[]) | Importerar annoteringar till dokumentet från array av andra PDF-dokument. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_1)(Stream[], AnnotationType[]) | Importerar de angivna annoteringarna till dokumentet från array av andra PDF-dokumentströmmar. |
| [ImportAnnotations](../../aspose.pdf.facades/pdfannotationeditor/importannotations/#importannotations_3)(string[], AnnotationType[]) | Importerar de angivna annoteringarna till dokumentet från array av andra PDF-dokument. |
| [ImportAnnotationsFromFdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/)(string) | Importerar alla annoteringar från FDF-fil. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf)(Stream) | Importerar alla annoteringar från XFDF-dataström. |
| [ImportAnnotationsFromXfdf](../../aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/#importannotationsfromxfdf_1)(string) | Importerar alla annoteringar från XFDF-fil. |
| [ModifyAnnotations](../../aspose.pdf.facades/pdfannotationeditor/modifyannotations/#modifyannotations)(int, int, Annotation) | Modifierar annoteringarna av den angivna typen på det angivna sidintervallet. Det stöder att modifiera följande annoteringsegenskaper: Modifierad, Titel, Innehåll, Färg, Ämne och Öppen. |
| [ModifyAnnotationsAuthor](../../aspose.pdf.facades/pdfannotationeditor/modifyannotationsauthor/)(int, int, string, string) | Modifierar författaren av annoteringar på det angivna sidintervallet. |
| [RedactArea](../../aspose.pdf.facades/pdfannotationeditor/redactarea/)(int, Rectangle, Color) | Redigerar område på den angivna sidan. Allt innehåll tas bort. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(Stream) | Sparar PDF-dokumentet till den angivna strömmen. |
| virtual [Save](../../aspose.pdf.facades/saveablefacade/save/)(string) | Sparar PDF-dokumentet till den angivna filen. |

### Se Även

* klass [SaveableFacade](../saveablefacade/)
* namnrymd [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../)