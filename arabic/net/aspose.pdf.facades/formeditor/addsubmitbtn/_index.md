---
title: "FormEditor.AddSubmitBtn"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة FormEditor. إضافة زر إرسال إلى النموذج"
type: docs
weight: 130
url: /ar/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn method

إضافة زر إرسال إلى النموذج.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الزر الجديد. |
| صفحة | Int32 | Page حيث سيتم وضع الزر. |
| التسمية | String | نص زر. |
| عنوان URL | String | عنوان URL لزر الإرسال. |
| llx | Single | الإحداثي السيني للزاوية السفلية اليسرى. |
| lly | Single | الإحداثي الصادي للزاوية السفلية اليسرى. |
| urx | Single | الإحداثي السيني للزاوية العلوية اليمنى. |
| ury | Single | الإحداثي الصادي للزاوية العلوية اليمنى. |

## أمثلة

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### انظر أيضًا

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


