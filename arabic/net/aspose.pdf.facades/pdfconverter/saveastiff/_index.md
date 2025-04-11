---
title: PdfConverter.SaveAsTIFF
second_title: Aspose.PDF for .NET API Reference
description: طريقة PdfConverter. تقوم بتحويل كل صفحات مستند PDF إلى صور وتخزين الصور في ملف TIFF واحد
type: docs
weight: 160
url: /ar/net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

تقوم بتحويل كل صفحات مستند PDF إلى صور وتخزين الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | الملف الذي سيتم حفظ صورة TIFF فيه. |

## Examples

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

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

تقوم بتحويل كل صفحات مستند PDF إلى صور وتخزين الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | ملف الإخراج. |
| compressionType | CompressionType | نوع الضغط. |

## Examples

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

### See Also

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

تقوم بتحويل كل صفحات مستند PDF إلى صور بأبعاد، وتخزين الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

تقوم بتحويل كل صفحات مستند PDF إلى صور بحجم الصفحة وتخزين الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| pageSize | PageSize | حجم الصفحة للصورة. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

تقوم بتحويل كل صفحات مستند PDF إلى صور بحجم الصفحة وتخزين الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| pageSize | PageSize | حجم الصفحة للصورة. |
| settings | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

تقوم بتحويل كل صفحات مستند PDF إلى صور بأبعاد، وتخزين الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |
| compressionType | CompressionType | نوع الضغط. |

### See Also

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

تقوم بتحويل كل صفحات مستند PDF إلى صور بأبعاد، وتخزين الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |
| settings | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

تقوم بتحويل كل صفحات مستند PDF إلى صور بأبعاد، وتخزين الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |
| settings | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |
| converter | IIndexBitmapConverter | محول خارجي |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

تقوم بتحويل كل صفحات مستند PDF إلى صور وتخزين الصور في تيار TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | التيار لحفظ صورة TIFF. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

تقوم بتحويل كل صفحات مستند PDF إلى صور وتخزين الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | تيار الإخراج. |
| compressionType | CompressionType | نوع الضغط. |

### See Also

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

تقوم بتحويل كل صفحات مستند PDF إلى صور بحجم الصفحة وتخزين الصور في تيار TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | التيار لحفظ صورة TIFF. |
| pageSize | PageSize | حجم الصفحة للصورة. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

تقوم بتحويل كل صفحات مستند PDF إلى صور بحجم الصفحة وتخزين الصور في تيار TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | التيار لحفظ صورة TIFF. |
| pageSize | PageSize | حجم الصفحة للصورة. |
| settings | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize/)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

تقوم بتحويل كل صفحات مستند PDF إلى صور بأبعاد، وتخزين الصور في تيار TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | التيار لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

تقوم بتحويل كل صفحات مستند PDF إلى صور بأبعاد، وتخزين الصور في تيار TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | التيار لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |
| compressionType | CompressionType | نوع الضغط. |

### See Also

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

تقوم بتحويل كل صفحات مستند PDF إلى صور بأبعاد، وتخزين الصور في تيار TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | التيار لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |
| settings | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

تقوم بتحويل كل صفحات مستند PDF إلى صور بأبعاد، وتخزين الصور في تيار TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | التيار لحفظ صورة TIFF. |
| imageWidth | Int32 | عرض الصورة، الوحدة هي بكسل. |
| imageHeight | Int32 | ارتفاع الصورة، الوحدة هي بكسل. |
| settings | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |
| converter | IIndexBitmapConverter | محول خارجي |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

تقوم بتحويل كل صفحات مستند PDF إلى صور وتخزين الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| settings | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

تقوم بتحويل كل صفحات مستند PDF إلى صور وتخزين الصور في ملف TIFF واحد.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | اسم الملف لحفظ صورة TIFF |
| settings | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |
| converter | IIndexBitmapConverter | محول خارجي |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

تقوم بتحويل كل صفحات مستند PDF إلى صور وتخزين الصور في تيار TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | التيار لحفظ صورة TIFF. |
| settings | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

تقوم بتحويل كل صفحات مستند PDF إلى صور وتخزين الصور في تيار TIFF واحد.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | التيار لحفظ صورة TIFF. |
| settings | TiffSettings | كائن الإعدادات الذي يحدد معلمات TIFF. |
| converter | IIndexBitmapConverter | محول خارجي |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)
* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)