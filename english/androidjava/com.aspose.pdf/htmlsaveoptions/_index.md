---
title: HtmlSaveOptions
second_title: Aspose.PDF for Java API Reference
description: Save options for export to Html format
type: docs
weight: 135
url: /java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.SaveOptions](../../com.aspose.pdf/saveoptions), [com.aspose.pdf.UnifiedSaveOptions](../../com.aspose.pdf/unifiedsaveoptions)
```
public class HtmlSaveOptions extends UnifiedSaveOptions
```

Save options for export to Html format
## Constructors

| Constructor | Description |
| --- | --- |
| [HtmlSaveOptions()](#HtmlSaveOptions--) | Initializes a new instance of the  class. |
| [HtmlSaveOptions(int documentType)](#HtmlSaveOptions-int-) | Initializes a new instance of the  HtmlSaveOptions  class. |
| [HtmlSaveOptions(boolean fixedLayout)](#HtmlSaveOptions-boolean-) | Initializes a new instance of the  HtmlSaveOptions  class. |
| [HtmlSaveOptions(int documentType, boolean fixedLayout)](#HtmlSaveOptions-int-boolean-) | Initializes a new instance of the  HtmlSaveOptions  class. |
## Fields

| Field | Description |
| --- | --- |
| [CustomProgressHandler](#CustomProgressHandler) | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [AntialiasingProcessing](#AntialiasingProcessing) | This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML |
| [SaveTransparentTexts](#SaveTransparentTexts) | Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). |
| [SaveShadowedTextsAsTransparentTexts](#SaveShadowedTextsAsTransparentTexts) | Pdf can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). |
| [FontSavingMode](#FontSavingMode) | Defines font saving mode that will be used during saving of PDF to desirable format |
| [PageBorderIfAny](#PageBorderIfAny) | This attribute represents set of settings used for drawing border (if any) in result HTML document around area that represent source PDF page. |
| [LettersPositioningMethod](#LettersPositioningMethod) | Sets mode of positioning of letters in words in result HTML |
| [ExplicitListOfSavedPages](#ExplicitListOfSavedPages) | With this property You can explicitely define what pages of document should be converted. |
| [CustomResourceSavingStrategy](#CustomResourceSavingStrategy) | This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced resource files (like images and fonts) related to nodes of saved HTML. |
| [CustomCssSavingStrategy](#CustomCssSavingStrategy) | This field can contain saving strategy that must be used (if present) during conversion of Pdf to Html for handling of saving of CSSes related to created HTML document as whole or to it's pages(if several HTMLpages are generated) If You want handle CSS file in some specific way, that just please create relevant method and Assign delegate created from it to this property. |
| [CustomHtmlSavingStrategy](#CustomHtmlSavingStrategy) | Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without external linked files if any) that was created during conversion. |
| [CustomStrategyOfCssUrlCreation](#CustomStrategyOfCssUrlCreation) | This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. |
| [SpecialFolderForSvgImages](#SpecialFolderForSvgImages) | Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. |
| [SpecialFolderForAllImages](#SpecialFolderForAllImages) | Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. |
| [CssClassNamesPrefix](#CssClassNamesPrefix) | When PDFtoHTML converter generates result CSSs, CSS class names (something like ".stl\_01 \{\}" ... ".stl\_NN \{\}) are generated and used in result CSS. |
| [PartsEmbeddingMode](#PartsEmbeddingMode) | It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities |
| [HtmlMarkupGenerationMode](#HtmlMarkupGenerationMode) | Sometimes specific reqirments to generation of HTML markup are present. |
| [RasterImagesSavingMode](#RasterImagesSavingMode) | Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML |
| [RemoveEmptyAreasOnTopAndBottom](#RemoveEmptyAreasOnTopAndBottom) | Defines whether in created HTML will be removed top and bottom empty area without any content (if any). |
| [FontEncodingStrategy](#FontEncodingStrategy) | Defines encoding special rule to tune PDF decoding for current document |
| [PagesFlowTypeDependsOnViewersScreenSize](#PagesFlowTypeDependsOnViewersScreenSize) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be put into one big result HTML file. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](#TrySaveTextUnderliningAndStrikeoutingInCss) | PDF itself does not contain underlining markers for texts. |
## Methods

| Method | Description |
| --- | --- |
| [getDocumentType()](#getDocumentType--) | Gets the  HtmlDocumentTypeInternal . |
| [setDocumentType(int value)](#setDocumentType-int-) | Sets the  HtmlDocumentType . |
| [getCompressSvgGraphicsIfAny()](#getCompressSvgGraphicsIfAny--) | Gets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving |
| [setCompressSvgGraphicsIfAny(boolean value)](#setCompressSvgGraphicsIfAny-boolean-) | Sets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving |
| [getSplitCssIntoPages()](#getSplitCssIntoPages--) | When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. |
| [setSplitCssIntoPages(boolean value)](#setSplitCssIntoPages-boolean-) | When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. |
| [getSplitIntoPages()](#getSplitIntoPages--) | Gets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages. |
| [setSplitIntoPages(boolean value)](#setSplitIntoPages-boolean-) | Sets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages. |
| [getFixedLayout()](#getFixedLayout--) | Gets a value indicating whether that HTML is created as fixed layout. |
| [setFixedLayout(boolean value)](#setFixedLayout-boolean-) | Sets a value indicating whether that HTML is created as fixed layout. |
| [getFontSources()](#getFontSources--) | Font sources of pre-saved fonts. |
| [getAdditionalMarginWidthInPoints()](#getAdditionalMarginWidthInPoints--) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. |
| [setAdditionalMarginWidthInPoints(int value)](#setAdditionalMarginWidthInPoints-int-) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. |
| [getUseZOrder()](#getUseZOrder--) | If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. |
| [setUseZOrder(boolean value)](#setUseZOrder-boolean-) | If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. |
| [getConvertMarkedContentToLayers()](#getConvertMarkedContentToLayers--) | If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML

with "data-pdflayer" attribute specifying a layer name. |
| [setConvertMarkedContentToLayers(boolean value)](#setConvertMarkedContentToLayers-boolean-) | If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML

with "data-pdflayer" attribute specifying a layer name. |
| [getMinimalLineWidth()](#getMinimalLineWidth--) | This attribute sets minimal width of graphic path line. |
| [setMinimalLineWidth(float value)](#setMinimalLineWidth-float-) | This attribute sets minimal width of graphic path line. |
| [getPreventGlyphsGrouping()](#getPreventGlyphsGrouping--) | This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. |
| [setPreventGlyphsGrouping(boolean value)](#setPreventGlyphsGrouping-boolean-) | This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. |
### HtmlSaveOptions() {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```


Initializes a new instance of the  class.

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

### CustomProgressHandler {#CustomProgressHandler}
```
public UnifiedSaveOptions.ConversionProgressEventHandler CustomProgressHandler
```


This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is :

--------------------

> ```
> public static void ConvertWithShowingProgress()
>      {
>      (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic");
>      Document doc = new Document("Booklet.pdf");
>      HtmlSaveOptions saveOptions = new HtmlSaveOptions();
>      saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() {
>      public void invoke(
>      UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) {
>      showProgressOnConsole(eventInfo);
>      }
>      };
>      doc.save("Booklet.doc", saveOptions);
>      }
>      public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo)
>      {
>      switch (eventInfo.EventType)
>      {
>      case HtmlSaveOptions.ProgressEventType.TotalProgress:
>      System.out.println(String.format("%s  - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value));
>      break;
>      case HtmlSaveOptions.ProgressEventType.SourcePageAnalized:
>      System.out.println(String.format("%s  - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
>      break;
>      case HtmlSaveOptions.ProgressEventType.ResultPageCreated:
>      System.out.println(String.format("%s  - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
>      break;
>      case HtmlSaveOptions.ProgressEventType.ResultPageSaved:
>      System.out.println(String.format("%s  - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue));
>      break;
>      default:
>      break;
>      }
>      }
> ```

### AntialiasingProcessing {#AntialiasingProcessing}
```
public int AntialiasingProcessing
```


This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML

### SaveTransparentTexts {#SaveTransparentTexts}
```
public boolean SaveTransparentTexts
```


Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML

### SaveShadowedTextsAsTransparentTexts {#SaveShadowedTextsAsTransparentTexts}
```
public boolean SaveShadowedTextsAsTransparentTexts
```


Pdf can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML to mimic behaviour of Acrobat Reader (othervise such texts are usually saved as hidden, not available for copying to clipboard)

### FontSavingMode {#FontSavingMode}
```
public int FontSavingMode
```


Defines font saving mode that will be used during saving of PDF to desirable format

### PageBorderIfAny {#PageBorderIfAny}
```
public SaveOptions.BorderInfo PageBorderIfAny
```


This attribute represents set of settings used for drawing border (if any) in result HTML document around area that represent source PDF page. In essence it concerns of showing of page's paper edges, not page border referenced in PDF page itself.

### LettersPositioningMethod {#LettersPositioningMethod}
```
public int LettersPositioningMethod
```


Sets mode of positioning of letters in words in result HTML

### ExplicitListOfSavedPages {#ExplicitListOfSavedPages}
```
public int[] ExplicitListOfSavedPages
```


With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown.

### CustomResourceSavingStrategy {#CustomResourceSavingStrategy}
```
public HtmlSaveOptions.ResourceSavingStrategy CustomResourceSavingStrategy
```


This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced resource files (like images and fonts) related to nodes of saved HTML. That strategy must process resources and return string that represents desirable URL of saved resource in generated HTML.

### CustomCssSavingStrategy {#CustomCssSavingStrategy}
```
public HtmlSaveOptions.CssSavingStrategy CustomCssSavingStrategy
```


This field can contain saving strategy that must be used (if present) during conversion of Pdf to Html for handling of saving of CSSes related to created HTML document as whole or to it's pages(if several HTMLpages are generated) If You want handle CSS file in some specific way, that just please create relevant method and Assign delegate created from it to this property.

### CustomHtmlSavingStrategy {#CustomHtmlSavingStrategy}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy CustomHtmlSavingStrategy
```


Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without external linked files if any) that was created during conversion. In such case processing (like saving of paage's HTML in stream or disk) can be done in that custom code . In such case all the necessary actions for saving of HTML page must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that case for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'htmlSavingInfo' parameter's variable : it will signal to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom code for procesing .

### CustomStrategyOfCssUrlCreation {#CustomStrategyOfCssUrlCreation}
```
public HtmlSaveOptions.CssUrlMakingStrategy CustomStrategyOfCssUrlCreation
```


This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. F.e. if You want converter put some specific URL instead of standard CSS file name into generated CSS, then You should just create and put into this property method that generates desirable URL. If flag 'SplitCssIntoPages' set, then this custom strategy (if any) must return not exact URL of CSS but rather template string that (after substitution of placeholder with page number with String.Format() function inside converter) can be resolved into URL for this or that page's CSS' URL. Examples of expected return string in such case are: 'SomeTargetLocation-page\_\{0\}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage=\{0\}' )

### SpecialFolderForSvgImages {#SpecialFolderForSvgImages}
```
public String SpecialFolderForSvgImages
```


Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. If parameter is empty or null then SVG files(if any) wil be saved together with other image-files (near to output file) or in special folder for images (if it specified in SpecialImagesFolderIfAny option). It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file.

### SpecialFolderForAllImages {#SpecialFolderForAllImages}
```
public String SpecialFolderForAllImages
```


Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. If parameter is empty or null then image files(if any) wil be saved together with other files linked to HTML It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file.

### CssClassNamesPrefix {#CssClassNamesPrefix}
```
public String CssClassNamesPrefix
```


When PDFtoHTML converter generates result CSSs, CSS class names (something like ".stl\_01 \{\}" ... ".stl\_NN \{\}) are generated and used in result CSS. This property allows forcibly set class name prefix For example, if You want that all class names start with 'my\_prefix\_' (i.e. were something like 'my\_prefix\_1' ... 'my\_prefix\_NNN' ) , then just assign 'my\_prefix\_' to this property before conversion. If this property will stay untouched(i.e. null will be leaved as value ), then converter will generate class names itself (it will be something like ".stl\_01 \{\}" ... ".stl\_NN \{\}")

### PartsEmbeddingMode {#PartsEmbeddingMode}
```
public int PartsEmbeddingMode
```


It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities

### HtmlMarkupGenerationMode {#HtmlMarkupGenerationMode}
```
public int HtmlMarkupGenerationMode
```


Sometimes specific reqirments to generation of HTML markup are present. This parameter defines HTML preparing modes that can be used during conversion of PDF to HTML to match such specific requirments.

### RasterImagesSavingMode {#RasterImagesSavingMode}
```
public int RasterImagesSavingMode
```


Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML

### RemoveEmptyAreasOnTopAndBottom {#RemoveEmptyAreasOnTopAndBottom}
```
public boolean RemoveEmptyAreasOnTopAndBottom
```


Defines whether in created HTML will be removed top and bottom empty area without any content (if any).

### FontEncodingStrategy {#FontEncodingStrategy}
```
public byte FontEncodingStrategy
```


Defines encoding special rule to tune PDF decoding for current document

### PagesFlowTypeDependsOnViewersScreenSize {#PagesFlowTypeDependsOnViewersScreenSize}
```
public boolean PagesFlowTypeDependsOnViewersScreenSize
```


If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be put into one big result HTML file. This flag defines whether result HTML will be generated in such way that flow of areas that represent PDF pages in result HTML will depend on screen resolution of viewer. Suppose width of screen on viewer side is big enough to put 2 or more pages one near other in horizontal direction. If this flag set to true, then this opportunity will be used (as many pages will be shown in horizontal direction one near another as it possible, then next horizontal group of pages will be shown under first one ). Otherwise pages will flow in such way: next page goes always under previous one.

### TrySaveTextUnderliningAndStrikeoutingInCss {#TrySaveTextUnderliningAndStrikeoutingInCss}
```
public boolean TrySaveTextUnderliningAndStrikeoutingInCss
```


PDF itself does not contain underlining markers for texts. It emulated with line situated under text. This option allows converter try guess that this or that line is a text's underlining and put this info into CSS instead of drawing of underlining graphically

### getDocumentType() {#getDocumentType--}
```
public int getDocumentType()
```


Gets the  HtmlDocumentTypeInternal .

**Returns:**
int - The  HtmlDocumentTypeInternal .
### setDocumentType(int value) {#setDocumentType-int-}
```
public void setDocumentType(int value)
```


Sets the  HtmlDocumentType .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | The  HtmlDocumentType . |

### getCompressSvgGraphicsIfAny() {#getCompressSvgGraphicsIfAny--}
```
public boolean getCompressSvgGraphicsIfAny()
```


Gets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving

Value: The  HtmlDocumentType .

**Returns:**
boolean - boolean value
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

### getSplitCssIntoPages() {#getSplitCssIntoPages--}
```
public boolean getSplitCssIntoPages()
```


When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue.

**Returns:**
boolean - boolean value
### setSplitCssIntoPages(boolean value) {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```


When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getSplitIntoPages() {#getSplitIntoPages--}
```
public boolean getSplitIntoPages()
```


Gets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages.

**Returns:**
boolean - boolean value
### setSplitIntoPages(boolean value) {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```


Sets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getFixedLayout() {#getFixedLayout--}
```
public boolean getFixedLayout()
```


Gets a value indicating whether that HTML is created as fixed layout.

**Returns:**
boolean - value:  true  if [fixed layout]; otherwise,  false .
### setFixedLayout(boolean value) {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```


Sets a value indicating whether that HTML is created as fixed layout.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | :  true  if [fixed layout]; otherwise,  false . |

### getFontSources() {#getFontSources--}
```
public FontSourceCollection getFontSources()
```


Font sources of pre-saved fonts.

**Returns:**
[FontSourceCollection](../../com.aspose.pdf.text/fontsourcecollection) - FontSourceCollection object

--------------------

Fonts may be saved preliminarily for cache purpose and then passed into Html conversion process. For example it may be useful in document splitting scenario and processing document pages in multiple threads with single set of fonts.
### getAdditionalMarginWidthInPoints() {#getAdditionalMarginWidthInPoints--}
```
public int getAdditionalMarginWidthInPoints()
```


If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. But each source PDF page will be represented with it's own rectangle area in HTML (if necessary that areas can be bordered to show page paper edges with special attribute 'PageBorderIfAny'. This parameter defines width of margin that will be forcibly left around that output HTML-areas that represent pages of source PDF document.In essence it defines guaranteed interval between HTML-representations of PDF "paper" pages such mode of conversion.

**Returns:**
int - int value
### setAdditionalMarginWidthInPoints(int value) {#setAdditionalMarginWidthInPoints-int-}
```
public void setAdditionalMarginWidthInPoints(int value)
```


If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont be not split into different HTML pages, but will be put into one big result HTML file. But each source PDF page will be represented with it's own rectangle area in HTML (if necessary that areas can be bordered to show page paper edges with special attribute 'PageBorderIfAny'. This parameter defines width of margin that will be forcibly left around that output HTML-areas that represent pages of source PDF document.In essence it defines guaranteed interval between HTML-representations of PDF "paper" pages such mode of conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### getUseZOrder() {#getUseZOrder--}
```
public boolean getUseZOrder()
```


If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. If this attribute is false all graphics is put as single layer which may cause some unnecessary effects for overlapped objects.

**Returns:**
boolean - boolean value
### setUseZOrder(boolean value) {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```


If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. If this attribute is false all graphics is put as single layer which may cause some unnecessary effects for overlapped objects.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getConvertMarkedContentToLayers() {#getConvertMarkedContentToLayers--}
```
public boolean getConvertMarkedContentToLayers()
```


If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML

with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content.

**Returns:**
boolean - boolean value
### setConvertMarkedContentToLayers(boolean value) {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```


If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML

with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getMinimalLineWidth() {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```


This attribute sets minimal width of graphic path line. If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can be used to emulate this behavior for HTML browsers.

**Returns:**
float - float value
### setMinimalLineWidth(float value) {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```


This attribute sets minimal width of graphic path line. If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can be used to emulate this behavior for HTML browsers.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | float | float value |

### getPreventGlyphsGrouping() {#getPreventGlyphsGrouping--}
```
public boolean getPreventGlyphsGrouping()
```


This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. This parameter will be applied to document only when the value of FixedLayout attribute is true.

**Returns:**
boolean - boolean value
### setPreventGlyphsGrouping(boolean value) {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```


This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. This parameter will be applied to document only when the value of FixedLayout attribute is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

