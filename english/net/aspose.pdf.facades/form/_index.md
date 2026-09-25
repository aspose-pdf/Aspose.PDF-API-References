---
title: "Form Class"
linktitle: "Form"
articleTitle: "Form"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Facades.Form class. Class representing Acro form object."
type: docs
weight: 180
url: "/net/aspose.pdf.facades/form/"
keywords: "Form, Aspose.Pdf.Facades, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## Form class

Class representing Acro form object.

```csharp
public sealed class Form : SaveableFacade
```

## Constructors

| Name | Description |
| --- | --- |
| [Form](./form/#constructor) | Construtcor of Form without parameters. |
| [Form](./form/#constructor_1)(*string*) | Constructor of Form. |
| [Form](./form/#constructor_2)(*Stream*) | Constructor for form. |
| [Form](./form/#constructor_3)(*[Document](../../aspose.pdf/document/)*) | Initializes new [`Form`](../../aspose.pdf.forms/form/) object on base of the *document*. |
| [Form](./form/#constructor_4)(*Stream, Stream*) | Constructor of Form with two stream parameters. |
| [Form](./form/#constructor_5)(*string, string*) | Constructor of Form class. |
| [Form](./form/#constructor_6)(*string, Stream*) | Constructor of Form. |
| [Form](./form/#constructor_7)(*Stream, string*) | Constructor of Form. |
| [Form](./form/#constructor_8)(*[Document](../../aspose.pdf/document/), string*) | Initializes new [`Form`](../../aspose.pdf.forms/form/) object on base of the *document*. |
| [Form](./form/#constructor_9)(*[Document](../../aspose.pdf/document/), Stream*) | Initializes new [`Form`](../../aspose.pdf.forms/form/) object on base of the *document*. |

## Properties

| Name | Description |
| --- | --- |
| [ConvertTo](./convertto/) { set; } | Sets PDF file format. Result file will be saved in specified file format. |
| [DestFileName](./destfilename/) { get; set; } | Gets or sets destiination file name. |
| [DestStream](./deststream/) { get; set; } | Gets or sets destination stream. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Gets the document facade is working on. *(Inherited from Facade)* |
| [FieldNames](./fieldnames/) { get; } | Gets list of field names on the form. |
| [FormSubmitButtonNames](./formsubmitbuttonnames/) { get; } | Gets all form submit button names. |
| [ImportResult](./importresult/) { get; } | Result of last import operation. Array of objects which descibre result of import for each field. |
| [SrcFileName](./srcfilename/) { get; set; } | Gets or sets source file name. |
| [SrcStream](./srcstream/) { get; set; } | Gets or sets source stream. |

## Methods

| Name | Description |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(*string*) | Initializes the facade. *(Inherited from Facade)* |
| [Close](./close/) | Closes opened files without any changes. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/) | Disposes the facade. *(Inherited from Facade)* |
| [ExportFdf](./exportfdf/)(*Stream*) | Exports the content of the fields of the pdf into the fdf stream. |
| [ExportJson](./exportjson/)(*Stream, bool*) | Exports the contents of all fields in the document into a JSON stream. Button field values are not exported. |
| [ExportXfdf](./exportxfdf/)(*Stream*) | Exports the content of the fields of the pdf into the xml stream. |
| [ExportXml](./exportxml/)(*Stream*) | Exports the content of the fields of the pdf into the xml stream. |
| [ExtractXfaData](./extractxfadata/)(*Stream*) | Extracts XFA data packet. |
| [FillBarcodeField](./fillbarcodefield/)(*string, string*) | Fill a barcode field according to its fully qualified field name. |
| [FillField](./fillfield/)(*string, string*) | Fills the field with a valid value according to a fully qualified field name. |
| [FillField](./fillfield/)(*string, int*) | Fills the radio box field with a valid index value according to a fully qualified field name. |
| [FillField](./fillfield/)(*string, bool*) | Fills the check box field with a boolean value. |
| [FillField](./fillfield/)(*string, string[]*) | Fill a field with multiple selections.Note: only for AcroForm List Box Field. |
| [FillField](./fillfield/)(*string, string, bool*) | Fills field with specified value. |
| [FillFields](./fillfields/)(*string[], string[], Stream*) |  |
| [FillImageField](./fillimagefield/)(*string, string*) | Pastes an image onto the existing button field as its appearance according to. |
| [FillImageField](./fillimagefield/)(*string, Stream*) | Overloads function of FillImageField. |
| [FlattenAllFields](./flattenallfields/) | Flattens all the fields. |
| [FlattenField](./flattenfield/)(*string*) | Flattens a specified field with the fully qualified field name. |
| [GetButtonOptionCurrentValue](./getbuttonoptioncurrentvalue/)(*string*) | Returns the current value for radio button option fields. |
| [GetButtonOptionValues](./getbuttonoptionvalues/)(*string*) | Gets the radio button option fields and related values based on the field name. |
| [GetField](./getfield/)(*string*) | Gets the field's value according to its field name. |
| [GetFieldFacade](./getfieldfacade/)(*string*) | Returns FrofmFieldFacade object containing all appearance attributes. |
| [GetFieldFlag](./getfieldflag/)(*string*) | Returns flags of the field. |
| [GetFieldLimit](./getfieldlimit/)(*string*) | Get the limitation of text field. |
| [GetFieldType](./getfieldtype/)(*string*) | Returns type of field. |
| [GetFullFieldName](./getfullfieldname/)(*string*) | Gets the full field name according to its short field name. |
| [GetRichText](./getrichtext/)(*string*) | Get a Rich Text field's value, including the formattinf information of every character. |
| [GetSubmitFlags](./getsubmitflags/)(*string*) | Returns the submit button's submission flags. |
| [ImportFdf](./importfdf/)(*Stream*) | Imports the content of the fields from the fdf file and put them into the new pdf. |
| [ImportJson](./importjson/)(*Stream*) | Imports all field data from a JSON stream into the document fields, matching the fields by their full names. |
| [ImportXfdf](./importxfdf/)(*Stream*) | Imports the content of the fields from the xfdf(xml) file and put them into the new pdf. |
| [ImportXml](./importxml/)(*Stream*) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [ImportXml](./importxml/)(*Stream, bool*) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [IsRequiredField](./isrequiredfield/)(*string*) | Determines whether field is required or not. |
| [RenameField](./renamefield/)(*string, string*) | Renames a field. Either AcroForm field or XFA field is OK. |
| [Save](./save/) | Saves the value of the filled fields and close the opened Pdf document. |
| [Save](./save/)(*string*) | Saves document into specified file. |
| [Save](./save/)(*Stream*) | Saves document into specified stream. |
| [SetXfaData](./setxfadata/)(*Stream*) | Replaces XFA data with specified data packet. Data packet may be extracted using ExtractXfaData. |

### See Also

* class [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)

