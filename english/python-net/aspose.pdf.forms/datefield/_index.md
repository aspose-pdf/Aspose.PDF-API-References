---
title: DateField
second_title: Aspose.PDF for Python via .NET API Reference
description: Date field with calendar view.
type: docs
weight: 60
url: /python-net/aspose.pdf.forms/datefield/
---

## DateField class

Date field with calendar view.

The DateField type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|DateField()|Initializes a new instance of the [DateField](/pdf/python-net/aspose.pdf.forms/datefield/)|
|DateField(doc)|Initializes a new instance of the DateField class|
|DateField(page, rect)|Initializes a new instance of the DateField class|
|DateField(doc, rect)|Initializes a new instance of the DateField class|
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
|value|Gets or sets Date.|
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
|date_format|Gets or sets the date format.|
## Indexer
| Name | Description |
| :- | :- |
|[index]|Gets subfield contained in this field by index.|
## Methods
| Name | Description |
| :- | :- |
|add_image(image)|Image adding denied for this field.|
|add_image(image)|Image adding denied for this field.|
|clone()|None|
|get_rectangle(consider_rotation)|None|
|accept(visitor)|None|
|flatten()|Removes this field and place its value directly on the page.|
|change_after_resize(transform)|None|
|recalculate()|Recaculates all calculated fields on the form.|
|copy_to(array, index)|Copies subfields of this field into array starting from specified index.|
|set_position(point)|Set position of the field.|
|add_barcode(code)|Adds barcode 128 into the field. <br/>            Field value will be changed onto the code and field become read only.|
|init(page)|Initializes the JS Action.|

### See Also

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

