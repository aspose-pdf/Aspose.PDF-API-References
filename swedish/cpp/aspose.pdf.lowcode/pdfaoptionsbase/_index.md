---
title: "Aspose::Pdf::LowCode::PdfAOptionsBase klass"
linktitle: "PdfAOptionsBase"
second_title: "Aspose.PDF för C++ API-referens"
description: "Aspose::Pdf::LowCode::PdfAOptionsBase klass. Representerar basklassen för PdfAConverter‑plugin‑alternativen. Denna klass tillhandahåller egenskaper och metoder för att konfigurera PDF/A‑konverterings‑ och valideringsprocessen i C++."
type: docs
weight: 5500
url: /sv/cpp/aspose.pdf.lowcode/pdfaoptionsbase/
---
## PdfAOptionsBase class


Representerar basklassen för [PdfAConverter](../pdfaconverter/) plugin‑alternativen. Denna klass tillhandahåller egenskaper och metoder för att konfigurera PDF/A‑konverterings‑ och valideringsprocessen.

```cpp
class PdfAOptionsBase : public Aspose::Pdf::LowCode::IPluginOptions,
                        public Aspose::Pdf::LowCode::IDataContainer
```

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Lägger till en ny datakälla i samlingen. |
| [get_AlignText](./get_aligntext/)() | Hämtar ett värde som indikerar om ytterligare åtgärder är nödvändiga för att bevara textjustering under PDF/A‑konverteringsprocessen. |
| [get_ErrorAction](./get_erroraction/)() | Hämtar den åtgärd som ska vidtas för objekt som inte kan konverteras. |
| [get_ExcludeFontsStrategy](./get_excludefontsstrategy/)() | Hämtar strategin för att ta bort teckensnitt för att minimera utdatafilens storlek under PDF/A‑konverteringsprocessen. |
| [get_FontEmbeddingOptions](./get_fontembeddingoptions/)() | Hämtar alternativen för att bearbeta teckensnitt som inte kan bäddas in i dokumentet. |
| [get_IccProfileFileName](./get_iccprofilefilename/)() | Hämtar filnamnet på ICC‑profilen (International [Color](../../aspose.pdf/color/) Consortium) som ska användas för PDF/A‑konverteringen i stället för standardprofilen. |
| [get_Inputs](./get_inputs/)() override | Hämtar samling av datakällor. |
| [get_IsLowMemoryMode](./get_islowmemorymode/)() | Hämtar ett värde som indikerar om lågt minnesläge är aktiverat under PDF/A‑konverteringsprocessen. |
| [get_LogOutputSource](./get_logoutputsource/)() const | Hämtar datakällan för loggutdata. |
| [get_NonSpecificationFlags](./get_nonspecificationflags/)() | Hämtar flaggorna som styr PDF/A‑konverteringen för fall då källdokumentet PDF inte överensstämmer med PDF‑specifikationen. |
| [get_OptimizeFileSize](./get_optimizefilesize/)() | Hämtar ett värde som indikerar om filstorleken ska försöka minskas under PDF/A‑konverteringsprocessen. |
| [get_PdfAVersion](./get_pdfaversion/)() const | Hämtar versionen av PDF/A‑standarden som ska användas för validering eller konvertering. |
| [get_PuaSymbolsProcessingStrategy](./get_puasymbolsprocessingstrategy/)() | Hämtar strategin för att bearbeta Private Use Area (PUA)-symboler i PDF‑dokumentet. |
| [get_SoftMaskAction](./get_softmaskaction/)() | Hämtar den åtgärd som ska vidtas under konvertering av bilder med mjuka maskeringar. |
| [get_SymbolicFontEncodingStrategy](./get_symbolicfontencodingstrategy/)() | Hämtar strategin för kodning av symboliska teckensnitt vid konvertering till PDF/A‑format. |
| [get_UnicodeProcessingRules](./get_unicodeprocessingrules/)() | Hämtar reglerna för att bearbeta ToUnicode CMap‑tabeller som inte är länkade till Unicode‑symboler under PDF/A‑konverteringsprocessen. |
| [PdfAOptionsBase](./pdfaoptionsbase/)() |  |
| [set_AlignText](./set_aligntext/)(bool) | Ställer in ett värde som indikerar om ytterligare åtgärder är nödvändiga för att bevara textjustering under PDF/A‑konverteringsprocessen. |
| [set_ErrorAction](./set_erroraction/)(ConvertErrorAction) | Ställer in åtgärden som ska vidtas för objekt som inte kan konverteras. |
| [set_ExcludeFontsStrategy](./set_excludefontsstrategy/)(PdfFormatConversionOptions::RemoveFontsStrategy) | Ställer in strategin för att ta bort teckensnitt för att minimera utdatafilens storlek under PDF/A-konverteringsprocessen. |
| [set_IccProfileFileName](./set_iccprofilefilename/)(const System::String\&) | Ställer in filnamnet för ICC (International [Color](../../aspose.pdf/color/) Consortium)-profilen som ska användas för PDF/A-konverteringen i stället för standardprofilen. |
| [set_IsLowMemoryMode](./set_islowmemorymode/)(bool) | Ställer in ett värde som indikerar om lågt minnesläge är aktiverat under PDF/A-konverteringsprocessen. |
| [set_LogOutputSource](./set_logoutputsource/)(const System::SharedPtr\<IDataSource\>\&) | Ställer in datakällan för loggutdata. |
| [set_OptimizeFileSize](./set_optimizefilesize/)(bool) | Ställer in ett värde som indikerar om filstorleken ska försöka minskas under PDF/A-konverteringsprocessen. |
| [set_PdfAVersion](./set_pdfaversion/)(PdfAStandardVersion) | Ställer in versionen av PDF/A-standarden som ska användas för validering eller konvertering. |
| [set_PuaSymbolsProcessingStrategy](./set_puasymbolsprocessingstrategy/)(PdfFormatConversionOptions::PuaProcessingStrategy) | Ställer in strategin för att bearbeta Private Use Area (PUA)-symboler i PDF-dokumentet. |
| [set_SoftMaskAction](./set_softmaskaction/)(ConvertSoftMaskAction) | Ställer in åtgärden som ska vidtas under konvertering av bilder med mjuka masker. |
| [set_SymbolicFontEncodingStrategy](./set_symbolicfontencodingstrategy/)(const System::SharedPtr\<PdfASymbolicFontEncodingStrategy\>\&) | Ställer in strategin för kodning av symboliska teckensnitt vid konvertering till PDF/A-format. |
| [set_UnicodeProcessingRules](./set_unicodeprocessingrules/)(const System::SharedPtr\<ToUnicodeProcessingRules\>\&) | Ställer in reglerna för att bearbeta ToUnicode CMap-tabeller som inte är länkade till Unicode-symboler under PDF/A-konverteringsprocessen. |
## Se även

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
