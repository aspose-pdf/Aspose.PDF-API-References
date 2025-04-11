---
title: Form.ExportJson
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تصدر محتويات جميع الحقول في الوثيقة إلى تدفق JSON. قيم حقول الأزرار لا يتم تصديرها
type: docs
weight: 80
url: /ar/net/aspose.pdf.facades/form/exportjson/
---
## طريقة Form.ExportJson

تصدر محتويات جميع الحقول في الوثيقة إلى تدفق JSON. قيم حقول الأزرار لا يتم تصديرها.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputJsonStream | Stream | تدفق JSON الناتج حيث سيتم كتابة بيانات حقول الوثيقة. |
| indented | Boolean | اختياري. يحدد ما إذا كان يجب تنسيق مخرجات JSON بشكل متداخل لتحسين القراءة. القيمة الافتراضية هي true. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)