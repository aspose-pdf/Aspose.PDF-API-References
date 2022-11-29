---
title: HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Save options for export to Html format
type: docs
weight: 3440
url: /net/aspose.pdf/htmlsaveoptions/
---
## HtmlSaveOptions class

Save options for export to Html format

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions#constructor)() | Initializes a new instance of the [`HtmlSaveOptions`](../htmlsaveoptions) class. |
| [HtmlSaveOptions](htmlsaveoptions#constructor_3)(bool) | Initializes a new instance of the [`HtmlSaveOptions`](../htmlsaveoptions) class. |
| [HtmlSaveOptions](htmlsaveoptions#constructor_1)(HtmlDocumentType) | Initializes a new instance of the [`HtmlSaveOptions`](../htmlsaveoptions) class. |
| [HtmlSaveOptions](htmlsaveoptions#constructor_2)(HtmlDocumentType, bool) | Initializes a new instance of the [`HtmlSaveOptions`](../htmlsaveoptions) class. |

## Properties

| Name | Description |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize) { get; set; } | Defines batch size if batched conversion is applicable to source and destination formats pair. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany) { get; set; } | Gets or sets the flag that indicates whether found SVG graphics(if any) will be compressed(zipped) into SVGZ format during saving |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers) { get; set; } | If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name. This layer name will be extracted from optional properties of PDF marked content. If this attribute is false (by default) then no any layers will be created from PDF marked content. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname) { get; set; } | Specifies the name of an installed font which is used to substitute any document font that is not embedded and not installed in the system. If null then default substitution font is used. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype) { get; set; } | Gets or sets the [`HtmlDocumentType`](../htmldocumenttype). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages) { get; set; } | With this property You can explicitely define what pages of document should be converted. Pages in this list must have 1-based numbers. I.e. valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument]) Order of appearing of pages in this list does not affect their order in result HTML page(s) - in result pages allways will go in order in which they are present in source PDF. If this list is null (as it is by default), all pages will be converted. If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument]) exception will be thrown. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly) { get; set; } | This atrribute turned on functionality for extracting image or text for PDF documents with OCR sublayer. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout) { get; set; } | Gets or sets a value indicating whether that HTML is created as fixed layout. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth) { get; set; } | This attribute specifies full width paragraph text for Flow mode, FixedLayout = false |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources) { get; } | Font sources of pre-saved fonts. |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution) { get; set; } | Gets or sets resolution for image rendering. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth) { get; set; } | This attribute sets minimal width of graphic path line. If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can be used to emulate this behavior for HTML browsers. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping) { get; set; } | This attribute switch on the mode when text glyphs will not be grouped into words and strings This mode allows to keep maximum precision during positioning of glyphs on the page and it can be used for conversion documents with music notes or glyphs that should be placed separately each other. This parameter will be applied to document only when the value of FixedLayout attribute is true. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage) { get; set; } | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. May be useful to make text unselectable or HTML text is not rendered properly. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat) { get; } | Format of data save. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping) { get; set; } | This attribute specifies a sequential grouping of glyphs and words into strings For example tags and words has different order in converted HTML and you want them to match. This parameter will be applied to document only when the value of FixedLayout attribute is true. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages) { get; set; } | When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), then this attribute defines whether should be created separate CSS-file for each result HTML page. By default this attribute is false, so, will be created one big common CSS for all created pages. Summary size of all CSSes generated in this mode(one CSS per page) usually much more than size of one big CSS file, because in former case CSS classes are duplicates in such case in several CSS files for each page. So, this setting is worse to be used only when You are interested in future processing of each HTML page independently, and therefore size of CSS of each one page taken apart is the most critical issue. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages) { get; set; } | Gets or sets the flag that indicates whether each page of source document will be converted into it's own target HTML document, i.e whether result HTML will be splitted into several HTML-pages. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder) { get; set; } | If attribute UseZORder set to true, graphics and text are added to resultant HTML document accordingly Z-order in original PDF document. If this attribute is false all graphics is put as single layer which may cause some unnecessary effects for overlapped objects. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler) { get; set; } | Callback to handle any warnings generated. The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease. |

## Fields

