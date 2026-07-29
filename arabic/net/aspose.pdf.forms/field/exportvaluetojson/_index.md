---
title: "Field.ExportValueToJson"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Field. تصدر محتوى الحقل المحدد إلى تدفق JSON. لا يتم تصدير قيم حقول الأزرار"
type: docs
weight: 180
url: /ar/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson method

يصدّر محتوى الحقل المحدد إلى دفق JSON. لا يتم تصدير قيم حقول الأزرار.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputJsonStream | Stream | تدفق JSON الناتج حيث سيتم كتابة بيانات الحقل. |
| مُسْتَفَصِل | Boolean | اختياري. يحدد ما إذا كان يجب أن يكون إخراج JSON مُستفصل لتحسين القابلية للقراءة. القيمة الافتراضية هي true. |

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


