---
title: Class XImage
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.XImage class. Class representing image XObject
type: docs
weight: 8850
url: /net/aspose.pdf/ximage/
---
## XImage class

Class representing image X-Object.

```csharp
public sealed class XImage
```

## Properties

| Name | Description |
| --- | --- |
| [ContainsTransparency](../../aspose.pdf/ximage/containstransparency/) { get; } | If the image contains transparancy than return true; otherwise, false. |
| [FilterType](../../aspose.pdf/ximage/filtertype/) { get; } | Gets image filter type. |
| [Grayscaled](../../aspose.pdf/ximage/grayscaled/) { get; } | Gets grayscaled version of image. |
| [Height](../../aspose.pdf/ximage/height/) { get; } | Gets height of the image. |
| [Metadata](../../aspose.pdf/ximage/metadata/) { get; } | Metadata of the image. |
| [Name](../../aspose.pdf/ximage/name/) { get; set; } | Gets or sets image name. Please note that if you change name of the image which has references in page contents, document may became incorrect. Please use XImage.Rename method in this case. |
| [Width](../../aspose.pdf/ximage/width/) { get; } | Gets width of the image. |

## Methods

| Name | Description |
| --- | --- |
| [GetColorType](../../aspose.pdf/ximage/getcolortype/)() | Returns color type of image. |
| [GetNameInCollection](../../aspose.pdf/ximage/getnameincollection/)() | Returns name of the image in ints collection. |
| [IsTheSameObject](../../aspose.pdf/ximage/isthesameobject/)(XImage) | Returns true if both images references to the same object. |
| [Rename](../../aspose.pdf/ximage/rename/)(string) | Renames image and replaces all references to the image with the new name |
| [Save](../../aspose.pdf/ximage/save/#save)(Stream) | Saves image data into stream as JPEG image. |
| [Save](../../aspose.pdf/ximage/save/#save_2)(Stream, ImageFormat) | Saves image into stream with requested format. |
| [Save](../../aspose.pdf/ximage/save/#save_1)(Stream, int) | Saves image data into stream as JPEG image with specified resolution. |
| [Save](../../aspose.pdf/ximage/save/#save_3)(Stream, ImageFormat, int) | Saves image into stream with requested format with specified resolution. |
| [ToStream](../../aspose.pdf/ximage/tostream/)() | Returns the original image stream. |
| static [DetectColorType](../../aspose.pdf/ximage/detectcolortype/)(Bitmap) |  |

### See Also

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


