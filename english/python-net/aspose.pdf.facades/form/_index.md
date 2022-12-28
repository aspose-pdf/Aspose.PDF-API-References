---
title: Form
second_title: Aspose.PDF for Python via .NET API Reference
description: Class representing Acro form object.
type: docs
weight: 80
url: /python-net/aspose.pdf.facades/form/
---

## Form class

Class representing Acro form object.

The Form type exposes the following members:
## Constructors
| Name | Description |
| :- | :- |
|Form(src_stream, dest_stream)|Initializes a new instance of the Form class|
|Form()|Construtcor of Form without parameters.|
|Form(src_file_name)|Initializes a new instance of the Form class|
|Form(src_stream)|Initializes a new instance of the Form class|
|Form(src_file_name, dest_file_name)|Initializes a new instance of the Form class|
|Form(src_file_name, dest_stream)|Initializes a new instance of the Form class|
|Form(src_stream, dest_file_name)|Initializes a new instance of the Form class|
|Form(document)|Initializes a new instance of the Form class|
|Form(document, dest_file_name)|Initializes a new instance of the Form class|
|Form(document, dest_stream)|Initializes a new instance of the Form class|
## Properties
| Name | Description |
| :- | :- |
|document|Gets the document facade is working on.|
|import_result|Result of last import operation. Array of objects which descibre result of import for each field.|
|src_file_name|Gets or sets source file name.|
|dest_file_name|Gets or sets destiination file name.|
|src_stream|Gets or sets source stream.|
|dest_stream|Gets or sets destination stream.|
|field_names|Gets list of field names on the form.|
|form_submit_button_names|Gets all form submit button names.|
## Methods
| Name | Description |
| :- | :- |
|bind_pdf(src_file)|Binds PDF document for editing.|
|bind_pdf(src_stream)|Binds PDF document for editing.|
|bind_pdf(src_doc)|Binds PDF document for editing.|
|save()|Saves the value of the filled fields and close the opened Pdf document.|
|save(dest_file)|Saves document into specified file.|
|save(dest_stream)|Saves document into specified stream.|
|fill_field(field_name, field_value)|Fills the field with a valid value according to a fully qualified field name.<br/>            Before filling the fields, every field's names and its corresponding valid values must be known.<br/>            Both the fields' name and values are case sensitive.<br/>            Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial <br/>            field names in contrast with Aspose.Pdf.Kit;<br/>            For example if field has full name "Form.Subform.TextField" you should specify full name and not "TextField". <br/>            You can use FieldNames property to explore existing field names and search required field by its partial name.|
|fill_field(field_name, index)|Fills the radio box field with a valid index value according to a fully qualified field name.<br/>            Before filling the fields, only field's name must be known. While the value can be specified by its index.<br/>            Notice: Only be applied to Radio Box, Combo Box and List Box fields.<br/>            Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial <br/>            field names in contrast with Aspose.Pdf.Kit;<br/>            For example if field has full name "Form.Subform.ListBoxField" you should specify full name and not "ListBoxField". <br/>            You can use FieldNames property to explore existing field names and search required field by its partial name.|
|fill_field(field_name, be_checked)|Fills the check box field with a boolean value.<br/>            Notice: Only be applied to Check Box.<br/>            Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial <br/>            field names in contrast with Aspose.Pdf.Kit;<br/>            For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". <br/>            You can use FieldNames property to explore existing field names and search required field by its partial name.|
|fill_field(field_name, field_values)|Fills the text box fields with a text values and save the document.<br/>            Relevant for signed documents.<br/>            Notice: Only be applied to Text Box.<br/>            Both the fields' name and values are case sensitive.|
|fill_field(field_name, value, fit_font_size)|Fills the check box field with a boolean value.<br/>            Notice: Only be applied to Check Box.<br/>            Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial <br/>            field names in contrast with Aspose.Pdf.Kit;<br/>            For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". <br/>            You can use FieldNames property to explore existing field names and search required field by its partial name.|
|import_xml(input_xml_stream)|Imports the content of the fields from the xml file and put them into the new pdf.|
|import_xml(input_xml_stream, ignore_form_template_changes)|Imports the content of the fields from the xml file and put them into the new pdf.|
|fill_image_field(field_name, image_file_name)|Pastes an image onto the existing button field as its appearance according to <br/>            its fully qualified field name.|
|fill_image_field(field_name, image_stream)|Overloads function of FillImageField.<br/>            The input is a image stream.|
|close()|Closes opened files without any changes.|
|get_field_facade(field_name)|Returns FrofmFieldFacade object containing all appearance attributes.|
|fill_fields(field_names, field_values, output)|Fills the text box fields with a text values and save the document.<br/>            Relevant for signed documents.<br/>            Notice: Only be applied to Text Box.<br/>            Both the fields' name and values are case sensitive.|
|get_button_option_current_value(field_name)|Returns the current value for radio button option fields.|
|get_field(field_name)|Returns FrofmFieldFacade object containing all appearance attributes.|
|get_full_field_name(field_name)|Gets the full field name according to its short field name.|
|get_field_limit(field_name)|Get the limitation of text field.|
|flatten_all_fields()|Flattens all the fields.|
|flatten_field(field_name)|Flattens a specified field with the fully qualified field name.<br/>            Any other field will remain unchangable. If the fieldName is invalid, <br/>            all the fields will remain unchangable.|
|fill_barcode_field(field_name, data)|Fill a barcode field according to its fully qualified field name.|
|import_fdf(input_fdf_stream)|Imports the content of the fields from the fdf file and put them into the new pdf.|
|export_fdf(output_fdf_stream)|Exports the content of the fields of the pdf into the fdf stream.|
|export_xml(output_xml_stream)|Exports the content of the fields of the pdf into the xml stream.<br/>            The button field's value will not be exported.|
|extract_xfa_data(output_xml_stream)|Extracts XFA data packet|
|set_xfa_data(input_xml_stream)|Replaces XFA data with specified data packet. Data packet may be extracted using ExtractXfaData.|
|import_xfdf(input_xfdf_stream)|Imports the content of the fields from the xfdf(xml) file and put them into the new pdf.|
|export_xfdf(output_xfdf_stream)|Exports the content of the fields of the pdf into the xml stream.<br/>            The button field's value will not be exported.|
|rename_field(field_name, new_field_name)|Renames a field. Either AcroForm field or XFA field is OK.|
|get_rich_text(field_name)|Get a Rich Text field's value, including the formattinf information of every character.|
|get_submit_flags(field_name)|Returns the submit button's submission flags|
|get_field_type(field_name)|Returns type of field.|
|is_required_field(field_name)|Determines whether field is required or not.|
|get_field_flag(field_name)|Returns flags of the field.|

### See Also

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

