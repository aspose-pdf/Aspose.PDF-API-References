---
title: "HtmlSaveOptions Class"
linktitle: "HtmlSaveOptions"
articleTitle: "HtmlSaveOptions"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.HtmlSaveOptions class. Save options for export to Html format"
type: docs
weight: 1190
url: "/net/aspose.pdf/htmlsaveoptions/"
keywords: "HtmlSaveOptions, Aspose.Pdf, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## HtmlSaveOptions class

Save options for export to Html format

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [HtmlSaveOptions](./htmlsaveoptions/#constructor) | Initializes a new instance of the [`HtmlSaveOptions`](../../aspose.pdf/htmlsaveoptions/) class. |
| [HtmlSaveOptions](./htmlsaveoptions/#constructor_1)(*[HtmlDocumentType](../../aspose.pdf/htmldocumenttype/)*) | Initializes a new instance of the [`HtmlSaveOptions`](../../aspose.pdf/htmlsaveoptions/) class. |
| [HtmlSaveOptions](./htmlsaveoptions/#constructor_2)(*bool*) | Initializes a new instance of the [`HtmlSaveOptions`](../../aspose.pdf/htmlsaveoptions/) class. |
| [HtmlSaveOptions](./htmlsaveoptions/#constructor_3)(*[HtmlDocumentType](../../aspose.pdf/htmldocumenttype/), bool*) | Initializes a new instance of the [`HtmlSaveOptions`](../../aspose.pdf/htmlsaveoptions/) class. |

## Properties

| Name | Description |
| --- | --- |
| [AdditionalMarginWidthInPoints](./additionalmarginwidthinpoints/) { get; set; } | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont. |
| [BatchSize](./batchsize/) { get; set; } | Defines batch size if batched conversion is applicable. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Gets or sets boolean value which indicates if will font glyphs be cached while preparing aps pages. *(Inherited from SaveOptions)* |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Gets or sets boolean value which indicates will Response object be closed after document saved into response. *(Inherited from SaveOptions)* |
| [CompressSvgGraphicsIfAny](./compresssvggraphicsifany/) { get; set; } | Gets or sets the flag that indicates whether. |
| [ConvertMarkedContentToLayers](./convertmarkedcontenttolayers/) { get; set; } | If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked. |
| [DefaultFontName](./defaultfontname/) { get; set; } | Specifies the name of an installed font which is used to substitute. |
| [DocumentType](./documenttype/) { get; set; } | Gets or sets the [`HtmlDocumentType`](../../aspose.pdf/htmldocumenttype/). |
| [ExplicitListOfSavedPages](./explicitlistofsavedpages/) { get; set; } | With this property You can explicitely define. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | This atrribute turned on functionality for extracting image or text. *(Inherited from UnifiedSaveOptions)* |
| [FixedLayout](./fixedlayout/) { get; set; } | Gets or sets a value indicating whether that HTML is created as fixed layout. |
| [FlowLayoutParagraphFullWidth](./flowlayoutparagraphfullwidth/) { get; set; } | This attribute specifies full width paragraph text for Flow mode, FixedLayout = false. |
| [FontSources](./fontsources/) { get; } | Font sources of pre-saved fonts. |
| [IgnoreResourceFontErrors](./ignoreresourcefonterrors/) { get; set; } | Gets or sets indication that errors related to absence of font will be ignored. |
| [IgnoredTextFontSize](./ignoredtextfontsize/) { get; set; } | Text with the specified size or less will be ignored during conversion. |
| [ImageResolution](./imageresolution/) { get; set; } | Gets or sets resolution for image rendering. |
| [MinimalLineWidth](./minimallinewidth/) { get; set; } | This attribute sets minimal width of graphic path line. |
| [PreventGlyphsGrouping](./preventglyphsgrouping/) { get; set; } | This attribute switch on the mode when text glyphs will not be grouped into words and strings. |
| [RenderTextAsImage](./rendertextasimage/) { get; set; } | If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Format of data save. *(Inherited from SaveOptions)* |
| [SaveFullFont](./savefullfont/) { get; set; } | Indicates that full font will be saved, supports only True Type Fonts. |
| [SimpleTextboxModeGrouping](./simpletextboxmodegrouping/) { get; set; } | This attribute specifies a sequential grouping of glyphs and words into strings. |
| [SplitCssIntoPages](./splitcssintopages/) { get; set; } | When multipage-mode selected(i.e 'SplitIntoPages' is 'true'),. |
| [SplitIntoPages](./splitintopages/) { get; set; } | Gets or sets the flag that indicates whether each page of source. |
| [Title](./title/) { get; set; } | Gets or sets HTML page title. |
| [TryMergeFragments](./trymergefragments/) { get; set; } | The flag for combining image fragments into one picture. |
| [UseZOrder](./usezorder/) { get; set; } | If attribute UseZORder set to true, graphics and text are added to resultant HTML document. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback to handle any warnings generated. *(Inherited from SaveOptions)* |

## Fields

| Name | Description |
| --- | --- |
| [AntialiasingProcessing](./antialiasingprocessing/) | This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML. |
| [CssClassNamesPrefix](./cssclassnamesprefix/) | When PDFtoHTML converter generates result CSSs, CSS class names. |
| [CustomCssSavingStrategy](./customcsssavingstrategy/) | This field can contain saving strategy. |
| [CustomHtmlSavingStrategy](./customhtmlsavingstrategy/) | Result of conversion can contain one or several HTML-pages. |
| [CustomProgressHandler](./customprogresshandler/) | This handler can be used to handle conversion progress events. |
| [CustomResourceSavingStrategy](./customresourcesavingstrategy/) | This field can contain saving strategy. |
| [CustomStrategyOfCssUrlCreation](./customstrategyofcssurlcreation/) | This field can contain custom method that returns. |
| [ExcludeFontNameList](./excludefontnamelist/) | List of PDF embedded font names that not be embedded in HTML. |
| [FontEncodingStrategy](./fontencodingstrategy/) | Defines encoding special rule to tune PDF decoding for current document. |
| [FontSavingMode](./fontsavingmode/) | Defines font saving mode that will be used during saving of PDF to desirable format. |
| [HtmlMarkupGenerationMode](./htmlmarkupgenerationmode/) | Sometimes specific reqirments to generation of HTML markup are present. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Process pages in few threads. *(Inherited from UnifiedSaveOptions)* |
| [LettersPositioningMethod](./letterspositioningmethod/) | Sets mode of positioning of letters in words in result HTML. |
| [PageBorderIfAny](./pageborderifany/) | This attribute represents set of settings used for drawing border (if any). |
| [PageMarginIfAny](./pagemarginifany/) | This attribute represents set of extra page margin (if any). |
| [PagesFlowTypeDependsOnViewersScreenSize](./pagesflowtypedependsonviewersscreensize/) | If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be. |
| [PartsEmbeddingMode](./partsembeddingmode/) | It defines whether referenced files (HTML, Fonts,Images, CSSes). |
| [RasterImagesSavingMode](./rasterimagessavingmode/) | Converted PDF can contain raster images. |
| [RemoveEmptyAreasOnTopAndBottom](./removeemptyareasontopandbottom/) | Defines whether in created HTML will be removed top and bottom empty area without any content (if any). |
| [SaveShadowedTextsAsTransparentTexts](./saveshadowedtextsastransparenttexts/) | Pdf can contain texts that are shadowed by another elements (f.e. by images) but. |
| [SaveTransparentTexts](./savetransparenttexts/) | Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it). |
| [SpecialFolderForAllImages](./specialfolderforallimages/) | Gets or sets path to directory to which must be saved any images if they. |
| [SpecialFolderForSvgImages](./specialfolderforsvgimages/) | Gets or sets path to directory to which must be saved only SVG-images if they. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Sometimes PDFs contain background images (of pages or table cells). *(Inherited from UnifiedSaveOptions)* |
| [TrySaveTextUnderliningAndStrikeoutingInCss](./trysavetextunderliningandstrikeoutingincss/) | PDF itself does not contain underlining markers for texts. It emulated with line situated under text. |

### See Also

* class [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)

