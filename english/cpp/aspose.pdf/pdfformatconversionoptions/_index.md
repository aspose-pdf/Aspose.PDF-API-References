---
title: Aspose::Pdf::PdfFormatConversionOptions class
linktitle: PdfFormatConversionOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::PdfFormatConversionOptions class. represents set of options for convert PDF document in C++.'
type: docs
weight: 15000
url: /cpp/aspose.pdf/pdfformatconversionoptions/
---
## PdfFormatConversionOptions class


represents set of options for convert PDF document

```cpp
class PdfFormatConversionOptions : public System::Object
```

## Enums

| Enum | Description |
| --- | --- |
| [PuaProcessingStrategy](./puaprocessingstrategy/) | Some PDF documents have special unicode symbols, which are belonged to Private Use Area (PUA), see description at [https://en.wikipedia.org/wiki/Private_Use_Areas](https://en.wikipedia.org/wiki/Private_Use_Areas). This symbols cause an PDF/A compliant errors like "Text is mapped to Unicode Private Use Area but no ActualText entry is present". This enumeration declares a strategies which can be used to handle PUA symbols. |
| [RemoveFontsStrategy](./removefontsstrategy/) | Some documens have large size after converison into PDF/A format. To reduce file size for these documents it's necessary to define a strategy of fonts removing. This enumeration declares a strategies which can be used to optimize fonts usage. Every strategy from this enumeration has sense only when flag [OptimizeFileSize](../) is set. |
| [SegmentAlignStrategy](./segmentalignstrategy/) | Describes strategies used to align document text segments. Now only strategy to restore segments to original bounds is supported. In future another strategies could be added. |
## Methods

| Method | Description |
| --- | --- |
| [get_AlignText](./get_aligntext/)() const | This flag controls text alignment in converted document. By default document conversion doesn't affect text alignment and leave text as is. But in some cases font substitution causes text overlapping or extra spaces in converted document. When this flag is set special alignment operations will be performed. This flag should be set only for documents which have problems with overlapped text or extra text spaces cause using of this flag decrease performance and in some cases could corrupt text content. |
| [get_AutoTaggingSettings](./get_autotaggingsettings/)() const | Gets the settings for automatic tagging during PDF format conversion. |
| [get_ConvertSoftMaskAction](./get_convertsoftmaskaction/)() const | Action for images with soft mask. |
| static [get_Default](./get_default/)() | Gets [PdfFormatConversionOptions](./) object with default parameters. |
| [get_ErrorAction](./get_erroraction/)() const | Action for objects that can not be converted. |
| [get_ExcludeFontsStrategy](./get_excludefontsstrategy/)() const | Strategy(ies) to exclude superfluous fonts and reduce document file size. This parameter has sense only when flag [OptimizeFileSize](../) is set to true. By default combination of strategies [SubsetFonts](./removefontsstrategy/) and [RemoveDuplicatedFonts](./removefontsstrategy/) is used. |
| [get_FontEmbeddingOptions](./get_fontembeddingoptions/)() const | Options for cases when it's not possible to embed some fonts into PDF document. |
| [get_Format](./get_format/)() const | PDF format. |
| [get_IccProfileFileName](./get_iccprofilefilename/)() const | Gets the filename of icc profile name. In case of null the default icc profile used. |
| [get_IsAsyncImageStreamsConversionMode](./get_isasyncimagestreamsconversionmode/)() const | Gets/sets run of image streams in async mode. |
| [get_IsLowMemoryMode](./get_islowmemorymode/)() const | Is low memory conversion mode enabled. |
| [get_IsTransferInfo](./get_istransferinfo/)() const | Gets whether to pass data from Info to [Metadata](../metadata/) when converted to PDF 2.0. True by default. |
| [get_LogFileName](./get_logfilename/)() const | Path to file where comments will be stored. |
| [get_LogStream](./get_logstream/)() const | Stream where comments will be stored. |
| [get_NonSpecificationCases](./get_nonspecificationcases/)() const | Holds flags to control PDF/A conversion process for cases when source document doesn't correspond to PDF/A specification. |
| [get_NotAccessibleFonts](./get_notaccessiblefonts/)() | This property is out-property. It holds all the fonts(font names) which were not found on computer at last PDF/A conversion. |
| [get_OptimizeFileSize](./get_optimizefilesize/)() const | Gets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size. Now this flag impacts on optimization of fonts used in PDF document, possibly, in future, this flag also will be used to switch on optimization for another data structures, such as graphic. Set of this flag and mode could significantly reduce file size but at the same time it could significantly decrease performance of conversion. |
| [get_OutputIntent](./get_outputintent/)() const | Gets the [Aspose::Pdf::OutputIntent](../outputintent/) for the PDF format conversion. |
| [get_PuaTextProcessingStrategy](./get_puatextprocessingstrategy/)() const | Strategy to process symbols from unicode Private Use Area (PUA). |
| [get_SymbolicFontEncodingStrategy](./get_symbolicfontencodingstrategy/)() const | Strategy to copy encoding data for symbolic fonts if symbolic TrueType font has more than one encoding subtable. |
| [get_TransparencyAction](./get_transparencyaction/)() const | Action for image masked objects. |
| [get_UnicodeProcessingRules](./get_unicodeprocessingrules/)() const | Rules to solve problems with unicode mapping. Can be null. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(System::String, PdfFormat, ConvertErrorAction) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(System::String, PdfFormat) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(PdfFormat) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(PdfFormat, ConvertErrorAction) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(System::String, PdfFormat, ConvertErrorAction, ConvertTransparencyAction) | Constructor. |
| [PdfFormatConversionOptions](./pdfformatconversionoptions/)(System::SharedPtr\<System::IO::Stream\>, PdfFormat, ConvertErrorAction) | Constructor. |
| [set_AlignText](./set_aligntext/)(bool) | This flag controls text alignment in converted document. By default document conversion doesn't affect text alignment and leave text as is. But in some cases font substitution causes text overlapping or extra spaces in converted document. When this flag is set special alignment operations will be performed. This flag should be set only for documents which have problems with overlapped text or extra text spaces cause using of this flag decrease performance and in some cases could corrupt text content. |
| [set_AutoTaggingSettings](./set_autotaggingsettings/)(System::SharedPtr\<Aspose::Pdf::AutoTaggingSettings\>) | Sets the settings for automatic tagging during PDF format conversion. |
| [set_ConvertSoftMaskAction](./set_convertsoftmaskaction/)(Aspose::Pdf::ConvertSoftMaskAction) | Action for images with soft mask. |
| [set_ErrorAction](./set_erroraction/)(ConvertErrorAction) | Action for objects that can not be converted. |
| [set_ExcludeFontsStrategy](./set_excludefontsstrategy/)(PdfFormatConversionOptions::RemoveFontsStrategy) | Strategy(ies) to exclude superfluous fonts and reduce document file size. This parameter has sense only when flag [OptimizeFileSize](../) is set to true. By default combination of strategies [SubsetFonts](./removefontsstrategy/) and [RemoveDuplicatedFonts](./removefontsstrategy/) is used. |
| [set_Format](./set_format/)(PdfFormat) | PDF format. |
| [set_IccProfileFileName](./set_iccprofilefilename/)(System::String) | Sets the filename of icc profile name. In case of null the default icc profile used. |
| [set_IsAsyncImageStreamsConversionMode](./set_isasyncimagestreamsconversionmode/)(bool) | Gets/sets run of image streams in async mode. |
| [set_IsLowMemoryMode](./set_islowmemorymode/)(bool) | Is low memory conversion mode enabled. |
| [set_IsTransferInfo](./set_istransferinfo/)(bool) | Sets whether to pass data from Info to [Metadata](../metadata/) when converted to PDF 2.0. True by default. |
| [set_LogFileName](./set_logfilename/)(System::String) | Path to file where comments will be stored. |
| [set_LogStream](./set_logstream/)(System::SharedPtr\<System::IO::Stream\>) | Stream where comments will be stored. |
| [set_OptimizeFileSize](./set_optimizefilesize/)(bool) | Sets a flag which enables/disables special conversion mode to get PDF/A document with reduced file size. Now this flag impacts on optimization of fonts used in PDF document, possibly, in future, this flag also will be used to switch on optimization for another data structures, such as graphic. Set of this flag and mode could significantly reduce file size but at the same time it could significantly decrease performance of conversion. |
| [set_OutputIntent](./set_outputintent/)(System::SharedPtr\<Aspose::Pdf::OutputIntent\>) | Sets the [Aspose::Pdf::OutputIntent](../outputintent/) for the PDF format conversion. |
| [set_PuaTextProcessingStrategy](./set_puatextprocessingstrategy/)(PdfFormatConversionOptions::PuaProcessingStrategy) | Strategy to process symbols from unicode Private Use Area (PUA). |
| [set_SymbolicFontEncodingStrategy](./set_symbolicfontencodingstrategy/)(System::SharedPtr\<PdfASymbolicFontEncodingStrategy\>) | Strategy to copy encoding data for symbolic fonts if symbolic TrueType font has more than one encoding subtable. |
| [set_TransparencyAction](./set_transparencyaction/)(ConvertTransparencyAction) | Action for image masked objects. |
| [set_UnicodeProcessingRules](./set_unicodeprocessingrules/)(System::SharedPtr\<ToUnicodeProcessingRules\>) | Rules to solve problems with unicode mapping. Can be null. |
## See Also

* Class [Object](../../system/object/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
