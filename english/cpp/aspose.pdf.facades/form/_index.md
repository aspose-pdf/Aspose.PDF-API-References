---
title: Aspose::Pdf::Facades::Form class
linktitle: Form
second_title: Aspose.PDF for C++ API Reference
description: 'Aspose::Pdf::Facades::Form class. Class representing Acro form object in C++.'
type: docs
weight: 800
url: /cpp/aspose.pdf.facades/form/
---
## Form class


Class representing Acro form object.

```cpp
class Form : public Aspose::Pdf::Facades::SaveableFacade
```

## Nested classes

* Class [FormImportResult](./formimportresult/)
## Enums

| Enum | Description |
| --- | --- |
| [ImportStatus](./importstatus/) | Status of imported field. |
## Methods

| Method | Description |
| --- | --- |
| [Close](./close/)() override | Closes opened files without any changes. |
| [ExportFdf](./exportfdf/)(System::SharedPtr\<System::IO::Stream\>) | Exports the content of the fields of the pdf into the fdf stream. |
| [ExportXfdf](./exportxfdf/)(System::SharedPtr\<System::IO::Stream\>) | Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported. |
| [ExportXml](./exportxml/)(System::SharedPtr\<System::IO::Stream\>) | Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported. |
| [ExtractXfaData](./extractxfadata/)(System::SharedPtr\<System::IO::Stream\>) | Extracts XFA data packet. |
| [FillBarcodeField](./fillbarcodefield/)(System::String, System::String) | Fill a barcode field according to its fully qualified field name. |
| [FillField](./fillfield/)(System::String, System::String) | Fills the field with a valid value according to a fully qualified field name. Before filling the fields, every field's names and its corresponding valid values must be known. Both the fields' name and values are case sensitive. Please note that [Aspose.Pdf.Facades](../) supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.TextField" you should specify full name and not "TextField". You can use FieldNames property to explore existing field names and search required field by its partial name. |
| [FillField](./fillfield/)(System::String, int32_t) | Fills the radio box field with a valid index value according to a fully qualified field name. Before filling the fields, only field's name must be known. While the value can be specified by its index. Notice: Only be applied to Radio Box, Combo Box and List Box fields. Please note that [Aspose.Pdf.Facades](../) supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.ListBoxField" you should specify full name and not "ListBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name. |
| [FillField](./fillfield/)(System::String, bool) | Fills the check box field with a boolean value. Notice: Only be applied to Check Box. Please note that [Aspose.Pdf.Facades](../) supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name. |
| [FillField](./fillfield/)(System::String, System::ArrayPtr\<System::String\>) | Fill a field with multiple selections.Note: only for AcroForm List Box Field. |
| [FillField](./fillfield/)(System::String, System::String, bool) | Fills field with specified value. |
| [FillFields](./fillfields/)(System::ArrayPtr\<System::String\>, System::ArrayPtr\<System::String\>, System::SharedPtr\<System::IO::Stream\>\&) | Fills the text box fields with a text values and save the document. Relevant for signed documents. Notice: Only be applied to [Text](../../aspose.pdf.text/) Box. Both the fields' name and values are case sensitive. |
| [FillImageField](./fillimagefield/)(System::String, System::String) | Pastes an image onto the existing button field as its appearance according to its fully qualified field name. |
| [FillImageField](./fillimagefield/)(System::String, System::SharedPtr\<System::IO::Stream\>) | Overloads function of FillImageField. The input is a image stream. |
| [FlattenAllFields](./flattenallfields/)() | Flattens all the fields. |
| [FlattenField](./flattenfield/)(System::String) | Flattens a specified field with the fully qualified field name. Any other field will remain unchangable. If the fieldName is invalid, all the fields will remain unchangable. |
| [Form](./form/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::IO::Stream\>) | Constructor of [Form](./) with two stream parameters. Specify same source and destination stream for incremental update. |
| [Form](./form/)() | Construtcor of [Form](./) without parameters. |
| [Form](./form/)(System::String) | Constructor of [Form](./). |
| [Form](./form/)(System::SharedPtr\<System::IO::Stream\>) | Constructor for form. |
| [Form](./form/)(System::String, System::String) | Constructor of [Form](./) class. Specify same source file name and destination file name to perform incremental update. |
| [Form](./form/)(System::String, System::SharedPtr\<System::IO::Stream\>) | Constructor of [Form](./). |
| [Form](./form/)(System::SharedPtr\<System::IO::Stream\>, System::String) | Constructor of [Form](./). |
| [Form](./form/)(System::SharedPtr\<Aspose::Pdf::Document\>) | Initializes new [Form](./) object on base of the *document* . |
| [Form](./form/)(System::SharedPtr\<Aspose::Pdf::Document\>, System::String) | Initializes new [Form](./) object on base of the *document* . |
| [Form](./form/)(System::SharedPtr\<Aspose::Pdf::Document\>, System::SharedPtr\<System::IO::Stream\>) | Initializes new [Form](./) object on base of the *document* . |
| [Form](./form/)(System::SharedPtr\<System::IO::Stream\>, System::SharedPtr\<System::Web::HttpResponse\>) | Creates form which will save result into HttpResponse object. |
| [Form](./form/)(System::String, System::SharedPtr\<System::Web::HttpResponse\>) | Creates form which will save result into HttpResponse object. |
| [get_AttachmentName](./get_attachmentname/)() const | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [get_ContentDisposition](./get_contentdisposition/)() const | Gets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [get_DestFileName](./get_destfilename/)() const | Gets destiination file name. |
| [get_DestStream](./get_deststream/)() const | Gets destination stream. |
| [get_FieldNames](./get_fieldnames/)() | Gets list of field names on the form. |
| [get_FormSubmitButtonNames](./get_formsubmitbuttonnames/)() | Gets all form submit button names. |
| [get_ImportResult](./get_importresult/)() | Result of last import operation. Array of objects which descibre result of import for each field. |
| [get_Response](./get_response/)() const | Gets Response object where result of operation will be stored. |
| [get_SaveOptions](./get_saveoptions/)() const | Gets save options when result is stored as HttpResponse. Default value: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [get_SrcFileName](./get_srcfilename/)() const | Gets source file name. |
| [get_SrcStream](./get_srcstream/)() const | Gets source stream. |
| [GetButtonOptionCurrentValue](./getbuttonoptioncurrentvalue/)(System::String) | Returns the current value for radio button option fields. |
| [GetButtonOptionValues](./getbuttonoptionvalues/)(System::String) | Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups. |
| [GetField](./getfield/)(System::String) | Gets the field's value according to its field name. |
| [GetFieldFacade](./getfieldfacade/)(System::String) | Returns FrofmFieldFacade object containing all appearance attributes. |
| [GetFieldFlag](./getfieldflag/)(System::String) | Returns flags of the field. |
| [GetFieldLimit](./getfieldlimit/)(System::String) | Get the limitation of text field. |
| [GetFieldType](./getfieldtype/)(System::String) | Returns type of field. |
| [GetFullFieldName](./getfullfieldname/)(System::String) | Gets the full field name according to its short field name. |
| [GetRichText](./getrichtext/)(System::String) | Get a Rich [Text](../../aspose.pdf.text/) field's value, including the formattinf information of every character. |
| [GetSubmitFlags](./getsubmitflags/)(System::String) | Returns the submit button's submission flags. |
| [ImportFdf](./importfdf/)(System::SharedPtr\<System::IO::Stream\>) | Imports the content of the fields from the fdf file and put them into the new pdf. |
| [ImportXfdf](./importxfdf/)(System::SharedPtr\<System::IO::Stream\>) | Imports the content of the fields from the xfdf(xml) file and put them into the new pdf. |
| [ImportXml](./importxml/)(System::SharedPtr\<System::IO::Stream\>) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [ImportXml](./importxml/)(System::SharedPtr\<System::IO::Stream\>, bool) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [IsRequiredField](./isrequiredfield/)(System::String) | Determines whether field is required or not. |
| [RenameField](./renamefield/)(System::String, System::String) | Renames a field. Either AcroForm field or XFA field is OK. |
| [Save](./save/)() | Saves the value of the filled fields and close the opened [Pdf](../../aspose.pdf/) document. |
| [Save](./save/)(System::String) override | Saves document into specified file. |
| [Save](./save/)(System::SharedPtr\<System::IO::Stream\>) override | Saves document into specified stream. |
| [set_AttachmentName](./set_attachmentname/)(System::String) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [set_ContentDisposition](./set_contentdisposition/)(Aspose::Pdf::ContentDisposition) | Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [set_ConvertTo](./set_convertto/)(PdfFormat) | Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion. |
| [set_DestFileName](./set_destfilename/)(System::String) | Sets destiination file name. |
| [set_DestStream](./set_deststream/)(System::SharedPtr\<System::IO::Stream\>) | Sets destination stream. |
| [set_Response](./set_response/)(System::SharedPtr\<System::Web::HttpResponse\>) | Sets Response object where result of operation will be stored. |
| [set_SaveOptions](./set_saveoptions/)(System::SharedPtr\<Aspose::Pdf::SaveOptions\>) | Sets save options when result is stored as HttpResponse. Default value: [PdfSaveOptions](../../aspose.pdf/pdfsaveoptions/). |
| [set_SrcFileName](./set_srcfilename/)(System::String) | Sets source file name. |
| [set_SrcStream](./set_srcstream/)(System::SharedPtr\<System::IO::Stream\>) | Sets source stream. |
| [SetXfaData](./setxfadata/)(System::SharedPtr\<System::IO::Stream\>) | Replaces XFA data with specified data packet. Data packet may be extracted using ExtractXfaData. |
## See Also

* Class [SaveableFacade](../saveablefacade/)
* Namespace [Aspose::Pdf::Facades](../)
* Library [Aspose.PDF for C++](../../)
