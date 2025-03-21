---
title: Class Stamp
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Stamp class. Class represeting stamp
type: docs
weight: 4720
url: /net/aspose.pdf.facades/stamp/
---
## Stamp class

Class represeting stamp.

```csharp
public sealed class Stamp
```

## Constructors

| Name | Description |
| --- | --- |
| [Stamp](stamp/)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Gets or sets a BlendingColorSpace value that defines a color space that is used to perform transparency and blending operations on the page. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Gets or sets background status. If true stamp will be placed as background of the spamped page. By default is set to false. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Gets or sets opacity of the stamp. |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Gets or sets page number. |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Gets or sets array with numbers of pages which will be affected by stamp. If Pages = null all pages of the document are affected. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Gets or sets quality of image stamp in percent. Valiued values 0..100%. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Gets or sets rotation of the stamp in degrees. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Gets or sets identifier of stamp. |

## Methods

| Name | Description |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage)(Stream) | Sets image which will be used as stamp. |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/#bindimage_1)(string) | Sets image as a stamp. |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(FormattedText) | Sets text as stamp. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf)(Stream, int) | Sets PDF file and number of page which will be used as stamp. |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/#bindpdf_1)(string, int) | Sets PDF file and number of page which will be used as stamp. |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(TextState) | Sets text state of stamp text. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(float, float) | Sets size of image stamp. Image will be scaled according to the specified values. |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(float, float) | Sets position on page where stamp will be placed. |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


