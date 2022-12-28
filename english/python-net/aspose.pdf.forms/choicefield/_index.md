---
title: ChoiceField
second_title: Aspose.PDF for Python via .NET API Reference
description: Represents base class for choice fields.
type: docs
weight: 40
url: /python-net/aspose.pdf.forms/choicefield/
---

## ChoiceField class

Represents base class for choice fields.

The ChoiceField type exposes the following members:
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
|annotation_type|Gets type of annotation.|
|width|None|
|actions|Gets the annotation actions.|
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
|on_activated|An action which shall be performed when the annotation is activated.|
|highlighting|Annotation highlighting mode.|
|parent|Gets annotation parent.|
|default_appearance|Gets or sets default appearance of the field.|
|read_only|Gets or sets read only status of the field.|
|required|Gets or sets required status of the field.|
|exportable|Gets or sets exportable flag of the field.|
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
|commit_immediately|Gets or sets commit on selection change flag.|
|multi_select|Gets or sets multiselection flag.|
|selected|Gets or sets index of selected option. This property allows to change selection.|
|selected_items|Gets or sets array of selected items. For multiselect list array contains more then one item. For single selection list it contains single item.|
|options|Gets collection of choice options.|
## Indexer
| Name | Description |
| :- | :- |
|[index]|Gets subfield contained in this field by index.|
## Methods
| Name | Description |
| :- | :- |
|add_option(option_name)|Adds new option with specified name.|
|add_option(export, name)|Adds new option with specified name.|
|clone()|None|
|get_rectangle(consider_rotation)|None|
|accept(visitor)|Accepts visitor.|
|flatten()|Removes this field and place its value directly on the page.|
|change_after_resize(transform)|None|
|recalculate()|Recaculates all calculated fields on the form.|
|copy_to(array, index)|Copies subfields of this field into array starting from specified index.|
|set_position(point)|Set position of the field.|
|delete_option(option_name)|Deletes option by its name.|

### See Also

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

