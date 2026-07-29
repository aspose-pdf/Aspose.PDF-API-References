---
title: "PdfAnnotationEditor.ImportAnnotationsFromXfdf"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfAnnotationEditor. تستورد جميع التعليقات التوضيحية من ملف XFDF"
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

يستورد جميع التعليقات التوضيحية من ملف XFDF.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| xfdfFile | String | ملف XFDF الإدخال. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

يستورد جميع التعليقات التوضيحية من تدفق بيانات XFDF.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| xfdfStream | Stream | تيار بيانات XFDF الإدخال. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


