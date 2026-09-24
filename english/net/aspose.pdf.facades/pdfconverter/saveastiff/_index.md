---
title: "PdfConverter.SaveAsTIFF"
linktitle: "SaveAsTIFF"
articleTitle: "SaveAsTIFF"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfConverter method. Converts each pages of a pdf document to images and saves images to a single TIFF file."
type: docs
weight: 40
url: "/net/aspose.pdf.facades/pdfconverter/saveastiff/"
product_version: "26.9.0"
---
## SaveAsTIFF(string) {#saveastiff}

Converts each pages of a pdf document to images and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | string | The file to save the TIFF image. |

## Examples

```csharp
[C#]
 PdfConverter converter = new PdfConverter();
 converter.BindPdf(@"D:\Test\test.pdf");
 converter.DoConvert();
 converter.SaveAsTIFF(@"D:\Test\test.tiff"); 
 
 [Visual Basic]
 Dim converter As PdfConverter = New PdfConverter() 
 converter.BindPdf("D:\Test\test.pdf")
 converter.DoConvert()
 converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, [CompressionType](../../../aspose.pdf.devices/compressiontype/)) {#saveastiff_1}

Converts each pages of a pdf document to images and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | string | The output file. |
| compressionType | CompressionType | Type of the compression. |

## Examples

```csharp
[C#]
 PdfConverter converter = new PdfConverter();
 converter.BindPdf(@"D:\Test\test.pdf");
 converter.DoConvert();
 converter.SaveAsTIFF(@"D:\Test\test.tiff");
 [Visual Basic]
 Dim converter As PdfConverter = New PdfConverter()
 converter.BindPdf("D:\Test\test.pdf")
 converter.DoConvert()
 converter.SaveAsTIFF(@"D:\Test\test.tiff")
```

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_2}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | string | The file name to save the TIFF image |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, [PageSize](../../../aspose.pdf/pagesize/)) {#saveastiff_3}

Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | string | The file name to save the TIFF image |
| pageSize | PageSize | The page size of the image. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, [PageSize](../../../aspose.pdf/pagesize/), [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)) {#saveastiff_4}

Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | string | The file name to save the TIFF image |
| pageSize | PageSize | The page size of the image. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, [CompressionType](../../../aspose.pdf.devices/compressiontype/)) {#saveastiff_5}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | string | The file name to save the TIFF image |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| compressionType | CompressionType | Type of the compression. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)) {#saveastiff_6}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | string | The file name to save the TIFF image |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, [TiffSettings](../../../aspose.pdf.devices/tiffsettings/), [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)) {#saveastiff_7}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | string | The file name to save the TIFF image |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |
| converter | IIndexBitmapConverter | External converter |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff_8}

Converts each pages of a pdf document to images and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, [CompressionType](../../../aspose.pdf.devices/compressiontype/)) {#saveastiff_9}

Converts each pages of a pdf document to images and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The output stream. |
| compressionType | CompressionType | Type of the compression. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, [PageSize](../../../aspose.pdf/pagesize/)) {#saveastiff_10}

Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| pageSize | PageSize | The page size of the image. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, [PageSize](../../../aspose.pdf/pagesize/), [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)) {#saveastiff_11}

Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| pageSize | PageSize | The page size of the image. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_12}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, [CompressionType](../../../aspose.pdf.devices/compressiontype/)) {#saveastiff_13}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| compressionType | CompressionType | Type of the compression. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)) {#saveastiff_14}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, [TiffSettings](../../../aspose.pdf.devices/tiffsettings/), [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)) {#saveastiff_15}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | int | The image width, the unit is pixel. |
| imageHeight | int | The image height, the unit is pixel. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |
| converter | IIndexBitmapConverter | External converter |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)) {#saveastiff_16}

Converts each pages of a pdf document to images with and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | string | The file name to save the TIFF image |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, [TiffSettings](../../../aspose.pdf.devices/tiffsettings/), [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)) {#saveastiff_17}

Converts each pages of a pdf document to images with and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | string | The file name to save the TIFF image |
| settings | TiffSettings | Settings object that defines TIFF parameters. |
| converter | IIndexBitmapConverter | External converter |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, [TiffSettings](../../../aspose.pdf.devices/tiffsettings/)) {#saveastiff_18}

Converts each pages of a pdf document to images and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, [TiffSettings](../../../aspose.pdf.devices/tiffsettings/), [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter/)) {#saveastiff_19}

Converts each pages of a pdf document to images and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |
| converter | IIndexBitmapConverter | External converter |

### See Also

* class [PdfConverter](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

