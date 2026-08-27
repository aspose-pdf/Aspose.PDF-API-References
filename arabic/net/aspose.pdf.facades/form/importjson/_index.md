---
title: "Form.ImportJson"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تستورد جميع بيانات الحقول من تدفق JSON إلى حقول المستند المطابقة للحقول بأسمائها الكاملة."
type: docs
weight: 290
url: /ar/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson method

يستورد جميع بيانات الحقول من تدفق JSON إلى حقول المستند، مطابقة الحقول بأسمائها الكاملة.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputJsonStream | Stream | تدفق JSON الإدخال الذي يحتوي على بيانات الحقول لتُستورد إلى حقول المستند. |

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


