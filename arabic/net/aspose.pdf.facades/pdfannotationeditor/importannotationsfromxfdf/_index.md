---
title: PdfAnnotationEditor.ImportAnnotationsFromXfdf
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfAnnotationEditor. تستورد جميع التعليقات التوضيحية من ملف XFDF
type: docs
weight: 110
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/importannotationsfromxfdf/
---
## ImportAnnotationsFromXfdf(string) {#importannotationsfromxfdf_1}

تستورد جميع التعليقات التوضيحية من ملف XFDF.

```csharp
public void ImportAnnotationsFromXfdf(string xfdfFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xfdfFile | String | ملف XFDF المدخل. |

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf("annots.xfdf");
editor.Save("example_out.pdf");
```

### See Also

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## ImportAnnotationsFromXfdf(Stream) {#importannotationsfromxfdf}

تستورد جميع التعليقات التوضيحية من تدفق بيانات XFDF.

```csharp
public void ImportAnnotationsFromXfdf(Stream xfdfStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| xfdfStream | Stream | تدفق بيانات XFDF المدخل. |

## Examples

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.ImportAnnotationsFromXfdf(File.OpenRead("annots.xfdf"));
editor.Save("example_out.pdf");
```

### See Also

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)