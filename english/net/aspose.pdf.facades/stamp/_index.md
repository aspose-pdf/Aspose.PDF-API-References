---
title: "Stamp Class"
linktitle: "Stamp"
articleTitle: "Stamp"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.Stamp class. Class represeting stamp."
type: docs
weight: 610
url: "/net/aspose.pdf.facades/stamp/"
keywords: "Stamp, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Stamp class

Class represeting stamp.

```csharp
public sealed class Stamp
```

## Constructors

| Name | Description |
| --- | --- |
| [Stamp](./stamp/#constructor) | Initializes a new instance of the Stamp class. |

## Properties

| Name | Description |
| --- | --- |
| [BlendingSpace](./blendingspace/) { get; set; } | Gets or sets a BlendingColorSpace value that defines a color space. |
| [IsBackground](./isbackground/) { get; set; } | Gets or sets background status. If true stamp will be placed as background of the spamped page. |
| [Opacity](./opacity/) { get; set; } | Gets or sets opacity of the stamp. |
| [PageNumber](./pagenumber/) { get; set; } | Gets or sets page number. |
| [Pages](./pages/) { get; set; } | Gets or sets array with numbers of pages which will be affected by stamp. |
| [Quality](./quality/) { get; set; } | Gets or sets quality of image stamp in percent. Valiued values 0..100%. |
| [Rotation](./rotation/) { get; set; } | Gets or sets rotation of the stamp in degrees. |
| [StampId](./stampid/) { get; set; } | Gets or sets identifier of stamp. |

## Methods

| Name | Description |
| --- | --- |
| [BindImage](./bindimage/)(*string*) | Sets image as a stamp. |
| [BindImage](./bindimage/)(*Stream*) | Sets image which will be used as stamp. |
| [BindLogo](./bindlogo/)(*FormattedText*) | Sets text as stamp. |
| [BindPdf](./bindpdf/)(*string, int*) | Sets PDF file and number of page which will be used as stamp. |
| [BindPdf](./bindpdf/)(*Stream, int*) | Sets PDF file and number of page which will be used as stamp. |
| [BindTextState](./bindtextstate/)(*TextState*) | Sets text state of stamp text. |
| [SetImageSize](./setimagesize/)(*float, float*) | Sets size of image stamp. Image will be scaled according to the specified values. |
| [SetOrigin](./setorigin/)(*float, float*) | Sets position on page where stamp will be placed. |

### See Also

* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

