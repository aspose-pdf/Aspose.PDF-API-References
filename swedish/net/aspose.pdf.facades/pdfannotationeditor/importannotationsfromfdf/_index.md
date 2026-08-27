---
title: "PdfAnnotationEditor.ImportAnnotationsFromFdf"
second_title: "Aspose.PDF för .NET API‑referens"
description: "PdfAnnotationEditor metod. Importerar alla annotationer från FDF-fil"
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf method

Importerar alla annotationer från en FDF-fil.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fdfFile | String | Den inmatade FDF-filen. |

## Exempel

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### Se även

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


