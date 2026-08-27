---
title: "PdfExtractor.GetNextImage"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfExtractor. تسترجع الصورة التالية من مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة"
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

يسترجع الصورة التالية من مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة.

```csharp
public bool GetNextImage(string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | الملف الذي سيتم تخزين الصورة فيه |

### قيمة الإرجاع

صحيح إذا تم استخراج الصورة بنجاح

## أمثلة

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf("sample.pdf");
extractor.ExtractImage();
int i = 1;
while (extractor.HasNextImage())
{
    extractor.GetNextImage("image-" + i +".pdf");
}
```

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

يسترجع الصورة التالية من مستند PDF بالتنسيق المحدد للصورة. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | الملف الذي سيتم تخزين الصورة فيه |
| format | ImageFormat | تنسيق الصورة. |

### قيمة الإرجاع

صحيح إذا تم استخراج الصورة بنجاح

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

يسترجع الصورة التالية من ملف PDF ويخزنها في تدفق بالتنسيق المحدد للصورة.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق الذي سيتم حفظ بيانات الصورة فيه |
| format | ImageFormat | تنسيق الصورة. |

### قيمة الإرجاع

صحيح في حال تم استخراج الصورة بنجاح.

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

يسترجع الصورة التالية من ملف PDF ويخزنها في تدفق.

```csharp
public bool GetNextImage(Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق الذي سيتم حفظ بيانات الصورة فيه |

### قيمة الإرجاع

صحيح في حال تم استخراج الصورة بنجاح.

### انظر أيضًا

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


