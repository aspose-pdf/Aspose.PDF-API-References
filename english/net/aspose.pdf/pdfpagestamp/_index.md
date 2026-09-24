---
title: "PdfPageStamp Class"
linktitle: "PdfPageStamp"
articleTitle: "PdfPageStamp"
second_title: "Aspose.PDF for .NET"
description: "Class represents stamp which uses PDF page as stamp."
type: docs
weight: 2490
url: "/net/aspose.pdf/pdfpagestamp/"
keywords: "PdfPageStamp, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PdfPageStamp class

Class represents stamp which uses PDF page as stamp.

```csharp
public sealed class PdfPageStamp : Stamp
```

## Constructors

| Name | Description |
| --- | --- |
| [PdfPageStamp](./pdfpagestamp/#constructor)(*[Page](../../aspose.pdf/page/)*) | Constructor of PdfPageStamp. |
| [PdfPageStamp](./pdfpagestamp/#constructor_1)(*string, int*) | Creates Pdf page stamp from specifed page of the document in specified file. |
| [PdfPageStamp](./pdfpagestamp/#constructor_2)(*Stream, int*) | Creates Pdf page stamp from specifed page in the document from the stream. |

## Properties

| Name | Description |
| --- | --- |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Gets or sets a BlendingColorSpace value that defines a color space. *(Inherited from Stamp)* |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Gets or sets background status. If true stamp will be placed as background of the spamped page. *(Inherited from Stamp)* |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Gets or sets opacity of the stamp. *(Inherited from Stamp)* |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Gets or sets page number. *(Inherited from Stamp)* |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Gets or sets array with numbers of pages which will be affected by stamp. *(Inherited from Stamp)* |
| [PdfPage](./pdfpage/) { get; set; } | Gets or sets page which will be used as stamp. |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Gets or sets quality of image stamp in percent. Valiued values 0..100%. *(Inherited from Stamp)* |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Gets or sets rotation of the stamp in degrees. *(Inherited from Stamp)* |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Gets or sets identifier of stamp. *(Inherited from Stamp)* |

## Methods

| Name | Description |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/)(*string*) | Sets image as a stamp. *(Inherited from Stamp)* |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(*FormattedText*) | Sets text as stamp. *(Inherited from Stamp)* |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/)(*string, int*) | Sets PDF file and number of page which will be used as stamp. *(Inherited from Stamp)* |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(*TextState*) | Sets text state of stamp text. *(Inherited from Stamp)* |
| [Put](./put/)(*Page*) | Put stamp on the specified page. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(*float, float*) | Sets size of image stamp. Image will be scaled according to the specified values. *(Inherited from Stamp)* |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(*float, float*) | Sets position on page where stamp will be placed. *(Inherited from Stamp)* |

### See Also

* class [Stamp](../../aspose.pdf.facades/stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

