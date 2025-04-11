---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. تعيين عنوان URL للزر
type: docs
weight: 340
url: /ar/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## طريقة FormEditor.SetSubmitUrl

تعيين عنوان URL للزر.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | سلسلة | اسم زر الإرسال. |
| url | سلسلة | عنوان URL مؤهل بالكامل. |

### قيمة الإرجاع

true إذا تم تعيين عنوان URL للزر بنجاح.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)