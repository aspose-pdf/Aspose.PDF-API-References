---
title: "FormEditor.SetSubmitUrl"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. تعيين عنوان URL للزر"
type: docs
weight: 340
url: /ar/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

يضبط URL للزر.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم زر الإرسال. |
| عنوان URL | String | عنوان URL مؤهل بالكامل. |

### قيمة الإرجاع

صحيح إذا تم تعيين عنوان URL للزر بنجاح.

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


