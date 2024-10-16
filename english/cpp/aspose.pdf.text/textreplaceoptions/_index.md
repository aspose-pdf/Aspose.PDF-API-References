---
title: Aspose::Pdf::Text::TextReplaceOptions class
linktitle: TextReplaceOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextReplaceOptions class. Represents text replace options in C++.'
type: docs
weight: 4800
url: /cpp/aspose.pdf.text/textreplaceoptions/
---
## TextReplaceOptions class


Represents text replace options.

```cpp
class TextReplaceOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Enum | Description |
| --- | --- |
| [ReplaceAdjustment](./replaceadjustment/) | Determines action that will be done after replace of text fragment to more short. None - no action, replaced text may overlaps rest of the line; AdjustSpaceWidth - tries adjust spaces between words to keep line length; WholeWordsHyphenation - tries distribute words between paragraph lines to keep paragraph's right field; ShiftRestOfLine - shifts rest of the line according to changing length of text, length of the line may be changed; Default value is ShiftRestOfLine. |
| [Scope](./scope/) | Scope where replace text operation is applied REPLACE_FIRST by default This obsolete option was kept for compatibility. It affects to PdfContentEditor and has no effect to [TextFragmentAbsorber](../textfragmentabsorber/). |
## Methods

| Method | Description |
| --- | --- |
| [get_AdjustmentNewLineSpacing](./get_adjustmentnewlinespacing/)() const | Gets value of line spacing that used if replace adjustment is forced to create new line of text. The value expected is multiplier of font size of the replaced text. Default is 1.2. |
| [get_IgnoreParagraphs](./get_ignoreparagraphs/)() const | Gets a value indicating whether to ignore distinct paragraphs when adjusting text on the page after text replacement. |
| [get_LeftAdjustment](./get_leftadjustment/)() const | Sets or gets left position adjustment for replaced text when using [TextReplaceOptions](./): |
| [get_ReplaceAdjustmentAction](./get_replaceadjustmentaction/)() const | Gets an action that will be done after replace of text fragment to more short. |
| [get_ReplaceScope](./get_replacescope/)() const | Gets a scope where replace text operation is applied. |
| [get_RightAdjustment](./get_rightadjustment/)() const | Sets or gets right position adjustment for replaced text when using [TextReplaceOptions](./): |
| [set_AdjustmentNewLineSpacing](./set_adjustmentnewlinespacing/)(double) | Sets value of line spacing that used if replace adjustment is forced to create new line of text. The value expected is multiplier of font size of the replaced text. Default is 1.2. |
| [set_IgnoreParagraphs](./set_ignoreparagraphs/)(bool) | Sets a value indicating whether to ignore distinct paragraphs when adjusting text on the page after text replacement. |
| [set_LeftAdjustment](./set_leftadjustment/)(double) | Sets or gets left position adjustment for replaced text when using [TextReplaceOptions](./): |
| [set_ReplaceAdjustmentAction](./set_replaceadjustmentaction/)(TextReplaceOptions::ReplaceAdjustment) | Sets an action that will be done after replace of text fragment to more short. |
| [set_ReplaceScope](./set_replacescope/)(TextReplaceOptions::Scope) | Sets a scope where replace text operation is applied. |
| [set_RightAdjustment](./set_rightadjustment/)(double) | Sets or gets right position adjustment for replaced text when using [TextReplaceOptions](./): |
| [TextReplaceOptions](./textreplaceoptions/)(TextReplaceOptions::Scope) | Initializes new instance of the [TextReplaceOptions](./) object for the specified scope. |
| [TextReplaceOptions](./textreplaceoptions/)(TextReplaceOptions::ReplaceAdjustment) | Initializes new instance of the [TextReplaceOptions](./) object for the specified after replace action. |
## See Also

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
