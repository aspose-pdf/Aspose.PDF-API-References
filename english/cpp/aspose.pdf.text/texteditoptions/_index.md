---
title: Aspose::Pdf::Text::TextEditOptions class
linktitle: TextEditOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Text::TextEditOptions class. Descubes options of text edit operations in C++.'
type: docs
weight: 3800
url: /cpp/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class


Descubes options of text edit operations.

```cpp
class TextEditOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Enum | Description |
| --- | --- |
| [ClippingPathsProcessingMode](./clippingpathsprocessingmode/) | Clipping path processing modes. |
| [FontReplace](./fontreplace/) | [Font](../font/) replacement behavior. |
| [LanguageTransformation](./languagetransformation/) | Language transformation modes. |
| [NoCharacterAction](./nocharacteraction/) | Action to perform if font does not contain required character. |
## Methods

| Method | Description |
| --- | --- |
| [get_AllowLanguageTransformation](./get_allowlanguagetransformation/)() const | Gets value that permits usage of language transformation during adding or editing of text. true - language transformation will be applied if necessary (default value). false - language transformation will NOT be applied. |
| [get_ClippingPathsProcessing](./get_clippingpathsprocessing/)() const | Gets mode for processing clipping path of the edited text. |
| [get_FontReplaceBehavior](./get_fontreplacebehavior/)() const | Gets mode that defines behavior for fonts replacement scenarios. |
| [get_LanguageTransformationBehavior](./get_languagetransformationbehavior/)() const | Gets mode that defines behavior for language transformation scenarios. |
| [get_NoCharacterBehavior](./get_nocharacterbehavior/)() const | Gets mode that defines behavior in case fonts don't contain requested characters. |
| [get_ReplacementFont](./get_replacementfont/)() const | Gets font used for replacing if user font does not contain required character. |
| [get_ToAttemptGetUnderlineFromSource](./get_toattemptgetunderlinefromsource/)() const | Gets value that permits searching for text underlining on the page of source document. (Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this. |
| [set_AllowLanguageTransformation](./set_allowlanguagetransformation/)(bool) | Sets value that permits usage of language transformation during adding or editing of text. true - language transformation will be applied if necessary (default value). false - language transformation will NOT be applied. |
| [set_ClippingPathsProcessing](./set_clippingpathsprocessing/)(TextEditOptions::ClippingPathsProcessingMode) | Gets mode for processing clipping path of the edited text. |
| [set_FontReplaceBehavior](./set_fontreplacebehavior/)(TextEditOptions::FontReplace) | Gets mode that defines behavior for fonts replacement scenarios. |
| [set_LanguageTransformationBehavior](./set_languagetransformationbehavior/)(TextEditOptions::LanguageTransformation) | Gets mode that defines behavior for language transformation scenarios. |
| [set_NoCharacterBehavior](./set_nocharacterbehavior/)(TextEditOptions::NoCharacterAction) | Sets mode that defines behavior in case fonts don't contain requested characters. |
| [set_ReplacementFont](./set_replacementfont/)(System::SharedPtr\<Font\>) | Sets font used for replacing if user font does not contain required character. |
| [set_ToAttemptGetUnderlineFromSource](./set_toattemptgetunderlinefromsource/)(bool) | Sets value that permits searching for text underlining on the page of source document. (Obsolete) Please use TextSearchOptions.SearchForTextRelatedGraphics instead this. |
| [TextEditOptions](./texteditoptions/)(TextEditOptions::NoCharacterAction) | Initializes new instance of the [TextEditOptions](./) object for the specified no-character behavior mode. |
| [TextEditOptions](./texteditoptions/)(TextEditOptions::FontReplace) | Initializes new instance of the [TextEditOptions](./) object for the specified font replacement behavior mode. |
| [TextEditOptions](./texteditoptions/)(bool) | Initializes new instance of the [TextEditOptions](./) object for the specified language transformation permission. |
| [TextEditOptions](./texteditoptions/)(TextEditOptions::LanguageTransformation) | Initializes new instance of the [TextEditOptions](./) object for the specified language transformation behavior mode. |
## See Also

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
