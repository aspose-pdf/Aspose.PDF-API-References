---
title: Aspose::Pdf::DocSaveOptions class
linktitle: DocSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::DocSaveOptions class. Save options for export to Doc format in C++.'
type: docs
weight: 4000
url: /cpp/aspose.pdf/docsaveoptions/
---
## DocSaveOptions class


Save options for export to Doc format.

```cpp
class DocSaveOptions : public Aspose::Pdf::UnifiedSaveOptions,
                       public Aspose::Pdf::IPipelineOptions
```

## Enums

| Enum | Description |
| --- | --- |
| [DocFormat](./docformat/) | Allows to specify .doc or .docx file format. |
| [RecognitionMode](./recognitionmode/) | Allows to control how a PDF document is converted into a word processing document. |
## Methods

| Method | Description |
| --- | --- |
| [DocSaveOptions](./docsaveoptions/)() | Constructor. |
| [get_AddReturnToLineEnd](./get_addreturntolineend/)() const | Use paragraph or line breaks. |
| [get_BatchSize](./get_batchsize/)() override | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [get_ConvertType3Fonts](./get_converttype3fonts/)() const | Gets conversion for Type3 fonts. In Type 3 fonts, glyphs shall be defined by streams of graphics operators. This means that in the DOC/DOCX output we see images instead of text. Set this flag to true to convert Type3 fonts to TTF and get text in the resulting file. |
| [get_Format](./get_format/)() const | Output format. |
| [get_ImageResolutionX](./get_imageresolutionx/)() const | Converted images X resolution. |
| [get_ImageResolutionY](./get_imageresolutiony/)() const | Converted images Y resolution. |
| [get_MaxDistanceBetweenTextLines](./get_maxdistancebetweentextlines/)() const | This parameter is used for grouping text lines into paragraphs. Determines how far apart can be two relative text lines. Specified in hundreds of percent of the text lines height. |
| [get_MemorySaveModePath](./get_memorysavemodepath/)() const | Defines the path (file name or directory name) to hold temporary data when converting in memory save mode. |
| [get_Mode](./get_mode/)() const | Recognition mode. |
| [get_RecognizeBullets](./get_recognizebullets/)() const | Switch on the recognition of bullets. |
| [get_RelativeHorizontalProximity](./get_relativehorizontalproximity/)() const | In [Pdf](../) words may be innerly represented with operators that prints words by independently printing their letters or syllables. So, to detect words sometimes we need detect groups of independent chars that are in fact words. This setting defines width of space between text elements(letters, syllables) that must be treated as distance between words during recognition of words in source PDF. (presence of empty space at least with this width between letters means that textual elements pertain to different words). It's normed to font size - 1.0 means 100% of supposed word's font size. ATTENTION!It's used only in cases when source PDF contains specific rarely used fonts for which optimal value cannot be calculated from font. So, in vast majority of cases this parameter changes nothing in result document. |
| [get_ReSaveFonts](./get_resavefonts/)() const | Gets the procedure for resaving fonts. If set to true, we reload fonts on every page to avoid the influence of previous font properties and load the newly created font from scratch. Set this option to false if you want to improve performance. The default value is true;. |
| [set_AddReturnToLineEnd](./set_addreturntolineend/)(bool) | Use paragraph or line breaks. |
| [set_BatchSize](./set_batchsize/)(int32_t) override | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [set_ConvertType3Fonts](./set_converttype3fonts/)(bool) | Sets conversion for Type3 fonts. In Type 3 fonts, glyphs shall be defined by streams of graphics operators. This means that in the DOC/DOCX output we see images instead of text. Set this flag to true to convert Type3 fonts to TTF and get text in the resulting file. |
| [set_Format](./set_format/)(DocSaveOptions::DocFormat) | Output format. |
| [set_ImageResolutionX](./set_imageresolutionx/)(int32_t) | Converted images X resolution. |
| [set_ImageResolutionY](./set_imageresolutiony/)(int32_t) | Converted images Y resolution. |
| [set_MaxDistanceBetweenTextLines](./set_maxdistancebetweentextlines/)(float) | This parameter is used for grouping text lines into paragraphs. Determines how far apart can be two relative text lines. Specified in hundreds of percent of the text lines height. |
| [set_MemorySaveModePath](./set_memorysavemodepath/)(System::String) | Defines the path (file name or directory name) to hold temporary data when converting in memory save mode. |
| [set_Mode](./set_mode/)(DocSaveOptions::RecognitionMode) | Recognition mode. |
| [set_RecognizeBullets](./set_recognizebullets/)(bool) | Switch on the recognition of bullets. |
| [set_RelativeHorizontalProximity](./set_relativehorizontalproximity/)(float) | In [Pdf](../) words may be innerly represented with operators that prints words by independently printing their letters or syllables. So, to detect words sometimes we need detect groups of independent chars that are in fact words. This setting defines width of space between text elements(letters, syllables) that must be treated as distance between words during recognition of words in source PDF. (presence of empty space at least with this width between letters means that textual elements pertain to different words). It's normed to font size - 1.0 means 100% of supposed word's font size. ATTENTION!It's used only in cases when source PDF contains specific rarely used fonts for which optimal value cannot be calculated from font. So, in vast majority of cases this parameter changes nothing in result document. |
| [set_ReSaveFonts](./set_resavefonts/)(bool) | Sets the procedure for resaving fonts. If set to true, we reload fonts on every page to avoid the influence of previous font properties and load the newly created font from scratch. Set this option to false if you want to improve performance. The default value is true;. |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Class [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
