---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfExtractor. تسترجع الصورة التالية من مستند PDF. ملاحظة يجب استدعاء ExtractImage قبل استخدام هذه الطريقة
type: docs
weight: 170
url: /ar/net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

تسترجع الصورة التالية من مستند PDF. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة.

```csharp
public bool GetNextImage(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | الملف الذي سيتم تخزين الصورة فيه |

### Return Value

صحيح إذا تم استخراج الصورة بنجاح

## Examples

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

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, ImageFormat) {#getnextimage_3}

تسترجع الصورة التالية من مستند PDF بالتنسيق المحدد للصورة. ملاحظة: يجب استدعاء ExtractImage قبل استخدام هذه الطريقة.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | الملف الذي سيتم تخزين الصورة فيه |
| format | ImageFormat | تنسيق الصورة. |

### Return Value

صحيح إذا تم استخراج الصورة بنجاح

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

تسترجع الصورة التالية من ملف PDF وتخزنها في دفق بالتنسيق المحدد للصورة.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | الدفق الذي سيتم حفظ بيانات الصورة فيه |
| format | ImageFormat | تنسيق الصورة. |

### Return Value

صحيح في حالة استخراج الصورة بنجاح.

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

تسترجع الصورة التالية من ملف PDF وتخزنها في دفق.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | الدفق الذي سيتم حفظ بيانات الصورة فيه |

### Return Value

صحيح في حالة استخراج الصورة بنجاح.

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)