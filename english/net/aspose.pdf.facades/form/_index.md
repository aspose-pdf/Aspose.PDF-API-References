---
title: Class Form
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Facades.Form class. Class representing Acro form object
type: docs
weight: 4280
url: /net/aspose.pdf.facades/form/
---
## Form class

Class representing Acro form object.

```csharp
public sealed class Form : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [Form](form/#constructor)() | Construtcor of Form without parameters. |
| [Form](form/#constructor_1)(Document) | Initializes new `Form` object on base of the *document*. |
| [Form](form/#constructor_4)(Stream) | Constructor for form. |
| [Form](form/#constructor_7)(string) | Constructor of Form. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/form/convertto/) { set; } | Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. |
| [FieldNames](../../aspose.pdf.facades/form/fieldnames/) { get; } | Gets list of field names on the form. |
| [FormSubmitButtonNames](../../aspose.pdf.facades/form/formsubmitbuttonnames/) { get; } | Gets all form submit button names. |
| [ImportResult](../../aspose.pdf.facades/form/importresult/) { get; } | Result of last import operation. Array of objects which descibre result of import for each field. |

## Methods

| Name | Description |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Initializes the facade. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Initializes the facade. |
| override [Close](../../aspose.pdf.facades/form/close/)() | Closes opened files without any changes. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Disposes the facade. |
| [ExportFdf](../../aspose.pdf.facades/form/exportfdf/)(Stream) | Exports the content of the fields of the pdf into the fdf stream. |
| [ExportJson](../../aspose.pdf.facades/form/exportjson/)(Stream, bool) | Exports the contents of all fields in the document into a JSON stream. Button field values are not exported. |
| [ExportXfdf](../../aspose.pdf.facades/form/exportxfdf/)(Stream) | Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported. |
| [ExportXml](../../aspose.pdf.facades/form/exportxml/)(Stream) | Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported. |
| [ExtractXfaData](../../aspose.pdf.facades/form/extractxfadata/)(Stream) | Extracts XFA data packet |
| [FillBarcodeField](../../aspose.pdf.facades/form/fillbarcodefield/)(string, string) | Fill a barcode field according to its fully qualified field name. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield)(string, bool) | Fills the check box field with a boolean value. Notice: Only be applied to Check Box. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_1)(string, int) | Fills the radio box field with a valid index value according to a fully qualified field name. Before filling the fields, only field's name must be known. While the value can be specified by its index. Notice: Only be applied to Radio Box, Combo Box and List Box fields. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.ListBoxField" you should specify full name and not "ListBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_2)(string, string) | Fills the field with a valid value according to a fully qualified field name. Before filling the fields, every field's names and its corresponding valid values must be known. Both the fields' name and values are case sensitive. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.TextField" you should specify full name and not "TextField". You can use FieldNames property to explore existing field names and search required field by its partial name. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_4)(string, string[]) | Fill a field with multiple selections.Note: only for AcroForm List Box Field. |
| [FillField](../../aspose.pdf.facades/form/fillfield/#fillfield_3)(string, string, bool) | Fills field with specified value. |
| [FillFields](../../aspose.pdf.facades/form/fillfields/)(string[], string[], out Stream) | Fills the text box fields with a text values and save the document. Relevant for signed documents. Notice: Only be applied to Text Box. Both the fields' name and values are case sensitive. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield)(string, Stream) | Overloads function of FillImageField. The input is a image stream. |
| [FillImageField](../../aspose.pdf.facades/form/fillimagefield/#fillimagefield_1)(string, string) | Pastes an image onto the existing button field as its appearance according to its fully qualified field name. |
| [FlattenAllFields](../../aspose.pdf.facades/form/flattenallfields/)() | Flattens all the fields. |
| [FlattenField](../../aspose.pdf.facades/form/flattenfield/)(string) | Flattens a specified field with the fully qualified field name. Any other field will remain unchangable. If the fieldName is invalid, all the fields will remain unchangable. |
| [GetButtonOptionCurrentValue](../../aspose.pdf.facades/form/getbuttonoptioncurrentvalue/)(string) | Returns the current value for radio button option fields. |
| [GetButtonOptionValues](../../aspose.pdf.facades/form/getbuttonoptionvalues/)(string) | Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups. |
| [GetField](../../aspose.pdf.facades/form/getfield/)(string) | Gets the field's value according to its field name. |
| [GetFieldFacade](../../aspose.pdf.facades/form/getfieldfacade/)(string) | Returns FrofmFieldFacade object containing all appearance attributes. |
| [GetFieldFlag](../../aspose.pdf.facades/form/getfieldflag/)(string) | Returns flags of the field. |
| [GetFieldLimit](../../aspose.pdf.facades/form/getfieldlimit/)(string) | Get the limitation of text field. |
| [GetFieldType](../../aspose.pdf.facades/form/getfieldtype/)(string) | Returns type of field. |
| [GetFullFieldName](../../aspose.pdf.facades/form/getfullfieldname/)(string) | Gets the full field name according to its short field name. |
| [GetRichText](../../aspose.pdf.facades/form/getrichtext/)(string) | Get a Rich Text field's value, including the formattinf information of every character. |
| [GetSubmitFlags](../../aspose.pdf.facades/form/getsubmitflags/)(string) | Returns the submit button's submission flags |
| [ImportFdf](../../aspose.pdf.facades/form/importfdf/)(Stream) | Imports the content of the fields from the fdf file and put them into the new pdf. |
| [ImportJson](../../aspose.pdf.facades/form/importjson/)(Stream) | Imports all field data from a JSON stream into the document fields, matching the fields by their full names. |
| [ImportXfdf](../../aspose.pdf.facades/form/importxfdf/)(Stream) | Imports the content of the fields from the xfdf(xml) file and put them into the new pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml)(Stream) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [ImportXml](../../aspose.pdf.facades/form/importxml/#importxml_1)(Stream, bool) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [IsRequiredField](../../aspose.pdf.facades/form/isrequiredfield/)(string) | Determines whether field is required or not. |
| [RenameField](../../aspose.pdf.facades/form/renamefield/)(string, string) | Renames a field. Either AcroForm field or XFA field is OK. |
| override [Save](../../aspose.pdf.facades/form/save/#save_1)(Stream) | Saves document into specified stream. |
| override [Save](../../aspose.pdf.facades/form/save/#save_2)(string) | Saves document into specified file. |
| [SetXfaData](../../aspose.pdf.facades/form/setxfadata/)(Stream) | Replaces XFA data with specified data packet. Data packet may be extracted using ExtractXfaData. |

## Other Members

| Name | Description |
| --- | --- |
| class [FormImportResult](../../aspose.pdf.facades/form.formimportresult) | Class which describes result if field import. |
| enum [ImportStatus](../../aspose.pdf.facades/form.importstatus) | Status of imported field |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)


