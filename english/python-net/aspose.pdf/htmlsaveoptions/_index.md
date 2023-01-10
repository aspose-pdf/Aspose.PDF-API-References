---
title: HtmlSaveOptions
second_title: Aspose.PDF for Python via .NET API Reference
description: Save options for export to Html format
type: docs
weight: 490
url: /python-net/aspose.pdf/htmlsaveoptions/
---

## HtmlSaveOptions class

Save options for export to Html format

The HtmlSaveOptions type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|HtmlSaveOptions()|Initializes a new instance of the [HtmlSaveOptions](/pdf/python-net/aspose.pdf/htmlsaveoptions/) class.|
|HtmlSaveOptions(document_type)|Initializes a new instance of the HtmlSaveOptions class|
|HtmlSaveOptions(fixed_layout)|Initializes a new instance of the HtmlSaveOptions class|
|HtmlSaveOptions(document_type, fixed_layout)|Initializes a new instance of the HtmlSaveOptions class|
## Properties
| Name | Description |
| :- | :- |
|warning_handler|Callback to handle any warnings generated. <br/>            The WarningHandler returns ReturnAction enum item specifying either Continue or Abort. <br/>            Continue is the default action and the Save operation continues, however the user may also return Abort in which case the Save operation should cease.|
|save_format|Format of data save.|
|close_response|Gets or sets boolean value which indicates will Response object be closed after document saved into response.|
|extract_ocr_sublayer_only|None|
|try_merge_adjacent_same_background_images|None|
|document_type|Gets or sets the [HtmlDocumentType](/pdf/python-net/aspose.pdf/htmldocumenttype/).|
|compress_svg_graphics_if_any|Gets or sets the flag that indicates whether<br/>            found SVG graphics(if any) will be compressed(zipped) <br/>            into SVGZ format during saving|
|split_css_into_pages|When multipage-mode selected(i.e 'SplitIntoPages' is 'true'), <br/>            then this attribute defines whether should be created separate CSS-file<br/>            for each result HTML page.<br/>            By default this attribute is false, so, will be created<br/>            one  big common CSS for all created pages. Summary size of all<br/>            CSSes generated in this mode(one CSS per page) usually<br/>            much more than size of one big CSS file, because in former case <br/>            CSS classes are duplicates in such case in several CSS files for each page.<br/>            So, this setting is worse to be used only when You are interested<br/>            in future processing of each HTML page independently, and therefore size<br/>            of CSS of each one page taken apart is the most critical issue.|
|split_into_pages|Gets or sets the flag that indicates whether each page of source <br/>            document will be converted into it's own target HTML document, <br/>            i.e whether result HTML will be splitted into several HTML-pages.|
|explicit_list_of_saved_pages|With this property You can explicitely define <br/>            what pages of document should be converted.<br/>            Pages in this list must have 1-based numbers. I.e. <br/>            valid numbers of pages must be taken from range (1...[NumberOfPagesInConvertedDocument])<br/>            Order of appearing of pages in this list does not affect their<br/>            order in result HTML page(s) - in result pages allways will go in order in which they are <br/>            present in source PDF.<br/>            If this list is null (as it is by default), all pages will be converted.<br/>            If any page number of this list will go out of range of present pages(1-[amountOfPagesInDocument])<br/>            exception will be thrown.|
|fixed_layout|Gets or sets a value indicating whether that HTML is created as fixed layout.|
|image_resolution|Gets or sets resolution for image rendering.|
|default_font_name|Specifies the name of an installed font which is used to substitute<br/>            any document font that is not embedded and not installed in the system. <br/>            If null then default substitution font is used.|
|batch_size|Defines batch size if batched conversion is applicable<br/>            to source and destination formats pair.|
|font_sources|Font sources of pre-saved fonts.|
|additional_margin_width_in_points|If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages wont<br/>            be not split into different HTML pages, but will be put into one big result HTML file.<br/>            But each source PDF page will be represented with it's own <br/>            rectangle  area in HTML (if necessary that areas can be bordered to show page paper edges<br/>            with special attribute 'PageBorderIfAny'.<br/>            This parameter defines width of margin that will be forcibly left around that output HTML-areas<br/>            that represent pages of source PDF document.In essence it defines guaranteed interval between<br/>            HTML-representations of PDF "paper" pages such mode of conversion.|
|use_z_order|If attribute UseZORder set to true, graphics and text are added to resultant HTML document<br/>            accordingly Z-order in original PDF document. If this attribute is false all graphics is put<br/>            as single layer which may cause some unnecessary effects for overlapped objects.|
|convert_marked_content_to_layers|If attribute ConvertMarkedContentToLayers set to true then an all elements inside a PDF marked<br/>            content (layer) will be put into an HTML div with "data-pdflayer" attribute specifying a layer name.<br/>            This layer name will be extracted from optional properties of PDF marked content.<br/>            If this attribute is false (by default) then no any layers will be created from PDF marked content.|
|minimal_line_width|This attribute sets minimal width of graphic path line.<br/>            If thickness of line is less than 1px Adobe Acrobat rounds it to this value. So this attribute can<br/>            be used to emulate this behavior for HTML browsers.|
|prevent_glyphs_grouping|This attribute switch on the mode when text glyphs will not be grouped into words and strings<br/>            This mode allows to keep maximum precision during positioning of glyphs on the page and it can be<br/>            used for conversion documents with music notes or glyphs that should be placed separately each other.<br/>            This parameter will be applied to document only when the value of FixedLayout attribute is true.|
|simple_textbox_mode_grouping|This attribute specifies a sequential grouping of glyphs and words into strings<br/>            For example tags and words has different order in converted HTML and you want them to match.<br/>            This parameter will be applied to document only when the value of FixedLayout attribute is true.|
|flow_layout_paragraph_full_width|This attribute specifies full width paragraph text for Flow mode, FixedLayout = false|
|render_text_as_image|If attribute RenderTextAsImage set to true, the text from the source becomes an image in HTML.<br/>            May be useful to make text unselectable<br/>            or HTML text is not rendered properly.|
|save_full_font|Indicates that full font will be saved, supports only True Type Fonts.<br/>            By default SaveFullFont = false and the converter saves the subset of the initial font<br/>            needed to display the text of the document.|
|antialiasing_processing|This parameter defines required antialiasing measures during conversion of compound background images from PDF to HTML|
|save_transparent_texts|Pdf can contain transparent texts that can be selected to clipboard (usually it happen when document contains images and OCRed texts extracted from it).<br/>            This settings tells to converter whether we need save such texts as transparent<br/>            selectable texts in result HTML|
|save_shadowed_texts_as_transparent_texts|Pdf can contain texts that are shadowed by another elements (f.e. by images) but <br/>            can be selected to clipboard in Acrobat Reader (usually it happen when document contains images and OCRed texts extracted from it).<br/>            This settings tells to converter whether we need save such texts as transparent<br/>            selectable texts in result HTML to mimic behaviour of Acrobat Reader (othervise such texts are usually saved as hidden, not available for copying to clipboard)|
|font_saving_mode|Defines font saving mode that will be used during saving of PDF to desirable format|
|page_border_if_any|This attribute represents set of settings used for drawing border (if any)<br/>            in result HTML document around area that represent source PDF page.<br/>            In essence it concerns of showing of page's paper edges,<br/>            not page border referenced in PDF page itself.|
|page_margin_if_any|This attribute represents set of extra page margin (if any)<br/>            in result HTML document around area that represent source PDF page.|
|letters_positioning_method|Sets mode of positioning of letters in words in result HTML|
|exclude_font_name_list|List of PDF embedded font names that not be embedded in HTML.|
|special_folder_for_svg_images|Gets or sets path to directory to which must be saved only SVG-images if they <br/>            are encountered during saving of document as HTML. If parameter is empty or null<br/>            then SVG files(if any) wil be saved together with other image-files (near to output file)<br/>            or in special folder for images (if it specified in SpecialImagesFolderIfAny option).<br/>            It does not affect anything if CustomImageSavingStrategy<br/>            property was successfully used to process relevant image file.|
|special_folder_for_all_images|Gets or sets path to directory to which must be saved any images if they <br/>            are encountered during saving of document as HTML. If parameter is empty or null<br/>            then image files(if any) wil be saved together with other files linked to HTML<br/>            It does not affect anything if CustomImageSavingStrategy<br/>            property was successfully used to process relevant image file.|
|css_class_names_prefix|When PDFtoHTML converter generates result CSSs, CSS class names<br/>            (something like ".stl_01 {}" ... ".stl_NN {}) are generated<br/>            and used in result CSS. This property allows forcibly set class name prefix<br/>            For example, if You want that all class names start with 'my_prefix_'<br/>            (i.e. were something like 'my_prefix_1' ... 'my_prefix_NNN' ) , <br/>            then just assign 'my_prefix_' to this property before conversion.<br/>            If this property will stay untouched(i.e. null will be leaved as value ), then<br/>            converter will generate class names itself <br/>            (it wil be something like ".stl_01 {}" ... ".stl_NN {}")|
|parts_embedding_mode|It defines whether referenced files (HTML, Fonts,Images, CSSes)<br/>            will be embedded into main HTML file or will be generated as apart binary entities|
|html_markup_generation_mode|Sometimes specific reqirments to generation of HTML markup are present.<br/>            This parameter defines HTML preparing modes that can be used<br/>            during conversion of PDF to HTML to match such specific requirments.|
|raster_images_saving_mode|Converted PDF can contain raster images<br/>            This parameter defines how they should be handled<br/>            during conversion of PDF to HTML|
|remove_empty_areas_on_top_and_bottom|Defines whether in created HTML will be removed top and bottom empty area without any content (if any).|
|font_encoding_strategy|Defines encoding special rule to tune PDF decoding for current document|
|pages_flow_type_depends_on_viewers_screen_size|If attribute 'SplitOnPages=false', than whole HTML representing all input PDF pages will be <br/>            put into one big result HTML file. <br/>            This flag defines whether result HTML will be generated in such way<br/>            that flow of areas that represent PDF pages in result HTML will depend<br/>            on screen resolution of viewer. <br/>            Suppose width of screen on viewer side is big enough to put 2 or more pages one near<br/>            other in horizontal direction. If this flag set to true, then this opportunity<br/>            will be used (as many pages will be shown  in horizontal direction one near another<br/>            as it possible, then next horizontal group of pages will be shown under first one ).<br/>            Otherwise pages will flow in such way: next page goes always under previous one.|
|try_save_text_underlining_and_strikeouting_in_css|PDF itself does not contain underlining markers for texts. It emulated with line situated under text.<br/>            This option allows converter try guess that this or that line is a text's underlining<br/>            and put this info into CSS instead of drawing of underlining graphically|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

