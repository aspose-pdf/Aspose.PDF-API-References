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

## Examples

The example demonstrates how to change text color and font size of the text with [`TextState`](../../../aspose.pdf.text/textstate/) object.

```csharp
// Open document
Document doc = new Document(@"D:\Tests\input.pdf");

// Create TextFragmentAbsorber object to find all "hello world" text occurrences
TextFragmentAbsorber absorber = new TextFragmentAbsorber("hello world");

// Accept the absorber for first page
doc.Pages[1].Accept(absorber);

// Change foreground color of the first text occurrence
absorber.TextFragments[1].TextState.ForegroundColor = Color.FromRgb(System.Drawing.Color.Red);
// Change font size of the first text occurrence
absorber.TextFragments[1].TextState.FontSize = 15;

// Save document
doc.Save(@"D:\Tests\output.pdf");
```

## Constructors

| Name | Description |
| --- | --- |
| [TextFragmentState](./textfragmentstate/)(TextFragment) | Initializes new instance of the [`TextFragmentState`](../../aspose.pdf.text/textfragmentstate/) object with specified [`TextFragment`](../../aspose.pdf.text/textfragment/) object. This [`TextFragmentState`](../../aspose.pdf.text/textfragmentstate/) initialization is not supported. TextFragmentState is only available with `TextState` property. |

## Properties

| Name | Description |
| --- | --- |
| override [BackgroundColor](./backgroundcolor/) { get; set; } | Sets background color of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object |
| override [CharacterSpacing](./characterspacing/) { get; set; } | Gets or sets character spacing of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| override [CoordinateOrigin](./coordinateorigin/) { get; set; } | Gets or sets text CoordinateOrigin. If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point. If CoordinateOrigin is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, CoordinateOrigin BaseLine can be selected for better text rendering. |
| [DrawTextRectangleBorder](./drawtextrectangleborder/) { get; set; } | Gets or sets if text rectangle border drawn flag. |
| override [Font](./font/) { get; set; } | Gets or sets font of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object |
| override [FontSize](./fontsize/) { get; set; } | Gets or sets font size of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object |
| override [FontStyle](./fontstyle/) { get; set; } | Sets font style of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object |
| override [ForegroundColor](./foregroundcolor/) { get; set; } | Gets or sets foreground color of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object |
| [FormattingOptions](./formattingoptions/) { get; set; } | Gets or sets formatting options. Setting of the options will be effective in generator scenarios only. |
| override [HorizontalAlignment](./horizontalalignment/) { get; set; } | Gets or sets horizontal alignment for the text. |
| override [HorizontalScaling](./horizontalscaling/) { get; set; } | Gets or sets horizontal scaling of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| override [Invisible](./invisible/) { get; set; } | Gets or sets invisibility of the text. |
| override [LineSpacing](./linespacing/) { get; set; } | Gets or sets line spacing of the text. |
| override [RenderingMode](./renderingmode/) { get; set; } | Gets or sets rendering mode of the text. |
| [Rotation](./rotation/) { get; set; } | Gets or sets rotation angle in degrees. |
| override [StrikeOut](./strikeout/) { get; set; } | Gets or sets strikeout for the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object |
| override [StrokingColor](./strokingcolor/) { get; set; } | Gets or sets color stroking operations of [`TextFragment`](../../aspose.pdf.text/textfragment/) rendering (stroke text, rectangle border) |
| override [Subscript](./subscript/) { get; set; } | Gets or sets subscript of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| override [Superscript](./superscript/) { get; set; } | Gets or sets superscript of the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [TabStops](./tabstops/) { get; } | Gets tabstops for the text. |
| [TabTag](../../aspose.pdf.text/textstate/tabtag/) { get; } | You can place this tag in text to declare tabulation. |
| override [Underline](./underline/) { get; set; } | Gets or sets underline for the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object |
| override [WordSpacing](./wordspacing/) { get; set; } | Gets or sets word spacing of the text. |

## Methods

| Name | Description |
| --- | --- |
| override [ApplyChangesFrom](./applychangesfrom/)(TextState) | Applies settings from another textState. |
| [IsFitRectangle](./isfitrectangle/)(string, Rectangle) | Checks if input string could be placed inside defined rectangle. |
| [MeasureHeight](./measureheight/)(char) | Measures character height. |
| override [MeasureString](./measurestring/)(string) | Measures the string. |

## Fields

| Name | Description |
| --- | --- |
| readonly [TabstopDefaultValue](../../aspose.pdf.text/textstate/tabstopdefaultvalue/) | Default value of tabulation in widths of space character of default font. |

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

