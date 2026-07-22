---
title: "Aspose::Pdf::PdfFormatConversionOptions-klass"
linktitle: "PdfFormatConversionOptions"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::PdfFormatConversionOptions-klass. representerar en uppsättning alternativ för att konvertera PDF-dokument i C++."
type: docs
weight: 15000
url: /sv/cpp/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class


representerar en uppsättning alternativ för att konvertera PDF-dokument

```cpp
class PdfFormatConversionOptions : public System::Object
```

## Enums

| Enum | Beskrivning |
| --- | --- |
| [PuaProcessingStrategy](./puaprocessingstrategy/) | Vissa PDF-dokument har speciella Unicode-symboler som tillhör Private Use Area (PUA), se beskrivningen på [https://en.wikipedia.org/wiki/Private_Use_Areas](https://en.wikipedia.org/wiki/Private_Use_Areas). Dessa symboler orsakar PDF/A-kompatibilitetsfel som "Text is mapped to Unicode Private Use Area but no ActualText entry is present". Denna uppräkning deklarerar strategier som kan användas för att hantera PUA-symboler. |
| [RemoveFontsStrategy](./removefontsstrategy/) | Vissa dokument har stor storlek efter konvertering till PDF/A-format. För att minska filstorleken för dessa dokument är det nödvändigt att definiera en strategi för att ta bort teckensnitt. Denna uppräkning deklarerar strategier som kan användas för att optimera teckensnittsanvändning. Varje strategi i denna uppräkning har mening endast när flaggan [OptimizeFileSize](../) är satt. |
| [SegmentAlignStrategy](./segmentalignstrategy/) | Beskriver strategier som används för att justera dokumentets textsegment. För närvarande stöds endast strategin för att återställa segment till sina ursprungliga gränser. I framtiden kan ytterligare strategier läggas till. |
## Metoder

| Metod | Beskrivning |
| --- | --- |
| [get_AlignText](./get_aligntext/)() const | Detta flagga styr textjustering i konverterat dokument. Som standard påverkar inte dokumentkonverteringen textjusteringen och lämnar texten som den är. Men i vissa fall kan teckensnittsersättning orsaka överlappande text eller extra mellanslag i det konverterade dokumentet. När detta flagga är satt utförs speciella justeringsoperationer. Detta flagga bör endast sättas för dokument som har problem med överlappande text eller extra mellanslag, eftersom användning av detta flagga minskar prestanda och i vissa fall kan korrupta textinnehållet. |
| [get_AutoTaggingSettings](./get_autotaggingsettings/)() const | Hämtar inställningarna för automatisk taggning under PDF-formatkonvertering. |
| [get_ConvertSoftMaskAction](./get_convertsoftmaskaction/)() const | Åtgärd för bilder med mjuk mask. |
| static [get_Default](./get_default/)() | Hämtar [PdfFormatConversionOptions](./)-objektet med standardparametrar. |
| [get_ErrorAction](./get_erroraction/)() const | Åtgärd för objekt som inte kan konverteras. |
| [get_ExcludeFontsStrategy](./get_excludefontsstrategy/)() const | Strategi(er) för att utesluta överflödiga teckensnitt och minska dokumentets filstorlek. Denna parameter har mening endast när flaggan [OptimizeFileSize](../) är satt till true. Som standard används en kombination av strategierna [SubsetFonts](./removefontsstrategy/) och [RemoveDuplicatedFonts](./removefontsstrategy/). |
| [get_FontEmbeddingOptions](./get_fontembeddingoptions/)() const | Alternativ för fall då det inte är möjligt att bädda in vissa teckensnitt i PDF-dokumentet. |
| [get_Format](./get_format/)() const | PDF-format. |
| [get_IccProfileFileName](./get_iccprofilefilename/)() const | Hämtar filnamnet för ICC-profilen. Om null används standard-ICC-profilen. |
| [get_IsAsyncImageStreamsConversionMode](./get_isasyncimagestreamsconversionmode/)() const | Hämtar/sätter körning av bildströmmar i asynkront läge. |
| [get_IsLowMemoryMode](./get_islowmemorymode/)() const | Är lågminneskonverteringsläge aktiverat. |
| [get_IsTransferInfo](./get_istransferinfo/)() const | Hämtar om data från Info ska överföras till [Metadata](../metadata/) när det konverteras till PDF 2.0. True som standard. |
| [get_LogFileName](./get_logfilename/)() const | Sökväg till fil där kommentarer kommer att lagras. |
| [get_LogStream](./get_logstream/)() const | Ström där kommentarer kommer att lagras. |
| [get_NonSpecificationCases](./get_nonspecificationcases/)() const | Innehåller flaggor för att kontrollera PDF/A‑konverteringsprocessen för fall då källdokumentet inte motsvarar PDF/A‑specifikationen. |
| [get_NotAccessibleFonts](./get_notaccessiblefonts/)() | Denna egenskap är en ut‑egenskap. Den innehåller alla teckensnitt (teckensnittsnamn) som inte hittades på datorn vid den senaste PDF/A‑konverteringen. |
| [get_OptimizeFileSize](./get_optimizefilesize/)() const | Hämtar en flagga som aktiverar/inaktiverar speciellt konverteringsläge för att få ett PDF/A‑dokument med reducerad filstorlek. Nu påverkar denna flagga optimeringen av teckensnitt som används i PDF‑dokumentet, möjligen kommer flaggan i framtiden även att användas för att slå på optimering av andra datastrukturer, såsom grafik. Kombinationen av denna flagga och läge kan avsevärt minska filstorleken men samtidigt kan den avsevärt minska konverteringsprestandan. |
| [get_OutputIntent](./get_outputintent/)() const | Hämtar [Aspose::Pdf::OutputIntent](../outputintent/) för PDF‑formatkonverteringen. |
| [get_PuaTextProcessingStrategy](./get_puatextprocessingstrategy/)() const | Strategi för att bearbeta symboler från Unicode Private Use Area (PUA). |
| [get_SymbolicFontEncodingStrategy](./get_symbolicfontencodingstrategy/)() const | Strategi för att kopiera kodningsdata för symboliska teckensnitt om ett symboliskt TrueType‑teckensnitt har mer än en kodningstabell. |
| [get_TransparencyAction](./get_transparencyaction/)() const | Åtgärd för bildmaskerade objekt. |
| [get_UnicodeProcessingRules](./get_unicodeprocessingrules/)() const | Regler för att lösa problem med Unicode‑mappning. Kan vara null. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(const System::String\&, PdfFormat, ConvertErrorAction) | Konstruktor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(const System::String\&, PdfFormat) | Konstruktor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(PdfFormat) | Konstruktor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(PdfFormat, ConvertErrorAction) | Konstruktor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(const System::String\&, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Konstruktor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(const System::SharedPtr\<System::IO::Stream\>\&, PdfFormat, ConvertErrorAction) | Konstruktor. |
| [set_AlignText](./set_aligntext/)(bool) | Detta flagga styr textjustering i konverterat dokument. Som standard påverkar inte dokumentkonverteringen textjusteringen och lämnar texten som den är. Men i vissa fall kan teckensnittsersättning orsaka överlappande text eller extra mellanslag i det konverterade dokumentet. När detta flagga är satt utförs speciella justeringsoperationer. Detta flagga bör endast sättas för dokument som har problem med överlappande text eller extra mellanslag, eftersom användning av detta flagga minskar prestanda och i vissa fall kan korrupta textinnehållet. |
| [set_AutoTaggingSettings](./set_autotaggingsettings/)(const System::SharedPtr\<Aspose::Pdf::AutoTaggingSettings\>\&) | Ställer in inställningarna för automatisk taggning under PDF‑formatkonvertering. |
| [set_ConvertSoftMaskAction](./set_convertsoftmaskaction/)(Aspose::Pdf::ConvertSoftMaskAction) | Åtgärd för bilder med mjuk mask. |
| [set_ErrorAction](./set_erroraction/)(ConvertErrorAction) | Åtgärd för objekt som inte kan konverteras. |
| [set_ExcludeFontsStrategy](./set_excludefontsstrategy/)(PdfFormatConversionOptions::RemoveFontsStrategy) | Strategi(er) för att utesluta överflödiga teckensnitt och minska dokumentets filstorlek. Denna parameter har mening endast när flaggan [OptimizeFileSize](../) är satt till true. Som standard används en kombination av strategierna [SubsetFonts](./removefontsstrategy/) och [RemoveDuplicatedFonts](./removefontsstrategy/). |
| [set_Format](./set_format/)(PdfFormat) | PDF-format. |
| [set_IccProfileFileName](./set_iccprofilefilename/)(const System::String\&) | Ställer in filnamnet för ICC‑profilnamnet. Om null används standard‑ICC‑profilen. |
| [set_IsAsyncImageStreamsConversionMode](./set_isasyncimagestreamsconversionmode/)(bool) | Hämtar/sätter körning av bildströmmar i asynkront läge. |
| [set_IsLowMemoryMode](./set_islowmemorymode/)(bool) | Är lågminneskonverteringsläge aktiverat. |
| [set_IsTransferInfo](./set_istransferinfo/)(bool) | Ställer in om data ska överföras från Info till [Metadata](../metadata/) vid konvertering till PDF 2.0. Sant som standard. |
| [set_LogFileName](./set_logfilename/)(const System::String\&) | Sökväg till fil där kommentarer kommer att lagras. |
| [set_LogStream](./set_logstream/)(const System::SharedPtr\<System::IO::Stream\>\&) | Ström där kommentarer kommer att lagras. |
| [set_OptimizeFileSize](./set_optimizefilesize/)(bool) | Ställer in en flagga som aktiverar/inaktiverar speciellt konverteringsläge för att få ett PDF/A‑dokument med reducerad filstorlek. Nu påverkar denna flagga optimeringen av teckensnitt som används i PDF‑dokumentet, möjligen kommer flaggan i framtiden även att användas för att slå på optimering av andra datastrukturer, såsom grafik. Kombinationen av denna flagga och läge kan avsevärt minska filstorleken men samtidigt kan den avsevärt minska konverteringsprestandan. |
| [set_OutputIntent](./set_outputintent/)(const System::SharedPtr\<Aspose::Pdf::OutputIntent\>\&) | Ställer in [Aspose::Pdf::OutputIntent](../outputintent/) för PDF‑formatkonverteringen. |
| [set_PuaTextProcessingStrategy](./set_puatextprocessingstrategy/)(PdfFormatConversionOptions::PuaProcessingStrategy) | Strategi för att bearbeta symboler från Unicode Private Use Area (PUA). |
| [set_SymbolicFontEncodingStrategy](./set_symbolicfontencodingstrategy/)(const System::SharedPtr\<PdfASymbolicFontEncodingStrategy\>\&) | Strategi för att kopiera kodningsdata för symboliska teckensnitt om ett symboliskt TrueType‑teckensnitt har mer än en kodningstabell. |
| [set_TransparencyAction](./set_transparencyaction/)(ConvertTransparencyAction) | Åtgärd för bildmaskerade objekt. |
| [set_UnicodeProcessingRules](./set_unicodeprocessingrules/)(const System::SharedPtr\<ToUnicodeProcessingRules\>\&) | Regler för att lösa problem med Unicode‑mappning. Kan vara null. |
## Se även

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
