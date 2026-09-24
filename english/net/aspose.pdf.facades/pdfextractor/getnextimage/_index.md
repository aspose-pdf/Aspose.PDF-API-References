---
title: "PdfExtractor.GetNextImage"
linktitle: "GetNextImage"
articleTitle: "GetNextImage"
second_title: "Aspose.PDF for .NET API Reference"
description: "PdfExtractor method. Retrieves next image from PDF document. Note: ExtractImage must be called before using of this method."
type: docs
weight: 110
url: "/net/aspose.pdf.facades/pdfextractor/getnextimage/"
product_version: "26.9.0"
---
## GetNextImage(string) {#getnextimage}

Retrieves next image from PDF document. Note: ExtractImage must be called before using of this method.

```csharp
public bool GetNextImage(string outputFile)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | string | File where image will be stored |

### Return Value

bool

True is image is successfully extracted

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(string, [ImageFormat](../../../aspose.pdf.drawing/imageformat/)) {#getnextimage_1}

Retrieves next image from PDF document with given image format. Note: ExtractImage must be called before using of this method.

```csharp
public bool GetNextImage(string outputFile, ImageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFile | string | File where image will be stored |
| format | ImageFormat | The format of the image. |

### Return Value

bool

True is image is successfully extracted

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream, [ImageFormat](../../../aspose.pdf.drawing/imageformat/)) {#getnextimage_2}

Retrieve next image from PDF file and stores it into stream with given image format.

```csharp
public bool GetNextImage(Stream outputStream, ImageFormat format)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where image data will be saved |
| format | ImageFormat | The format of the image. |

### Return Value

bool

True in case the image is successfully extracted.

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## GetNextImage(Stream) {#getnextimage_3}

Retrieve next image from PDF file and stores it into stream.

```csharp
public bool GetNextImage(Stream outputStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputStream | Stream | Stream where image data will be saved |

### Return Value

bool

True in case the image is successfully extracted.

### See Also

* class [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

