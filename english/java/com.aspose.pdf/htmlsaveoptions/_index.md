---
title: HtmlSaveOptions
linktitle: HtmlSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Html format
type: docs
weight: 1990
url: /java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.HtmlSaveOptions

**All Implemented Interfaces:**
IPageSetOptions, IPipelineOptions

```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions , IPipelineOptions
```

Save options for export to Html format

## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlSaveOptions](#HtmlSaveOptions--) | Initializes a new instance of the HtmlSaveOptions class. |
| [HtmlSaveOptions](#HtmlSaveOptions-boolean-) | Initializes a new instance of the {@code HtmlSaveOptions} class. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-) | Initializes a new instance of the HtmlSaveOptions class. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-) | Initializes a new instance of the HtmlSaveOptions class. |

## Methods

| Method | Description |
| --- | --- |
| [getAdditionalMarginWidthInPoints](#getAdditionalMarginWidthInPoints--) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. But each source PDF page will be represented with it's own rectangle area in HTML (if necessary that areas can be bordered to show page paper edges with special attribute 'PageBorderIfAny'. This parameter defines width of margin that will be forcibly left around that output HTML-areas that represent pages of source PDF document.In essence it defines guaranteed interval between HTML-representations of PDF "paper" pages such mode of conversion. |
| [getAntialiasingProcessing](#getAntialiasingProcessing--) | This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML |
| [getBatchSize](#getBatchSize--) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [getCssClassNamesPrefix](#getCssClassNamesPrefix--) | When PDFtoHTML converter generates result CSSs, CSS class names (something like ".stl_01 {}" ... ".stl_NN {}) are generated and used in result CSS. This property allows forcibly set class name prefix For example, if You want that all class names start with 'my_prefix_' (i.e. were something like 'my_prefix_1' ... 'my_prefix_NNN' ) , then just assign 'my_prefix_' to this property before conversion. If this property will stay untouched(i.e. null will be leaved as value ), then converter will generate class names itself (it will be something like ".stl_01 {}" ... ".stl_NN {}") |
| [getCustomCssSavingStrategy](#getCustomCssSavingStrategy--) | This field can contain saving strategy that must be used (if present) during conversion of Pdf to Html for handling of saving of CSSes related to created HTML document as whole or to it's pages(if several HTMLpages are generated) If You want handle CSS file in some specific way, that just please create relevant method and Assign delegate created from it to this property. |
| [getCustomHtmlSavingStrategy](#getCustomHtmlSavingStrategy--) | Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without external linked files if any) that was created during conversion. In such case processing (like saving of paage's HTML in stream or disk) can be done in that custom code . In such case all the necessary actions for saving of HTML page must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that case for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'htmlSavingInfo' parameter's variable : it will signal to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom code for procesing . |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre> |
| [getCustomResourceSavingStrategy](#getCustomResourceSavingStrategy--) | This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced resource files (like images and fonts) related to nodes of saved HTML. That strategy must process resources and return string that represents desirable URL of saved resource in generated HTML. |
| [getCustomStrategyOfCssUrlCreation](#getCustomStrategyOfCssUrlCreation--) | This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. F.e. if You want converter put some specific URL instead of standard CSS file name into generated CSS, then You should just create and put into this property method that generates desirable URL. If flag 'SplitCssIntoPages' set, then this custom strategy (if any) must return not exact URL of CSS but rather template string that (after substitution of placeholder with page number with String.Format() function inside converter) can be resolved into URL for this or that page's CSS' URL. Examples of expected return string in such case are: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 } ' ) |
| [getDefaultFontName](#getDefaultFontName--) | Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. If null then default substitution font is used. |
| [getDocumentType](#getDocumentType--) | Gets the {@code HtmlDocumentTypeInternal}. |
| [getExcludeFontNameList](#getExcludeFontNameList--) | List of PDF embedded font names that not be embedded in HTML. |
| [getExplicitListOfSavedPages](#getExplicitListOfSavedPages--) | With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown. |
| [getFlowLayoutParagraphFullWidth](#getFlowLayoutParagraphFullWidth--) | This attribute specifies full width paragraph text for Flow mode, FixedLayout = false |
| [getFontEncodingStrategy](#getFontEncodingStrategy--) | Defines encoding special rule to tune PDF decoding for current document |
| [getFontSavingMode](#getFontSavingMode--) | Defines font saving mode that will be used during saving of PDF to desirable format |
| [getFontSources](#getFontSources--) | <p> Font sources of pre-saved fonts. </p> |
| [getHtmlMarkupGenerationMode](#getHtmlMarkupGenerationMode--) | Sometimes specific reqirments to generation of HTML markup are present. This parameter defines HTML preparing modes that can be used during conversion of PDF to HTML to match such specific requirments. |
| [getImageResolution](#getImageResolution--) | Gets or sets resolution for image rendering. |
| [getLettersPositioningMethod](#getLettersPositioningMethod--) | Sets mode of positioning of letters in words in result HTML |
| [getMinimalLineWidth](#getMinimalLineWidth--) | This attribute sets minimal width of graphic path line. If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can be used to emulate this behavior for HTML browsers. |
| [getPageBorderIfAny](#getPageBorderIfAny--) | This attribute represents set of settings used for drawing border (if any) in result HTML document around area that represent source PDF page. In essence it concerns of showing of page's paper edges, not page border referenced in PDF page itself. |
| [getPageMarginIfAny](#getPageMarginIfAny--) | This attribute represents set of extra page margin (if any) in result HTML document around area that represent source PDF page. |
| [getPartsEmbeddingMode](#getPartsEmbeddingMode--) | It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities |
| [getRasterImagesSavingMode](#getRasterImagesSavingMode--) | Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML |
| [getSpecialFolderForAllImages](#getSpecialFolderForAllImages--) | Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. If parameter is empty or null then image files(if any) wil be saved together with other files linked to HTML It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file. |
| [getSpecialFolderForSvgImages](#getSpecialFolderForSvgImages--) | Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. If parameter is empty or null then SVG files(if any) wil be saved together with other image-files (near to output file) or in special folder for images (if it specified in SpecialImagesFolderIfAny option). It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file. |
| [getTitle](#getTitle--) | Gets or sets HTML page title. |
| [isCompressSvgGraphicsIfAny](#isCompressSvgGraphicsIfAny--) | Gets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving Value: The {@code HtmlDocumentType}. |
| [isConvertMarkedContentToLayers](#isConvertMarkedContentToLayers--) | If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content. |
| [isFixedLayout](#isFixedLayout--) | Gets a value indicating whether that HTML is created as fixed layout. |
| [isIgnoreResourceFontErrors](#isIgnoreResourceFontErrors--) | Gets or sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false by default |
| [isPagesFlowTypeDependsOnViewersScreenSize](#isPagesFlowTypeDependsOnViewersScreenSize--) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be put into one big result HTML file. This flag defines whether result HTML will be generated in such way that flow of areas that represent PDF pages in result HTML will depend on screen resolution of viewer. Suppose width of screen on viewer side is big enough to put 2 or more pages one near other in horizontal direction. If this flag set to true, then this opportunity will be used (as many pages will be shown in horizontal direction one near another as it possible, then next horizontal group of pages will be shown under first one ). Otherwise pages will flow in such way: next page goes always under previous one. |
| [isPreventGlyphsGrouping](#isPreventGlyphsGrouping--) | This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. This parameter will be applied to document only when the value of FixedLayout attribute is true. |
| [isRemoveEmptyAreasOnTopAndBottom](#isRemoveEmptyAreasOnTopAndBottom--) | Defines whether in created HTML will be removed top and bottom empty area without any content (if any). |
| [isRenderTextAsImage](#isRenderTextAsImage--) | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly. |
| [isSaveFullFont](#isSaveFullFont--) | Indicates that full font will be saved, supports only True Type Fonts. By default SaveFullFont = false and the converter saves the subset of the initial font needed to display the text of the document. |
| [isSaveShadowedTextsAsTransparentTexts](#isSaveShadowedTextsAsTransparentTexts--) | Pdf can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML to mimic behaviour of Acrobat Reader (othervise such texts are usually saved as hidden, not available for copying to clipboard) |
| [isSaveTransparentTexts](#isSaveTransparentTexts--) | Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML |
| [isSimpleTextboxModeGrouping](#isSimpleTextboxModeGrouping--) | This attribute specifies a sequential grouping of glyphs and words into strings For example tags and words has different order in converted HTML and you want them to match. This parameter will be applied to document only when the value of FixedLayout attribute is true. |
| [isSplitCssIntoPages](#isSplitCssIntoPages--) | When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue. |
| [isSplitIntoPages](#isSplitIntoPages--) | Gets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages. |
| [isTrySaveTextUnderliningAndStrikeoutingInCss](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | PDF itself does not contain underlining markers for texts. It emulated with line situated under text. This option allows converter try guess that this or that line is a text's underlining and put this info into CSS instead of drawing of underlining graphically |
| [isUseZOrder](#isUseZOrder--) | If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. If this attribute is false all graphics is put as single layer which may cause some unnecessary effects for overlapped objects. |
| [setAdditionalMarginWidthInPoints](#setAdditionalMarginWidthInPoints-int-) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. But each source PDF page will be represented with it's own rectangle area in HTML (if necessary that areas can be bordered to show page paper edges with special attribute 'PageBorderIfAny'. This parameter defines width of margin that will be forcibly left around that output HTML-areas that represent pages of source PDF document.In essence it defines guaranteed interval between HTML-representations of PDF "paper" pages such mode of conversion. |
| [setAntialiasingProcessing](#setAntialiasingProcessing-int-) | This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML |
| [setBatchSize](#setBatchSize-int-) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [setCompressSvgGraphicsIfAny](#setCompressSvgGraphicsIfAny-boolean-) | Sets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving Value: The {@code HtmlDocumentType}. |
| [setConvertMarkedContentToLayers](#setConvertMarkedContentToLayers-boolean-) | If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content. |
| [setCssClassNamesPrefix](#setCssClassNamesPrefix-java.lang.String-) | When PDFtoHTML converter generates result CSSs, CSS class names (something like ".stl_01 {}" ... ".stl_NN {}) are generated and used in result CSS. This property allows forcibly set class name prefix For example, if You want that all class names start with 'my_prefix_' (i.e. were something like 'my_prefix_1' ... 'my_prefix_NNN' ) , then just assign 'my_prefix_' to this property before conversion. If this property will stay untouched(i.e. null will be leaved as value ), then converter will generate class names itself (it will be something like ".stl_01 {}" ... ".stl_NN {}") |
| [setCustomCssSavingStrategy](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | This field can contain saving strategy that must be used (if present) during conversion of Pdf to Html for handling of saving of CSSes related to created HTML document as whole or to it's pages(if several HTMLpages are generated) If You want handle CSS file in some specific way, that just please create relevant method and Assign delegate created from it to this property. |
| [setCustomHtmlSavingStrategy](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without external linked files if any) that was created during conversion. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | This handler can be used to handle conversion progress events f.e. |
| [setCustomResourceSavingStrategy](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced resource files (like images and fonts) related to nodes of saved HTML. |
| [setCustomStrategyOfCssUrlCreation](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. If null then default substitution font is used. |
| [setDocumentType](#setDocumentType-com.aspose.pdf.HtmlDocumentType-) | Sets the {@code HtmlDocumentType}. |
| [setExcludeFontNameList](#setExcludeFontNameList-java.lang.String:A-) | List of PDF embedded font names that not be embedded in HTML. |
| [setExplicitListOfSavedPages](#setExplicitListOfSavedPages-int:A-) | With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown. |
| [setFixedLayout](#setFixedLayout-boolean-) | Sets a value indicating whether that HTML is created as fixed layout. |
| [setFlowLayoutParagraphFullWidth](#setFlowLayoutParagraphFullWidth-boolean-) | This attribute specifies full width paragraph text for Flow mode, FixedLayout = false |
| [setFontEncodingStrategy](#setFontEncodingStrategy-byte-) | Defines encoding special rule to tune PDF decoding for current document |
| [setFontSavingMode](#setFontSavingMode-int-) | Defines font saving mode that will be used during saving of PDF to desirable format |
| [setHtmlMarkupGenerationMode](#setHtmlMarkupGenerationMode-int-) | Sometimes specific reqirments to generation of HTML markup are present. This parameter defines HTML preparing modes that can be used during conversion of PDF to HTML to match such specific requirments. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Gets or sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false by default |
| [setImageResolution](#setImageResolution-int-) | Gets or sets resolution for image rendering. |
| [setLettersPositioningMethod](#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-) | Sets mode of positioning of letters in words in result HTML |
| [setMinimalLineWidth](#setMinimalLineWidth-float-) | This attribute sets minimal width of graphic path line. If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can be used to emulate this behavior for HTML browsers. |
| [setPageBorderIfAny](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | This attribute represents set of settings used for drawing border (if any) in result HTML document around area that represent source PDF page. |
| [setPageMarginIfAny](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | This attribute represents set of extra page margin (if any) in result HTML document around area that represent source PDF page. |
| [setPagesFlowTypeDependsOnViewersScreenSize](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be put into one big result HTML file. This flag defines whether result HTML will be generated in such way that flow of areas that represent PDF pages in result HTML will depend on screen resolution of viewer. Suppose width of screen on viewer side is big enough to put 2 or more pages one near other in horizontal direction. If this flag set to true, then this opportunity will be used (as many pages will be shown in horizontal direction one near another as it possible, then next horizontal group of pages will be shown under first one ). Otherwise pages will flow in such way: next page goes always under previous one. |
| [setPartsEmbeddingMode](#setPartsEmbeddingMode-int-) | It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities |
| [setPreventGlyphsGrouping](#setPreventGlyphsGrouping-boolean-) | This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. This parameter will be applied to document only when the value of FixedLayout attribute is true. |
| [setRasterImagesSavingMode](#setRasterImagesSavingMode-int-) | Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML |
| [setRemoveEmptyAreasOnTopAndBottom](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | Defines whether in created HTML will be removed top and bottom empty area without any content (if any). |
| [setRenderTextAsImage](#setRenderTextAsImage-boolean-) | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly. |
| [setSaveFullFont](#setSaveFullFont-boolean-) | Indicates that full font will be saved, supports only True Type Fonts. By default SaveFullFont = false and the converter saves the subset of the initial font needed to display the text of the document. |
| [setSaveShadowedTextsAsTransparentTexts](#setSaveShadowedTextsAsTransparentTexts-boolean-) | Pdf can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML to mimic behaviour of Acrobat Reader (othervise such texts are usually saved as hidden, not available for copying to clipboard) |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML |
| [setSimpleTextboxModeGrouping](#setSimpleTextboxModeGrouping-boolean-) | This attribute specifies a sequential grouping of glyphs and words into strings For example tags and words has different order in converted HTML and you want them to match. This parameter will be applied to document only when the value of FixedLayout attribute is true. |
| [setSpecialFolderForAllImages](#setSpecialFolderForAllImages-java.lang.String-) | Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. If parameter is empty or null then image files(if any) wil be saved together with other files linked to HTML It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file. |
| [setSpecialFolderForSvgImages](#setSpecialFolderForSvgImages-java.lang.String-) | Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. If parameter is empty or null then SVG files(if any) wil be saved together with other image-files (near to output file) or in special folder for images (if it specified in SpecialImagesFolderIfAny option). It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file. |
| [setSplitCssIntoPages](#setSplitCssIntoPages-boolean-) | When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue. |
| [setSplitIntoPages](#setSplitIntoPages-boolean-) | Sets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages. |
| [setTitle](#setTitle-java.lang.String-) | Gets or sets HTML page title. |
| [setTrySaveTextUnderliningAndStrikeoutingInCss](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | PDF itself does not contain underlining markers for texts. It emulated with line situated under text. This option allows converter try guess that this or that line is a text's underlining and put this info into CSS instead of drawing of underlining graphically |
| [setUseZOrder](#setUseZOrder-boolean-) | If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. If this attribute is false all graphics is put as single layer which may cause some unnecessary effects for overlapped objects. |

### HtmlSaveOptions {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```

Initializes a new instance of the HtmlSaveOptions class.

### HtmlSaveOptions {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```

Initializes a new instance of the {@code HtmlSaveOptions} class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fixedLayout |  | boolean value |

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-}
Initializes a new instance of the HtmlSaveOptions class.

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-}
Initializes a new instance of the HtmlSaveOptions class.

### getAdditionalMarginWidthInPoints {#getAdditionalMarginWidthInPoints--}
```
@Deprecated public int getAdditionalMarginWidthInPoints()
```

If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. But each source PDF page will be represented with it's own rectangle area in HTML (if necessary that areas can be bordered to show page paper edges with special attribute 'PageBorderIfAny'. This parameter defines width of margin that will be forcibly left around that output HTML-areas that represent pages of source PDF document.In essence it defines guaranteed interval between HTML-representations of PDF "paper" pages such mode of conversion.

**Returns:**
int value @deprecated AdditionalMarginWidthInPoints is deprecated, please use PageMarginIfAny instead.

### getAntialiasingProcessing {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```

This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML

**Returns:**
AntialiasingProcessingType element @see AntialiasingProcessingType

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Defines batch size if batched conversion is applicable to source and destination formats pair.

**Returns:**
int value

### getCssClassNamesPrefix {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```

When PDFtoHTML converter generates result CSSs, CSS class names (something like ".stl_01 {}" ... ".stl_NN {}) are generated and used in result CSS. This property allows forcibly set class name prefix For example, if You want that all class names start with 'my_prefix_' (i.e. were something like 'my_prefix_1' ... 'my_prefix_NNN' ) , then just assign 'my_prefix_' to this property before conversion. If this property will stay untouched(i.e. null will be leaved as value ), then converter will generate class names itself (it will be something like ".stl_01 {}" ... ".stl_NN {}")

**Returns:**
String value

### getCustomCssSavingStrategy {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```

This field can contain saving strategy that must be used (if present) during conversion of Pdf to Html for handling of saving of CSSes related to created HTML document as whole or to it's pages(if several HTMLpages are generated) If You want handle CSS file in some specific way, that just please create relevant method and Assign delegate created from it to this property.

**Returns:**
CssSavingStrategy instance

### getCustomHtmlSavingStrategy {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```

Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without external linked files if any) that was created during conversion. In such case processing (like saving of paage's HTML in stream or disk) can be done in that custom code . In such case all the necessary actions for saving of HTML page must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that case for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'htmlSavingInfo' parameter's variable : it will signal to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom code for procesing .

**Returns:**
HtmlPageMarkupSavingStrategy instance

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre>

**Returns:**
ConversionProgressEventHandler instance

### getCustomResourceSavingStrategy {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```

This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced resource files (like images and fonts) related to nodes of saved HTML. That strategy must process resources and return string that represents desirable URL of saved resource in generated HTML.

**Returns:**
ResourceSavingStrategy instance

### getCustomStrategyOfCssUrlCreation {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```

This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. F.e. if You want converter put some specific URL instead of standard CSS file name into generated CSS, then You should just create and put into this property method that generates desirable URL. If flag 'SplitCssIntoPages' set, then this custom strategy (if any) must return not exact URL of CSS but rather template string that (after substitution of placeholder with page number with String.Format() function inside converter) can be resolved into URL for this or that page's CSS' URL. Examples of expected return string in such case are: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 } ' )

**Returns:**
CssUrlMakingStrategy instance

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. If null then default substitution font is used.

**Returns:**
String value: Font name

### getDocumentType {#getDocumentType--}
```
public HtmlDocumentType getDocumentType()
```

Gets the {@code HtmlDocumentTypeInternal}.

**Returns:**
The {@code HtmlDocumentTypeInternal}.

### getExcludeFontNameList {#getExcludeFontNameList--}
```
public String [] getExcludeFontNameList()
```

List of PDF embedded font names that not be embedded in HTML.

**Returns:**
array of String elements

### getExplicitListOfSavedPages {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```

With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown.

**Returns:**
int array

### getFlowLayoutParagraphFullWidth {#getFlowLayoutParagraphFullWidth--}
```
public final boolean getFlowLayoutParagraphFullWidth()
```

This attribute specifies full width paragraph text for Flow mode, FixedLayout = false

**Returns:**
boolean value

### getFontEncodingStrategy {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```

Defines encoding special rule to tune PDF decoding for current document

**Returns:**
FontEncodingRules element @see FontEncodingRules

### getFontSavingMode {#getFontSavingMode--}
```
public int getFontSavingMode()
```

Defines font saving mode that will be used during saving of PDF to desirable format

**Returns:**
FontSavingModes element @see FontSavingModes

### getFontSources {#getFontSources--}
```
public FontSourceCollection getFontSources()
```

<p> Font sources of pre-saved fonts. </p>

**Returns:**
FontSourceCollection object <hr> <p> Fonts may be saved preliminarily for cache purpose and then passed into Html conversion process. For example it may be useful in document splitting scenario and processing document pages in multiple threads with single set of fonts. </p>

### getHtmlMarkupGenerationMode {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```

Sometimes specific reqirments to generation of HTML markup are present. This parameter defines HTML preparing modes that can be used during conversion of PDF to HTML to match such specific requirments.

**Returns:**
HtmlMarkupGenerationModes element @see HtmlMarkupGenerationModes

### getImageResolution {#getImageResolution--}
```
public int getImageResolution()
```

Gets or sets resolution for image rendering.

**Returns:**
Value: Resolution

### getLettersPositioningMethod {#getLettersPositioningMethod--}
```
public LettersPositioningMethods getLettersPositioningMethod()
```

Sets mode of positioning of letters in words in result HTML

**Returns:**
LettersPositioningMethods element @see LettersPositioningMethods

### getMinimalLineWidth {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```

This attribute sets minimal width of graphic path line. If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can be used to emulate this behavior for HTML browsers.

**Returns:**
float value

### getPageBorderIfAny {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```

This attribute represents set of settings used for drawing border (if any) in result HTML document around area that represent source PDF page. In essence it concerns of showing of page's paper edges, not page border referenced in PDF page itself.

**Returns:**
BorderInfo instance

### getPageMarginIfAny {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```

This attribute represents set of extra page margin (if any) in result HTML document around area that represent source PDF page.

**Returns:**
MarginInfo instance

### getPartsEmbeddingMode {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```

It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities

**Returns:**
PartsEmbeddingModes element @see PartsEmbeddingModes

### getRasterImagesSavingMode {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```

Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML

**Returns:**
RasterImagesSavingModes element @see RasterImagesSavingModes

### getSpecialFolderForAllImages {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```

Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. If parameter is empty or null then image files(if any) wil be saved together with other files linked to HTML It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file.

**Returns:**
String value

### getSpecialFolderForSvgImages {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```

Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. If parameter is empty or null then SVG files(if any) wil be saved together with other image-files (near to output file) or in special folder for images (if it specified in SpecialImagesFolderIfAny option). It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file.

**Returns:**
String value

### getTitle {#getTitle--}
```
public final String getTitle()
```

Gets or sets HTML page title.

**Returns:**
String value

### isCompressSvgGraphicsIfAny {#isCompressSvgGraphicsIfAny--}
```
public boolean isCompressSvgGraphicsIfAny()
```

Gets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving Value: The {@code HtmlDocumentType}.

**Returns:**
boolean value

### isConvertMarkedContentToLayers {#isConvertMarkedContentToLayers--}
```
public boolean isConvertMarkedContentToLayers()
```

If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content.

**Returns:**
boolean value

### isFixedLayout {#isFixedLayout--}
```
public boolean isFixedLayout()
```

Gets a value indicating whether that HTML is created as fixed layout.

**Returns:**
value: {@code true} if [fixed layout]; otherwise, {@code false}.

### isIgnoreResourceFontErrors {#isIgnoreResourceFontErrors--}
```
public final boolean isIgnoreResourceFontErrors()
```

Gets or sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false by default

**Returns:**
boolean value

### isPagesFlowTypeDependsOnViewersScreenSize {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```

If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be put into one big result HTML file. This flag defines whether result HTML will be generated in such way that flow of areas that represent PDF pages in result HTML will depend on screen resolution of viewer. Suppose width of screen on viewer side is big enough to put 2 or more pages one near other in horizontal direction. If this flag set to true, then this opportunity will be used (as many pages will be shown in horizontal direction one near another as it possible, then next horizontal group of pages will be shown under first one ). Otherwise pages will flow in such way: next page goes always under previous one.

**Returns:**
boolean value

### isPreventGlyphsGrouping {#isPreventGlyphsGrouping--}
```
public boolean isPreventGlyphsGrouping()
```

This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. This parameter will be applied to document only when the value of FixedLayout attribute is true.

**Returns:**
boolean value

### isRemoveEmptyAreasOnTopAndBottom {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```

Defines whether in created HTML will be removed top and bottom empty area without any content (if any).

**Returns:**
boolean value

### isRenderTextAsImage {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```

If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly.

**Returns:**
boolean value

### isSaveFullFont {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```

Indicates that full font will be saved, supports only True Type Fonts. By default SaveFullFont = false and the converter saves the subset of the initial font needed to display the text of the document.

**Returns:**
boolean value

### isSaveShadowedTextsAsTransparentTexts {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```

Pdf can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML to mimic behaviour of Acrobat Reader (othervise such texts are usually saved as hidden, not available for copying to clipboard)

**Returns:**
boolean value

### isSaveTransparentTexts {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```

Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML

**Returns:**
boolean value

### isSimpleTextboxModeGrouping {#isSimpleTextboxModeGrouping--}
```
public final boolean isSimpleTextboxModeGrouping()
```

This attribute specifies a sequential grouping of glyphs and words into strings For example tags and words has different order in converted HTML and you want them to match. This parameter will be applied to document only when the value of FixedLayout attribute is true.

**Returns:**
boolean value

### isSplitCssIntoPages {#isSplitCssIntoPages--}
```
public boolean isSplitCssIntoPages()
```

When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue.

**Returns:**
boolean value

### isSplitIntoPages {#isSplitIntoPages--}
```
public boolean isSplitIntoPages()
```

Gets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages.

**Returns:**
boolean value

### isTrySaveTextUnderliningAndStrikeoutingInCss {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```

PDF itself does not contain underlining markers for texts. It emulated with line situated under text. This option allows converter try guess that this or that line is a text's underlining and put this info into CSS instead of drawing of underlining graphically

**Returns:**
boolean value

### isUseZOrder {#isUseZOrder--}
```
public boolean isUseZOrder()
```

If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. If this attribute is false all graphics is put as single layer which may cause some unnecessary effects for overlapped objects.

**Returns:**
boolean value

### setAdditionalMarginWidthInPoints {#setAdditionalMarginWidthInPoints-int-}
```
@Deprecated public void setAdditionalMarginWidthInPoints(int value)
```

If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. But each source PDF page will be represented with it's own rectangle area in HTML (if necessary that areas can be bordered to show page paper edges with special attribute 'PageBorderIfAny'. This parameter defines width of margin that will be forcibly left around that output HTML-areas that represent pages of source PDF document.In essence it defines guaranteed interval between HTML-representations of PDF "paper" pages such mode of conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | int value @deprecated AdditionalMarginWidthInPoints is deprecated, please use PageMarginIfAny instead. |

### setAntialiasingProcessing {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```

This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| antialiasingProcessing |  | AntialiasingProcessingType element @see AntialiasingProcessingType |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Defines batch size if batched conversion is applicable to source and destination formats pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### setCompressSvgGraphicsIfAny {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```

Sets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving Value: The {@code HtmlDocumentType}.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setConvertMarkedContentToLayers {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```

If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setCssClassNamesPrefix {#setCssClassNamesPrefix-java.lang.String-}
When PDFtoHTML converter generates result CSSs, CSS class names (something like ".stl_01 {}" ... ".stl_NN {}) are generated and used in result CSS. This property allows forcibly set class name prefix For example, if You want that all class names start with 'my_prefix_' (i.e. were something like 'my_prefix_1' ... 'my_prefix_NNN' ) , then just assign 'my_prefix_' to this property before conversion. If this property will stay untouched(i.e. null will be leaved as value ), then converter will generate class names itself (it will be something like ".stl_01 {}" ... ".stl_NN {}")

### setCustomCssSavingStrategy {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
This field can contain saving strategy that must be used (if present) during conversion of Pdf to Html for handling of saving of CSSes related to created HTML document as whole or to it's pages(if several HTMLpages are generated) If You want handle CSS file in some specific way, that just please create relevant method and Assign delegate created from it to this property.

### setCustomHtmlSavingStrategy {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without external linked files if any) that was created during conversion.

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
This handler can be used to handle conversion progress events f.e.

### setCustomResourceSavingStrategy {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced resource files (like images and fonts) related to nodes of saved HTML.

### setCustomStrategyOfCssUrlCreation {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML.

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. If null then default substitution font is used.

### setDocumentType {#setDocumentType-com.aspose.pdf.HtmlDocumentType-}
Sets the {@code HtmlDocumentType}.

### setExcludeFontNameList {#setExcludeFontNameList-java.lang.String:A-}
List of PDF embedded font names that not be embedded in HTML.

### setExplicitListOfSavedPages {#setExplicitListOfSavedPages-int:A-}
```
public final void setExplicitListOfSavedPages(int[] value)
```

With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  |  |

### setFixedLayout {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```

Sets a value indicating whether that HTML is created as fixed layout.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | : {@code true} if [fixed layout]; otherwise, {@code false}. |

### setFlowLayoutParagraphFullWidth {#setFlowLayoutParagraphFullWidth-boolean-}
```
public final void setFlowLayoutParagraphFullWidth(boolean value)
```

This attribute specifies full width paragraph text for Flow mode, FixedLayout = false

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setFontEncodingStrategy {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```

Defines encoding special rule to tune PDF decoding for current document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontEncodingStrategy |  | FontEncodingRules element @see FontEncodingRules |

### setFontSavingMode {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```

Defines font saving mode that will be used during saving of PDF to desirable format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSavingMode |  | FontSavingModes element @see FontSavingModes |

### setHtmlMarkupGenerationMode {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```

Sometimes specific reqirments to generation of HTML markup are present. This parameter defines HTML preparing modes that can be used during conversion of PDF to HTML to match such specific requirments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlMarkupGenerationMode |  | HtmlMarkupGenerationModes element @see HtmlMarkupGenerationModes |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Gets or sets indication that errors related to absence of font will be ignored. true - means that errors of absence of font will be ignored. Text segments that refer to incorrect resources will be skipped during processing. false by default

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setImageResolution {#setImageResolution-int-}
```
public void setImageResolution(int value)
```

Gets or sets resolution for image rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | Value: Resolution |

### setLettersPositioningMethod {#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-}
Sets mode of positioning of letters in words in result HTML

### setMinimalLineWidth {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```

This attribute sets minimal width of graphic path line. If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can be used to emulate this behavior for HTML browsers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setPageBorderIfAny {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
This attribute represents set of settings used for drawing border (if any) in result HTML document around area that represent source PDF page.

### setPageMarginIfAny {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
This attribute represents set of extra page margin (if any) in result HTML document around area that represent source PDF page.

### setPagesFlowTypeDependsOnViewersScreenSize {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```

If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be put into one big result HTML file. This flag defines whether result HTML will be generated in such way that flow of areas that represent PDF pages in result HTML will depend on screen resolution of viewer. Suppose width of screen on viewer side is big enough to put 2 or more pages one near other in horizontal direction. If this flag set to true, then this opportunity will be used (as many pages will be shown in horizontal direction one near another as it possible, then next horizontal group of pages will be shown under first one ). Otherwise pages will flow in such way: next page goes always under previous one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pagesFlowTypeDependsOnViewersScreenSize |  | boolean value |

### setPartsEmbeddingMode {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```

It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| partsEmbeddingMode |  | PartsEmbeddingModes element @see PartsEmbeddingModes |

### setPreventGlyphsGrouping {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```

This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. This parameter will be applied to document only when the value of FixedLayout attribute is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRasterImagesSavingMode {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```

Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImagesSavingMode |  | RasterImagesSavingModes element @see RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```

Defines whether in created HTML will be removed top and bottom empty area without any content (if any).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom |  | boolean value |

### setRenderTextAsImage {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```

If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSaveFullFont {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean value)
```

Indicates that full font will be saved, supports only True Type Fonts. By default SaveFullFont = false and the converter saves the subset of the initial font needed to display the text of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSaveShadowedTextsAsTransparentTexts {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```

Pdf can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML to mimic behaviour of Acrobat Reader (othervise such texts are usually saved as hidden, not available for copying to clipboard)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts |  | boolean value |

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```

Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveTransparentTexts |  | boolean value |

### setSimpleTextboxModeGrouping {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```

This attribute specifies a sequential grouping of glyphs and words into strings For example tags and words has different order in converted HTML and you want them to match. This parameter will be applied to document only when the value of FixedLayout attribute is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSpecialFolderForAllImages {#setSpecialFolderForAllImages-java.lang.String-}
Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. If parameter is empty or null then image files(if any) wil be saved together with other files linked to HTML It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file.

### setSpecialFolderForSvgImages {#setSpecialFolderForSvgImages-java.lang.String-}
Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. If parameter is empty or null then SVG files(if any) wil be saved together with other image-files (near to output file) or in special folder for images (if it specified in SpecialImagesFolderIfAny option). It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file.

### setSplitCssIntoPages {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```

When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSplitIntoPages {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```

Sets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setTitle {#setTitle-java.lang.String-}
Gets or sets HTML page title.

### setTrySaveTextUnderliningAndStrikeoutingInCss {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```

PDF itself does not contain underlining markers for texts. It emulated with line situated under text. This option allows converter try guess that this or that line is a text's underlining and put this info into CSS instead of drawing of underlining graphically

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss |  | boolean value |

### setUseZOrder {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```

If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. If this attribute is false all graphics is put as single layer which may cause some unnecessary effects for overlapped objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |
