---
title: FormEditor.SetSubmitFlag
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تعيين علامة الإرسال لزر الإرسال
type: docs
weight: 330
url: /ar/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## طريقة FormEditor.SetSubmitFlag

تعيين علامة الإرسال لزر الإرسال.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم زر الإرسال. |
| submitFormFlag | SubmitFormFlag | علامة الإرسال. |

### قيمة الإرجاع

true إذا تم العثور على الحقل وتم تعيين علامة الإرسال بنجاح.

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