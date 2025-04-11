---
title: PdfAnnotationEditor.DeleteAnnotations
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfAnnotationEditor. تحذف جميع التعليقات التوضيحية في المستند
type: docs
weight: 30
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

تحذف جميع التعليقات التوضيحية في المستند.

```csharp
public void DeleteAnnotations()
```

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

تحذف جميع التعليقات التوضيحية من النوع المحدد في المستند.

```csharp
public void DeleteAnnotations(string annotType)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| annotType | String | نوع التعليق التوضيحي الذي سيتم حذفه. |

## أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### انظر أيضًا

* class [PdfAnnotationEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)