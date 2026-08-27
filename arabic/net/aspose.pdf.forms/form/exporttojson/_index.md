---
title: "Form.ExportToJson"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تصدر حقول نموذج PDF إلى تنسيق JSON وتكتب النتيجة إلى الدفق المقدم."
type: docs
weight: 260
url: /ar/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

يصدّر حقول نموذج PDF إلى تنسيق JSON ويكتب النتيجة إلى الدفق المقدم.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق لكتابة مخرجات JSON إليه. |
| options | ExportFieldsToJsonOptions | إعدادات اختيارية لتصدير حقول النموذج إلى JSON. |

### قيمة الإرجاع

مجموعة من [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) تشير إلى نتيجة عملية التصدير لكل حقل نموذج.

## أمثلة

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### انظر أيضًا

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

يصدّر حقول نموذج PDF إلى تنسيق JSON ويكتب النتيجة إلى الملف المحدد.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف الذي سيتم كتابة مخرجات JSON إليه. |
| options | ExportFieldsToJsonOptions | إعدادات اختيارية لتصدير حقول النموذج إلى JSON. |

### قيمة الإرجاع

مجموعة من [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) تشير إلى نتيجة عملية التصدير لكل حقل نموذج.

## أمثلة

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### انظر أيضًا

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


