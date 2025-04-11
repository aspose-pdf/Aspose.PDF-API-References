---
title: FormEditor.SetFieldAppearance
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تعيين علامات الحقل
type: docs
weight: 280
url: /ar/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## طريقة FormEditor.SetFieldAppearance

تعيين علامات الحقل

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي يجب تحديث علاماته. |
| flags | AnnotationFlags | علامة الحقل. |

### قيمة الإرجاع

true إذا تم تحديث العلامات بنجاح.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm1.pdf", "FormEditor_SetFieldAppearance.pdf");
formEditor.SetFieldAppearance("Name", AnnotationFlags.Hidden);
formEditor.SetFieldAppearance("Phone", AnnotationFlags.NoView | AnnotationFlags.Print);
```

### انظر أيضًا

* enum [AnnotationFlags](../../../aspose.pdf.annotations/annotationflags/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)