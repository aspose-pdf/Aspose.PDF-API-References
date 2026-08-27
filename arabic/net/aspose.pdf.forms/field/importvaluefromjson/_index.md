---
title: "Field.ImportValueFromJson"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Field. تستورد البيانات إلى الحقول المحددة من تدفق JSON بناءً على تطابق كامل لأسماء الحقول."
type: docs
weight: 210
url: /ar/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

يستورد البيانات إلى الحقول المحددة من دفق JSON، بناءً على مطابقة دقيقة لأسماء الحقول الكاملة.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputJsonStream | Stream | تدفق JSON الإدخال الذي يحتوي على بيانات الحقل لتُستورد إلى الحقل. |

### قيمة الإرجاع

صحيح إذا تم العثور على الحقل في تدفق JSON؛ وإلا - خطأ

## أمثلة

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### انظر أيضًا

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

يستورد البيانات إلى الحقل المحدد من دفق JSON، باستخدام الاسم الكامل المحدد في المتغيّر 'fieldFullNameInJSON' للمطابقة.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| inputJsonStream | Stream | تدفق JSON الإدخال الذي يحتوي على بيانات الحقل لتُستورد إلى الحقل. |
| fieldFullNameInJSON | String | اسم البيانات داخل تدفق JSON للمطابقة. إذا كان للبيانات داخل تدفق JSON بنية متداخلة، يجب تحديد الاسم الكامل مع جميع العناصر الأصلية والفرعية مفصولة بـ '.' |

### قيمة الإرجاع

صحيح إذا تم العثور على الحقل في ملف JSON؛ وإلا - خطأ

## أمثلة

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### انظر أيضًا

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


