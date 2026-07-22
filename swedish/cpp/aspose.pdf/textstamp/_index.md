---
title: "Aspose::Pdf::TextStamp klass"
linktitle: "TextStamp"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::TextStamp klass. Representerar textstämpling i C++."
type: docs
weight: 18400
url: /sv/cpp/aspose.pdf/textstamp/
---
## TextStamp class


Representerar en textuell stämpel.

```cpp
class TextStamp : public Aspose::Pdf::Stamp
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [NoCharacterAction](./nocharacteraction/) | Åtgärd att utföra om teckensnittet inte innehåller det erforderliga tecknet. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AutoAdjustFontSizePrecision](./get_autoadjustfontsizeprecision/)() const | Justera automatiskt precisionen för teckenstorlek. Standardvärde: 0.1;. |
| [get_AutoAdjustFontSizeToFitStampRectangle](./get_autoadjustfontsizetofitstamprectangle/)() const | Om aktiverat kommer teckenstorleken att automatiskt justeras för att passa stämpelrektangeln med storleken: [Width](../) och [Height](../). Standardbredd och -höjd hämtas från sidrektangeln. |
| [get_Draw](./get_draw/)() const | Denna egenskap bestämmer hur stämpeln ritas på sidan. Om Draw = true ritas stämpeln som grafiska operatorer och om Draw = false ritas stämpeln som text. |
| [get_FontSize](./get_fontsize/)() | Den faktiska teckenstorleken efter att stämpeln har placerats. (Kan skilja sig från den ursprungliga teckenstorleken som angavs via konstruktorn om alternativet 'AutoAdjustFontSizeToFitStampRectangle' är aktiverat.) |
| [get_Height](./get_height/)() override | Önskad höjd på stampen på sidan. |
| [get_Justify](./get_justify/)() | Definierar textjustering. Om denna egenskap är satt till true är både vänster- och högerranden av texten justerade. Standardvärde: false. |
| [get_MaxRowWidth](./get_maxrowwidth/)() const | Maximal radhöjd för WordWrap-alternativet. |
| [get_NoCharacterBehavior](./get_nocharacterbehavior/)() const | Hämtar läge som definierar beteende om teckensnitt inte innehåller begärda tecken. |
| [get_ReplacementFont](./get_replacementfont/)() const | Hämtar teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet. |
| [get_Scale](./get_scale/)() const | Definierar skalning av texten. Om denna egenskap är satt till true och ett Width‑värde har angetts kommer texten att skalas för att passa den angivna bredden. |
| [get_TextAlignment](./get_textalignment/)() const | Justering av texten inom stämpeln. |
| [get_TextState](./get_textstate/)() const | Hämtar textegenskaperna för stämpeln. Se **TextState** för detaljer. |
| [get_TreatYIndentAsBaseLine](./get_treatyindentasbaseline/)() const | Definierar koordinatursprunget för placering av text. Om TreatYIndentAsBaseLine = true (standard när Draw = true) kommer YIndent‑värdet att behandlas som textens baslinje. Om TreatYIndentAsBaseLine = false (standard när Draw = false) kommer YIndent‑värdet att behandlas som botten (nedstigningslinje) av texten. |
| [get_Value](./get_value/)() | Hämtar strängvärdet som används som stämpel på sidan. |
| [get_Width](./get_width/)() override | Önskad bredd på stämpeln på sidan. |
| [get_WordWrap](./get_wordwrap/)() const | Definierar radbrytning. Om denna egenskap är satt till true och ett Width‑värde har angetts kommer texten att brytas i flera rader för att passa den angivna bredden. Standardvärde: false. |
| [get_WordWrapMode](./get_wordwrapmode/)() const | Hämtar radbrytningsläget för textrendering. |
| [Put](./put/)(System::SharedPtr\<Page\>) override | Lägger till en textstämpel på sidan. |
| [set_AutoAdjustFontSizePrecision](./set_autoadjustfontsizeprecision/)(float) | Justera automatiskt precisionen för teckenstorlek. Standardvärde: 0.1;. |
| [set_AutoAdjustFontSizeToFitStampRectangle](./set_autoadjustfontsizetofitstamprectangle/)(bool) | Om aktiverat kommer teckenstorleken att automatiskt justeras för att passa stämpelrektangeln med storleken: [Width](../) och [Height](../). Standardbredd och -höjd hämtas från sidrektangeln. |
| [set_Draw](./set_draw/)(bool) | Denna egenskap bestämmer hur stämpeln ritas på sidan. Om Draw = true ritas stämpeln som grafiska operatorer och om Draw = false ritas stämpeln som text. |
| [set_Height](./set_height/)(double) override | Önskad höjd på stampen på sidan. |
| [set_Justify](./set_justify/)(bool) | Definierar textjustering. Om denna egenskap är satt till true är både vänster- och högerranden av texten justerade. Standardvärde: false. |
| [set_MaxRowWidth](./set_maxrowwidth/)(double) | Maximal radhöjd för WordWrap-alternativet. |
| [set_NoCharacterBehavior](./set_nocharacterbehavior/)(TextStamp::NoCharacterAction) | Ställer in läge som definierar beteende om teckensnitt inte innehåller begärda tecken. |
| [set_ReplacementFont](./set_replacementfont/)(const System::SharedPtr\<Text::Font\>\&) | Ställer in teckensnitt som används för ersättning om användarens teckensnitt inte innehåller det erforderliga tecknet. |
| [set_Scale](./set_scale/)(bool) | Definierar skalning av texten. Om denna egenskap är satt till true och ett Width‑värde har angetts kommer texten att skalas för att passa den angivna bredden. |
| [set_TextAlignment](./set_textalignment/)(Aspose::Pdf::HorizontalAlignment) | Justering av texten inom stämpeln. |
| [set_TreatYIndentAsBaseLine](./set_treatyindentasbaseline/)(bool) | Definierar koordinatursprunget för placering av text. Om TreatYIndentAsBaseLine = true (standard när Draw = true) kommer YIndent‑värdet att behandlas som textens baslinje. Om TreatYIndentAsBaseLine = false (standard när Draw = false) kommer YIndent‑värdet att behandlas som botten (nedstigningslinje) av texten. |
| [set_Value](./set_value/)(const System::String\&) | Ställer in strängvärdet som används som stämpel på sidan. |
| [set_Width](./set_width/)(double) override | Önskad bredd på stämpeln på sidan. |
| [set_WordWrap](./set_wordwrap/)(bool) | Definierar radbrytning. Om denna egenskap är satt till true och ett Width‑värde har angetts kommer texten att brytas i flera rader för att passa den angivna bredden. Standardvärde: false. |
| [set_WordWrapMode](./set_wordwrapmode/)(Aspose::Pdf::Text::TextFormattingOptions::WordWrapMode) | Ställer in radbrytningsläget för textrendering. |
| [TextStamp](./textstamp/)(const System::String\&) | Initierar en ny instans av klassen [TextStamp](./). |
| [TextStamp](./textstamp/)(const System::String\&, const System::SharedPtr\<Aspose::Pdf::Text::TextState\>\&) | Initierar en ny instans av klassen [TextStamp](./). |
| [TextStamp](./textstamp/)(const System::SharedPtr\<Facades::FormattedText\>\&) | Initierar en ny instans av klassen [TextStamp](./) med ett formattedText‑objekt. |
## Se även

* Class [Stamp](../stamp/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
