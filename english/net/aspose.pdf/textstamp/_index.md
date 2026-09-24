---
title: "TextStamp Class"
linktitle: "TextStamp"
articleTitle: "TextStamp"
second_title: "Aspose.PDF for .NET"
description: "Represents textual stamp."
type: docs
weight: 3030
url: "/net/aspose.pdf/textstamp/"
keywords: "TextStamp, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextStamp class

Represents textual stamp.

```csharp
public class TextStamp : Stamp
```

## Constructors

| Name | Description |
| --- | --- |
| [TextStamp](./textstamp/#constructor)(*string*) | Initializes a new instance of the [`TextStamp`](../../aspose.pdf/textstamp/) class. |
| [TextStamp](./textstamp/#constructor_1)(*[FormattedText](../../aspose.pdf.facades/formattedtext/)*) | Initializes a new instance of the [`TextStamp`](../../aspose.pdf/textstamp/) class with formattedText object. |
| [TextStamp](./textstamp/#constructor_2)(*string, [TextState](../../aspose.pdf.text/textstate/)*) | Initializes a new instance of the [`TextStamp`](../../aspose.pdf/textstamp/) class. |

## Properties

| Name | Description |
| --- | --- |
| [AutoAdjustFontSizePrecision](./autoadjustfontsizeprecision/) { get; set; } | Automatically adjust font size precision. Default value: 0.1;. |
| [AutoAdjustFontSizeToFitStampRectangle](./autoadjustfontsizetofitstamprectangle/) { get; set; } | If enabled, the font size will be automatically adjusted to fit the stamp rectangle of size: `Width` and `Height`. Default width and height are derived from the page rectangle. |
| [BlendingSpace](../../aspose.pdf.facades/stamp/blendingspace/) { get; set; } | Gets or sets a BlendingColorSpace value that defines a color space. *(Inherited from Stamp)* |
| [Draw](./draw/) { get; set; } | This property determines how stamp is drawn on page. If Draw = true stamp is drawn as graphic operators and if draw = false then stamp is drawn as text. |
| [FontSize](./fontsize/) { get; } | Actual font size after the stamp has been placed. (May differ from the initial font size provided through the constructor if the 'AutoAdjustFontSizeToFitStampRectangle' option is enabled.). |
| [Height](./height/) { get; set; } | Desired height of the stamp on the page. |
| [IsBackground](../../aspose.pdf.facades/stamp/isbackground/) { get; set; } | Gets or sets background status. If true stamp will be placed as background of the spamped page. *(Inherited from Stamp)* |
| [Justify](./justify/) { get; set; } | Defines text justification. If this property is set to true, both left and right edges of the text are aligned. Default value: false. |
| [MaxRowWidth](./maxrowwidth/) { get; set; } | Max row height for WordWrap option. |
| [NoCharacterBehavior](./nocharacterbehavior/) { get; set; } | Gets or sets mode that defines behavior in case fonts don't contain requested characters. |
| [Opacity](../../aspose.pdf.facades/stamp/opacity/) { get; set; } | Gets or sets opacity of the stamp. *(Inherited from Stamp)* |
| [PageNumber](../../aspose.pdf.facades/stamp/pagenumber/) { get; set; } | Gets or sets page number. *(Inherited from Stamp)* |
| [Pages](../../aspose.pdf.facades/stamp/pages/) { get; set; } | Gets or sets array with numbers of pages which will be affected by stamp. *(Inherited from Stamp)* |
| [Quality](../../aspose.pdf.facades/stamp/quality/) { get; set; } | Gets or sets quality of image stamp in percent. Valiued values 0..100%. *(Inherited from Stamp)* |
| [ReplacementFont](./replacementfont/) { get; set; } | Gets or sets font used for replacing if user font does not contain required character. |
| [Rotation](../../aspose.pdf.facades/stamp/rotation/) { get; set; } | Gets or sets rotation of the stamp in degrees. *(Inherited from Stamp)* |
| [Scale](./scale/) { get; set; } | Defines scaling of the text. If this property is set to true and Width value specified, text will be scaled in order to fit to specified width. |
| [StampId](../../aspose.pdf.facades/stamp/stampid/) { get; set; } | Gets or sets identifier of stamp. *(Inherited from Stamp)* |
| [TextAlignment](./textalignment/) { get; set; } | Alignment of the text inside the stamp. |
| [TextState](./textstate/) { get; } | Gets text properties of the stamp. See `TextState` for details. |
| [TreatYIndentAsBaseLine](./treatyindentasbaseline/) { get; set; } | Defines coordinate origin for placing text. |
| [Value](./value/) { get; set; } | Gets or sets string value which is used as stamp on the page. |
| [Width](./width/) { get; set; } | Desired width of the stamp on the page. |
| [WordWrap](./wordwrap/) { get; set; } | Defines word wrap. If this property set to true and Width value specified, text will be broken in the several lines to fit into specified width. Default value: false. |
| [WordWrapMode](./wordwrapmode/) { get; set; } | Gets or sets the word wrap mode for text rendering. |

## Methods

| Name | Description |
| --- | --- |
| [BindImage](../../aspose.pdf.facades/stamp/bindimage/)(*string*) | Sets image as a stamp. *(Inherited from Stamp)* |
| [BindLogo](../../aspose.pdf.facades/stamp/bindlogo/)(*FormattedText*) | Sets text as stamp. *(Inherited from Stamp)* |
| [BindPdf](../../aspose.pdf.facades/stamp/bindpdf/)(*string, int*) | Sets PDF file and number of page which will be used as stamp. *(Inherited from Stamp)* |
| [BindTextState](../../aspose.pdf.facades/stamp/bindtextstate/)(*TextState*) | Sets text state of stamp text. *(Inherited from Stamp)* |
| [Put](./put/)(*Page*) | Adds textual stamp on the page. |
| [SetImageSize](../../aspose.pdf.facades/stamp/setimagesize/)(*float, float*) | Sets size of image stamp. Image will be scaled according to the specified values. *(Inherited from Stamp)* |
| [SetOrigin](../../aspose.pdf.facades/stamp/setorigin/)(*float, float*) | Sets position on page where stamp will be placed. *(Inherited from Stamp)* |
| [createXForm](./createxform/)(*Page*) | Creates XForm which contains operators for text output. |

### See Also

* class [Stamp](../../aspose.pdf.facades/stamp/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

