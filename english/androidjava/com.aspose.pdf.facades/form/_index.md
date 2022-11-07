---
title: Form
second_title: Aspose.PDF for Java API Reference
description: Class representing Acro form object.
type: docs
weight: 24
url: /java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade), com.aspose.pdf.facades.AForm
```
public final class Form extends AForm
```

Class representing Acro form object.
## Constructors

| Constructor | Description |
| --- | --- |
| [Form()](#Form--) | Construtcor of Form without parameters. |
| [Form(IDocument document)](#Form-com.aspose.pdf.IDocument-) | Initializes new  Form  object on base of the  document . |
| [Form(IDocument document, OutputStream destStream)](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | Initializes new  Form  object on base of the  document . |
| [Form(IDocument document, String destFileName)](#Form-com.aspose.pdf.IDocument-java.lang.String-) | Initializes new  Form  object on base of the  document . |
| [Form(InputStream srcStream)](#Form-java.io.InputStream-) | Constructor for form. |
| [Form(InputStream srcStream, OutputStream destStream)](#Form-java.io.InputStream-java.io.OutputStream-) | Constructor of Form with two stream parameters. |
| [Form(InputStream srcStream, String destFileName)](#Form-java.io.InputStream-java.lang.String-) | Constructor of Form |
| [Form(String srcFileName)](#Form-java.lang.String-) | Constructor of Form. |
| [Form(String srcFileName, OutputStream destStream)](#Form-java.lang.String-java.io.OutputStream-) | Constructor of Form. |
| [Form(String srcFileName, String destFileName)](#Form-java.lang.String-java.lang.String-) | Constructor of Form class. |
## Methods

| Method | Description |
| --- | --- |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Initializes the facade. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [close()](#close--) | Closes opened files without any changes. |
| [dispose()](#dispose--) | Closes all opened resources. |
| [exportFdf(OutputStream outputFdfStream)](#exportFdf-java.io.OutputStream-) | Exports the content of the fields of the pdf into the fdf stream. |
| [exportXfdf(OutputStream outputXfdfStream)](#exportXfdf-java.io.OutputStream-) | Exports the content of the fields of the pdf into the xml stream. |
| [exportXml(OutputStream outputXmlStream)](#exportXml-java.io.OutputStream-) | Exports the content of the fields of the pdf into the xml stream. |
| [extractXfaData(OutputStream outputXmlStream)](#extractXfaData-java.io.OutputStream-) | Extracts XFA data packet |
| [fillBarcodeField(String fieldName, String data)](#fillBarcodeField-java.lang.String-java.lang.String-) | Fill a barcode field according to its fully qualified field name. |
| [fillField(String fieldName, boolean beChecked)](#fillField-java.lang.String-boolean-) | Fills the check box field with a boolean value. |
| [fillField(String fieldName, int index)](#fillField-java.lang.String-int-) | Fills the radio box field with a valid index value according to a fully qualified field name. |
| [fillField(String fieldName, String fieldValue)](#fillField-java.lang.String-java.lang.String-) | Fills the field with a valid value according to a fully qualified field name. |
| [fillField(String fieldName, String value, boolean fitFontSize)](#fillField-java.lang.String-java.lang.String-boolean-) | Fills field with specified value. |
| [fillField(String fieldName, String[] fieldValues)](#fillField-java.lang.String-java.lang.String---) | Fill a field with multiple selections.Note: only for AcroForm List Box Field. |
| [flattenAllFields()](#flattenAllFields--) | Flattens all the fields. |
| [flattenField(String fieldName)](#flattenField-java.lang.String-) | Flattens a specified field with the fully qualified field name. |
| [getAttachmentName()](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getButtonOptionCurrentValue(String fieldName)](#getButtonOptionCurrentValue-java.lang.String-) | Returns the current value for radio button option fields. |
| [getButtonOptionValues(String fieldName)](#getButtonOptionValues-java.lang.String-) | Gets the radio button option fields and related values based on the field name. |
| [getContentDisposition()](#getContentDisposition--) | Gets or sets how content will be stored when result of operation is stored into HttpResponse object. |
| [getDestFileName()](#getDestFileName--) | Gets destination file name. |
| [getDestStream()](#getDestStream--) | Gets or sets destination stream. |
| [getField(String fieldName)](#getField-java.lang.String-) | Gets the field's value according to its field name. |
| [getFieldFacade(String fieldName)](#getFieldFacade-java.lang.String-) | Returns FrofmFieldFacade object containing all appearance attributes. |
| [getFieldFlag(String fieldName)](#getFieldFlag-java.lang.String-) | Returns flags of the field. |
| [getFieldLimit(String fieldName)](#getFieldLimit-java.lang.String-) | Get the limitation of text field. |
| [getFieldNames()](#getFieldNames--) | Gets list of field names on the form. |
| [getFieldType(String fieldName)](#getFieldType-java.lang.String-) | Returns type of field. |
| [getFormSubmitButtonNames()](#getFormSubmitButtonNames--) | Gets all form submit button names. |
| [getFullFieldName(String fieldName)](#getFullFieldName-java.lang.String-) | Gets the full field name according to its short field name. |
| [getImportResult()](#getImportResult--) | Result of last import operation. |
| [getRichText(String fieldName)](#getRichText-java.lang.String-) | Get a Rich Text field's value, including the formatting information of every character. |
| [getSaveOptions()](#getSaveOptions--) | Gets or sets save options when result is stored as HttpResponse. |
| [getSrcFileName()](#getSrcFileName--) | Gets source file name. |
| [getSrcStream()](#getSrcStream--) | Gets source stream. |
| [getSubmitFlags(String fieldName)](#getSubmitFlags-java.lang.String-) | Returns the submit button's submission flags |
| [importFdf(InputStream inputFdfStream)](#importFdf-java.io.InputStream-) | Imports the content of the fields from the fdf file and put them into the new pdf. |
| [importXfdf(InputStream inputXfdfStream)](#importXfdf-java.io.InputStream-) | Imports the content of the fields from the xfdf(xml) file and put them into the new pdf. |
| [importXml(InputStream inputXmlStream)](#importXml-java.io.InputStream-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)](#importXml-java.io.InputStream-boolean-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [isRequiredField(String fieldName)](#isRequiredField-java.lang.String-) | Determines whether field is required or not. |
| [renameField(String fieldName, String newFieldName)](#renameField-java.lang.String-java.lang.String-) | Renames a field. |
| [save()](#save--) | Saves the value of the filled fields and close the opened Pdf document. |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Saves document into specified stream. |
| [save(String destFile)](#save-java.lang.String-) | Saves document into specified file. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Sets how content will be stored when result of operation is stored into HttpResponse object. |
| [setConvertTo(int value)](#setConvertTo-int-) | Sets PDF file format. |
| [setDestFileName(String value)](#setDestFileName-java.lang.String-) | Sets destination file name. |
| [setDestStream(OutputStream value)](#setDestStream-java.io.OutputStream-) | Gets destination stream. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Gets or sets save options when result is stored as HttpResponse. |
| [setSrcFileName(String value)](#setSrcFileName-java.lang.String-) | Sets source file name. |
| [setSrcStream(InputStream value)](#setSrcStream-java.io.InputStream-) | Gets source stream. |
| [setXfaData(InputStream inputXmlStream)](#setXfaData-java.io.InputStream-) | Replaces XFA data with specified data packet. |
### Form() {#Form--}
```
public Form()
```


Construtcor of Form without parameters.

--------------------

```
Form form = new com.aspose.pdf.facades.Form();
   form.setSrcFileName( "file.pdf");
```

### Form(IDocument document) {#Form-com.aspose.pdf.IDocument-}
```
public Form(IDocument document)
```


Initializes new  Form  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### Form(IDocument document, OutputStream destStream) {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public Form(IDocument document, OutputStream destStream)
```


Initializes new  Form  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. Obsolete("Use constructor without destination.") |
| destStream | java.io.OutputStream | Destination stream. |

### Form(IDocument document, String destFileName) {#Form-com.aspose.pdf.IDocument-java.lang.String-}
```
public Form(IDocument document, String destFileName)
```


Initializes new  Form  object on base of the  document .

Obsolete("Use constructor without destination.")

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| destFileName | java.lang.String | Path of the destination file. |

### Form(InputStream srcStream) {#Form-java.io.InputStream-}
```
public Form(InputStream srcStream)
```


Constructor for form.

--------------------

```
Form form = new Form(new FileInputStream("PdfForm.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | source stream. |

### Form(InputStream srcStream, OutputStream destStream) {#Form-java.io.InputStream-java.io.OutputStream-}
```
public Form(InputStream srcStream, OutputStream destStream)
```


Constructor of Form with two stream parameters. Specify same source and destination stream for incremental update.

--------------------

```
Form form = new Form(new FileInputStream("InFile.pdf"), new FileOutputStream("OutFile.pdf"));
```

Obsolete("Use constructor without destination.")

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | Source stream. |
| destStream | java.io.OutputStream | Destination stream. |

### Form(InputStream srcStream, String destFileName) {#Form-java.io.InputStream-java.lang.String-}
```
public Form(InputStream srcStream, String destFileName)
```


Constructor of Form

--------------------

```
Form form = new Form(new FileInputStream("PdfForm.pdf"), "PdfForm_Updated.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | Source stream. |
| destFileName | java.lang.String | Destination file path. |

### Form(String srcFileName) {#Form-java.lang.String-}
```
public Form(String srcFileName)
```


Constructor of Form.

--------------------

```
Form form = new Form("PdfForm.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | Source file path. |

### Form(String srcFileName, OutputStream destStream) {#Form-java.lang.String-java.io.OutputStream-}
```
public Form(String srcFileName, OutputStream destStream)
```


Constructor of Form.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_Updated.pdf");
 Obsolete("Use constructor without destination.")
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | Source file path. |
| destStream | java.io.OutputStream | Destination file path. |

### Form(String srcFileName, String destFileName) {#Form-java.lang.String-java.lang.String-}
```
public Form(String srcFileName, String destFileName)
```


Constructor of Form class. Specify same source file name and destination file name to perform incremental update.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_Updated.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | Path of the source file. |
| destFileName | java.lang.String | Path of the destination file. |

### bindPdf(InputStream srcStream, String password) {#bindPdf-java.io.InputStream-java.lang.String-}
```
public void bindPdf(InputStream srcStream, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |
| password | java.lang.String | The password of the PDF document. |

### bindPdf(String srcFile, String password) {#bindPdf-java.lang.String-java.lang.String-}
```
public void bindPdf(String srcFile, String password)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file. |
| password | java.lang.String | The password of the PDF document. |

### close() {#close--}
```
public void close()
```


Closes opened files without any changes.

### dispose() {#dispose--}
```
public void dispose()
```


Closes all opened resources.

### exportFdf(OutputStream outputFdfStream) {#exportFdf-java.io.OutputStream-}
```
public void exportFdf(OutputStream outputFdfStream)
```


Exports the content of the fields of the pdf into the fdf stream.

--------------------

```
Form form = new Form("PdfForm.pdf");
 OutputStream stream = new FileOutputStream("export.fdf");
 form.exportFdf(stream);
 stream.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFdfStream | java.io.OutputStream | The output fdf stream. |

### exportXfdf(OutputStream outputXfdfStream) {#exportXfdf-java.io.OutputStream-}
```
public void exportXfdf(OutputStream outputXfdfStream)
```


Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported.

--------------------

```
Form form = new Form("PdfForm.pdf");
  FileInputStream fs = new FileInputStream("export.xfdf", FileMode.Create, FileAccess.Write);
  form.exportXfdf(fs);
  fs.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputXfdfStream | java.io.OutputStream | The output xml stream. |

### exportXml(OutputStream outputXmlStream) {#exportXml-java.io.OutputStream-}
```
public void exportXml(OutputStream outputXmlStream)
```


Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported.

--------------------

```
Form form = new Form("PdfForm.pdf"));
 OutputStream fs = new FileOutputStream("export.xml");
 form.exportXml(fs);
 fs.close();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputXmlStream | java.io.OutputStream | Output Xml stream. |

### extractXfaData(OutputStream outputXmlStream) {#extractXfaData-java.io.OutputStream-}
```
public void extractXfaData(OutputStream outputXmlStream)
```


Extracts XFA data packet

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputXmlStream | java.io.OutputStream | Stream where XML data will be stored. |

### fillBarcodeField(String fieldName, String data) {#fillBarcodeField-java.lang.String-java.lang.String-}
```
public boolean fillBarcodeField(String fieldName, String data)
```


Fill a barcode field according to its fully qualified field name.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillBarcodeField("textField", "42207252");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |
| data | java.lang.String | The new barcode value. |

**Returns:**
boolean - If filling succeed, return true; otherwise, false.
### fillField(String fieldName, boolean beChecked) {#fillField-java.lang.String-boolean-}
```
public boolean fillField(String fieldName, boolean beChecked)
```


Fills the check box field with a boolean value. Notice: Only be applied to Check Box. Please note that Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("checkboxField", true);


 //how to search field by its partial name:
 Form form = new Form("input.pdf", "output.pdf");
 for(String fieldName : form.getFieldNames())
 {
   if (fieldName.endsWith("CheckBoxField"))
   {
     System.out.println("Full name is: " + fieldName);
   }
 }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The field's name to be filled. |
| beChecked | boolean | A boolean flag: true means to check the box, while false to uncheck it. |

**Returns:**
boolean - true if field was found and successfully filled.
### fillField(String fieldName, int index) {#fillField-java.lang.String-int-}
```
public boolean fillField(String fieldName, int index)
```


Fills the radio box field with a valid index value according to a fully qualified field name. Before filling the fields, only field's name must be known. While the value can be specified by its index. Notice: Only be applied to Radio Box, Combo Box and List Box fields. Please note that Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.ListBoxField" you should specify full name and not "ListBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name.

--------------------

```
//1
 Form form = new Form("PdfForm.pdf");
 form.fillField("listboxField", 2);
 form.fillField("comboboxField", 2);
 form.fillField("radiobuttonField", 2);

 //2
 //how to search field by its partial name:
 Form form = new Form("input.pdf", "output.pdf");
 for(String fieldName : form.getFieldNames())
 {
   if (fieldName.endsWith("ListBoxField"))
   {
     System.out.println("Full name is: " + fieldName);
   }
 }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of field to be filled. |
| index | int | Index of chosen item. |

**Returns:**
boolean - true if field was found and successfully filled.
### fillField(String fieldName, String fieldValue) {#fillField-java.lang.String-java.lang.String-}
```
public boolean fillField(String fieldName, String fieldValue)
```


Fills the field with a valid value according to a fully qualified field name. Before filling the fields, every field's names and its corresponding valid values must be known. Both the fields' name and values are case sensitive. Please note that Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.TextField" you should specify full name and not "TextField". You can use FieldNames property to explore existing field names and search required field by its partial name.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.fillField("FirstName", "John");
 form.fillField("LastName",  "Smith");


 //how to search field by its partial name:
 Form form = new Form("input.pdf", "output.pdf");
 for(String fieldName : form.getFieldNames())
 {
   if (fieldName.endsWith("TextField"))
   {
     System.out.println("Full name is: " + fieldName);
   }
 }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The field's name to be filled. |
| fieldValue | java.lang.String | The field's value which must be a valid value for some fields. |

**Returns:**
boolean - true if field is found and filled successfully.
### fillField(String fieldName, String value, boolean fitFontSize) {#fillField-java.lang.String-java.lang.String-boolean-}
```
public boolean fillField(String fieldName, String value, boolean fitFontSize)
```


Fills field with specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of field |
| value | java.lang.String | New value of the field |
| fitFontSize | boolean | If true, the font size in the edit boxes will be fitted. |

**Returns:**
boolean - true if field was found and successfully filled.
### fillField(String fieldName, String[] fieldValues) {#fillField-java.lang.String-java.lang.String---}
```
public void fillField(String fieldName, String[] fieldValues)
```


Fill a field with multiple selections.Note: only for AcroForm List Box Field.

--------------------

```
Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf");
 form.fillField("ListBox1", new String[] { "Three", "One" });
 form.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |
| fieldValues | java.lang.String[] | A String array which contains several items to be selected. |

### flattenAllFields() {#flattenAllFields--}
```
public void flattenAllFields()
```


Flattens all the fields.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.flattenAllFields();
```

### flattenField(String fieldName) {#flattenField-java.lang.String-}
```
public void flattenField(String fieldName)
```


Flattens a specified field with the fully qualified field name. Any other field will remain unchangable. If the fieldName is invalid, all the fields will remain unchangable.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.flattenField("textField");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The name of the field to be flattened. |

### getAttachmentName() {#getAttachmentName--}
```
public String getAttachmentName()
```


Gets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Returns:**
java.lang.String - string object
### getButtonOptionCurrentValue(String fieldName) {#getButtonOptionCurrentValue-java.lang.String-}
```
public String getButtonOptionCurrentValue(String fieldName)
```


Returns the current value for radio button option fields.

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println(form.GetButtonOptionCurrentValue("btnField"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Field Name |

**Returns:**
java.lang.String - String value for the current radio group optino. See also  GetButtonOptionValues 
### getButtonOptionValues(String fieldName) {#getButtonOptionValues-java.lang.String-}
```
public Hashtable<String,String> getButtonOptionValues(String fieldName)
```


Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups.

--------------------

```
Form form = new Form("PdfForm.pdf");
     java.util.Map values = form.getButtonOptionValues("Color");
     System.out.println(values.get("White").toString());
     System.out.println(values.get("Black").toString());
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Field Name |

**Returns:**
java.util.Hashtable<java.lang.String,java.lang.String> - Hash table of option values keyed by form item name
### getContentDisposition() {#getContentDisposition--}
```
public int getContentDisposition()
```


Gets or sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Returns:**
int - ContentDisposition element
### getDestFileName() {#getDestFileName--}
```
public String getDestFileName()
```


Gets destination file name.

**Returns:**
java.lang.String - string object
### getDestStream() {#getDestStream--}
```
public OutputStream getDestStream()
```


Gets or sets destination stream.

**Returns:**
java.io.OutputStream - OutputStream object
### getField(String fieldName) {#getField-java.lang.String-}
```
public String getField(String fieldName)
```


Gets the field's value according to its field name.

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println("Field value = " + form.getField("Field1"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |

**Returns:**
java.lang.String - The field's value.
### getFieldFacade(String fieldName) {#getFieldFacade-java.lang.String-}
```
public FormFieldFacade getFieldFacade(String fieldName)
```


Returns FrofmFieldFacade object containing all appearance attributes.

--------------------

```
com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf"));
 FormFieldFacade field = form.getFieldFacade("field1");
 System.out.println("Color of field border: " + field.getBorderColor());
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of field to read. |

**Returns:**
[FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) - FormFieldFacade object
### getFieldFlag(String fieldName) {#getFieldFlag-java.lang.String-}
```
public int getFieldFlag(String fieldName)
```


Returns flags of the field.

--------------------

```
Form form = new Form("PdfForm.pdf");
 if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly)
 {
    System.out.println("Field is read-only");
 }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Field name |

**Returns:**
int - Property flag (ReadOnly/ Required/NoExport
### getFieldLimit(String fieldName) {#getFieldLimit-java.lang.String-}
```
public int getFieldLimit(String fieldName)
```


Get the limitation of text field.

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println(form.getFieldLimit("textfieldBox"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The qualified field name. |

**Returns:**
int - Return the limitation number of characters a text field can be filled. It not set, return 0.
### getFieldNames() {#getFieldNames--}
```
public String[] getFieldNames()
```


Gets list of field names on the form.

--------------------

```
Form form = new Form("PdfForm.pdf");
 String[] fields = form.getFieldNames();
 for(String field : fields)
 {
   System.out.println(field);
 }
```

**Returns:**
java.lang.String[] - String[] object
### getFieldType(String fieldName) {#getFieldType-java.lang.String-}
```
public int getFieldType(String fieldName)
```


Returns type of field.

--------------------

```
Form form = new Form("PdfForm.pdf");
 if (form.getFieldType("textField") == FieldType.Text)
 {
    System.out.println("Type of field is text");
 }
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Field name. |

**Returns:**
int - Element of FileType enumeration corresponding to field type.
### getFormSubmitButtonNames() {#getFormSubmitButtonNames--}
```
public String[] getFormSubmitButtonNames()
```


Gets all form submit button names.

--------------------

```
Form form = new Form("PdfForm.pdf");
 String[] submits = form.getFormSubmitButtonNames();
 for(String btn : submits)
 {
   System.out.println(btn);
 }
```

**Returns:**
java.lang.String[] - String[] object
### getFullFieldName(String fieldName) {#getFullFieldName-java.lang.String-}
```
public String getFullFieldName(String fieldName)
```


Gets the full field name according to its short field name.

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println("Full field name is : " + form.getFullFieldName("textField"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |

**Returns:**
java.lang.String - The full field name.
### getImportResult() {#getImportResult--}
```
public AForm.FormImportResult[] getImportResult()
```


Result of last import operation. Array of objects which describe result of import for each field.

**Returns:**
com.aspose.pdf.facades.AForm.FormImportResult[] - FormImportResult[] array
### getRichText(String fieldName) {#getRichText-java.lang.String-}
```
public String getRichText(String fieldName)
```


Get a Rich Text field's value, including the formatting information of every character.

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println(form.getRichText("txtDescriptionRTF"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name of the Rich Text field. |

**Returns:**
java.lang.String - Return a String containing formatting information of the Rich Text field.
### getSaveOptions() {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```


Gets or sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Returns:**
[SaveOptions](../../com.aspose.pdf/saveoptions) - SaveOptions object
### getSrcFileName() {#getSrcFileName--}
```
public String getSrcFileName()
```


Gets source file name.

--------------------

```
Form form = new com.aspose.pdf.Form();
   form.setSrcFileName("file.pdf");
```

**Returns:**
java.lang.String - string object
### getSrcStream() {#getSrcStream--}
```
public InputStream getSrcStream()
```


Gets source stream.

**Returns:**
java.io.InputStream - InputStream object
### getSubmitFlags(String fieldName) {#getSubmitFlags-java.lang.String-}
```
public int getSubmitFlags(String fieldName)
```


Returns the submit button's submission flags

--------------------

```
Form form = new Form("PdfForm.pdf");
 System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " ");
 /// System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Fdf != 0) ? " FDF" : " ");
 System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Pdf != 0) ? " PDF" : " ");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The qualified field name. |

**Returns:**
int - Submission flags of the button.
### importFdf(InputStream inputFdfStream) {#importFdf-java.io.InputStream-}
```
public void importFdf(InputStream inputFdfStream)
```


Imports the content of the fields from the fdf file and put them into the new pdf.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
 form.importFdf(new FileInputStream("data.fdf"));
 form.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFdfStream | java.io.InputStream | The input fdf stream. |

### importXfdf(InputStream inputXfdfStream) {#importXfdf-java.io.InputStream-}
```
public void importXfdf(InputStream inputXfdfStream)
```


Imports the content of the fields from the xfdf(xml) file and put them into the new pdf.

--------------------

```
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
 InputStream fs = new FileInputStream("export_old.xfdf");
 form.importXfdf(fs);
 fs.close();
 form.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputXfdfStream | java.io.InputStream | The input xfdf(xml) stream. |

### importXml(InputStream inputXmlStream) {#importXml-java.io.InputStream-}
```
public void importXml(InputStream inputXmlStream)
```


Imports the content of the fields from the xml file and put them into the new pdf.

--------------------

```
Form form = new Form("PdfForm.pdf");
 InputStream fs = new FileInputStream("import.xml");
 form.importXml(fs);
 form.save("Form_Imported.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | Stream from which XML for import is read. |

### importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges) {#importXml-java.io.InputStream-boolean-}
```
public void importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)
```


Imports the content of the fields from the xml file and put them into the new pdf.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | The input xml stream. |
| IgnoreFormTemplateChanges | boolean | If this parameter is true then all changes of the XFA form template will not be saved |

### isRequiredField(String fieldName) {#isRequiredField-java.lang.String-}
```
public boolean isRequiredField(String fieldName)
```


Determines whether field is required or not.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The name of field. |

**Returns:**
boolean - True - the field is required; otherwise, false.
### renameField(String fieldName, String newFieldName) {#renameField-java.lang.String-java.lang.String-}
```
public void renameField(String fieldName, String newFieldName)
```


Renames a field. Either AcroForm field or XFA field is OK.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
 form.renameField("field", "field1");
 form.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | the old field name |
| newFieldName | java.lang.String | the new field name |

### save() {#save--}
```
public void save()
```


Saves the value of the filled fields and close the opened Pdf document.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf");
 form.fillField("textField", "new value");
 form.save();
```

### save(OutputStream destStream) {#save-java.io.OutputStream-}
```
public void save(OutputStream destStream)
```


Saves document into specified stream.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destStream | java.io.OutputStream | Stream where document will be saved. |

### save(String destFile) {#save-java.lang.String-}
```
public void save(String destFile)
```


Saves document into specified file.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| destFile | java.lang.String | File where document will be saved. |

### setAttachmentName(String value) {#setAttachmentName-java.lang.String-}
```
public void setAttachmentName(String value)
```


Sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setContentDisposition(int value) {#setContentDisposition-int-}
```
public void setContentDisposition(int value)
```


Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | ContentDisposition element |

### setConvertTo(int value) {#setConvertTo-int-}
```
public void setConvertTo(int value)
```


Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | PdfFormat element |

### setDestFileName(String value) {#setDestFileName-java.lang.String-}
```
public void setDestFileName(String value)
```


Sets destination file name.

--------------------

```
Form form = new com.aspose.pdf.Form();
   form.setDestFileName("file.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String object |

### setDestStream(OutputStream value) {#setDestStream-java.io.OutputStream-}
```
public void setDestStream(OutputStream value)
```


Gets destination stream.

--------------------

```
Form form = new com.aspose.pdf.Form();
   form.setDestStream (new FileInputStream("file.pdf"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.OutputStream | OutputStream object |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions(SaveOptions value)
```


Gets or sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) | SaveOptions object |

### setSrcFileName(String value) {#setSrcFileName-java.lang.String-}
```
public void setSrcFileName(String value)
```


Sets source file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | string object |

### setSrcStream(InputStream value) {#setSrcStream-java.io.InputStream-}
```
public void setSrcStream(InputStream value)
```


Gets source stream.

--------------------

```
Form form = new com.aspose.pdf.Form();
  form.setSrcStream (new FileInputStream("source.pdf")));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream | InputStream object |

### setXfaData(InputStream inputXmlStream) {#setXfaData-java.io.InputStream-}
```
public void setXfaData(InputStream inputXmlStream)
```


Replaces XFA data with specified data packet. Data packet may be extracted using ExtractXfaData.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | Stream where XML is stored. |

