---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: طريقة الحقل. تستورد البيانات إلى الحقول المحددة من تدفق JSON بناءً على تطابق دقيق لأسماء الحقول الكاملة
type: docs
weight: 210
url: /ar/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

تستورد البيانات إلى الحقول المحددة من تدفق JSON، بناءً على تطابق دقيق لأسماء الحقول الكاملة.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputJsonStream | Stream | تدفق JSON المدخل الذي يحتوي على بيانات الحقل التي سيتم استيرادها إلى الحقل. |

### Return Value

صحيح إذا تم العثور على الحقل في تدفق JSON؛ خلاف ذلك - خطأ

## Examples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### See Also

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

تستورد البيانات إلى الحقل المحدد من تدفق JSON، باستخدام الاسم الكامل المحدد في متغير 'fieldFullNameInJSON' للمطابقة.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputJsonStream | Stream | تدفق JSON المدخل الذي يحتوي على بيانات الحقل التي سيتم استيرادها إلى الحقل. |
| fieldFullNameInJSON | String | اسم البيانات داخل تدفق JSON للمطابقة. إذا كانت البيانات داخل تدفق JSON تحتوي على هيكل متداخل، يجب تحديد الاسم الكامل مع جميع العناصر الأبوية والطفلية مفصولة بـ '.' |

### Return Value

صحيح إذا تم العثور على الحقل في ملف JSON؛ خلاف ذلك - خطأ

## Examples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### See Also

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)