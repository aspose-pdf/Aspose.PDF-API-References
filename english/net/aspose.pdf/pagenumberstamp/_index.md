---
title: "PageNumberStamp Class"
linktitle: "PageNumberStamp"
articleTitle: "PageNumberStamp"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.PageNumberStamp class. Represents page number stamp and used to number pages."
type: docs
weight: 2300
url: "/net/aspose.pdf/pagenumberstamp/"
keywords: "PageNumberStamp, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## PageNumberStamp class

Represents page number stamp and used to number pages.

```csharp
public sealed class PageNumberStamp : TextStamp
```

## Constructors

| Name | Description |
| --- | --- |
| [PageNumberStamp](./pagenumberstamp/#constructor) | Initializes a new instance of the [`PageNumberStamp`](../../aspose.pdf/pagenumberstamp/) class. Format is set to "#". |
| [PageNumberStamp](./pagenumberstamp/#constructor_1)(*string*) | Initializes a new instance of the [`PageNumberStamp`](../../aspose.pdf/pagenumberstamp/) class. |
| [PageNumberStamp](./pagenumberstamp/#constructor_2)(*[FormattedText](../../aspose.pdf.facades/formattedtext/)*) | Creates PageNumberStamp by formatted text. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustFontSizePrecision](../../aspose.pdf/textstamp/autoadjustfontsizeprecision/) { get; set; } | Automatically adjust font size precision. Default value: 0.1;. *(Inherited from TextStamp)* |
| [AutoAdjustFontSizeToFitStampRectangle](../../aspose.pdf/textstamp/autoadjustfontsizetofitstamprectangle/) { get; set; } | If enabled, the font size will be automatically adjusted to fit the stamp rectangle of size: `Width` and `Height`. Default width and height are derived from the page rectangle. *(Inherited from TextStamp)* |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Gets or sets a BlendingColorSpace value that defines a color space. *(Inherited from Stamp)* |
| [Draw](../../aspose.pdf/textstamp/draw/) { get; set; } | This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text. *(Inherited from TextStamp)* |
| [FontSize](../../aspose.pdf/textstamp/fontsize/) { get; } | Actual font size after the stamp has been placed. (May differ from the initial font size provided through the constructor if the 'AutoAdjustFontSizeToFitStampRectangle' option is enabled.). *(Inherited from TextStamp)* |
| [Format](./format/) { get; set; } | String value for stamping page numbers. |
| [Height](../../aspose.pdf/textstamp/height/) { get; set; } | Desired height of the stamp on the page. *(Inherited from TextStamp)* |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Gets or sets background status. If true stamp will be placed as background of the spamped page. *(Inherited from Stamp)* |
| [Justify](../../aspose.pdf/textstamp/justify/) { get; set; } | Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false. *(Inherited from TextStamp)* |
| [MaxRowWidth](../../aspose.pdf/textstamp/maxrowwidth/) { get; set; } | Max row height for WordWrap option. *(Inherited from TextStamp)* |
| [NoCharacterBehavior](../../aspose.pdf/textstamp/nocharacterbehavior/) { get; set; } | Gets or sets mode that defines behavior in case fonts don't contain requested characters. *(Inherited from TextStamp)* |
| [NumberingStyle](./numberingstyle/) { get; set; } | Numbering style which used by this stamp. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Gets or sets opacity of the stamp. *(Inherited from Stamp)* |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Gets or sets page number. *(Inherited from Stamp)* |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Gets or sets array with numbers of pages which will be affected by stamp. *(Inherited from Stamp)* |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Gets or sets quality of image stamp in percent. Valiued values 0..100%. *(Inherited from Stamp)* |
| [ReplacementFont](../../aspose.pdf/textstamp/replacementfont/) { get; set; } | Gets or sets font used for replacing if user font does not contain required character. *(Inherited from TextStamp)* |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Gets or sets rotation of the stamp in degrees. *(Inherited from Stamp)* |
| [Scale](../../aspose.pdf/textstamp/scale/) { get; set; } | Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width. *(Inherited from TextStamp)* |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Gets or sets identifier of stamp. *(Inherited from Stamp)* |
| [StartingNumber](./startingnumber/) { get; set; } | Gets or sets value of the number of starting page. Other pages will be numbered starting from this value. |
| [TextAlignment](../../aspose.pdf/textstamp/textalignment/) { get; set; } | Alignment of the text inside the stamp. *(Inherited from TextStamp)* |
| [TextState](../../aspose.pdf/textstamp/textstate/) { get; } | Gets text properties of the stamp. See `TextState` for details. *(Inherited from TextStamp)* |
| [TreatYIndentAsBaseLine](../../aspose.pdf/textstamp/treatyindentasbaseline/) { get; set; } | Defines coordinate origin for placing text. *(Inherited from TextStamp)* |
| [Value](../../aspose.pdf/textstamp/value/) { get; set; } | Gets or sets string value which is used as stamp on the page. *(Inherited from TextStamp)* |
| [Width](../../aspose.pdf/textstamp/width/) { get; set; } | Desired width of the stamp on the page. *(Inherited from TextStamp)* |
| [WordWrap](../../aspose.pdf/textstamp/wordwrap/) { get; set; } | Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false. *(Inherited from TextStamp)* |
| [WordWrapMode](../../aspose.pdf/textstamp/wordwrapmode/) { get; set; } | Gets or sets the word wrap mode for text rendering. *(Inherited from TextStamp)* |

## Methods

| Name | Description |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/)(*string*) | Sets image as a stamp. *(Inherited from Stamp)* |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(*FormattedText*) | Sets text as stamp. *(Inherited from Stamp)* |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/)(*string, int*) | Sets PDF file and number of page which will be used as stamp. *(Inherited from Stamp)* |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(*TextState*) | Sets text state of stamp text. *(Inherited from Stamp)* |
| [Put](./put/)(*Page*) | Adds page number. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(*float, float*) | Sets size of image stamp. Image will be scaled according to the specified values. *(Inherited from Stamp)* |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(*float, float*) | Sets position on page where stamp will be placed. *(Inherited from Stamp)* |

### See Also

* class [TextStamp](../textstamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

