---
title: "PdfAnnotationEditor.ImportAnnotationsFromFdf"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfAnnotationEditor. تستورد جميع التعليقات التوضيحية من ملف FDF"
type: docs
weight: 100
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromfdf/
---
## PdfAnnotationEditor.ImportAnnotationsFromFdf method

يستورد جميع التعليقات التوضيحية من ملف FDF.

```csharp
public void ImportAnnotationsFromFdf(string fdfFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fdfFile | String | ملف FDF الإدخال. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromFdf("annots.fdf");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


