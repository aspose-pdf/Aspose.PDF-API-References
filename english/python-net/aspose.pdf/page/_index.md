---
title: Page
second_title: Aspose.PDF for Python via .NET API Reference
description: Class representing page of PDF document.
type: docs
weight: 1080
url: /python-net/aspose.pdf/page/
---

## Page class

Class representing page of PDF document.

The Page type exposes the following members:
## Properties
| Name | Description |
| :- | :- |
|is_add_paragraphs_after_last|Gets or sets the addition of paragraphs after the last paragraph of the page|
|background_image|Gets or sets background image for page (for generator only, not filled in when reading document).|
|toc_info|Gets or sets table of contents info.|
|header|Gets or sets page header.|
|layers|Gets or sets layers collection.|
|footer|Gets or sets page footer.|
|paragraphs|Gets the paragraphs.|
|page_info|Gets or sets the page info (for generator only, not filled in when reading document).|
|rect|Gets or sets rectangle of the page.<br/>            For get: page crop box is returned if specified, otherwise page media box is returned.<br/>            For set: page media box always set.<br/>            Please note that this property don't consider page rotation. To get page rectangle considering rotation please use ActualRect.|
|color_type|Sets color type of the pages based on information getting from operators SetColor,<br/>            images and forms.|
|note_line_style|Gets or sets the line style for notes.(for generator only, not filled in when reading document)|
|tab_order|Gets or sets tab order of the page. <br/>            Possible values: Row, Column. Default, Manual|
|duration|Gets of set page display duration. This is time in seconds that page shall be displayed during presentation.<br/>            Returs -1 if duration is not defined.|
|contents|Gets collection of operators in the content stream of the page.<br/>            [OperatorCollection](/pdf/python-net/aspose.pdf/operatorcollection/)|
|group|Gets or sets a group attributes class specifying the attributes of the page�s page group for use in the transparent imaging model.|
|annotations|Gets collection of page annotations.<br/>            [annotations](/pdf/python-net/aspose.pdf/page/)|
|resources|Gets page resources. Resources object contains collections of images, forms and fonts.<br/>            [resources](/pdf/python-net/aspose.pdf/page/)|
|rotate|Gets or sets rotation of the page.|
|trim_box|Gets or sets trim box of the page.|
|art_box|Gets or sets art box of the page.|
|bleed_box|Gets or sets bleed box of the page.|
|crop_box|Gets or sets crop box of the page.|
|media_box|Gets or sets media box of the page.|
|number|Get number of the page.|
|rotation_matrix|Gets transofmation matrix for the page.|
|background|Gets or sets the background color of the page.|
|watermark|Gets or sets the watermark of the page.|
|artifacts|Gets collection of artifacts on the page.|
|actions|Gets collection of page properties.|
|fields_in_tab_order|Gets list of Field object in Tab order on this page.|
|user_unit|Gets or sets UserUnit value. A positive number giving the size of default user space units, in multiples of 1 ⁄ 72 inch.<br/>            Default value is 1. Please set zero or negative value in order to clear this entry in page.|
## Methods
| Name | Description |
| :- | :- |
|send_to(device, output)|Sends page to process with given page device.|
|send_to(device, output_file_name)|Sends page to process with given page device.|
|accept(visitor)|Accepts [AnnotationSelector](/pdf/python-net/aspose.pdf.annotations/annotationselector/) visitor object that provides functionality to work with annotations.|
|accept(visitor)|Accepts [TextFragmentAbsorber](/pdf/python-net/aspose.pdf.text/textfragmentabsorber/) visitor object that provides functionality to work with text objects.|
|accept(visitor)|Accepts [ImagePlacementAbsorber](/pdf/python-net/aspose.pdf/imageplacementabsorber/) visitor object that provides functionality to work with image placement objects.|
|accept(visitor)|Accepts [TextAbsorber](/pdf/python-net/aspose.pdf.text/textabsorber/) visitor object that provides functionality to work with text objects.|
|add_image(image_stream, image_rect)|Adds image onto the page and locates it in the middle of specified rectangle saving image's proportion.|
|add_image(hocr, image_stream, image_rect)|Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion.|
|add_image(image_stream, image_rect, image_width, image_height, save_image_proportions)|Adds image on page and places it depend on image rectangle position.|
|add_image(image_path, rectangle)|Adds searchable image onto the page and locates it in the middle of specified rectangle saving image's proportion.|
|is_blank(fill_threshold_factor)|Gets the flag whether page is blank or not.|
|get_page_rect(consider_rotation)|Returns rectangle of the page according to its CropBox (or MediaBox if CropBox null).|
|calculate_content_b_box()|Calculates bbox value - rectangle containing contents without visible margins.|
|rotation_to_int(rotation)|Translates rotation enumeration member into integer value.|
|int_to_rotation(rotation)|Translates integer value into corresponding rotation enumeration member.|
|add_stamp(stamp)|Put stamp into page. Stamp can be page number, image or simple text, e.g. some logo.|
|flatten()|Removes all fields located on the page and place their values instead.|
|set_page_size(width, height)|Sets page size for page.|
|make_grayscale()|Converts the page to grayscale.|
|free_memory()|Clears cached data|
|get_notifications()|Returns notifications about inside operations with page content. (Only notifications about paragraph events in text adding scenarios are supported now.)|
|as_byte_array(resolution)|Converts current page as bitmap and than returns array of bytes.|
|as_xml()|Converts current page as xml in utf8 encoding.|

### See Also

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

