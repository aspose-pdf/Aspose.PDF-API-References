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

## Nested classes

* Class [CssSavingInfo](./csssavinginfo/)
* Class [CssUrlRequestInfo](./cssurlrequestinfo/)
* Class [HtmlImageSavingInfo](./htmlimagesavinginfo/)
* Class [HtmlPageMarkupSavingInfo](./htmlpagemarkupsavinginfo/)
## Enums

| Enum | Description |
| --- | --- |
| [AntialiasingProcessingType](./antialiasingprocessingtype/) | This enum describes possible antialiasing measures during conversion. |
| [FontEncodingRules](./fontencodingrules/) | This enumeration defines rules which tune encoding logic. |
| [FontSavingModes](./fontsavingmodes/) | Enumerates modes that can be used for saving of fonts referenced in saved PDF. |
| [HtmlImageType](./htmlimagetype/) | enumerates possible types of image files that can be saved as external resources during [Pdf](../) to Html conversion |
| [HtmlMarkupGenerationModes](./htmlmarkupgenerationmodes/) | Sometimes specific reqirments to created HTML are present. This enum defines HTML preparing modes that can be used during conversion of PDF to HTML to match such specific requirments. |
| [ImageParentTypes](./imageparenttypes/) | Enumerates possible types of image's parents [Image](../image/) can pertain to HTML page or to SVG parent image. |
| [LettersPositioningMethods](./letterspositioningmethods/) | It enumerates possible modes of positioning of letters in words in result HTML. |
| [PartsEmbeddingModes](./partsembeddingmodes/) | This enum enumerates possible modes of embedding of files referenced in HTML It allows to control whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities. |
| [RasterImagesSavingModes](./rasterimagessavingmodes/) | Converted PDF can contain raster images(.png, *.jpeg etc.) This enum defines methods of how raster images can be handled during conversion of PDF to HTML. |
## Methods

| Method | Description |
| --- | --- |
| [get_AdditionalMarginWidthInPoints](./get_additionalmarginwidthinpoints/)() const | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. But each source PDF page will be represented with it's own rectangle area in HTML (if necessary that areas can be bordered to show page paper edges with special attribute 'PageBorderIfAny'. This parameter defines width of margin that will be forcibly left around that output HTML-areas that represent pages of source PDF document.In essence it defines guaranteed interval between HTML-representations of PDF "paper" pages such mode of conversion. |
| [get_BatchSize](./get_batchsize/)() override | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [get_CompressSvgGraphicsIfAny](./get_compresssvggraphicsifany/)() const | Gets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving. |
| [get_ConvertMarkedContentToLayers](./get_convertmarkedcontenttolayers/)() const | If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content. |
| [get_DefaultFontName](./get_defaultfontname/)() const | Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. If null then default substitution font is used. |
| [get_DocumentType](./get_documenttype/)() const | Gets the [HtmlDocumentType](../htmldocumenttype/). |
| [get_ExplicitListOfSavedPages](./get_explicitlistofsavedpages/)() override | With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown. |
| [get_FixedLayout](./get_fixedlayout/)() const | Gets a value indicating whether that HTML is created as fixed layout. |
| [get_FlowLayoutParagraphFullWidth](./get_flowlayoutparagraphfullwidth/)() const | This attribute specifies full width paragraph text for Flow mode, FixedLayout = false. |
| [get_FontSources](./get_fontsources/)() const | Font sources of pre-saved fonts. |
| [get_IgnoredTextFontSize](./get_ignoredtextfontsize/)() const | [Text](../../aspose.pdf.text/) with the specified size or less will be ignored during conversion. We do not remove this text, we ignore it and do not transfer it to the output file. |
| [get_IgnoreResourceFontErrors](./get_ignoreresourcefonterrors/)() const | Gets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. [Text](../../aspose.pdf.text/) segments that refer to incorrect resources will be skipped during processing. false by default. |
| [get_ImageResolution](./get_imageresolution/)() const | Gets resolution for image rendering. |
| [get_MinimalLineWidth](./get_minimallinewidth/)() const | This attribute sets minimal width of graphic path line. If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can be used to emulate this behavior for HTML browsers. |
| [get_PreventGlyphsGrouping](./get_preventglyphsgrouping/)() const | This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. This parameter will be applied to document only when the value of FixedLayout attribute is true. |
| [get_RenderTextAsImage](./get_rendertextasimage/)() const | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly. |
| [get_SimpleTextboxModeGrouping](./get_simpletextboxmodegrouping/)() const | This attribute specifies a sequential grouping of glyphs and words into strings For example tags and words has different order in converted HTML and you want them to match. This parameter will be applied to document only when the value of FixedLayout attribute is true. |
| [get_SplitCssIntoPages](./get_splitcssintopages/)() const | When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue. |
| [get_SplitIntoPages](./get_splitintopages/)() const | Gets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages. |
| [get_Title](./get_title/)() const | Gets HTML page title. |
| [get_TryMergeFragments](./get_trymergefragments/)() const | The flag for combining image fragments into one picture. |
| [get_UseZOrder](./get_usezorder/)() const | If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. If this attribute is false all graphics is put as single layer which may cause some unnecessary effects for overlapped objects. |
| [HtmlSaveOptions](./htmlsaveoptions/)() | Initializes a new instance of the [HtmlSaveOptions](./) class. |
| [HtmlSaveOptions](./htmlsaveoptions/)(HtmlDocumentType) | Initializes a new instance of the [HtmlSaveOptions](./) class. |
| [HtmlSaveOptions](./htmlsaveoptions/)(bool) | Initializes a new instance of the [HtmlSaveOptions](./) class. |
| [HtmlSaveOptions](./htmlsaveoptions/)(HtmlDocumentType, bool) | Initializes a new instance of the [HtmlSaveOptions](./) class. |
| [set_AdditionalMarginWidthInPoints](./set_additionalmarginwidthinpoints/)(int32_t) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. But each source PDF page will be represented with it's own rectangle area in HTML (if necessary that areas can be bordered to show page paper edges with special attribute 'PageBorderIfAny'. This parameter defines width of margin that will be forcibly left around that output HTML-areas that represent pages of source PDF document.In essence it defines guaranteed interval between HTML-representations of PDF "paper" pages such mode of conversion. |
| [set_BatchSize](./set_batchsize/)(int32_t) override | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [set_CompressSvgGraphicsIfAny](./set_compresssvggraphicsifany/)(bool) | Sets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving. |
| [set_ConvertMarkedContentToLayers](./set_convertmarkedcontenttolayers/)(bool) | If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content. |
| [set_DefaultFontName](./set_defaultfontname/)(System::String) | Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. If null then default substitution font is used. |
| [set_DocumentType](./set_documenttype/)(HtmlDocumentType) | Sets the [HtmlDocumentType](../htmldocumenttype/). |
| [set_ExplicitListOfSavedPages](./set_explicitlistofsavedpages/)(System::ArrayPtr\<int32_t\>) override | With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown. |
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
## Fields

