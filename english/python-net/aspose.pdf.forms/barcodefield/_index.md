---
title: BarcodeField
second_title: Aspose.PDF for Python via .NET API Reference
description: Class represents barcode field.
type: docs
weight: 10
url: /python-net/aspose.pdf.forms/barcodefield/
---

## BarcodeField class

Class represents barcode field.

The BarcodeField type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|BarcodeField(page, rect)|Initializes a new instance of the BarcodeField class|
|BarcodeField(doc, rect)|Initializes a new instance of the BarcodeField class|
## Properties
| Name | Description |
| :- | :- |
|vertical_alignment|None|
|horizontal_alignment|None|
|margin|None|
|is_first_paragraph_in_column|None|
|is_kept_with_next|None|
|is_in_new_page|None|
|is_in_line_paragraph|None|
|hyperlink|None|
|z_index|None|
|update_appearance_on_convert|None|
|use_font_subset|None|
|flags|None|
|annotation_type|None|
|width|None|
|actions|None|
|height|None|
|rect|Gets or sets the field rectangle.|
|contents|None|
|name|None|
|modified|None|
|color|None|
|border|None|
|active_state|None|
|characteristics|None|
|states|None|
|alignment|None|
|text_horizontal_alignment|None|
|full_name|None|
|appearance|None|
|page_index|Gets index of page which contains this field.|
|on_activated|None|
|highlighting|None|
|parent|None|
|default_appearance|None|
|read_only|None|
|required|None|
|exportable|None|
|partial_name|Gets or sets partial name of the field.|
|alternate_name|Gets or sets alternate name of the field (An alternate field <br/>            name that shall be used in place of the actual field name <br/>            wherever the field shall be identified in the user interface).<br/>            Alternate name is used as field tooltip in Adobe Acrobat.|
|mapping_name|Gets or sets mapping name  of the field that shall be used when exporting interactive form field data from the document.|
|value|Gets or sets value of the field.|
|is_synchronized|Returns true if dictionary is synchronized.|
|sync_root|Synchronization object.|
|is_group|Gets or sets boolean value which indicates is this field non-terminal field i.e. group of fields.|
|annotation_index|Gets or sets index of this anotation on the page.|
|is_shared_field|Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page.|
|fit_into_rectangle|If true then font size will reduced to fit text to specified rectangle.|
|max_font_size|Maximail font size which can be used for field contents. -1 to don't check size.|
|min_font_size|Minimal font size which can be used for field contents. -1 to don't check size.|
|tab_order|Gets or sets tab order of the field.|
|multiline|Gets or sets multiline flag of the field. If Multiline is true field can contain multiple lines of text.|
|spell_check|Gets or sets spellcheck flag for field. If true field shall be spell checked.|
|scrollable|Gets or sets scrollable flag of field. If true field can be scrolled.|
|force_combs|Gets or sets flag which indicates is field divided into spaced positions.|
|max_len|Gets or sets maximum length of text in the field.|
|text_vertical_alignment|Gets or sets text vertical alignment for annotation.|
|resolution|Gets the resolution, in dots-per-inch (dpi), at which the barcode object is rendered.|
|caption|Gets the caption of the barcode object.|
|symbology|Specifies which barcode or glyph technology is to be used on this annotation,<br/>            see [symbology](/pdf/python-net/aspose.pdf.forms/barcodefield/) for details.|
|x_sym_width|Gets The horizontal distance, in pixels, between two barcode modules.|
|x_sym_height|Gets the the vertical distance between two barcode modules, measured in pixels. <br/>            The ratio XSymHeight/XSymWidth shall be an integer value. <br/>            For PDF417, the acceptable ratio range is from 1 to 4. For QRCode and DataMatrix, <br/>            this ratio shall always be 1|
|ecc|Gets an integer value representing the error correction coefficient. <br/>            For PDF417, shall be from 0 to 8. For QRCode, shall be from 0 to 3 <br/>            (0 for �L�, 1 for �M�, 2 for �Q�, and 3 for �H�).|
## Indexer
| Name | Description |
| :- | :- |
|[index]|Gets subfield contained in this field by index.|
## Methods
| Name | Description |
| :- | :- |
|clone()|None|
|get_rectangle(consider_rotation)|None|
|accept(visitor)|None|
|flatten()|Removes this field and place its value directly on the page.|
|change_after_resize(transform)|None|
|recalculate()|Recaculates all calculated fields on the form.|
|copy_to(array, index)|Copies subfields of this field into array starting from specified index.|
|set_position(point)|Set position of the field.|
|add_image(image)|Adds image into the field resources an draws it.|
|add_barcode(code)|Adds barcode 128 into the field. <br/>            Field value will be changed onto the code and field become read only.|

### See Also

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

