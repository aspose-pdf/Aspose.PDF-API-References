---
title: DeleteAnnotations
second_title: Aspose.PDF لمرجع .NET API
description: حذف كافة التعليقات التوضيحية في المستند.
type: docs
weight: 30
url: /ar/net/aspose.pdf.facades/pdfannotationeditor/deleteannotations/
---
## DeleteAnnotations() {#deleteannotations}

حذف كافة التعليقات التوضيحية في المستند.

```csharp
public void DeleteAnnotations()
```

### أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations();
editor.Save("example_out.pdf");
```

### أنظر أيضا

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfannotationeditor)
* المجسم [Aspose.PDF](../../../)

---

## DeleteAnnotations(string) {#deleteannotations_1}

حذف كافة التعليقات التوضيحية من النوع المحدد في المستند.

```csharp
public void DeleteAnnotations(string annotType)
```

| معامل | يكتب | وصف |
| --- | --- | --- |
| annotType | String | سيتم حذف نوع التعليق التوضيحي. |

### أمثلة

```csharp
PdfAnnotationEditor editor = new PdfAnnotationEditor();
editor.BindPdf("example.pdf");
editor.DeleteAnnotations("Text");
editor.Save("example_out.pdf");
```

### أنظر أيضا

* class [PdfAnnotationEditor](../../pdfannotationeditor)
* مساحة الاسم [Aspose.Pdf.Facades](../../pdfannotationeditor)
* المجسم [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->