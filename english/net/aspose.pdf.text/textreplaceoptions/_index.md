---
title: "TextReplaceOptions Class"
linktitle: "TextReplaceOptions"
articleTitle: "TextReplaceOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Text.TextReplaceOptions class. Represents text replace options"
type: docs
weight: 620
url: "/net/aspose.pdf.text/textreplaceoptions/"
keywords: "TextReplaceOptions, Aspose.Pdf.Text, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9"
---
## TextReplaceOptions class

Represents text replace options

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(Scope) | Initializes new instance of the `TextReplaceOptions` object for the specified scope. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(ReplaceAdjustment) | Initializes new instance of the `TextReplaceOptions` object for the specified after replace action. |

## Properties

| Name | Description |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. The value expected is multiplier of font size of the replaced text. Default is 1.2. |
| [FontSizeAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/fontsizeadjustmentaction/) { get; set; } | Gets or sets the policy for adjusting the font size to fit within the bounds defined by the [`Rectangle`](./rectangle/). |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Gets or sets a value indicating whether to ignore distinct paragraphs when adjusting text on the page after text replacement. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Sets or gets left position adjustment for replaced text when using TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [Rectangle](../../aspose.pdf.text/textreplaceoptions/rectangle/) { get; set; } | Gets or sets the rectangle to fit the text after replacement. |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Gets or sets an action that will be done after replace of text fragment to more short. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Gets or sets a scope where replace text operation is applied |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Sets or gets right position adjustment for replaced text when using TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

## Other Members

| Name | Description |
| --- | --- |
| enum [FontSizeAdjustment](../../aspose.pdf.text/textreplaceoptions.fontsizeadjustment) | Specifies a policy for how the font size of text should be adjusted to fit within a containing area. |
| enum [ReplaceAdjustment](../../aspose.pdf.text/textreplaceoptions.replaceadjustment) | Determines action that will be done after replace of text fragment to more short. None - no action, replaced text may overlaps rest of the line; AdjustSpaceWidth - tries adjust spaces between words to keep line length; WholeWordsHyphenation - tries distribute words between paragraph lines to keep paragraph's right field; ShiftRestOfLine - shifts rest of the line according to changing length of text, length of the line may be changed; Default value is ShiftRestOfLine. |
| enum [Scope](../../aspose.pdf.text/textreplaceoptions.scope) | Scope where replace text operation is applied REPLACE_FIRST by default This obsolete option was kept for compatibility. It affects to PdfContentEditor and has no effect to TextFragmentAbsorber. |

### See Also

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)

