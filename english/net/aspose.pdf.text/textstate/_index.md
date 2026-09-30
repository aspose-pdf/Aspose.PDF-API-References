---
title: "TextState Class"
linktitle: "TextState"
articleTitle: "TextState"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TextState class. Represents a text state of a text"
type: docs
weight: 690
url: "/net/aspose.pdf.text/textstate/"
keywords: "TextState, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## TextState class

Represents a text state of a text

```csharp
public class TextState
```

## Constructors

| Name | Description |
| --- | --- |
| [TextState](./textstate/#constructor)() | Creates text state object. |
| [TextState](./textstate/#constructor_1)(Color) | Creates text state object with foreground color specification. |
| [TextState](./textstate/#constructor_2)(double) | Creates text state object with font size specification. |
| [TextState](./textstate/#constructor_3)(string) | Creates text state object with font family specification. |
| [TextState](./textstate/#constructor_4)(Color, double) | Creates text state object with foreground color and font size specification. |
| [TextState](./textstate/#constructor_5)(string, double) | Creates text state object with font family and font size specification. |
| [TextState](./textstate/#constructor_6)(string, bool, bool) | Creates text state object with font family and font style specification. |

## Properties

| Name | Description |
| --- | --- |
| virtual [BackgroundColor](./backgroundcolor/) { get; set; } | Sets background color of the text. |
| virtual [CharacterSpacing](./characterspacing/) { get; set; } | Gets or sets character spacing of the text. |
| virtual [CoordinateOrigin](./coordinateorigin/) { get; set; } | Gets or sets text CoordinateOrigin. If CoordinateOrigin is Descender, the text Y coordinate corresponds to the font's lowest point. If CoordinateOrigin is BaseLine, the text Y coordinate corresponds to the font's baseline. The default value is Descender. If the font's Descent value is too big, text can be rendered higher than other fonts. In this case, CoordinateOrigin BaseLine can be selected for better text rendering. |
| virtual [Font](./font/) { get; set; } | Gets or sets font of the text. |
| virtual [FontSize](./fontsize/) { get; set; } | Gets or sets font size of the text. |
| virtual [FontStyle](./fontstyle/) { get; set; } | Sets font style of the text. |
| virtual [ForegroundColor](./foregroundcolor/) { get; set; } | Gets or sets foreground color of the text. |
| virtual [HorizontalAlignment](./horizontalalignment/) { get; set; } | Gets or sets horizontal alignment for the text. |
| virtual [HorizontalScaling](./horizontalscaling/) { get; set; } | Gets or sets horizontal scaling of the text. |
| virtual [Invisible](./invisible/) { get; set; } | Gets or sets the invisibility of text. This basically reflects the `RenderingMode` state, except for some special cases (like clipping). |
| virtual [LineSpacing](./linespacing/) { get; set; } | Gets or sets line spacing of the text. |
| virtual [RenderingMode](./renderingmode/) { get; set; } | Gets or sets rendering mode of text. |
| virtual [StrikeOut](./strikeout/) { get; set; } | Gets or sets strikeout for the text, represented by the [`TextSegment`](../../aspose.pdf.text/textsegment/) object |
| virtual [StrokingColor](./strokingcolor/) { get; set; } | Gets or sets foreground color of the text. |
| virtual [Subscript](./subscript/) { get; set; } | Gets or sets subscript of the text. |
| virtual [Superscript](./superscript/) { get; set; } | Gets or sets superscript of the text. |
| [TabTag](./tabtag/) { get; } | You can place this tag in text to declare tabulation. |
| virtual [Underline](./underline/) { get; set; } | Gets or sets underline for the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object |
| virtual [WordSpacing](./wordspacing/) { get; set; } | Gets or sets word spacing of the text. |

## Methods

| Name | Description |
| --- | --- |
| virtual [ApplyChangesFrom](./applychangesfrom/)(TextState) | Applies settings from another textState. |
| [MeasureHeight](./measureheight/)(char) | Measures character height. |
| virtual [MeasureString](./measurestring/)(string) | Measures the string. |

## Fields

| Name | Description |
| --- | --- |
| readonly [TabstopDefaultValue](./tabstopdefaultvalue/) | Default value of tabulation in widths of space character of default font. |

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

