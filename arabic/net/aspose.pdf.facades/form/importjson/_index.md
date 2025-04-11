---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تستورد جميع بيانات الحقول من تدفق JSON إلى حقول الوثيقة مطابقة الحقول بأسمائها الكاملة
type: docs
weight: 290
url: /ar/net/aspose.pdf.facades/form/importjson/
---
## طريقة Form.ImportJson

تستورد جميع بيانات الحقول من تدفق JSON إلى حقول الوثيقة، مطابقة الحقول بأسمائها الكاملة.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| inputJsonStream | Stream | تدفق JSON المدخل الذي يحتوي على بيانات الحقول التي سيتم استيرادها إلى حقول الوثيقة. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)