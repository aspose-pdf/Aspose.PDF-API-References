---
title: "PdfAnnotationEditor.DeleteAnnotations"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfAnnotationEditor. تحذف جميع التعليقات التوضيحية في المستند"
type: docs
weight: 30
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

يحذف جميع التعليقات التوضيحية في المستند.

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

يحذف جميع التعليقات التوضيحية من النوع المحدد في المستند.

```csharp
public void DeleteAnnotations(string annotType)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| annotType | String | سيتم حذف نوع التعليق التوضيحي. |

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


