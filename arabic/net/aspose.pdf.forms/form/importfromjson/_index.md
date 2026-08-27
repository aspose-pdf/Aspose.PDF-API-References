---
title: "Form.ImportFromJson"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تستورد حقول نموذج PDF من تنسيق JSON المقدم في الدفق."
type: docs
weight: 310
url: /ar/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

يستورد حقول نموذج PDF من تنسيق JSON المقدم في الدفق.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق لقراءة مدخلات JSON منه. |

### قيمة الإرجاع

مجموعة من [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) تشير إلى نتيجة عملية الاستيراد لكل حقل نموذج.

## أمثلة

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### انظر أيضًا

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

يستورد حقول نموذج PDF من تنسيق JSON المقدم في الملف المحدد.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف لقراءة مدخلات JSON منه. |

### قيمة الإرجاع

مجموعة من [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) تشير إلى نتيجة عملية الاستيراد لكل حقل نموذج.

## أمثلة

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### انظر أيضًا

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


