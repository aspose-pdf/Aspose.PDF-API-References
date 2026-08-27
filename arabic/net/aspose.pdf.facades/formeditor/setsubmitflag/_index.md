---
title: "FormEditor.SetSubmitFlag"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. تعيين علامة الإرسال (submit flag) لزر الإرسال."
type: docs
weight: 330
url: /ar/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag method

تعيين علامة الإرسال لزر الإرسال.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم زر الإرسال. |
| submitFormFlag | SubmitFormFlag | علامة الإرسال. |

### قيمة الإرجاع

صحيح إذا تم العثور على الحقل وتم تعيين علامة الإرسال بنجاح.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### انظر أيضًا

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


