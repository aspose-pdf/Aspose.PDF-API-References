---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: طريقة WidgetAnnotation. تصدر حقل نموذج PDF المحدد إلى تنسيق JSON وتكتب النتيجة إلى الدفق المقدم
type: docs
weight: 120
url: /ar/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

تصدر حقل نموذج PDF المحدد إلى تنسيق JSON وتكتب النتيجة إلى الدفق المقدم.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| stream | Stream | الدفق الذي سيتم كتابة مخرجات JSON فيه. |
| options | ExportFieldsToJsonOptions | إعدادات اختيارية لتصدير حقل النموذج إلى JSON. |

### قيمة الإرجاع

مجموعة من [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) تشير إلى نتيجة عملية التصدير للحقل المحدد وعناصره الفرعية، إذا كانت موجودة.

## أمثلة

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### انظر أيضًا

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

تصدر حقل نموذج PDF المحدد إلى تنسيق JSON وتكتب النتيجة إلى الملف المحدد.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fileName | String | اسم الملف الذي سيتم كتابة مخرجات JSON فيه. |
| options | ExportFieldsToJsonOptions | إعدادات اختيارية لتصدير حقل النموذج إلى JSON. |

### قيمة الإرجاع

مجموعة من [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) تشير إلى نتيجة عملية التصدير للحقل المحدد وعناصره الفرعية، إذا كانت موجودة.

## أمثلة

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### انظر أيضًا

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)