| Field | Description |
| --- | --- |
| [AntialiasingProcessing](./antialiasingprocessing/) | This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML. |
| [CssClassNamesPrefix](./cssclassnamesprefix/) | When PDFtoHTML converter generates result CSSs, CSS class names (something like ".stl_01 {}" ... ".stl_NN {}) are generated
and used in result CSS. This property allows forcibly set class name prefix
For example, if You want that all class names start with 'my_prefix_'
(i.e. were something like 'my_prefix_1' ... 'my_prefix_NNN' ) , 
then just assign 'my_prefix_' to this property before conversion.
If this property will stay untouched(i.e. null will be leaved as value ), then
converter will generate class names itself 
(it wil be something like ".stl_01 {}" ... ".stl_NN {}") |
| [CustomCssSavingStrategy](./customcsssavingstrategy/) | This field can contain saving strategy that must be used (if present) during conversion of [Pdf](../) to Html for handling of saving of CSSes related to created HTML document as whole or to it's pages(if several HTMLpages are generated) If You want handle CSS file in some specific way, that just please create relevant method and assign delegate created from it to this property. |
| [CustomHtmlSavingStrategy](./customhtmlsavingstrategy/) | Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without exteranl linked files if any) that was created during conversion. In such case processing (like saving of paage's HTML in stream or disk) can be done in that custom code . In such case all the necessary actions for saving of HTML page must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that case for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'htmlSavingInfo' parameter's variable : it will signal to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom code for procesing . |
| [CustomProgressHandler](./customprogresshandler/) | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [CustomResourceSavingStrategy](./customresourcesavingstrategy/) | This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced resource files (like images and fonts) related to nodes of saved HTML. That strategy must process resources and return string that represents desirable URL of saved resource in generated HTML. |
| [CustomStrategyOfCssUrlCreation](./customstrategyofcssurlcreation/) | This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. F.e. if You want converter put some specific URL instead of standard CSS file name into generated CSS, then You should just create and put into this property method that generates desirable URL. If flag 'SplitCssIntoPages' set, then this custom strategy (if any) must return not exact URL of CSS but rather template string that (after substitution of placeholder with page number with string.Format() function inside converter) can be resolved into URL for this or that page's CSS' URL. Examples of expected return string in such case are: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0}') |
| [ExcludeFontNameList](./excludefontnamelist/) | List of PDF embedded font names that not be embedded in HTML. |
| [FontEncodingStrategy](./fontencodingstrategy/) | Defines encoding special rule to tune PDF decoding for current document. |
| [FontSavingMode](./fontsavingmode/) | Defines font saving mode that will be used during saving of PDF to desirable format. |
| [HtmlMarkupGenerationMode](./htmlmarkupgenerationmode/) | Sometimes specific reqirments to generation of HTML markup are present. This parameter defines HTML preparing modes that can be used during conversion of PDF to HTML to match such specific requirments. |
| [IsMultiThreading](../unifiedsaveoptions/ismultithreading/) | Process pages in few threads. |
| [LettersPositioningMethod](./letterspositioningmethod/) | Sets mode of positioning of letters in words in result HTML. |
| [PageBorderIfAny](./pageborderifany/) | This attribute represents set of settings used for drawing border (if any) in result HTML document around area that represent source PDF page. In essence it concerns of showing of page's paper edges, not page border referenced in PDF page itself. |
| [PageMarginIfAny](./pagemarginifany/) | This attribute represents set of extra page margin (if any) in result HTML document around area that represent source PDF page. |
| [PagesFlowTypeDependsOnViewersScreenSize](./pagesflowtypedependsonviewersscreensize/) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be put into one big result HTML file. This flag defines whether result HTML will be generated in such way that flow of areas that represent PDF pages in result HTML will depend on screen resolution of viewer. Suppose width of screen on viewer side is big enough to put 2 or more pages one near other in horizontal direction. If this flag set to true, then this opportunity will be used (as many pages will be shown in horizontal direction one near another as it possible, then next horizontal group of pages will be shown under first one ). Otherwise pages will flow in such way: next page goes always under previous one. |
| [PartsEmbeddingMode](./partsembeddingmode/) | It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities. |
| [RasterImagesSavingMode](./rasterimagessavingmode/) | Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML. |
| [RemoveEmptyAreasOnTopAndBottom](./removeemptyareasontopandbottom/) | Defines whether in created HTML will be removed top and bottom empty area without any content (if any). |
| [SaveFullFont](./savefullfont/) | Indicates that full font will be saved, supports only True Type Fonts. By default SaveFullFont = false and the converter saves the subset of the initial font needed to display the text of the document. |
| [SaveShadowedTextsAsTransparentTexts](./saveshadowedtextsastransparenttexts/) | [Pdf](../) can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML to mimic behaviour of Acrobat Reader (othervise such texts are usually saved as hidden, not available for copying to clipboard) |
| [SaveTransparentTexts](./savetransparenttexts/) | [Pdf](../) can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML. |
| [SpecialFolderForAllImages](./specialfolderforallimages/) | Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. If parameter is empty or null then image files(if any) wil be saved together with other files linked to HTML It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file. |
| [SpecialFolderForSvgImages](./specialfolderforsvgimages/) | Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. If parameter is empty or null then SVG files(if any) wil be saved together with other image-files (near to output file) or in special folder for images (if it specified in SpecialImagesFolderIfAny option). It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file. |
| [TryMergeAdjacentSameBackgroundImages](../unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](./trysavetextunderliningandstrikeoutingincss/) | PDF itself does not contain underlining markers for texts. It emulated with line situated under text. This option allows converter try guess that this or that line is a text's underlining and put this info into CSS instead of drawing of underlining graphically. |
## Typedefs

| Typedef | Description |
| --- | --- |
| [CssSavingStrategy](./csssavingstrategy/) |  |
| [CssUrlMakingStrategy](./cssurlmakingstrategy/) |  |
| [HtmlPageMarkupSavingStrategy](./htmlpagemarkupsavingstrategy/) |  |
| [ResourceSavingStrategy](./resourcesavingstrategy/) | To this property You can assign delegate created from custom method that implements processing of external resource(Font or Image) that was extracted from PDF and must be saved as external resource during conversion of PDF to HTML. In such case processing (like saving in stream or disk) can be done in that custom code and that custom code must return path(or any another string without quotemarks) that will be afterwards incorporated into generated HTML instead of original supposed path to that image resource. In such case All the necessary actions for saving of image must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that file for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'resourceSavingInfo' parameter's variable It signals to converter that all the necessary steps for processing of that resource must be done in converter itself as if there was no any external custom code . |
## See Also

* Class [UnifiedSaveOptions](../unifiedsaveoptions/)
* Class [IPageSetOptions](../ipagesetoptions/)
* Class [IPipelineOptions](../ipipelineoptions/)
* Namespace [Aspose::Pdf](../)
* Library [Aspose.PDF for C++](../../)
