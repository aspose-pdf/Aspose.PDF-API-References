---
title: Form.FillImageField
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. يلصق صورة على حقل الزر الموجود كمظهر له وفقًا لاسم الحقل المؤهل بالكامل
type: docs
weight: 150
url: /ar/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

يلصق صورة على حقل الزر الموجود كمظهر له وفقًا لاسم الحقل المؤهل بالكامل.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | الاسم المؤهل بالكامل لحقل زر الصورة. |
| imageFileName | String | مسار ملف الصورة، النسبي والمطلق كلاهما مقبول. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", "file.jpg");
form.Save();
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## FillImageField(string, Stream) {#fillimagefield}

تقوم بتحميل وظيفة FillImageField. الإدخال هو دفق صورة.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | الاسم المؤهل بالكامل. |
| imageStream | Stream | دفق الصورة. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
form.FillImageField("fieldName", new FileStream("file.jpg", FileMode.Open, FileAccess.Read));
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)