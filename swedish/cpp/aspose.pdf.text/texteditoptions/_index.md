---
title: "Aspose::Pdf::Text::TextEditOptions-klass"
linktitle: "TextEditOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::Text::TextEditOptions-klass. Beskriver alternativ för textredigeringsoperationer i C++."
type: docs
weight: 3800
url: /sv/cpp/aspose.pdf.text/texteditoptions/
---
## TextEditOptions class


Beskriver alternativ för textredigeringsoperationer.

```cpp
class TextEditOptions : public Aspose::Pdf::Text::TextOptions
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [ClippingPathsProcessingMode](./clippingpathsprocessingmode/) | Klippvägsbearbetningslägen. |
| [FontReplace](./fontreplace/) | [Font](../font/)-ersättningsbeteende. |
| [LanguageTransformation](./languagetransformation/) | Språktransformeringslägen. |
| [NoCharacterAction](./nocharacteraction/) | Åtgärd att utföra om teckensnittet inte innehåller det erforderliga tecknet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AllowLanguageTransformation](./get_allowlanguagetransformation/)() const | Hämtar värdet som tillåter användning av språktransformering vid tillägg eller redigering av text. true - språktransformering kommer att tillämpas om nödvändigt (standardvärde). false - språktransformering kommer INTE att tillämpas. |
| [get_ClippingPathsProcessing](./get_clippingpathsprocessing/)() const | Hämtar läge för bearbetning av klippväg för den redigerade texten. |
| [get_FontReplaceBehavior](./get_fontreplacebehavior/)() const | Hämtar läge som definierar beteende för scenarier med teckensnittsersättning. |
| [get_LanguageTransformationBehavior](./get_languagetransformationbehavior/)() const | Hämtar läge som definierar beteende för scenarier med språktransformering. |
| [get_NoCharacterBehavior](./get_nocharacterbehavior/)() const | Hämtar läge som definierar beteende om teckensnitt inte innehåller begärda tecken. |
| [get_ReplacementFont](./get_replacementfont/)() const | Hämtar teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet. |
| [get_ToAttemptGetUnderlineFromSource](./get_toattemptgetunderlinefromsource/)() const | Hämtar värdet som tillåter sökning efter understruken text på sidan i källdokumentet. (Föråldrad) Använd TextSearchOptions.SearchForTextRelatedGraphics istället för detta. |
| [set_AllowLanguageTransformation](./set_allowlanguagetransformation/)(bool) | Ställer in värdet som tillåter användning av språktransformering vid tillägg eller redigering av text. true - språktransformering kommer att tillämpas om nödvändigt (standardvärde). false - språktransformering kommer INTE att tillämpas. |
| [set_ClippingPathsProcessing](./set_clippingpathsprocessing/)(TextEditOptions::ClippingPathsProcessingMode) | Hämtar läge för bearbetning av klippväg för den redigerade texten. |
| [set_FontReplaceBehavior](./set_fontreplacebehavior/)(TextEditOptions::FontReplace) | Hämtar läge som definierar beteende för scenarier med teckensnittsersättning. |
| [set_LanguageTransformationBehavior](./set_languagetransformationbehavior/)(TextEditOptions::LanguageTransformation) | Hämtar läge som definierar beteende för scenarier med språktransformering. |
| [set_NoCharacterBehavior](./set_nocharacterbehavior/)(TextEditOptions::NoCharacterAction) | Ställer in läge som definierar beteende om teckensnitt inte innehåller begärda tecken. |
| [set_ReplacementFont](./set_replacementfont/)(const System::SharedPtr\<Font\>\&) | Ställer in teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet. |
| [set_ToAttemptGetUnderlineFromSource](./set_toattemptgetunderlinefromsource/)(bool) | Ställer in värde som tillåter sökning efter textunderstrykning på sidan i källdokumentet. (Föråldrad) Använd TextSearchOptions.SearchForTextRelatedGraphics istället för detta. |
| [TextEditOptions](./texteditoptions/)(TextEditOptions::NoCharacterAction) | Initierar en ny instans av objektet [TextEditOptions](./) för det specificerade beteendet utan tecken. |
| [TextEditOptions](./texteditoptions/)(TextEditOptions::FontReplace) | Initierar en ny instans av objektet [TextEditOptions](./) för det specificerade teckensnittsersättningsbeteendet. |
| [TextEditOptions](./texteditoptions/)(bool) | Initierar en ny instans av objektet [TextEditOptions](./) för den specificerade språktransformationsbehörigheten. |
| [TextEditOptions](./texteditoptions/)(TextEditOptions::LanguageTransformation) | Initierar en ny instans av objektet [TextEditOptions](./) för det specificerade språktransformationsbeteendet. |
## Se även

* Class [TextOptions](../textoptions/)
* Namespace [Aspose::Pdf::Text](../)
* Library [Aspose.PDF for C++](../../)
