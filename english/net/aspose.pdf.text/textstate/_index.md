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
| [TextState](./textstate/#constructor) | Creates text state object. |
| [TextState](./textstate/#constructor_1)(*double*) | Creates text state object with font size specification. |
| [TextState](./textstate/#constructor_2)(*[Color](../../aspose.pdf/color/)*) | Creates text state object with foreground color specification. |
| [TextState](./textstate/#constructor_3)(*string*) | Creates text state object with font family specification. |
| [TextState](./textstate/#constructor_4)(*[Color](../../aspose.pdf/color/), double*) | Creates text state object with foreground color and font size specification. |
| [TextState](./textstate/#constructor_5)(*string, double*) | Creates text state object with font family and font size specification. |
| [TextState](./textstate/#constructor_6)(*string, bool, bool*) | Creates text state object with font family and font style specification. |

## Properties

| Name | Description |
| --- | --- |
| [BackgroundColor](./backgroundcolor/) { get; set; } | Sets background color of the text. |
| [CharacterSpacing](./characterspacing/) { get; set; } | Gets or sets character spacing of the text. |
| [CoordinateOrigin](./coordinateorigin/) { get; set; } | Gets or sets text CoordinateOrigin. |
| [Font](./font/) { get; set; } | Gets or sets font of the text. |
| [FontSize](./fontsize/) { get; set; } | Gets or sets font size of the text. |
| [FontStyle](./fontstyle/) { get; set; } | Sets font style of the text. |
| [ForegroundColor](./foregroundcolor/) { get; set; } | Gets or sets foreground color of the text. |
| [HorizontalAlignment](./horizontalalignment/) { get; set; } | Gets or sets horizontal alignment for the text. |
| [HorizontalScaling](./horizontalscaling/) { get; set; } | Gets or sets horizontal scaling of the text. |
| [Invisible](./invisible/) { get; set; } | Gets or sets the invisibility of text. This basically reflects the `RenderingMode` state, except for some special cases (like clipping). |
| [IsBackgroundColorSet](./isbackgroundcolorset/) { get; set; } |  |
| [IsCharacterSpacingSet](./ischaracterspacingset/) { get; set; } |  |
| [IsFontSet](./isfontset/) { get; set; } |  |
| [IsFontSizeSet](./isfontsizeset/) { get; set; } |  |
| [IsFontStyleSet](./isfontstyleset/) { get; set; } |  |
| [IsForegroundColorSet](./isforegroundcolorset/) { get; set; } |  |
| [IsHorizontalAlignmentSet](./ishorizontalalignmentset/) { get; set; } |  |
| [IsHorizontalScalingSet](./ishorizontalscalingset/) { get; set; } |  |
| [IsInvisibilitySet](./isinvisibilityset/) { get; set; } |  |
| [IsLineSpacingSet](./islinespacingset/) { get; set; } |  |
| [IsRenderingModeSet](./isrenderingmodeset/) { get; set; } |  |
| [IsStrikeOutSet](./isstrikeoutset/) { get; set; } |  |
| [IsStrokingColorSet](./isstrokingcolorset/) { get; set; } |  |
| [IsSubSuperscriptSet](./issubsuperscriptset/) { get; set; } |  |
| [IsTextMatrixSet](./istextmatrixset/) { get; set; } |  |
| [IsUnderlineSet](./isunderlineset/) { get; set; } |  |
| [IsVerticalAlignmentSet](./isverticalalignmentset/) { get; set; } |  |
| [IsWordSpacingSet](./iswordspacingset/) { get; set; } |  |
| [LineSpacing](./linespacing/) { get; set; } | Gets or sets line spacing of the text. |
| [RenderingMode](./renderingmode/) { get; set; } | Gets or sets rendering mode of text. |
| [StrikeOut](./strikeout/) { get; set; } | Gets or sets strikeout for the text, represented by the [`TextSegment`](../../aspose.pdf.text/textsegment/) object. |
| [StrokingColor](./strokingcolor/) { get; set; } | Gets or sets foreground color of the text. |
| [Subscript](./subscript/) { get; set; } | Gets or sets subscript of the text. |
| [Superscript](./superscript/) { get; set; } | Gets or sets superscript of the text. |
| [TabTag](./tabtag/) { get; } | You can place this tag in text to declare tabulation. |
| [Underline](./underline/) { get; set; } | Gets or sets underline for the text, represented by the [`TextFragment`](../../aspose.pdf.text/textfragment/) object. |
| [WordSpacing](./wordspacing/) { get; set; } | Gets or sets word spacing of the text. |

## Methods

| Name | Description |
| --- | --- |
| [ApplyChangesFrom](./applychangesfrom/)(*TextState*) | Applies settings from another textState. |
| [MeasureHeight](./measureheight/)(*char*) | Measures character height. |
| [MeasureString](./measurestring/)(*string*) | Measures the string. |

## Fields

| Name | Description |
| --- | --- |
| readonly [TabstopDefaultValue](./tabstopdefaultvalue/) | Default value of tabulation in widths of space character of default font. |

### See Also

* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