| Name | Description |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing) | This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix) | When PDFtoHTML converter generates result CSSs, CSS class names (something like ".stl_01 {}" ... ".stl_NN {}) are generated and used in result CSS. This property allows forcibly set class name prefix For example, if You want that all class names start with 'my_prefix_' (i.e. were something like 'my_prefix_1' ... 'my_prefix_NNN' ) , then just assign 'my_prefix_' to this property before conversion. If this property will stay untouched(i.e. null will be leaved as value ), then converter will generate class names itself (it wil be something like ".stl_01 {}" ... ".stl_NN {}") |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy) | This field can contain saving strategy that must be used (if present) during conversion of Pdf to Html for handling of saving of CSSes related to created HTML document as whole or to it's pages(if several HTMLpages are generated) If You want handle CSS file in some specific way, that just please create relevant method and assign delegate created from it to this property. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy) | Result of conversion can contain one or several HTML-pages You can assign to this property delegate created from custom method that implements processing of one HTML-page(to be accurately - markup-HTML, without exteranl linked files if any) that was created during conversion. In such case processing (like saving of paage's HTML in stream or disk) can be done in that custom code . In such case all the necessary actions for saving of HTML page must be undertaken in code of supplied method, because saving of result in code of converter will be not in use . If processing for this or that case for some reason must be done by converter's code itself, not in custom code, please set in custom code flag 'CustomProcessingCancelled' of 'htmlSavingInfo' parameter's variable : it will signal to converter that all the necessary steps for processing of that resource must be done in converter itself in same way as if there was no any external custom code for procesing . |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler) | This handler can be used to handle conversion progress events f.e. it can be used to show progress bar or messages about current amount of processed pages, example of handler's code that shows progress on console is : |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy) | This field can contain saving strategy that must be used (if present) during conversion for customized handling of created referenced resource files (like images and fonts) related to nodes of saved HTML. That strategy must process resources and return string that represents desirable URL of saved resource in generated HTML. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation) | This field can contain custom method that returns URL (Or URL template if multipage generation is on - see details below) of subject CSS as it should be put in generated result HTML. F.e. if You want converter put some specific URL instead of standard CSS file name into generated CSS, then You should just create and put into this property method that generates desirable URL. If flag 'SplitCssIntoPages' set, then this custom strategy (if any) must return not exact URL of CSS but rather template string that (after substitution of placeholder with page number with string.Format() function inside converter) can be resolved into URL for this or that page's CSS' URL. Examples of expected return string in such case are: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist) | List of PDF embedded font names that not be embedded in HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy) | Defines encoding special rule to tune PDF decoding for current document |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode) | Defines font saving mode that will be used during saving of PDF to desirable format |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode) | Sometimes specific reqirments to generation of HTML markup are present. This parameter defines HTML preparing modes that can be used during conversion of PDF to HTML to match such specific requirments. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod) | Sets mode of positioning of letters in words in result HTML |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany) | This attribute represents set of settings used for drawing border (if any) in result HTML document around area that represent source PDF page. In essence it concerns of showing of page's paper edges, not page border referenced in PDF page itself. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany) | This attribute represents set of extra page margin (if any) in result HTML document around area that represent source PDF page. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be put into one big result HTML file. This flag defines whether result HTML will be generated in such way that flow of areas that represent PDF pages in result HTML will depend on screen resolution of viewer. Suppose width of screen on viewer side is big enough to put 2 or more pages one near other in horizontal direction. If this flag set to true, then this opportunity will be used (as many pages will be shown in horizontal direction one near another as it possible, then next horizontal group of pages will be shown under first one ). Otherwise pages will flow in such way: next page goes always under previous one. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode) | It defines whether referenced files (HTML, Fonts,Images, CSSes) will be embedded into main HTML file or will be generated as apart binary entities |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode) | Converted PDF can contain raster images This parameter defines how they should be handled during conversion of PDF to HTML |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom) | Defines whether in created HTML will be removed top and bottom empty area without any content (if any). |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont) | Indicates that full font will be saved, supports only True Type Fonts. By default SaveFullFont = false and the converter saves the subset of the initial font needed to display the text of the document. |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts) | Pdf can contain texts that are shadowed by another elements (f.e. by images) but can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML to mimic behaviour of Acrobat Reader (othervise such texts are usually saved as hidden, not available for copying to clipboard) |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts) | Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). This settings tells to converter whether we need save such texts as transparent selectable texts in result HTML |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages) | Gets or sets path to directory to which must be saved any images if they are encountered during saving of document as HTML. If parameter is empty or null then image files(if any) wil be saved together with other files linked to HTML It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages) | Gets or sets path to directory to which must be saved only SVG-images if they are encountered during saving of document as HTML. If parameter is empty or null then SVG files(if any) wil be saved together with other image-files (near to output file) or in special folder for images (if it specified in SpecialImagesFolderIfAny option). It does not affect anything if CustomImageSavingStrategy property was successfully used to process relevant image file. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages) | Sometimes PDFs contain background images (of pages or table cells) constructed from several same tiling background images put one near other. In such case renderers of target formats (f.e MsWord for DOCS format) sometimes generates visible boundaries beetween parts of background images, cause their techniques of image edge smoothing (anti-aliasing) is different from Acrobat Reader. If it looks like exported document contains such visible boundaries between parts of same background images, please try use this setting to get rid of that unwanted effect. ATTENTION! This optimization of quality usually essentially slows down conversion, so, please, use this option only when it's really necessary. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss) | PDF itself does not contain underlining markers for texts. It emulated with line situated under text. This option allows converter try guess that this or that line is a text's underlining and put this info into CSS instead of drawing of underlining graphically |

## Examples

The following example shows how to convert PDF file to HTML file

```csharp
[C#]
// The path to the documents directory.
string dataDir = "YOUR_DATA_DIRECTORY";
// The path to your PDF File.
var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");
// The path to output HTML File.
var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
    
using (Document pdfDocument = new Document(pdfFile)){
    // initialize HtmlSaveOptions 	
    HtmlSaveOptions saveOptions = new HtmlSaveOptions();
    
    // Save HTML file
    pdfDocument.Save(htmlFile, saveOptions);
}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf")
    ' The path to output HTML File.
    Dim htmlFile = Path.Combine(dataDir, "PDF-to-HTML.html")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' initialize HtmlSaveOptions    
        Dim saveOptions As HtmlSaveOptions = New HtmlSaveOptions()
 
        ' Save HTML file
        pdfDocument.Save(htmlFile, saveOptions)
    End Using
```

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions)
* interface [IPageSetOptions](../ipagesetoptions)
* interface [IPipelineOptions](../ipipelineoptions)
* namespace [Aspose.Pdf](../../aspose.pdf)
* assembly [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
