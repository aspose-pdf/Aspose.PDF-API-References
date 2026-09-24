---
title: "XImage Class"
linktitle: "XImage"
articleTitle: "XImage"
second_title: "Aspose.PDF for .NET"
description: "Class representing image X-Object."
type: docs
weight: 3210
url: "/net/aspose.pdf/ximage/"
keywords: "XImage, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## XImage class

Class representing image X-Object.

```csharp
public sealed class XImage
```

## Properties

| Name | Description |
| --- | --- |
| [ContainsTransparency](./containstransparency/) { get; } | If the image contains transparancy than return true; otherwise, false. |
| [FilterType](./filtertype/) { get; } | Gets image filter type. |
| [Grayscaled](./grayscaled/) { get; } | Gets grayscaled version of image. |
| [Height](./height/) { get; } | Gets height of the image. |
| [ImageMask](./imagemask/) { get; } | Gets a flag indicating whether the image shall be treated as an image mask (see 8.9.6, "Masked Images"). |
| [Metadata](./metadata/) { get; } | Metadata of the image. |
| [Name](./name/) { get; set; } | Gets or sets image name. Please note that if you change name of the image which has references in page contents, document may became incorrect. Please use XImage.Rename method in this case. |
| [Width](./width/) { get; } | Gets width of the image. |

## Methods

| Name | Description |
| --- | --- |
| [AddStencilMask](./addstencilmask/)(*Stream*) | Adds a stencil mask to the XImage. |
| [DetectColorType](./detectcolortype/)(*Bitmap*) |  |
| [GetAlternativeText](./getalternativetext/)(*Page*) | Returns a list of strings with Alternative Text for an XImage. |
| [GetColorType](./getcolortype/) | Returns color type of image. |
| [GetNameInCollection](./getnameincollection/) | Returns the name of the image in its collection. |
| [GetRawImageData](./getrawimagedata/) | Retrieves the raw image data from the source image. |
| [IsTheSameObject](./isthesameobject/)(*XImage*) | Returns true if both images references to the same object. |
| [Rename](./rename/)(*string*) | Renames image and replaces all references to the image with the new name. |
| [Save](./save/)(*Stream*) | Saves image data into stream as JPEG image. |
| [Save](./save/)(*Stream, ImageFormat*) | Saves image into stream with requested format. |
| [Save](./save/)(*Stream, int*) | Saves image data into stream as JPEG image with specified resolution. |
| [Save](./save/)(*Stream, ImageFormat, int*) | Saves image into stream with requested format with specified resolution. |
| [ToStream](./tostream/) | Returns the original image stream. |
| [TrySetAlternativeText](./trysetalternativetext/)(*string, Page*) | Sets alternative text for an XImage on the page. |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

