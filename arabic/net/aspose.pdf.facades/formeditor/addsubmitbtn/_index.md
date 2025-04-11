---
title: FormEditor.AddSubmitBtn
second_title: Aspose.PDF for .NET API Reference
description: طريقة FormEditor. إضافة زر إرسال على النموذج
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## طريقة FormEditor.AddSubmitBtn

إضافة زر إرسال على النموذج.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الزر الجديد. |
| page | Int32 | الصفحة التي سيتم وضع الزر عليها. |
| label | String | عنوان الزر. |
| url | String | عنوان URL لزر الإرسال. |
| llx | Single | الإحداثي السيني للزاوية السفلى اليسرى. |
| lly | Single | الإحداثي الصادي للزاوية السفلى اليسرى. |
| urx | Single | الإحداثي السيني للزاوية العليا اليمنى. |
| ury | Single | الإحداثي الصادي للزاوية العليا اليمنى. |

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)