---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: PdfAnnotationEditor metod. Importerar alla anteckningar från FDF-fil
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf metod

Importerar alla anteckningar från FDF-fil.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fdfFile | Sträng | Den inmatade FDF-filen. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### Se Även

* klass [PdfAnnotationEditor](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)