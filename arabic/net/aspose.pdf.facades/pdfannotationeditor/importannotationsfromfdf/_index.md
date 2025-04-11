---
title: PdfAnnotationEditor.ImportAnnotationsFromFdf
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfAnnotationEditor. تستورد جميع التعليقات التوضيحية من ملف FDF
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf method

تستورد جميع التعليقات التوضيحية من ملف FDF.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fdfFile | String | ملف FDF المدخل. |

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)