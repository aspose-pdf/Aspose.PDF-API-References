---
title: "FormEditor.SetFieldAppearance"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. تعيين أعلام الحقل"
type: docs
weight: 280
url: /ar/net/aspose.pdf.facades/formeditor/setfieldappearance/
---
## FormEditor.SetFieldAppearance method

حدد أعلام الحقل

```csharp
public bool SetFieldAppearance(string fieldName, AnnotationFlags flags)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل الذي يجب تحديث أعلامه. |
| flags | AnnotationFlags | علامة الحقل. |

### قيمة الإرجاع

صحيح إذا تم تحديث العلامات بنجاح.

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


