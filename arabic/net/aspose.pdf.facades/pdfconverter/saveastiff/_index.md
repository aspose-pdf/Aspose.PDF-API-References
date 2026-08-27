---
title: "PdfConverter.SaveAsTIFF"
second_title: "مرجع API لـ Aspose.PDF لـ .NET"
description: "طريقة PdfConverter. تحول كل صفحات مستند pdf إلى صور وتحفظ الصور في ملف TIFF واحد"
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | الملف لحفظ صورة TIFF. |

## أمثلة

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");	

[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter() 
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | ملف الإخراج. |
| compressionType | CompressionType | نوع الضغط. |

## أمثلة

```csharp
[C#]
PdfConverter converter = new PdfConverter();
converter.BindPdf(@"D:\Test\test.pdf");
converter.DoConvert();
converter.SaveAsTIFF(@"D:\Test\test.tiff");
[Visual Basic]
Dim converter As PdfConverter =  New PdfConverter()
converter.BindPdf("D:\Test\test.pdf")
converter.DoConvert()
converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### انظر أيضًا

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

يحوّل كل صفحة من مستند pdf إلى صور مع حجم الصفحة ويحفظ الصور إلى ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| pageSize | PageSize | حجم الصفحة للصورة. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

يحوّل كل صفحة من مستند pdf إلى صور مع حجم الصفحة ويحفظ الصور إلى ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| pageSize | PageSize | حجم الصفحة للصورة. |
| الإعدادات | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |
| compressionType | CompressionType | نوع الضغط. |

### انظر أيضًا

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |
| الإعدادات | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |

### انظر أيضًا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |
| الإعدادات | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |
| محول | IIndexBitmapConverter | محول خارجي |

### انظر أيضًا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى تدفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق لحفظ صورة TIFF. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | تدفق الإخراج. |
| compressionType | CompressionType | نوع الضغط. |

### انظر أيضًا

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

يحوّل كل صفحة من مستند pdf إلى صور مع حجم الصفحة ويحفظ الصور إلى تدفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق لحفظ صورة TIFF. |
| pageSize | PageSize | حجم الصفحة للصورة. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

يحوّل كل صفحة من مستند pdf إلى صور مع حجم الصفحة ويحفظ الصور إلى تدفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق لحفظ صورة TIFF. |
| pageSize | PageSize | حجم الصفحة للصورة. |
| الإعدادات | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |

### انظر أيضًا

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى تدفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |

### انظر أيضًا

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى تدفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |
| compressionType | CompressionType | نوع الضغط. |

### انظر أيضًا

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى تدفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |
| الإعدادات | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |

### انظر أيضًا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

يحوّل كل صفحة من مستند pdf إلى صور بالأبعاد، ويحفظ الصور إلى تدفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي pixel. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي pixel. |
| الإعدادات | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |
| محول | IIndexBitmapConverter | محول خارجي |

### انظر أيضًا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| الإعدادات | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |

### انظر أيضًا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| الإعدادات | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |
| محول | IIndexBitmapConverter | محول خارجي |

### انظر أيضًا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى تدفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق لحفظ صورة TIFF. |
| الإعدادات | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |

### انظر أيضًا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

يحوّل كل صفحة من مستند pdf إلى صور ويحفظ الصور إلى تدفق TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| معامل | النوع | الوصف |
| --- | --- | --- |
| outputStream | Stream | التدفق لحفظ صورة TIFF. |
| الإعدادات | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |
| محول | IIndexBitmapConverter | محول خارجي |

### انظر أيضًا

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


