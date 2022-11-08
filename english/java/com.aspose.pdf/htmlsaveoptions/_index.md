---
title: HtmlSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Html format
type: docs
weight: 161
url: /java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)

**All Implemented Interfaces:**
[com.aspose.pdf.IPageSetOptions](../../com.aspose.pdf/ipagesetoptions), [com.aspose.pdf.IPipelineOptions](../../com.aspose.pdf/ipipelineoptions)
```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions, IPipelineOptions
```

Save options for export to Html format
## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) | Initializes a new instance of the HtmlSaveOptions class. |
| [HtmlSaveOptions(int documentType)](#HtmlSaveOptions-int-) | Initializes a new instance of the  HtmlSaveOptions  class. |
| [HtmlSaveOptions(boolean fixedLayout)](#HtmlSaveOptions-boolean-) | Initializes a new instance of the  HtmlSaveOptions  class. |
| [HtmlSaveOptions(int documentType, boolean fixedLayout)](#HtmlSaveOptions-int-boolean-) | Initializes a new instance of the  HtmlSaveOptions  class. |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getAdditionalMarginWidthInPoints()](#getAdditionalMarginWidthInPoints--) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. |
| [getAntialiasingProcessing()](#getAntialiasingProcessing--) | This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML |
| [getBatchSize()](#getBatchSize--) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [getClass()](#getClass--) |  |
| [getCompressSvgGraphicsIfAny()](#getCompressSvgGraphicsIfAny--) | Gets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving |
| [getConvertMarkedContentToLayers()](#getConvertMarkedContentToLayers--) | If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. |
| [getCssClassNamesPrefix()](#getCssClassNamesPrefix--) | When PDFtoHTML converter generates result CSSs, CSS class names (something like ".stl\_01 \{\}" ... ".stl\_NN \{\}) are generated and used in result CSS. |
| [getCustomCssSavingStrategy()](#getCustomCssSavingStrategy--) | This field can contain saving strategy that must be used (if present) during conversion of Pdf to Html for handling of saving of CSSes related to created HTML document as whole or to it's pages(if several HTMLpages are generated) If You want handle CSS file in some specific way, that just please create relevant method and Assign delegate created from it to this property. |
| [getCustomHtmlSavingStrategy()](#getCustomHtmlSavingStrategy--) | Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without external linked files if any) that was created during conversion. |
| [getCustomProgressHandler()](#getCustomProgressHandler--) | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [getCustomResourceSavingStrategy()](#getCustomResourceSavingStrategy--) | This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced resource files (like images and fonts) related to nodes of saved HTML. |
| [getCustomStrategyOfCssUrlCreation()](#getCustomStrategyOfCssUrlCreation--) | This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. |
| [getDefaultFontName()](#getDefaultFontName--) | Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. |
| [getDocumentType()](#getDocumentType--) | Gets the  HtmlDocumentTypeInternal . |
| [getExcludeFontNameList()](#getExcludeFontNameList--) | List of PDF embedded font names that not be embedded in HTML. |
| [getExplicitListOfSavedPages()](#getExplicitListOfSavedPages--) | With this property You can explicitely define what pages of document should be converted. |
| [getFixedLayout()](#getFixedLayout--) | Gets a value indicating whether that HTML is created as fixed layout. |
| [getFontEncodingStrategy()](#getFontEncodingStrategy--) | Defines encoding special rule to tune PDF decoding for current document |
| [getFontSavingMode()](#getFontSavingMode--) | Defines font saving mode that will be used during saving of PDF to desirable format |
| [getFontSources()](#getFontSources--) | Font sources of pre-saved fonts. |
| [getHtmlMarkupGenerationMode()](#getHtmlMarkupGenerationMode--) | Sometimes specific reqirments to generation of HTML markup are present. |
| [getImageResolution()](#getImageResolution--) | Gets or sets resolution for image rendering. |
| [getLettersPositioningMethod()](#getLettersPositioningMethod--) | Sets mode of positioning of letters in words in result HTML |
| [getMinimalLineWidth()](#getMinimalLineWidth--) | This attribute sets minimal width of graphic path line. |
| [getPageBorderIfAny()](#getPageBorderIfAny--) | This attribute represents set of settings used for drawing border (if any) in result HTML document around area that represent source PDF page. |
| [getPageMarginIfAny()](#getPageMarginIfAny--) | This attribute represents set of extra page margin (if any) in result HTML document around area that represent source PDF page. |
| [getPartsEmbeddingMode()](#getPartsEmbeddingMode--) | It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities |
| [getPreventGlyphsGrouping()](#getPreventGlyphsGrouping--) | This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. |
| [getProgressEventsRetranslator()](#getProgressEventsRetranslator--) | Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress |
| [getRasterImagesSavingMode()](#getRasterImagesSavingMode--) | Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML |
| [getSaveFormat()](#getSaveFormat--) | Format of data save. |
| [getSimpleTextboxModeGrouping()](#getSimpleTextboxModeGrouping--) | This attribute specifies a sequential grouping of glyphs and words into strings For example tags and words has different order in converted HTML and you want them to match. |
| [getSpecialFolderForAllImages()](#getSpecialFolderForAllImages--) | Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. |
| [getSpecialFolderForSvgImages()](#getSpecialFolderForSvgImages--) | Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. |
| [getSplitCssIntoPages()](#getSplitCssIntoPages--) | When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. |
| [getSplitIntoPages()](#getSplitIntoPages--) | Gets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages. |
| [getUseZOrder()](#getUseZOrder--) | If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. |
| [getWarningHandler()](#getWarningHandler--) | Callback to handle any warnings generated. |
| [hashCode()](#hashCode--) |  |
| [isCloseResponse()](#isCloseResponse--) | Gets boolean value which indicates will Response object be closed after document saved into response. |
| [isExtractOcrSublayerOnly()](#isExtractOcrSublayerOnly--) | This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [isPagesFlowTypeDependsOnViewersScreenSize()](#isPagesFlowTypeDependsOnViewersScreenSize--) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be put into one big result HTML file. |
| [isRemoveEmptyAreasOnTopAndBottom()](#isRemoveEmptyAreasOnTopAndBottom--) | Defines whether in created HTML will be removed top and bottom empty area without any content (if any). |
| [isRenderTextAsImage()](#isRenderTextAsImage--) | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. |
| [isSaveFullFont()](#isSaveFullFont--) | Indicates that full font will be saved, supports only True Type Fonts. |
| [isSaveShadowedTextsAsTransparentTexts()](#isSaveShadowedTextsAsTransparentTexts--) | Pdf can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). |
| [isSaveTransparentTexts()](#isSaveTransparentTexts--) | Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). |
| [isTryMergeAdjacentSameBackgroundImages()](#isTryMergeAdjacentSameBackgroundImages--) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [isTrySaveTextUnderliningAndStrikeoutingInCss()](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | PDF itself does not contain underlining markers for texts. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setAdditionalMarginWidthInPoints(int value)](#setAdditionalMarginWidthInPoints-int-) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. |
| [setAntialiasingProcessing(int antialiasingProcessing)](#setAntialiasingProcessing-int-) | This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML |
| [setBatchSize(int value)](#setBatchSize-int-) | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [setCloseResponse(boolean value)](#setCloseResponse-boolean-) | Sets boolean value which indicates will Response object be closed after document saved into response. |
| [setCompressSvgGraphicsIfAny(boolean value)](#setCompressSvgGraphicsIfAny-boolean-) | Sets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving |
| [setConvertMarkedContentToLayers(boolean value)](#setConvertMarkedContentToLayers-boolean-) | If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. |
| [setCssClassNamesPrefix(String cssClassNamesPrefix)](#setCssClassNamesPrefix-java.lang.String-) | When PDFtoHTML converter generates result CSSs, CSS class names (something like ".stl\_01 \{\}" ... ".stl\_NN \{\}) are generated and used in result CSS. |
| [setCustomCssSavingStrategy(HtmlSaveOptions.CssSavingStrategy customCssSavingStrategy)](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | This field can contain saving strategy that must be used (if present) during conversion of Pdf to Html for handling of saving of CSSes related to created HTML document as whole or to it's pages(if several HTMLpages are generated) If You want handle CSS file in some specific way, that just please create relevant method and Assign delegate created from it to this property. |
| [setCustomHtmlSavingStrategy(HtmlSaveOptions.HtmlPageMarkupSavingStrategy customHtmlSavingStrategy)](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without external linked files if any) that was created during conversion. |
| [setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [setCustomResourceSavingStrategy(HtmlSaveOptions.ResourceSavingStrategy customResourceSavingStrategy)](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced resource files (like images and fonts) related to nodes of saved HTML. |
| [setCustomStrategyOfCssUrlCreation(HtmlSaveOptions.CssUrlMakingStrategy customStrategyOfCssUrlCreation)](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. |
| [setDefaultFontName(String value)](#setDefaultFontName-java.lang.String-) | Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. |
| [setDocumentType(int value)](#setDocumentType-int-) | Sets the  HtmlDocumentType . |
| [setExcludeFontNameList(String[] excludeFontNameList)](#setExcludeFontNameList-java.lang.String---) | List of PDF embedded font names that not be embedded in HTML. |
| [setExplicitListOfSavedPages(int[] value)](#setExplicitListOfSavedPages-int---) | With this property You can explicitely define what pages of document should be converted. |
| [setExtractOcrSublayerOnly(boolean value)](#setExtractOcrSublayerOnly-boolean-) | This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [setFixedLayout(boolean value)](#setFixedLayout-boolean-) | Sets a value indicating whether that HTML is created as fixed layout. |
| [setFontEncodingStrategy(byte fontEncodingStrategy)](#setFontEncodingStrategy-byte-) | Defines encoding special rule to tune PDF decoding for current document |
| [setFontSavingMode(int fontSavingMode)](#setFontSavingMode-int-) | Defines font saving mode that will be used during saving of PDF to desirable format |
| [setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)](#setHtmlMarkupGenerationMode-int-) | Sometimes specific reqirments to generation of HTML markup are present. |
| [setImageResolution(int value)](#setImageResolution-int-) | Gets or sets resolution for image rendering. |
| [setLettersPositioningMethod(int lettersPositioningMethod)](#setLettersPositioningMethod-int-) | Sets mode of positioning of letters in words in result HTML |
| [setMinimalLineWidth(float value)](#setMinimalLineWidth-float-) | This attribute sets minimal width of graphic path line. |
| [setPageBorderIfAny(SaveOptions.BorderInfo pageBorderIfAny)](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | This attribute represents set of settings used for drawing border (if any) in result HTML document around area that represent source PDF page. |
| [setPageMarginIfAny(SaveOptions.MarginInfo pageMarginIfAny)](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | This attribute represents set of extra page margin (if any) in result HTML document around area that represent source PDF page. |
| [setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be put into one big result HTML file. |
| [setPartsEmbeddingMode(int partsEmbeddingMode)](#setPartsEmbeddingMode-int-) | It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities |
| [setPreventGlyphsGrouping(boolean value)](#setPreventGlyphsGrouping-boolean-) | This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. |
| [setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)](#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-) | Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress |
| [setRasterImagesSavingMode(int rasterImagesSavingMode)](#setRasterImagesSavingMode-int-) | Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML |
| [setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | Defines whether in created HTML will be removed top and bottom empty area without any content (if any). |
| [setRenderTextAsImage(boolean value)](#setRenderTextAsImage-boolean-) | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. |
| [setSaveFullFont(boolean saveFullFont)](#setSaveFullFont-boolean-) | Indicates that full font will be saved, supports only True Type Fonts. |
| [setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)](#setSaveShadowedTextsAsTransparentTexts-boolean-) | Pdf can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). |
| [setSaveTransparentTexts(boolean saveTransparentTexts)](#setSaveTransparentTexts-boolean-) | Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). |
| [setSimpleTextboxModeGrouping(boolean value)](#setSimpleTextboxModeGrouping-boolean-) | This attribute specifies a sequential grouping of glyphs and words into strings For example tags and words has different order in converted HTML and you want them to match. |
| [setSpecialFolderForAllImages(String specialFolderForAllImages)](#setSpecialFolderForAllImages-java.lang.String-) | Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. |
| [setSpecialFolderForSvgImages(String specialFolderForSvgImages)](#setSpecialFolderForSvgImages-java.lang.String-) | Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. |
| [setSplitCssIntoPages(boolean value)](#setSplitCssIntoPages-boolean-) | When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. |
| [setSplitIntoPages(boolean value)](#setSplitIntoPages-boolean-) | Sets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages. |
| [setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)](#setTryMergeAdjacentSameBackgroundImages-boolean-) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. |
| [setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | PDF itself does not contain underlining markers for texts. |
| [setUseZOrder(boolean value)](#setUseZOrder-boolean-) | If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. |
| [setWarningHandler(WarningCallback value)](#setWarningHandler-com.aspose.pdf.WarningCallback-) | Callback to handle any warnings generated. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


Initializes a new instance of the HtmlSaveOptions class.

### HtmlSaveOptions(int documentType) {#HtmlSaveOptions-int-}
```
public HtmlSaveOptions(int documentType)
```


Initializes a new instance of the  HtmlSaveOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentType | int | The  HtmlDocumentTypeInternal . |

### HtmlSaveOptions(boolean fixedLayout) {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```


Initializes a new instance of the  HtmlSaveOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fixedLayout | boolean | boolean value |

### HtmlSaveOptions(int documentType, boolean fixedLayout) {#HtmlSaveOptions-int-boolean-}
```
public HtmlSaveOptions(int documentType, boolean fixedLayout)
```


Initializes a new instance of the  HtmlSaveOptions  class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| documentType | int | The  HtmlDocumentTypeInternal . |
| fixedLayout | boolean | if set to  true  HTML is created as fixed layout. |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
### getAdditionalMarginWidthInPoints() {#getAdditionalMarginWidthInPoints--}
```
public int getAdditionalMarginWidthInPoints()
```


If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. But each source PDF page will be represented with it's own rectangle area in HTML (if necessary that areas can be bordered to show page paper edges with special attribute 'PageBorderIfAny'. This parameter defines width of margin that will be forcibly left around that output HTML-areas that represent pages of source PDF document.In essence it defines guaranteed interval between HTML-representations of PDF "paper" pages such mode of conversion.

**Returns:**
int - int value
### getAntialiasingProcessing() {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```


This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML

**Returns:**
int - AntialiasingProcessingType element
### getBatchSize() {#getBatchSize--}
```
public final int getBatchSize()
```


Defines batch size if batched conversion is applicable to source and destination formats pair.

**Returns:**
int
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getCompressSvgGraphicsIfAny() {#getCompressSvgGraphicsIfAny--}
```
public boolean getCompressSvgGraphicsIfAny()
```


Gets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving

Value: The  HtmlDocumentType .

**Returns:**
boolean - boolean value
### getConvertMarkedContentToLayers() {#getConvertMarkedContentToLayers--}
```
public boolean getConvertMarkedContentToLayers()
```


If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content.

**Returns:**
boolean - boolean value
### getCssClassNamesPrefix() {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```


When PDFtoHTML converter generates result CSSs, CSS class names (something like ".stl\_01 \{\}" ... ".stl\_NN \{\}) are generated and used in result CSS. This property allows forcibly set class name prefix For example, if You want that all class names start with 'my\_prefix\_' (i.e. were something like 'my\_prefix\_1' ... 'my\_prefix\_NNN' ) , then just assign 'my\_prefix\_' to this property before conversion. If this property will stay untouched(i.e. null will be leaved as value ), then converter will generate class names itself (it will be something like ".stl\_01 \{\}" ... ".stl\_NN \{\}")

**Returns:**
java.lang.String - String value
### getCustomCssSavingStrategy() {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```


This field can contain saving strategy that must be used (if present) during conversion of Pdf to Html for handling of saving of CSSes related to created HTML document as whole or to it's pages(if several HTMLpages are generated) If You want handle CSS file in some specific way, that just please create relevant method and Assign delegate created from it to this property.

**Returns:**
[CssSavingStrategy](../../com.aspose.pdf/csssavingstrategy) - CssSavingStrategy instance
### getCustomHtmlSavingStrategy() {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```


Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without external linked files if any) that was created during conversion. In such case processing (like saving of paage's HTML in stream or disk) can be done in that custom code . In such case all the necessary actions for saving of HTML page must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that case for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'htmlSavingInfo' parameter's variable : it will signal to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom code for procesing .

**Returns:**
[HtmlPageMarkupSavingStrategy](../../com.aspose.pdf/htmlpagemarkupsavingstrategy) - HtmlPageMarkupSavingStrategy instance
### getCustomProgressHandler() {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```


This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is :

--------------------

```
public static void ConvertWithShowingProgress()
     {
         (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
         Document doc = new Document("Booklet.pdf");
         HtmlSaveOptions saveOptions = new HtmlSaveOptions();
         saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() {
        public void invoke(
    	    UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) {
    	showProgressOnConsole(eventInfo);
        }
    };
         doc.save("Booklet.doc", saveOptions);
     }
     public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
     {
         switch (eventInfo.EventType)
         {
             case HtmlSaveOptions.ProgressEventType.TotalProgress:
                 System.out.println(String.format("%s  - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value));
                 break;
             case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
        	 System.out.println(String.format("%s  - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
                 break;
             case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
        	 System.out.println(String.format("%s  - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
                 break;
             case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
        	 System.out.println(String.format("%s  - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
                 break;
             default:
                 break;
         }
      }
```

**Returns:**
[ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) - ConversionProgressEventHandler instance
### getCustomResourceSavingStrategy() {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```


This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced resource files (like images and fonts) related to nodes of saved HTML. That strategy must process resources and return string that represents desirable URL of saved resource in generated HTML.

**Returns:**
[ResourceSavingStrategy](../../com.aspose.pdf/resourcesavingstrategy) - ResourceSavingStrategy instance
### getCustomStrategyOfCssUrlCreation() {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```


This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. F.e. if You want converter put some specific URL instead of standard CSS file name into generated CSS, then You should just create and put into this property method that generates desirable URL. If flag 'SplitCssIntoPages' set, then this custom strategy (if any) must return not exact URL of CSS but rather template string that (after substitution of placeholder with page number with String.Format() function inside converter) can be resolved into URL for this or that page's CSS' URL. Examples of expected return string in such case are: 'SomeTargetLocation-page\_\{0\}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage=\{0 \} ' )

**Returns:**
[CssUrlMakingStrategy](../../com.aspose.pdf/cssurlmakingstrategy) - CssUrlMakingStrategy instance
### getDefaultFontName() {#getDefaultFontName--}
```
public String getDefaultFontName()
```


Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. If null then default substitution font is used.

**Returns:**
java.lang.String - String value: Font name
### getDocumentType() {#getDocumentType--}
```
public int getDocumentType()
```


Gets the  HtmlDocumentTypeInternal .

**Returns:**
int - The  HtmlDocumentTypeInternal .
### getExcludeFontNameList() {#getExcludeFontNameList--}
```
public String[] getExcludeFontNameList()
```


List of PDF embedded font names that not be embedded in HTML.

**Returns:**
java.lang.String[] - array of String elements
### getExplicitListOfSavedPages() {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```


With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown.

**Returns:**
int[]
### getFixedLayout() {#getFixedLayout--}
```
public boolean getFixedLayout()
```


Gets a value indicating whether that HTML is created as fixed layout.

**Returns:**
boolean - value:  true  if [fixed layout]; otherwise,  false .
### getFontEncodingStrategy() {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```


Defines encoding special rule to tune PDF decoding for current document

**Returns:**
byte - FontEncodingRules element
### getFontSavingMode() {#getFontSavingMode--}
```
public int getFontSavingMode()
```


Defines font saving mode that will be used during saving of PDF to desirable format

**Returns:**
int - FontSavingModes element
### getFontSources() {#getFontSources--}
```
public FontSourceCollection getFontSources()
```


Font sources of pre-saved fonts.

**Returns:**
[FontSourceCollection](../../com.aspose.pdf.text/fontsourcecollection) - FontSourceCollection object

--------------------

Fonts may be saved preliminarily for cache purpose and then passed into Html conversion process. For example it may be useful in document splitting scenario and processing document pages in multiple threads with single set of fonts.
### getHtmlMarkupGenerationMode() {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```


Sometimes specific reqirments to generation of HTML markup are present. This parameter defines HTML preparing modes that can be used during conversion of PDF to HTML to match such specific requirments.

**Returns:**
int - HtmlMarkupGenerationModes element
### getImageResolution() {#getImageResolution--}
```
public int getImageResolution()
```


Gets or sets resolution for image rendering.

**Returns:**
int - Value: Resolution
### getLettersPositioningMethod() {#getLettersPositioningMethod--}
```
public int getLettersPositioningMethod()
```


Sets mode of positioning of letters in words in result HTML

**Returns:**
int - LettersPositioningMethods element
### getMinimalLineWidth() {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```


This attribute sets minimal width of graphic path line. If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can be used to emulate this behavior for HTML browsers.

**Returns:**
float - float value
### getPageBorderIfAny() {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```


This attribute represents set of settings used for drawing border (if any) in result HTML document around area that represent source PDF page. In essence it concerns of showing of page's paper edges, not page border referenced in PDF page itself.

**Returns:**
[BorderInfo](../../com.aspose.pdf/borderinfo) - BorderInfo instance
### getPageMarginIfAny() {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```


This attribute represents set of extra page margin (if any) in result HTML document around area that represent source PDF page.

**Returns:**
[MarginInfo](../../com.aspose.pdf/margininfo) - MarginInfo instance
### getPartsEmbeddingMode() {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```


It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities

**Returns:**
int - PartsEmbeddingModes element
### getPreventGlyphsGrouping() {#getPreventGlyphsGrouping--}
```
public boolean getPreventGlyphsGrouping()
```


This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. This parameter will be applied to document only when the value of FixedLayout attribute is true.

**Returns:**
boolean - boolean value
### getProgressEventsRetranslator() {#getProgressEventsRetranslator--}
```
public ConversionProgressEventsTranslator getProgressEventsRetranslator()
```


Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress

**Returns:**
com.aspose.pdf.ConversionProgressEventsTranslator - ConversionProgressEventsTranslator instance
### getRasterImagesSavingMode() {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```


Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML

**Returns:**
int - RasterImagesSavingModes element
### getSaveFormat() {#getSaveFormat--}
```
public SaveFormat getSaveFormat()
```


Format of data save.

**Returns:**
[SaveFormat](../../com.aspose.pdf/saveformat) - SaveFormat value
### getSimpleTextboxModeGrouping() {#getSimpleTextboxModeGrouping--}
```
public final boolean getSimpleTextboxModeGrouping()
```


This attribute specifies a sequential grouping of glyphs and words into strings For example tags and words has different order in converted HTML and you want them to match. This parameter will be applied to document only when the value of FixedLayout attribute is true.

**Returns:**
boolean - boolean value
### getSpecialFolderForAllImages() {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```


Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. If parameter is empty or null then image files(if any) wil be saved together with other files linked to HTML It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file.

**Returns:**
java.lang.String - String value
### getSpecialFolderForSvgImages() {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```


Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. If parameter is empty or null then SVG files(if any) wil be saved together with other image-files (near to output file) or in special folder for images (if it specified in SpecialImagesFolderIfAny option). It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file.

**Returns:**
java.lang.String - String value
### getSplitCssIntoPages() {#getSplitCssIntoPages--}
```
public boolean getSplitCssIntoPages()
```


When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue.

**Returns:**
boolean - boolean value
### getSplitIntoPages() {#getSplitIntoPages--}
```
public boolean getSplitIntoPages()
```


Gets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages.

**Returns:**
boolean - boolean value
### getUseZOrder() {#getUseZOrder--}
```
public boolean getUseZOrder()
```


If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. If this attribute is false all graphics is put as single layer which may cause some unnecessary effects for overlapped objects.

**Returns:**
boolean - boolean value
### getWarningHandler() {#getWarningHandler--}
```
public WarningCallback getWarningHandler()
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.

**Returns:**
[WarningCallback](../../com.aspose.pdf/warningcallback) - IWarningCallback value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isCloseResponse() {#isCloseResponse--}
```
public boolean isCloseResponse()
```


Gets boolean value which indicates will Response object be closed after document saved into response.

**Returns:**
boolean - boolean value
### isExtractOcrSublayerOnly() {#isExtractOcrSublayerOnly--}
```
public boolean isExtractOcrSublayerOnly()
```


This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer.

Value:  true  text will be extracted in result document; otherwise,  false .

**Returns:**
boolean - boolean value
### isPagesFlowTypeDependsOnViewersScreenSize() {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```


If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be put into one big result HTML file. This flag defines whether result HTML will be generated in such way that flow of areas that represent PDF pages in result HTML will depend on screen resolution of viewer. Suppose width of screen on viewer side is big enough to put 2 or more pages one near other in horizontal direction. If this flag set to true, then this opportunity will be used (as many pages will be shown in horizontal direction one near another as it possible, then next horizontal group of pages will be shown under first one ). Otherwise pages will flow in such way: next page goes always under previous one.

**Returns:**
boolean - boolean value
### isRemoveEmptyAreasOnTopAndBottom() {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```


Defines whether in created HTML will be removed top and bottom empty area without any content (if any).

**Returns:**
boolean - boolean value
### isRenderTextAsImage() {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```


If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly.

**Returns:**
boolean - boolean value
### isSaveFullFont() {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```


Indicates that full font will be saved, supports only True Type Fonts. By default SaveFullFont = false and the converter saves the subset of the initial font needed to display the text of the document.

**Returns:**
boolean - boolean value
### isSaveShadowedTextsAsTransparentTexts() {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```


Pdf can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML to mimic behaviour of Acrobat Reader (othervise such texts are usually saved as hidden, not available for copying to clipboard)

**Returns:**
boolean - boolean value
### isSaveTransparentTexts() {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```


Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML

**Returns:**
boolean - boolean value
### isTryMergeAdjacentSameBackgroundImages() {#isTryMergeAdjacentSameBackgroundImages--}
```
public boolean isTryMergeAdjacentSameBackgroundImages()
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Returns:**
boolean - boolean value
### isTrySaveTextUnderliningAndStrikeoutingInCss() {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```


PDF itself does not contain underlining markers for texts. It emulated with line situated under text. This option allows converter try guess that this or that line is a text's underlining and put this info into CSS instead of drawing of underlining graphically

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setAdditionalMarginWidthInPoints(int value) {#setAdditionalMarginWidthInPoints-int-}
```
public void setAdditionalMarginWidthInPoints(int value)
```


If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. But each source PDF page will be represented with it's own rectangle area in HTML (if necessary that areas can be bordered to show page paper edges with special attribute 'PageBorderIfAny'. This parameter defines width of margin that will be forcibly left around that output HTML-areas that represent pages of source PDF document.In essence it defines guaranteed interval between HTML-representations of PDF "paper" pages such mode of conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### setAntialiasingProcessing(int antialiasingProcessing) {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```


This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| antialiasingProcessing | int | AntialiasingProcessingType element |

### setBatchSize(int value) {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```


Defines batch size if batched conversion is applicable to source and destination formats pair.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### setCloseResponse(boolean value) {#setCloseResponse-boolean-}
```
public void setCloseResponse(boolean value)
```


Sets boolean value which indicates will Response object be closed after document saved into response.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCompressSvgGraphicsIfAny(boolean value) {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```


Sets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving

Value: The  HtmlDocumentType .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setConvertMarkedContentToLayers(boolean value) {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```


If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCssClassNamesPrefix(String cssClassNamesPrefix) {#setCssClassNamesPrefix-java.lang.String-}
```
public void setCssClassNamesPrefix(String cssClassNamesPrefix)
```


When PDFtoHTML converter generates result CSSs, CSS class names (something like ".stl\_01 \{\}" ... ".stl\_NN \{\}) are generated and used in result CSS. This property allows forcibly set class name prefix For example, if You want that all class names start with 'my\_prefix\_' (i.e. were something like 'my\_prefix\_1' ... 'my\_prefix\_NNN' ) , then just assign 'my\_prefix\_' to this property before conversion. If this property will stay untouched(i.e. null will be leaved as value ), then converter will generate class names itself (it will be something like ".stl\_01 \{\}" ... ".stl\_NN \{\}")

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| cssClassNamesPrefix | java.lang.String | String value |

### setCustomCssSavingStrategy(HtmlSaveOptions.CssSavingStrategy customCssSavingStrategy) {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
```
public void setCustomCssSavingStrategy(HtmlSaveOptions.CssSavingStrategy customCssSavingStrategy)
```


This field can contain saving strategy that must be used (if present) during conversion of Pdf to Html for handling of saving of CSSes related to created HTML document as whole or to it's pages(if several HTMLpages are generated) If You want handle CSS file in some specific way, that just please create relevant method and Assign delegate created from it to this property.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customCssSavingStrategy | [CssSavingStrategy](../../com.aspose.pdf/csssavingstrategy) | CssSavingStrategy instance |

### setCustomHtmlSavingStrategy(HtmlSaveOptions.HtmlPageMarkupSavingStrategy customHtmlSavingStrategy) {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
```
public void setCustomHtmlSavingStrategy(HtmlSaveOptions.HtmlPageMarkupSavingStrategy customHtmlSavingStrategy)
```


Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without external linked files if any) that was created during conversion. In such case processing (like saving of paage's HTML in stream or disk) can be done in that custom code . In such case all the necessary actions for saving of HTML page must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that case for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'htmlSavingInfo' parameter's variable : it will signal to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom code for procesing .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customHtmlSavingStrategy | [HtmlPageMarkupSavingStrategy](../../com.aspose.pdf/htmlpagemarkupsavingstrategy) | HtmlPageMarkupSavingStrategy instance |

### setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler) {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
```
public void setCustomProgressHandler(UnifiedSaveOptions.ConversionProgressEventHandler customProgressHandler)
```


This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is :

--------------------

```
public static void ConvertWithShowingProgress()
     {
     (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
     Document doc = new Document("Booklet.pdf");
     HtmlSaveOptions saveOptions = new HtmlSaveOptions();
     saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() {
     public void invoke(
     UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) {
     showProgressOnConsole(eventInfo);
     }
     };
     doc.save("Booklet.doc", saveOptions);
     }
     public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
     {
     switch (eventInfo.EventType)
     {
     case HtmlSaveOptions.ProgressEventType.TotalProgress:
     System.out.println(String.format("%s  - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value));
     break;
     case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
     System.out.println(String.format("%s  - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
     break;
     case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
     System.out.println(String.format("%s  - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
     break;
     case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
     System.out.println(String.format("%s  - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
     break;
     default:
     break;
     }
     }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customProgressHandler | [ConversionProgressEventHandler](../../com.aspose.pdf/conversionprogresseventhandler) | ConversionProgressEventHandler instance |

### setCustomResourceSavingStrategy(HtmlSaveOptions.ResourceSavingStrategy customResourceSavingStrategy) {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
```
public void setCustomResourceSavingStrategy(HtmlSaveOptions.ResourceSavingStrategy customResourceSavingStrategy)
```


This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced resource files (like images and fonts) related to nodes of saved HTML. That strategy must process resources and return string that represents desirable URL of saved resource in generated HTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customResourceSavingStrategy | [ResourceSavingStrategy](../../com.aspose.pdf/resourcesavingstrategy) | ResourceSavingStrategy instance |

### setCustomStrategyOfCssUrlCreation(HtmlSaveOptions.CssUrlMakingStrategy customStrategyOfCssUrlCreation) {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
```
public void setCustomStrategyOfCssUrlCreation(HtmlSaveOptions.CssUrlMakingStrategy customStrategyOfCssUrlCreation)
```


This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. F.e. if You want converter put some specific URL instead of standard CSS file name into generated CSS, then You should just create and put into this property method that generates desirable URL. If flag 'SplitCssIntoPages' set, then this custom strategy (if any) must return not exact URL of CSS but rather template string that (after substitution of placeholder with page number with String.Format() function inside converter) can be resolved into URL for this or that page's CSS' URL. Examples of expected return string in such case are: 'SomeTargetLocation-page\_\{0\}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage=\{0 \} ' )

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| customStrategyOfCssUrlCreation | [CssUrlMakingStrategy](../../com.aspose.pdf/cssurlmakingstrategy) | CssUrlMakingStrategy instance |

### setDefaultFontName(String value) {#setDefaultFontName-java.lang.String-}
```
public void setDefaultFontName(String value)
```


Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. If null then default substitution font is used.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Font name |

### setDocumentType(int value) {#setDocumentType-int-}
```
public void setDocumentType(int value)
```


Sets the  HtmlDocumentType .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The  HtmlDocumentType . |

### setExcludeFontNameList(String[] excludeFontNameList) {#setExcludeFontNameList-java.lang.String---}
```
public void setExcludeFontNameList(String[] excludeFontNameList)
```


List of PDF embedded font names that not be embedded in HTML.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| excludeFontNameList | java.lang.String[] | array of String elements |

### setExplicitListOfSavedPages(int[] value) {#setExplicitListOfSavedPages-int---}
```
public final void setExplicitListOfSavedPages(int[] value)
```


With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int[] |  |

### setExtractOcrSublayerOnly(boolean value) {#setExtractOcrSublayerOnly-boolean-}
```
public void setExtractOcrSublayerOnly(boolean value)
```


This attribute turned on functionality for extracting image or text for PDF documents with OCR sublayer.

Value:  true  text will be extracted in result document; otherwise,  false .

--------------------

Default value == false

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setFixedLayout(boolean value) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```


Sets a value indicating whether that HTML is created as fixed layout.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | :  true  if [fixed layout]; otherwise,  false . |

### setFontEncodingStrategy(byte fontEncodingStrategy) {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```


Defines encoding special rule to tune PDF decoding for current document

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontEncodingStrategy | byte | FontEncodingRules element |

### setFontSavingMode(int fontSavingMode) {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```


Defines font saving mode that will be used during saving of PDF to desirable format

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fontSavingMode | int | FontSavingModes element |

### setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode) {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```


Sometimes specific reqirments to generation of HTML markup are present. This parameter defines HTML preparing modes that can be used during conversion of PDF to HTML to match such specific requirments.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| htmlMarkupGenerationMode | int | HtmlMarkupGenerationModes element |

### setImageResolution(int value) {#setImageResolution-int-}
```
public void setImageResolution(int value)
```


Gets or sets resolution for image rendering.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Value: Resolution |

### setLettersPositioningMethod(int lettersPositioningMethod) {#setLettersPositioningMethod-int-}
```
public void setLettersPositioningMethod(int lettersPositioningMethod)
```


Sets mode of positioning of letters in words in result HTML

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| lettersPositioningMethod | int | LettersPositioningMethods element |

### setMinimalLineWidth(float value) {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```


This attribute sets minimal width of graphic path line. If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can be used to emulate this behavior for HTML browsers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### setPageBorderIfAny(SaveOptions.BorderInfo pageBorderIfAny) {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
```
public void setPageBorderIfAny(SaveOptions.BorderInfo pageBorderIfAny)
```


This attribute represents set of settings used for drawing border (if any) in result HTML document around area that represent source PDF page. In essence it concerns of showing of page's paper edges, not page border referenced in PDF page itself.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageBorderIfAny | [BorderInfo](../../com.aspose.pdf/borderinfo) | BorderInfo instance |

### setPageMarginIfAny(SaveOptions.MarginInfo pageMarginIfAny) {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
```
public void setPageMarginIfAny(SaveOptions.MarginInfo pageMarginIfAny)
```


This attribute represents set of extra page margin (if any) in result HTML document around area that represent source PDF page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pageMarginIfAny | [MarginInfo](../../com.aspose.pdf/margininfo) | MarginInfo instance |

### setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize) {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```


If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be put into one big result HTML file. This flag defines whether result HTML will be generated in such way that flow of areas that represent PDF pages in result HTML will depend on screen resolution of viewer. Suppose width of screen on viewer side is big enough to put 2 or more pages one near other in horizontal direction. If this flag set to true, then this opportunity will be used (as many pages will be shown in horizontal direction one near another as it possible, then next horizontal group of pages will be shown under first one ). Otherwise pages will flow in such way: next page goes always under previous one.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| pagesFlowTypeDependsOnViewersScreenSize | boolean | boolean value |

### setPartsEmbeddingMode(int partsEmbeddingMode) {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```


It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| partsEmbeddingMode | int | PartsEmbeddingModes element |

### setPreventGlyphsGrouping(boolean value) {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```


This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. This parameter will be applied to document only when the value of FixedLayout attribute is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator) {#setProgressEventsRetranslator-com.aspose.pdf.ConversionProgressEventsTranslator-}
```
public void setProgressEventsRetranslator(ConversionProgressEventsTranslator progressEventsRetranslator)
```


Represents internal progress events processor that works during conversion and translates conversion events of internal conversion stages into external total progress events Also class broadcasts events that allow to free resources that not needed anymore This internal class handles events of PDF to APS and APS to [Other format] progress to calculate total progress and inform customer's code about that total progress events this class uses two types of events : ApsToExternal model conversion and events of conversion Pdf to APS to generate total progress events Export has three stage : 1) Pdf to Aps 2) Aps recognition 3\_ Aps export to target format Constructor allows tune how much pages are converted and what is approximmate part of this or that stage in total progress

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| progressEventsRetranslator | com.aspose.pdf.ConversionProgressEventsTranslator | ConversionProgressEventsTranslator instance |

### setRasterImagesSavingMode(int rasterImagesSavingMode) {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```


Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rasterImagesSavingMode | int | RasterImagesSavingModes element |

### setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom) {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```


Defines whether in created HTML will be removed top and bottom empty area without any content (if any).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| removeEmptyAreasOnTopAndBottom | boolean | boolean value |

### setRenderTextAsImage(boolean value) {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```


If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSaveFullFont(boolean saveFullFont) {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean saveFullFont)
```


Indicates that full font will be saved, supports only True Type Fonts. By default SaveFullFont = false and the converter saves the subset of the initial font needed to display the text of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveFullFont | boolean | boolean value |

### setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts) {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```


Pdf can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML to mimic behaviour of Acrobat Reader (othervise such texts are usually saved as hidden, not available for copying to clipboard)

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveShadowedTextsAsTransparentTexts | boolean | boolean value |

### setSaveTransparentTexts(boolean saveTransparentTexts) {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```


Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| saveTransparentTexts | boolean | boolean value |

### setSimpleTextboxModeGrouping(boolean value) {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```


This attribute specifies a sequential grouping of glyphs and words into strings For example tags and words has different order in converted HTML and you want them to match. This parameter will be applied to document only when the value of FixedLayout attribute is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSpecialFolderForAllImages(String specialFolderForAllImages) {#setSpecialFolderForAllImages-java.lang.String-}
```
public void setSpecialFolderForAllImages(String specialFolderForAllImages)
```


Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. If parameter is empty or null then image files(if any) wil be saved together with other files linked to HTML It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| specialFolderForAllImages | java.lang.String | String value |

### setSpecialFolderForSvgImages(String specialFolderForSvgImages) {#setSpecialFolderForSvgImages-java.lang.String-}
```
public void setSpecialFolderForSvgImages(String specialFolderForSvgImages)
```


Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. If parameter is empty or null then SVG files(if any) wil be saved together with other image-files (near to output file) or in special folder for images (if it specified in SpecialImagesFolderIfAny option). It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| specialFolderForSvgImages | java.lang.String | String value |

### setSplitCssIntoPages(boolean value) {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```


When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSplitIntoPages(boolean value) {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```


Sets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages) {#setTryMergeAdjacentSameBackgroundImages-boolean-}
```
public void setTryMergeAdjacentSameBackgroundImages(boolean tryMergeAdjacentSameBackgroundImages)
```


Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| tryMergeAdjacentSameBackgroundImages | boolean | boolean value |

### setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss) {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```


PDF itself does not contain underlining markers for texts. It emulated with line situated under text. This option allows converter try guess that this or that line is a text's underlining and put this info into CSS instead of drawing of underlining graphically

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| trySaveTextUnderliningAndStrikeoutingInCss | boolean | boolean value |

### setUseZOrder(boolean value) {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```


If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. If this attribute is false all graphics is put as single layer which may cause some unnecessary effects for overlapped objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setWarningHandler(WarningCallback value) {#setWarningHandler-com.aspose.pdf.WarningCallback-}
```
public void setWarningHandler(WarningCallback value)
```


Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [WarningCallback](../../com.aspose.pdf/warningcallback) | IWarningCallback value |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

