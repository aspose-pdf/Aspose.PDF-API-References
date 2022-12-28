---
title: FormEditor
second_title: Aspose.PDF for Python via .NET API Reference
description: Class for editing forms (ading/deleting field etc)
type: docs
weight: 110
url: /python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

Class for editing forms (ading/deleting field etc)

The FormEditor type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|FormEditor(src_stream, dest_stream)|Initializes a new instance of the FormEditor class|
|FormEditor(src_file_name, dest_file_name)|Initializes a new instance of the FormEditor class|
|FormEditor()|Constructor for FormEditor.|
|FormEditor(document)|Initializes a new instance of the FormEditor class|
|FormEditor(document, dest_file_name)|Initializes a new instance of the FormEditor class|
|FormEditor(document, dest_stream)|Initializes a new instance of the FormEditor class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|src_file_name|Gets or sets name of source file.|
|dest_file_name|Gets or sets destination file name.|
|src_stream|Gets or sets source stream.|
|dest_stream|Gets or sets destination stream.|
|items|Sets items which will be added t onewly created list box or combo box.|
|export_items|Sets options for combo box with export values.|
|facade|Sets visual attributes of the field.|
|radio_gap|The member to record the gap between two neighboring radio buttons in pixels,default is 50.|
|radio_horiz|The flag to indicate whether the radios are arranged horizontally or vertically, default value is true.|
|radio_button_item_size|Gets or sets size of radio button item size (when new radio button field is added).|
|submit_flag|Set the submit button's submission flags|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(src_file)|Binds PDF document for editing.|
|bind_pdf(src_stream)|Binds PDF document for editing.|
|bind_pdf(src_doc)|Binds PDF document for editing.|
|save()|Saves changes into destination file.|
|save(dest_file)|Saves changes into destination file.|
|save(dest_stream)|Saves changes into destination file.|
|add_field(field_type, field_name, page_num, llx, lly, urx, ury)|Add field of specified type to the form.|
|add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury)|Add field of specified type to the form.|
|copy_inner_field(field_name, new_field_name, page_num)|Copies an existing field to the same position in specified page number.<br/>            A new document will be produced, which contains everything the source document has except for the newly copied field.|
|copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate)|Copies an existing field to a new position specified by both page number and ordinates.<br/>            A new document will be produced, which contains everything the source document has except for the newly copied field.|
|copy_outer_field(src_file_name, field_name)|Copies an existing field from one PDF document to another document with original page number and ordinates.<br/>            Notice: Only for AcroForm fields (excluding radio box).|
|copy_outer_field(src_file_name, field_name, page_num)|Copies an existing field from one PDF document to another document with specified page number and original ordinates.<br/>             Notice: Only for AcroForm fields (excluding radio box).|
|copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate)|Copies an existing field from one PDF document to another document with specified page number and ordinates.<br/>            Notice: Only for AcroForm fields (excluding radio box).|
|decorate_field(field_name)|Changes visual attributes of the specified field.|
|decorate_field(field_type)|Changes visual attributes of all fields with the specified field type.|
|decorate_field()|Changes visual attributes of the specified field.|
|add_list_item(field_name, item_name)|Adds new item to the list box.|
|add_list_item(field_name, export_name)|Add a new item with Export value to the existing list box field, only for AcroForm combo box field.|
|close()|Closes the facade.|
|set_field_attribute(field_name, flag)|Set attributes of field.|
|set_field_appearance(field_name, flags)|Set field flags|
|get_field_appearance(field_name)|Get field flags.|
|set_submit_flag(field_name, submit_form_flag)|Set submit flag of submit button.|
|set_submit_url(field_name, url)|Sets URL of the button.|
|set_field_limit(field_name, field_limit)|Sets maximum character count of the text field.|
|set_field_comb_number(field_name, comb_number)|Sets number of combs for a regular single-line text field (the field is <br/>            automatically divided into as many equally spaced positions, or combs, <br/>            as the value of combNumber parameter).|
|move_field(field_name, llx, lly, urx, ury)|Set new position of field.|
|remove_field(field_name)|Remove field from the form.|
|reset_facade()|Reset all visual attribtues to empty value.|
|reset_inner_facade()|Reset all visual attribtues of inner facade to empty value.|
|rename_field(field_name, new_field_name)|Change name of the field.|
|remove_field_action(field_name)|Remove submit action of the field.|
|add_submit_btn(field_name, page, label, url, llx, lly, urx, ury)|Add submit button on the form.|
|del_list_item(field_name, item_name)|Delete item from the list field.|
|set_field_script(field_name, script)|Set JavaScript for a PushButton field. If old JavaScript existed, it will be replaced by the new one.|
|add_field_script(field_name, script)|Add JavaScript for a PushButton field. If old event exists, new event is added after it.|
|single_2_multiple(field_name)|Change a single-lined text field to a multiple-lined one.|
|set_field_alignment(field_name, alignment)|Set the alignment style of a text field.|
|set_field_alignment_v(field_name, alignment)|Set the vertical alignment style of a text field.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

