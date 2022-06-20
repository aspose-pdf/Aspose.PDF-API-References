---
title: SaveAsTIFF
second_title: Aspose.PDF for .NET API Reference
description: Converts each pages of a pdf document to images and saves images to a single TIFF file.
type: docs
weight: 160
url: /net/aspose.pdf.facades/pdfconverter/saveastiff/
---
## SaveAsTIFF(string) {#saveastiff_10}

Converts each pages of a pdf document to images and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file to save the TIFF image. |

### Examples

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

* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, CompressionType) {#saveastiff_11}

Converts each pages of a pdf document to images and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The output file. |
| compressionType | CompressionType | Type of the compression. |

### Examples

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

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int) {#saveastiff_16}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |

### See Also

* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize) {#saveastiff_14}

Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| pageSize | PageSize | The page size of the image. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, PageSize, TiffSettings) {#saveastiff_15}

Converts each pages of a pdf document to images with page size and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, PageSize pageSize, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| pageSize | PageSize | The page size of the image. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, CompressionType) {#saveastiff_17}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |
| compressionType | CompressionType | Type of the compression. |

### See Also

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings) {#saveastiff_18}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_19}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |
| converter | IIndexBitmapConverter | External converter |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream) {#saveastiff}

Converts each pages of a pdf document to images and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |

### See Also

* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, CompressionType) {#saveastiff_1}

Converts each pages of a pdf document to images and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(Stream outputStream, CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The output stream. |
| compressionType | CompressionType | Type of the compression. |

### See Also

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize) {#saveastiff_4}

Converts each pages of a pdf document to images with page size and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, PageSize pageSize)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| pageSize | PageSize | The page size of the image. |

### See Also

* class [PageSize](../../../aspose.pdf/pagesize)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, PageSize, TiffSettings) {#saveastiff_5}

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

* class [PageSize](../../../aspose.pdf/pagesize)
* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int) {#saveastiff_6}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |

### See Also

* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, CompressionType) {#saveastiff_7}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, 
    CompressionType compressionType)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |
| compressionType | CompressionType | Type of the compression. |

### See Also

* enum [CompressionType](../../../aspose.pdf.devices/compressiontype)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings) {#saveastiff_8}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, int, int, TiffSettings, IIndexBitmapConverter) {#saveastiff_9}

Converts each pages of a pdf document to images with dimensions, and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, int imageWidth, int imageHeight, TiffSettings settings, 
    IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| imageWidth | Int32 | The image width, the unit is pixel. |
| imageHeight | Int32 | The image height, the unit is pixel. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |
| converter | IIndexBitmapConverter | External converter |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings) {#saveastiff_12}

Converts each pages of a pdf document to images with and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(string, TiffSettings, IIndexBitmapConverter) {#saveastiff_13}

Converts each pages of a pdf document to images with and saves images to a single TIFF file.

```csharp
public void SaveAsTIFF(string outputFile, TiffSettings settings, IIndexBitmapConverter converter)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | The file name to save the TIFF image |
| settings | TiffSettings | Settings object that defines TIFF parameters. |
| converter | IIndexBitmapConverter | External converter |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings) {#saveastiff_2}

Converts each pages of a pdf document to images and saves images to a single TIFF stream.

```csharp
public void SaveAsTIFF(Stream outputStream, TiffSettings settings)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | The stream to save the TIFF image. |
| settings | TiffSettings | Settings object that defines TIFF parameters. |

### See Also

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

---

## SaveAsTIFF(Stream, TiffSettings, IIndexBitmapConverter) {#saveastiff_3}

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

* class [TiffSettings](../../../aspose.pdf.devices/tiffsettings)
* interface [IIndexBitmapConverter](../../../aspose.pdf/iindexbitmapconverter)
* class [PdfConverter](../../pdfconverter)
* namespace [Aspose.Pdf.Facades](../../pdfconverter)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
