---
title: Aspose::Pdf::HtmlSaveOptions class
linktitle: HtmlSaveOptions
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::HtmlSaveOptions class. Save options for export to Html format in C++.'
type: docs
weight: 5800
url: /cpp/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class


Save options for export to Html format.

```cpp
class HtmlSaveOptions : public Aspose::Pdf::UnifiedSaveOptions,
                        public Aspose::Pdf::IPageSetOptions,
                        public Aspose::Pdf::IPipelineOptions
```

## Methods

| Method | Description |
| --- | --- |
| [get_AdditionalMarginWidthInPoints](./get_additionalmarginwidthinpoints/)() const | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. But each source PDF page will be represented with it's own rectangle area in HTML (if necessary that areas can be bordered to show page paper edges with special attribute 'PageBorderIfAny'. This parameter defines width of margin that will be forcibly left around that output HTML-areas that represent pages of source PDF document.In essence it defines guaranteed interval between HTML-representations of PDF "paper" pages such mode of conversion. |
| [get_BatchSize](./get_batchsize/)() override | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [get_CacheGlyphs](../saveoptions/get_cacheglyphs/)() const | Gets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [get_CloseResponse](../saveoptions/get_closeresponse/)() const | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [get_CompressSvgGraphicsIfAny](./get_compresssvggraphicsifany/)() const | Gets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving. |
| [get_ConvertMarkedContentToLayers](./get_convertmarkedcontenttolayers/)() const | If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content. |
| [get_DefaultFontName](./get_defaultfontname/)() const | Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. If null then default substitution font is used. |
| [get_DocumentType](./get_documenttype/)() const | Gets the [HtmlDocumentType](../htmldocumenttype/). |
| [get_ExplicitListOfSavedPages](./get_explicitlistofsavedpages/)() override | With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown. |
| [get_ExtractOcrSublayerOnly](../unifiedsaveoptions/get_extractocrsublayeronly/)() const | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [get_FixedLayout](./get_fixedlayout/)() const | Gets a value indicating whether that HTML is created as fixed layout. |
| [get_FlowLayoutParagraphFullWidth](./get_flowlayoutparagraphfullwidth/)() const | This attribute specifies full width paragraph text for Flow mode, FixedLayout = false. |
| [get_FontSources](./get_fontsources/)() const | Font sources of pre-saved fonts. |
| [get_IgnoredTextFontSize](./get_ignoredtextfontsize/)() const | [Text](../../aspose.pdf.text/) with the specified size or less will be ignored during conversion. We do not remove this text, we ignore it and do not transfer it to the output file. |
| [get_IgnoreResourceFontErrors](./get_ignoreresourcefonterrors/)() const | Gets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. [Text](../../aspose.pdf.text/) segments that refer to incorrect resources will be skipped during processing. false by default. |
| [get_ImageResolution](./get_imageresolution/)() const | Gets resolution for image rendering. |
| [get_MinimalLineWidth](./get_minimallinewidth/)() const | This attribute sets minimal width of graphic path line. If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can be used to emulate this behavior for HTML browsers. |
| [get_PreventGlyphsGrouping](./get_preventglyphsgrouping/)() const | This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. This parameter will be applied to document only when the value of FixedLayout attribute is true. |
| [get_RenderTextAsImage](./get_rendertextasimage/)() const | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly. |
| [get_SaveFormat](../saveoptions/get_saveformat/)() const | Format of data save. |
| [get_SimpleTextboxModeGrouping](./get_simpletextboxmodegrouping/)() const | This attribute specifies a sequential grouping of glyphs and words into strings For example tags and words has different order in converted HTML and you want them to match. This parameter will be applied to document only when the value of FixedLayout attribute is true. |
| [get_SplitCssIntoPages](./get_splitcssintopages/)() const | When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue. |
| [get_SplitIntoPages](./get_splitintopages/)() const | Gets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages. |
| [get_Title](./get_title/)() const | Gets HTML page title. |
| [get_TryMergeFragments](./get_trymergefragments/)() const | The flag for combining image fragments into one picture. |
| [get_UseZOrder](./get_usezorder/)() const | If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. If this attribute is false all graphics is put as single layer which may cause some unnecessary effects for overlapped objects. |
| [get_WarningHandler](../saveoptions/get_warninghandler/)() const | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [HtmlSaveOptions](./htmlsaveoptions/)() | Initializes a new instance of the [HtmlSaveOptions](./) class. |
| [HtmlSaveOptions](./htmlsaveoptions/)(HtmlDocumentType) | Initializes a new instance of the [HtmlSaveOptions](./) class. |
| [HtmlSaveOptions](./htmlsaveoptions/)(bool) | Initializes a new instance of the [HtmlSaveOptions](./) class. |
| [HtmlSaveOptions](./htmlsaveoptions/)(HtmlDocumentType, bool) | Initializes a new instance of the [HtmlSaveOptions](./) class. |
| [set_AdditionalMarginWidthInPoints](./set_additionalmarginwidthinpoints/)(int32_t) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. But each source PDF page will be represented with it's own rectangle area in HTML (if necessary that areas can be bordered to show page paper edges with special attribute 'PageBorderIfAny'. This parameter defines width of margin that will be forcibly left around that output HTML-areas that represent pages of source PDF document.In essence it defines guaranteed interval between HTML-representations of PDF "paper" pages such mode of conversion. |
| [set_BatchSize](./set_batchsize/)(int32_t) override | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [set_CacheGlyphs](../saveoptions/set_cacheglyphs/)(bool) | Sets boolean value which indicates if will font glyphs be cached while preparing aps pages. Improves performance of conversion pdf to other formats but increases memory consumption. |
| [set_CloseResponse](../saveoptions/set_closeresponse/)(bool) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [set_CompressSvgGraphicsIfAny](./set_compresssvggraphicsifany/)(bool) | Sets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving. |
| [set_ConvertMarkedContentToLayers](./set_convertmarkedcontenttolayers/)(bool) | If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content. |
| [set_DefaultFontName](./set_defaultfontname/)(System::String) | Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. If null then default substitution font is used. |
| [set_DocumentType](./set_documenttype/)(HtmlDocumentType) | Sets the [HtmlDocumentType](../htmldocumenttype/). |
| [set_ExplicitListOfSavedPages](./set_explicitlistofsavedpages/)(System::ArrayPtr\<int32_t\>) override | With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown. |
| [set_ExtractOcrSublayerOnly](../unifiedsaveoptions/set_extractocrsublayeronly/)(bool) | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [set_FixedLayout](./set_fixedlayout/)(bool) | Sets a value indicating whether that HTML is created as fixed layout. |
| [set_FlowLayoutParagraphFullWidth](./set_flowlayoutparagraphfullwidth/)(bool) | This attribute specifies full width paragraph text for Flow mode, FixedLayout = false. |
| [set_IgnoredTextFontSize](./set_ignoredtextfontsize/)(System::Nullable\<float\>) | [Text](../../aspose.pdf.text/) with the specified size or less will be ignored during conversion. We do not remove this text, we ignore it and do not transfer it to the output file. |
| [set_IgnoreResourceFontErrors](./set_ignoreresourcefonterrors/)(bool) | Sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. [Text](../../aspose.pdf.text/) segments that refer to incorrect resources will be skipped during processing. false by default. |
| [set_ImageResolution](./set_imageresolution/)(int32_t) | Sets resolution for image rendering. |
| [set_MinimalLineWidth](./set_minimallinewidth/)(float) | This attribute sets minimal width of graphic path line. If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can be used to emulate this behavior for HTML browsers. |
| [set_PreventGlyphsGrouping](./set_preventglyphsgrouping/)(bool) | This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. This parameter will be applied to document only when the value of FixedLayout attribute is true. |
| [set_RenderTextAsImage](./set_rendertextasimage/)(bool) | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly. |
| [set_SimpleTextboxModeGrouping](./set_simpletextboxmodegrouping/)(bool) | This attribute specifies a sequential grouping of glyphs and words into strings For example tags and words has different order in converted HTML and you want them to match. This parameter will be applied to document only when the value of FixedLayout attribute is true. |
| [set_SplitCssIntoPages](./set_splitcssintopages/)(bool) | When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue. |
| [set_SplitIntoPages](./set_splitintopages/)(bool) | Sets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages. |
| [set_Title](./set_title/)(System::String) | Sets HTML page title. |
| [set_TryMergeFragments](./set_trymergefragments/)(bool) | The flag for combining image fragments into one picture. |
| [set_UseZOrder](./set_usezorder/)(bool) | If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. If this attribute is false all graphics is put as single layer which may cause some unnecessary effects for overlapped objects. |
| [set_WarningHandler](../saveoptions/set_warninghandler/)(System::SharedPtr\<IWarningCallback\>) | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |
| [UnifiedSaveOptions](../unifiedsaveoptions/unifiedsaveoptions/)() |  |
## Typedefs

| Typedef | Description |
| --- | --- |
| [ResourceSavingStrategy](./resourcesavingstrategy/) | To this property You can assign delegate created from custom method that implements processing of external resource(Font or Image) that was extracted from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like saving in stream or disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated HTML instead of original supposed path to that image resource. In such case All the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'resourceSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code . |
| [HtmlPageMarkupSavingStrategy](./htmlpagemarkupsavingstrategy/) |  |
| [CssSavingStrategy](./csssavingstrategy/) |  |
| [CssUrlMakingStrategy](./cssurlmakingstrategy/) |  |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Class [IPageSetOptions](../ipagesetoptions/)
* Class [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
