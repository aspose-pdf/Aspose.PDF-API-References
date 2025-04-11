---
title: Field.ExportValueToJson
second_title: Aspose.PDF for .NET API Reference
description: طريقة الحقل. تصدر محتوى الحقل المحدد إلى تدفق JSON. لا يتم تصدير قيمة حقل الزر
type: docs
weight: 180
url: /ar/net/aspose.pdf.forms/field/exportvaluetojson/
---
## طريقة Field.ExportValueToJson

تصدر محتوى الحقل المحدد إلى تدفق JSON. لا يتم تصدير قيمة حقل الزر.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputJsonStream | Stream | تدفق JSON الناتج حيث سيتم كتابة بيانات الحقل. |
| indented | Boolean | اختياري. يحدد ما إذا كان يجب تنسيق مخرجات JSON بشكل متداخل لتحسين القراءة. القيمة الافتراضية هي true. |

## أمثلة

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### انظر أيضًا

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)