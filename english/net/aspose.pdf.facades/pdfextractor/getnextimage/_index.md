---
title: PdfExtractor.GetNextImage
second_title: Aspose.PDF for .NET API Reference
description: PdfExtractor method. Retrieves next image from PDF document. Note ExtractImage must be called before using of this method
type: docs
weight: 170
url: /net/aspose.pdf.facades/pdfextractor/getnextimage/
---
## GetNextImage(string) {#getnextimage_2}

Retrieves next image from PDF document. Note: ExtractImage must be called before using of this method.

```csharp
public bool GetNextImage(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | File where image will be stored |

### Return Value

True is image is successfully extracted

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

Retrieves next image from PDF document with given image format. Note: ExtractImage must be called before using of this method.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | String | File where image will be stored |
| format | ImageFormat | The format of the image. |

### Return Value

True is image is successfully extracted

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, ImageFormat) {#getnextimage_1}

Retrieve next image from PDF file and stores it into stream with given image format.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where image data will be saved |
| format | ImageFormat | The format of the image. |

### Return Value

True in case the image is successfully extracted.

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage}

Retrieve next image from PDF file and stores it into stream.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where image data will be saved |

### Return Value

True in case the image is successfully extracted.

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


