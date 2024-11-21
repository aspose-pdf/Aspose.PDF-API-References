---
title: Class TextReplaceOptions
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Text.TextReplaceOptions class. Represents text replace options
type: docs
weight: 8440
url: /net/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class

Represents text replace options

```csharp
public sealed class TextReplaceOptions : TextOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [TextReplaceOptions](textreplaceoptions/#constructor)(ReplaceAdjustment) | Initializes new instance of the `TextReplaceOptions` object for the specified after replace action. |
| [TextReplaceOptions](textreplaceoptions/#constructor_1)(Scope) | Initializes new instance of the `TextReplaceOptions` object for the specified scope. |

## Properties

| Name | Description |
| --- | --- |
| [AdjustmentNewLineSpacing](../../aspose.pdf.text/textreplaceoptions/adjustmentnewlinespacing/) { get; set; } | Gets or sets value of line spacing that used if replace adjustment is forced to create new line of text. The value expected is multiplier of font size of the replaced text. Default is 1.2. |
| [IgnoreParagraphs](../../aspose.pdf.text/textreplaceoptions/ignoreparagraphs/) { get; set; } | Gets or sets a value indicating whether to ignore distinct paragraphs when adjusting text on the page after text replacement. |
| [LeftAdjustment](../../aspose.pdf.text/textreplaceoptions/leftadjustment/) { get; set; } | Sets or gets left position adjustment for replaced text when using TextReplaceOptions: - ReplaceAdjustmentAction = IsFormFillingMode; |
| [ReplaceAdjustmentAction](../../aspose.pdf.text/textreplaceoptions/replaceadjustmentaction/) { get; set; } | Gets or sets an action that will be done after replace of text fragment to more short. |
| [ReplaceScope](../../aspose.pdf.text/textreplaceoptions/replacescope/) { get; set; } | Gets or sets a scope where replace text operation is applied |
| [RightAdjustment](../../aspose.pdf.text/textreplaceoptions/rightadjustment/) { get; set; } | Sets or gets right position adjustment for replaced text when using TextReplaceOptions: - ReplaceAdjustmentAction = WholeWordsHyphenation; - ReplaceAdjustmentAction = IsFormFillingMode; |

### See Also

* class [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)


