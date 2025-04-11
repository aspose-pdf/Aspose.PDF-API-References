---
title: Form.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تصدر حقول نموذج PDF إلى تنسيق JSON وتكتب النتيجة إلى التدفق المقدم
type: docs
weight: 240
url: /ar/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

تصدر حقول نموذج PDF إلى تنسيق JSON وتكتب النتيجة إلى التدفق المقدم.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | التدفق الذي سيتم كتابة مخرجات JSON فيه. |
| options | ExportFieldsToJsonOptions | إعدادات اختيارية لتصدير حقول النموذج إلى JSON. |

### Return Value

مجموعة من [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) تشير إلى نتيجة عملية التصدير لكل حقل من حقول النموذج.

## Examples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### See Also

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

تصدر حقول نموذج PDF إلى تنسيق JSON وتكتب النتيجة إلى الملف المحدد.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | اسم الملف الذي سيتم كتابة مخرجات JSON فيه. |
| options | ExportFieldsToJsonOptions | إعدادات اختيارية لتصدير حقول النموذج إلى JSON. |

### Return Value

مجموعة من [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) تشير إلى نتيجة عملية التصدير لكل حقل من حقول النموذج.

## Examples

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### See Also

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)