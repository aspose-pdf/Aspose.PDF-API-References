---
title: Aspose::Pdf::LowCode::PdfAOptionsBase class
linktitle: PdfAOptionsBase
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::LowCode::PdfAOptionsBase class. Represents the base class for the PdfAConverter plugin options. This class provides properties and methods for configuring the PDF/A conversion and validation process in C++.'
type: docs
weight: 5500
url: /cpp/aspose.pdf.lowcode/pdfaoptionsbase/
---
## PdfAOptionsBase class


Represents the base class for the [PdfAConverter](../pdfaconverter/) plugin options. This class provides properties and methods for configuring the PDF/A conversion and validation process.

```cpp
class PdfAOptionsBase : public Aspose::Pdf::LowCode::IPluginOptions,
                        public Aspose::Pdf::LowCode::IDataContainer
```

## Methods

| Method | Description |
| --- | --- |
| [AddInput](./addinput/)(System::SharedPtr\<IDataSource\>) override | Adds new data source to the collection. |
| [get_AlignText](./get_aligntext/)() | Gets a value indicating whether additional means are necessary to preserve text alignment during the PDF/A conversion process. |
| [get_ErrorAction](./get_erroraction/)() | Gets the action to be taken for objects that cannot be converted. |
| [get_ExcludeFontsStrategy](./get_excludefontsstrategy/)() | Gets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process. |
| [get_FontEmbeddingOptions](./get_fontembeddingoptions/)() | Gets the options to process fonts that cannot be embedded into the document. |
| [get_IccProfileFileName](./get_iccprofilefilename/)() | Gets the filename of the ICC (International [Color](../../aspose.pdf/color/) Consortium) profile to be used for the PDF/A conversion in place of the default one. |
| [get_Inputs](./get_inputs/)() override | Gets collection of data sources. |
| [get_IsLowMemoryMode](./get_islowmemorymode/)() | Gets a value indicating whether the low memory mode is enabled during the PDF/A conversion process. |
| [get_LogOutputSource](./get_logoutputsource/)() const | Gets the data source for the log output. |
| [get_NonSpecificationFlags](./get_nonspecificationflags/)() | Gets the flags that control the PDF/A conversion for cases when the source PDF document doesn't correspond to the PDF specification. |
| [get_OptimizeFileSize](./get_optimizefilesize/)() | Gets a value indicating whether to try to reduce the file size during the PDF/A conversion process. |
| [get_PdfAVersion](./get_pdfaversion/)() const | Gets the version of the PDF/A standard to be used for validation or conversion. |
| [get_PuaSymbolsProcessingStrategy](./get_puasymbolsprocessingstrategy/)() | Gets the strategy for processing Private Use Area (PUA) symbols in the PDF document. |
| [get_SoftMaskAction](./get_softmaskaction/)() | Gets the action to be taken during the conversion of images with soft masks. |
| [get_SymbolicFontEncodingStrategy](./get_symbolicfontencodingstrategy/)() | Gets the strategy for encoding symbolic fonts when converting to PDF/A format. |
| [get_UnicodeProcessingRules](./get_unicodeprocessingrules/)() | Gets the rules for processing ToUnicode CMap tables and not linked to Unicode symbols during the PDF/A conversion process. |
| [PdfAOptionsBase](./pdfaoptionsbase/)() |  |
| [set_AlignText](./set_aligntext/)(bool) | Sets a value indicating whether additional means are necessary to preserve text alignment during the PDF/A conversion process. |
| [set_ErrorAction](./set_erroraction/)(ConvertErrorAction) | Sets the action to be taken for objects that cannot be converted. |
| [set_ExcludeFontsStrategy](./set_excludefontsstrategy/)(PdfFormatConversionOptions::RemoveFontsStrategy) | Sets the strategy for removing fonts to minimize the output file size during the PDF/A conversion process. |
| [set_IccProfileFileName](./set_iccprofilefilename/)(System::String) | Sets the filename of the ICC (International [Color](../../aspose.pdf/color/) Consortium) profile to be used for the PDF/A conversion in place of the default one. |
| [set_IsLowMemoryMode](./set_islowmemorymode/)(bool) | Sets a value indicating whether the low memory mode is enabled during the PDF/A conversion process. |
| [set_LogOutputSource](./set_logoutputsource/)(System::SharedPtr\<IDataSource\>) | Sets the data source for the log output. |
| [set_OptimizeFileSize](./set_optimizefilesize/)(bool) | Sets a value indicating whether to try to reduce the file size during the PDF/A conversion process. |
| [set_PdfAVersion](./set_pdfaversion/)(PdfAStandardVersion) | Sets the version of the PDF/A standard to be used for validation or conversion. |
| [set_PuaSymbolsProcessingStrategy](./set_puasymbolsprocessingstrategy/)(PdfFormatConversionOptions::PuaProcessingStrategy) | Sets the strategy for processing Private Use Area (PUA) symbols in the PDF document. |
| [set_SoftMaskAction](./set_softmaskaction/)(ConvertSoftMaskAction) | Sets the action to be taken during the conversion of images with soft masks. |
| [set_SymbolicFontEncodingStrategy](./set_symbolicfontencodingstrategy/)(System::SharedPtr\<PdfASymbolicFontEncodingStrategy\>) | Sets the strategy for encoding symbolic fonts when converting to PDF/A format. |
| [set_UnicodeProcessingRules](./set_unicodeprocessingrules/)(System::SharedPtr\<ToUnicodeProcessingRules\>) | Sets the rules for processing ToUnicode CMap tables and not linked to Unicode symbols during the PDF/A conversion process. |
## See Also

* Class [IPluginOptions](../ipluginoptions/)
* Class [IDataContainer](../idatacontainer/)
* Namespace [Aspose::Pdf::LowCode](../)
* Library [Aspose.PDF for C++](../../)
