---
title: Form.ImportFromJson
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تستورد حقول نموذج PDF من تنسيق JSON المقدم في الدفق
type: docs
weight: 290
url: /ar/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

تستورد حقول نموذج PDF من تنسيق JSON المقدم في الدفق.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | الدفق لقراءة مدخلات JSON منه. |

### Return Value

مجموعة من [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) تشير إلى نتيجة عملية الاستيراد لكل حقل نموذج.

## Examples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### See Also

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

تستورد حقول نموذج PDF من تنسيق JSON المقدم في الملف المحدد.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | اسم الملف لقراءة مدخلات JSON منه. |

### Return Value

مجموعة من [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) تشير إلى نتيجة عملية الاستيراد لكل حقل نموذج.

## Examples

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### See Also

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)