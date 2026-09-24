---
title: "ImageStamp Class"
linktitle: "ImageStamp"
articleTitle: "ImageStamp"
second_title: "Aspose.PDF for .NET"
description: "Represents a graphic stamp."
type: docs
weight: 1560
url: "/net/aspose.pdf/imagestamp/"
keywords: "ImageStamp, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## ImageStamp class

Represents a graphic stamp.

```csharp
public sealed class ImageStamp : Stamp
```

## Constructors

| Name | Description |
| --- | --- |
| [ImageStamp](./imagestamp/#constructor)(*Stream*) | Initializes a new instance of the [`ImageStamp`](../../aspose.pdf/imagestamp/) class. |
| [ImageStamp](./imagestamp/#constructor_1)(*string*) | Creates image stamp by image in the specified file. |

## Properties

| Name | Description |
| --- | --- |
| [AlternativeText](./alternativetext/) { get; set; } | Gets or sets Alternative Text for image stamp. |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Gets or sets a BlendingColorSpace value that defines a color space. *(Inherited from Stamp)* |
| [Height](./height/) { get; set; } | Gets or sets image height. Setting this image allows to scale image vertically. |
| [Image](./image/) { get; } | Gets image stream used for stamping. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Gets or sets background status. If true stamp will be placed as background of the spamped page. *(Inherited from Stamp)* |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Gets or sets opacity of the stamp. *(Inherited from Stamp)* |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Gets or sets page number. *(Inherited from Stamp)* |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Gets or sets array with numbers of pages which will be affected by stamp. *(Inherited from Stamp)* |
| [Quality](./quality/) { get; set; } | Gets or sets quality of image stamp in percent. Valid values are 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Gets or sets rotation of the stamp in degrees. *(Inherited from Stamp)* |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Gets or sets identifier of stamp. *(Inherited from Stamp)* |
| [Width](./width/) { get; set; } | Gets or sets image width. Setting this property allos to scal image horizontally. |
| [XIndent](./xindent/) { get; set; } | Gets and sets horizontal stamp coordinate, starting from the left. |
| [YIndent](./yindent/) { get; set; } | Gets and sets vertical stamp coordinate, starting from the bottom. |

## Methods

| Name | Description |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/)(*string*) | Sets image as a stamp. *(Inherited from Stamp)* |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(*FormattedText*) | Sets text as stamp. *(Inherited from Stamp)* |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/)(*string, int*) | Sets PDF file and number of page which will be used as stamp. *(Inherited from Stamp)* |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(*TextState*) | Sets text state of stamp text. *(Inherited from Stamp)* |
| [Put](./put/)(*Page*) | Adds graphic stamp on the page. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(*float, float*) | Sets size of image stamp. Image will be scaled according to the specified values. *(Inherited from Stamp)* |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(*float, float*) | Sets position on page where stamp will be placed. *(Inherited from Stamp)* |

### See Also

* class [Stamp](../../aspose.pdf.facades/stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

