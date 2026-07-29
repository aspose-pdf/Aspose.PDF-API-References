---
title: "Form.FillImageField"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة Form. تلصق صورة على حقل الزر الموجود كظهره وفقًا لاسم الحقل المؤهل بالكامل"
type: docs
weight: 150
url: /ar/net/aspose.pdf.facades/form/fillimagefield/
---
## FillImageField(string, string) {#fillimagefield_1}

يلصق صورة على حقل الزر الموجود كظهوره وفقًا لاسمه الكامل المؤهل.

```csharp
public void FillImageField(string fieldName, string imageFileName)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل بالكامل لحقل زر الصورة. |
| imageFileName | String | مسار ملف الصورة، سواءً النسبي أو المطلق مقبولان. |

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

يحمّل نسخة مفرطة من دالة FillImageField. الإدخال هو تدفق صورة.

```csharp
public void FillImageField(string fieldName, Stream imageStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| fieldName | String | اسم الحقل المؤهل بالكامل. |
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


