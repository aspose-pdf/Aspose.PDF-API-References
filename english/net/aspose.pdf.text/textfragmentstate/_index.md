---
title: "TextFragmentState Class"
linktitle: "TextFragmentState"
articleTitle: "TextFragmentState"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TextFragmentState class. Represents a text state of a text fragment."
type: docs
weight: 580
url: "/net/aspose.pdf.text/textfragmentstate/"
keywords: "TextFragmentState, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextFragmentState class

Represents a text state of a text fragment.

```csharp
public sealed class TextFragmentState : TextState
```

## Constructors

| Name | Description |
| --- | --- |
| [TextFragmentState](./textfragmentstate/#constructor)(*[TextFragment](../../aspose.pdf.text/textfragment/)*) | Initializes new instance of the [`TextFragmentState`](../../aspose.pdf.text/textfragmentstate/) object with specified [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](./backgroundcolor/) { get; set; } | Sets background color of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [CharacterSpacing](./characterspacing/) { get; set; } | Gets or sets character spacing of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [CoordinateOrigin](./coordinateorigin/) { get; set; } | Gets or sets text CoordinateOrigin. |
| [DrawTextRectangleBorder](./drawtextrectangleborder/) { get; set; } | Gets or sets if text rectangle border drawn flag. |
| [Font](./font/) { get; set; } | Gets or sets font of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [FontSize](./fontsize/) { get; set; } | Gets or sets font size of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [FontStyle](./fontstyle/) { get; set; } | Sets font style of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [ForegroundColor](./foregroundcolor/) { get; set; } | Gets or sets foreground color of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [FormattingOptions](./formattingoptions/) { get; set; } | Gets or sets formatting options. |
| [HorizontalAlignment](./horizontalalignment/) { get; set; } | Gets or sets horizontal alignment for the text. |
| [HorizontalScaling](./horizontalscaling/) { get; set; } | Gets or sets horizontal scaling of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [Invisible](./invisible/) { get; set; } | Gets or sets invisibility of the text. |
| [LineSpacing](./linespacing/) { get; set; } | Gets or sets line spacing of the text. |
| [RenderingMode](./renderingmode/) { get; set; } | Gets or sets rendering mode of the text. |
| [Rotation](./rotation/) { get; set; } | Gets or sets rotation angle in degrees. |
| [StrikeOut](./strikeout/) { get; set; } | Gets or sets strikeout for the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [StrokingColor](./strokingcolor/) { get; set; } | Gets or sets color stroking operations of [`TextFragment`](../../aspose.pdf.text/textfragment/) rendering (stroke text, rectangle border). |
| [Subscript](./subscript/) { get; set; } | Gets or sets subscript of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [Superscript](./superscript/) { get; set; } | Gets or sets superscript of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [TabStops](./tabstops/) { get; } | Gets tabstops for the text. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | You can place this tag in text to declare tabulation. *(Inherited from TextState)* |
| [Underline](./underline/) { get; set; } | Gets or sets underline for the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [WordSpacing](./wordspacing/) { get; set; } | Gets or sets word spacing of the text. |

## Methods

| Name | Description |
| --- | --- |
| [ApplyChangesFrom](./applychangesfrom/)(*TextState*) | Applies settings from another textState. |
| [IsFitRectangle](./isfitrectangle/)(*string, Rectangle*) | Checks if input string could be placed inside defined rectangle. |
| [MeasureHeight](./measureheight/)(*char*) | Measures character height. |
| [MeasureString](./measurestring/)(*string*) | Measures the string. |

## Fields

| Name | Description |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Default value of tabulation in widths of space character of default font. *(Inherited from TextState)* |

## Remarks

Provides a way to change following properties of the text:
 font (`Font` property)
 font size (`FontSize` property)
 font style (`FontStyle` property)
 foreground color (`ForegroundColor` property)
 background color (`BackgroundColor` property)
 
 Note that changing [`TextFragmentState`](../../aspose.pdf.text/textfragmentstate/) properties may change inner `Segments` collection because TextFragment is an aggregate object 
 and it may rearrange internal segments or merge them into single segment.
 If your requirement is to leave the `Segments` collection unchanged, please change inner segments individually.

### See Also

* [TextFragmentAbsorber](../textfragmentabsorber/)
* [Document](../document/)
* class [TextState](../textstate/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

