---
title: IForm
second_title: Aspose.PDF for Java API Reference
description: Class representing Acro form object.
type: docs
weight: 60
url: /java/com.aspose.pdf.facades/iform/
---
**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable
```
public interface IForm extends System.IDisposable
```

Class representing Acro form object.
## Methods

| Method | Description |
| --- | --- |
| [getSrcFileName()](#getSrcFileName--) | Gets source file name. |
| [setSrcFileName(String value)](#setSrcFileName-java.lang.String-) | Sets source file name. |
| [setConvertTo(int value)](#setConvertTo-int-) | Sets PDF file format. |
| [getDestFileName()](#getDestFileName--) | Gets destiination file name. |
| [setDestFileName(String value)](#setDestFileName-java.lang.String-) | Sets destiination file name. |
| [getSrcStream()](#getSrcStream--) | Gets source stream. |
| [setSrcStream(InputStream value)](#setSrcStream-java.io.InputStream-) | Gets source stream. |
| [getDestStream()](#getDestStream--) | Gets destination stream. |
| [setDestStream(OutputStream value)](#setDestStream-java.io.OutputStream-) | Gets destination stream. |
| [getFieldNames()](#getFieldNames--) | Gets list of field names on the form. |
| [getFormSubmitButtonNames()](#getFormSubmitButtonNames--) | Gets all form submit button names. |
| [getFieldFacade(String fieldName)](#getFieldFacade-java.lang.String-) | Returns FrofmFieldFacade object containing all appearance attributes. |
| [fillField(String fieldName, String fieldValue)](#fillField-java.lang.String-java.lang.String-) | Fills the field with a valid value according to a fully qualified field name. |
| [fillField(String fieldName, int index)](#fillField-java.lang.String-int-) | Fills the radio box field with a valid index value according to a fully qualified field name. |
| [fillField(String fieldName, boolean beChecked)](#fillField-java.lang.String-boolean-) | Fills the check box field with a boolean value. |
| [getButtonOptionCurrentValue(String fieldName)](#getButtonOptionCurrentValue-java.lang.String-) | Returns the current value for radio button option fields. |
| [getButtonOptionValues(String fieldName)](#getButtonOptionValues-java.lang.String-) | Gets the radio button option fields and related values based on the field name. |
| [getField(String fieldName)](#getField-java.lang.String-) | Gets the field's value according to its field name. |
| [getFullFieldName(String fieldName)](#getFullFieldName-java.lang.String-) | Gets the full field name according to its short field name. |
| [getFieldLimit(String fieldName)](#getFieldLimit-java.lang.String-) | Get the limitation of text field. |
| [save()](#save--) | Saves the value of the filled fields and close the opened Pdf document. |
| [close()](#close--) | Closes opened files without any changes. |
| [flattenAllFields()](#flattenAllFields--) | Flattens all the fields. |
| [flattenField(String fieldName)](#flattenField-java.lang.String-) | Flattens a specified field with the fully qualified field name. |
| [fillBarcodeField(String fieldName, String data)](#fillBarcodeField-java.lang.String-java.lang.String-) | Fill a barcode field according to its fully qualified field name. |
| [importFdf(InputStream inputFdfStream)](#importFdf-java.io.InputStream-) | Imports the content of the fields from the fdf file and put them into the new pdf. |
| [exportFdf(OutputStream outputFdfStream)](#exportFdf-java.io.OutputStream-) | Exports the content of the fields of the pdf into the fdf stream. |
| [importXml(InputStream inputXmlStream)](#importXml-java.io.InputStream-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [exportXml(OutputStream outputXmlStream)](#exportXml-java.io.OutputStream-) | Exports the content of the fields of the pdf into the xml stream. |
| [importXfdf(InputStream inputXfdfStream)](#importXfdf-java.io.InputStream-) | Imports the content of the fields from the xfdf(xml) file and put them into the new pdf. |
| [exportXfdf(OutputStream outputXfdfStream)](#exportXfdf-java.io.OutputStream-) | Exports the content of the fields of the pdf into the xml stream. |
| [fillField(String fieldName, String[] fieldValues)](#fillField-java.lang.String-java.lang.String---) | Fill a field with multiple selections.Note: only for AcroForm List Box Field. |
| [renameField(String fieldName, String newFieldName)](#renameField-java.lang.String-java.lang.String-) | Renames a field. |
| [getRichText(String fieldName)](#getRichText-java.lang.String-) | Get a Rich Text field's value, including the formattinf information of every character. |
| [getSubmitFlags(String fieldName)](#getSubmitFlags-java.lang.String-) | Returns the submit button's submission flags |
| [getFieldType(String fieldName)](#getFieldType-java.lang.String-) | Returns type of field. |
| [getFieldFlag(String fieldName)](#getFieldFlag-java.lang.String-) | Returns flags of the field. |
| [getDocument()](#getDocument--) | Gets the document  Form  is working on. |
| [importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)](#importXml-java.io.InputStream-boolean-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [fillField(String fieldName, String value, boolean fitFontSize)](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
### getSrcFileName() {#getSrcFileName--}
```
public abstract String getSrcFileName()
```


Gets source file name.

--------------------

> ```
> Form form = new com.aspose.pdf.Form();
>  form.setSrcFileName("file.pdf");
> ```

**Returns:**
java.lang.String
### setSrcFileName(String value) {#setSrcFileName-java.lang.String-}
```
public abstract void setSrcFileName(String value)
```


Sets source file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### setConvertTo(int value) {#setConvertTo-int-}
```
public abstract void setConvertTo(int value)
```


Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getDestFileName() {#getDestFileName--}
```
public abstract String getDestFileName()
```


Gets destiination file name.

**Returns:**
java.lang.String
### setDestFileName(String value) {#setDestFileName-java.lang.String-}
```
public abstract void setDestFileName(String value)
```


Sets destiination file name.

--------------------

> ```
> Form form = new com.aspose.pdf.Form();
>  form.setDestFileName("file.pdf");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getSrcStream() {#getSrcStream--}
```
public abstract InputStream getSrcStream()
```


Gets source stream.

**Returns:**
java.io.InputStream
### setSrcStream(InputStream value) {#setSrcStream-java.io.InputStream-}
```
public abstract void setSrcStream(InputStream value)
```


Gets source stream.

--------------------

> ```
> Form form = new com.aspose.pdf.Form();
>   form.setSrcStream (new FileInputStream("source.pdf"), FileMode.Open, FileAccess.Read));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.InputStream |  |

### getDestStream() {#getDestStream--}
```
public abstract OutputStream getDestStream()
```


Gets destination stream.

**Returns:**
java.io.OutputStream
### setDestStream(OutputStream value) {#setDestStream-java.io.OutputStream-}
```
public abstract void setDestStream(OutputStream value)
```


Gets destination stream.

--------------------

> ```
> Form form = new com.aspose.pdf.Form();
>  form.DestStream = new FileInputStream("file.pdf", FileMode.Open,
>  		FileAccess.Read);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.io.OutputStream |  |

### getFieldNames() {#getFieldNames--}
```
public abstract String[] getFieldNames()
```


Gets list of field names on the form.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  String[] fields = form.getFieldNames();
>  for (String field : fields) {
>  	System.out.println(field);
>  }
> ```

**Returns:**
java.lang.String[]
### getFormSubmitButtonNames() {#getFormSubmitButtonNames--}
```
public abstract String[] getFormSubmitButtonNames()
```


Gets all form submit button names.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  String[] submits = form.getFormSubmitButtonNames();
>  for (String btn : submits) {
>  	System.out.println(btn);
>  }
> ```

**Returns:**
java.lang.String[]
### getFieldFacade(String fieldName) {#getFieldFacade-java.lang.String-}
```
public abstract FormFieldFacade getFieldFacade(String fieldName)
```


Returns FrofmFieldFacade object containing all appearance attributes.

--------------------

> ```
> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf"));
>  FormFieldFacade field = form.getFieldFacade("field1");
>  System.out.println("Color of field border: " + field.BorderColor);
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of field to read. |

**Returns:**
[FormFieldFacade](../../com.aspose.pdf.facades/formfieldfacade) - FormFieldFacade object
### fillField(String fieldName, String fieldValue) {#fillField-java.lang.String-java.lang.String-}
```
public abstract boolean fillField(String fieldName, String fieldValue)
```


Fills the field with a valid value according to a fully qualified field name. Before filling the fields, every field's names and its corresponding valid values must be known. Both the fields' name and values are case sensitive. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.TextField" you should specify full name and not "TextField". You can use FieldNames property to explore existing field names and search required field by its partial name.

--------------------

> ```
> Form form = new Form(TestSettings.GetInputFile("PdfForm.pdf"));
>  form.fillField("FirstName", "John");
>  form.fillField("LastName", "Smith");
>  
>  
>  
>  // how to search field by its partial name:
>  Form form = new Form("input.pdf", "output.pdf");
>  for (String fieldName : form.getFieldNames()) {
>  	if (fieldName.endsWith("TextField")) {
>  		System.out.println("Full name is: " + fieldName);
>  	}
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The field's name to be filled. |
| fieldValue | java.lang.String | The field's value which must be a valid value for some fields. |

**Returns:**
boolean
### fillField(String fieldName, int index) {#fillField-java.lang.String-int-}
```
public abstract boolean fillField(String fieldName, int index)
```


Fills the radio box field with a valid index value according to a fully qualified field name. Before filling the fields, only field's name must be known. While the value can be specified by its index. Notice: Only be applied to Radio Box, Combo Box and List Box fields. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.ListBoxField" you should specify full name and not "ListBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  form.fillField("listboxField", 2);
>  form.fillField("comboboxField", 2);
>  form.fillField("radiobuttonField", 2);
>  
>  
>  
>  // how to search field by its partial name:
>  Form form = new Form("input.pdf", "output.pdf");
>  for (String fieldName : form.getFieldNames()) {
>  	if (fieldName.endsWith("ListBoxField")) {
>  		System.out.println("Full name is: " + fieldName);
>  	}
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The field's name to be filled. |
| index | int | The selected box's index in the whole radio box group. |

**Returns:**
boolean
### fillField(String fieldName, boolean beChecked) {#fillField-java.lang.String-boolean-}
```
public abstract boolean fillField(String fieldName, boolean beChecked)
```


Fills the check box field with a boolean value. Notice: Only be applied to Check Box. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  form.fillField("checkboxField", true);
>  
>  
>  
>  // how to search field by its partial name:
>  Form form = new Form("input.pdf", "output.pdf");
>  for (String fieldName : form.getFieldNames()) {
>  	if (fieldName.endsWith("CheckBoxField")) {
>  		System.out.println("Full name is: " + fieldName);
>  	}
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The field's name to be filled. |
| beChecked | boolean | A boolean flag: true means to check the box, while false to uncheck it.. |

**Returns:**
boolean
### getButtonOptionCurrentValue(String fieldName) {#getButtonOptionCurrentValue-java.lang.String-}
```
public abstract String getButtonOptionCurrentValue(String fieldName)
```


Returns the current value for radio button option fields.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  System.out.println(form.GetButtonOptionCurrentValue("btnField"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Field Name |

**Returns:**
java.lang.String - String value for the current radio group optino. See also  GetButtonOptionValues 
### getButtonOptionValues(String fieldName) {#getButtonOptionValues-java.lang.String-}
```
public abstract Hashtable<String,String> getButtonOptionValues(String fieldName)
```


Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  Hashtable values = form.getButtonOptionValues("Color");
>  System.out.println(values["White"].toString());
>  System.out.println(values["Black"].toString());
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Field Name |

**Returns:**
java.util.Hashtable<java.lang.String,java.lang.String> - Hash table of option values keyed by form item name
### getField(String fieldName) {#getField-java.lang.String-}
```
public abstract String getField(String fieldName)
```


Gets the field's value according to its field name.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  System.out.println("Field value = " + form.getField("Field1"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |

**Returns:**
java.lang.String - The field's value.
### getFullFieldName(String fieldName) {#getFullFieldName-java.lang.String-}
```
public abstract String getFullFieldName(String fieldName)
```


Gets the full field name according to its short field name.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  System.out
>  		.println("Full field name is : " + form.getFullFieldName("textField"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |

**Returns:**
java.lang.String - The full field name.
### getFieldLimit(String fieldName) {#getFieldLimit-java.lang.String-}
```
public abstract int getFieldLimit(String fieldName)
```


Get the limitation of text field.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  System.out.println(form.getFieldLimit("textfieldBox"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The qualified field name. |

**Returns:**
int - Return the limitation number of characters a text field can be filled. It not set, return 0.
### save() {#save--}
```
public abstract void save()
```


Saves the value of the filled fields and close the opened Pdf document.

--------------------

> ```
> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf");
>  form.fillField("textField", "new value");
>  form.save();
> ```

### close() {#close--}
```
public abstract void close()
```


Closes opened files without any changes.

### flattenAllFields() {#flattenAllFields--}
```
public abstract void flattenAllFields()
```


Flattens all the fields.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  form.flattenAllFields();
> ```

### flattenField(String fieldName) {#flattenField-java.lang.String-}
```
public abstract void flattenField(String fieldName)
```


Flattens a specified field with the fully qualified field name. Any other field will remain unchangable. If the fieldName is invalid, all the fields will remain unchangable.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  form.flattenField("textField");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The name of the field to be flattened. |

### fillBarcodeField(String fieldName, String data) {#fillBarcodeField-java.lang.String-java.lang.String-}
```
public abstract boolean fillBarcodeField(String fieldName, String data)
```


Fill a barcode field according to its fully qualified field name.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  form.fillBarcodeField("textField", "42207252");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |
| data | java.lang.String | The new barcode value. |

**Returns:**
boolean - If filling succeed, return true; otherwise, false.
### importFdf(InputStream inputFdfStream) {#importFdf-java.io.InputStream-}
```
public abstract void importFdf(InputStream inputFdfStream)
```


Imports the content of the fields from the fdf file and put them into the new pdf.

--------------------

> ```
> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
>  form.importFdf(new FileInputStream("data.fdf", FileMode.Open, FileAccess.Read));
>  form.save();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFdfStream | java.io.InputStream | The input fdf stream. |

### exportFdf(OutputStream outputFdfStream) {#exportFdf-java.io.OutputStream-}
```
public abstract void exportFdf(OutputStream outputFdfStream)
```


Exports the content of the fields of the pdf into the fdf stream.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  Stream stream = new FileInputStream("export.fdf", FileMode.Create,
>  		FileAccess.Write);
>  form.exportFdf(stream);
>  stream.Close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputFdfStream | java.io.OutputStream | The output fdf stream. |

### importXml(InputStream inputXmlStream) {#importXml-java.io.InputStream-}
```
public abstract void importXml(InputStream inputXmlStream)
```


Imports the content of the fields from the xml file and put them into the new pdf.

--------------------

> ```
> Form form = new Form("PdfForm.pdf", "Form_Imported.pdf");
>  FileInputStream fs = new FileInputStream(
>  		TestSettings.GetInputFile("import.xml"), FileMode.Open, FileAccess.Read);
>  form.importXml(fs);
>  form.save();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream |  |

### exportXml(OutputStream outputXmlStream) {#exportXml-java.io.OutputStream-}
```
public abstract void exportXml(OutputStream outputXmlStream)
```


Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported.

--------------------

> ```
> Form form = new Form("PdfForm.pdf"));
>  FileOutputStream fs = new FileOutputStream("export.xml");
>  form.exportXml(fs);
>  fs.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputXmlStream | java.io.OutputStream |  |

### importXfdf(InputStream inputXfdfStream) {#importXfdf-java.io.InputStream-}
```
public abstract void importXfdf(InputStream inputXfdfStream)
```


Imports the content of the fields from the xfdf(xml) file and put them into the new pdf.

--------------------

> ```
> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
>  Stream fs = new FileInputStream("export_old.xfdf", FileMode.Open,
>  		FileAccess.Read);
>  form.importXfdf(fs);
>  fs.close();
>  form.save();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputXfdfStream | java.io.InputStream | The input xfdf(xml) stream. |

### exportXfdf(OutputStream outputXfdfStream) {#exportXfdf-java.io.OutputStream-}
```
public abstract void exportXfdf(OutputStream outputXfdfStream)
```


Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  FileInputStream fs = new FileInputStream("export.xfdf", FileMode.Create,
>  		FileAccess.Write);
>  form.exportXfdf(fs);
>  fs.close();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| outputXfdfStream | java.io.OutputStream | The output xml stream. |

### fillField(String fieldName, String[] fieldValues) {#fillField-java.lang.String-java.lang.String---}
```
public abstract void fillField(String fieldName, String[] fieldValues)
```


Fill a field with multiple selections.Note: only for AcroForm List Box Field.

--------------------

> ```
> Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf");
>  form.fillField("ListBox1", new String[] { "Three", "One" });
>  form.save();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |
| fieldValues | java.lang.String[] | A String array which contains several items to be selected. |

### renameField(String fieldName, String newFieldName) {#renameField-java.lang.String-java.lang.String-}
```
public abstract void renameField(String fieldName, String newFieldName)
```


Renames a field. Either AcroForm field or XFA field is OK.

--------------------

> ```
> Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
>  form.renameField("field", "field1");
>  form.save();
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | the old field name |
| newFieldName | java.lang.String | the new field name |

### getRichText(String fieldName) {#getRichText-java.lang.String-}
```
public abstract String getRichText(String fieldName)
```


Get a Rich Text field's value, including the formattinf information of every character.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  System.out.println(form.getRichText("txtDescriptionRTF"));
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name of the Rich Text field. |

**Returns:**
java.lang.String - Return a String containing formatting information of the Rich Text field.
### getSubmitFlags(String fieldName) {#getSubmitFlags-java.lang.String-}
```
public abstract int getSubmitFlags(String fieldName)
```


Returns the submit button's submission flags

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  System.out
>  		.println((form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Xfdf != 0) ? " XFDF"
>  				: " ");
>  // / System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Fdf
>  // != 0) ? " FDF" : " ");
>  System.out
>  		.println((form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Pdf != 0) ? " PDF"
>  				: " ");
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The qualified field name. |

**Returns:**
int
### getFieldType(String fieldName) {#getFieldType-java.lang.String-}
```
public abstract int getFieldType(String fieldName)
```


Returns type of field.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  if (form.GetFieldType("textField") == FieldType.Text) {
>  	System.out.println("Type of field is text");
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Field name. |

**Returns:**
int - Element of FileType enumeration corresponding to field type.
### getFieldFlag(String fieldName) {#getFieldFlag-java.lang.String-}
```
public abstract int getFieldFlag(String fieldName)
```


Returns flags of the field.

--------------------

> ```
> Form form = new Form("PdfForm.pdf");
>  if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) {
>  	System.out.println("Field is read-only");
>  }
> ```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Field name |

**Returns:**
int - Property flag (ReadOnly/ Required/NoExport
### getDocument() {#getDocument--}
```
public abstract IDocument getDocument()
```


Gets the document  Form  is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument)
### importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges) {#importXml-java.io.InputStream-boolean-}
```
public abstract void importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)
```


Imports the content of the fields from the xml file and put them into the new pdf.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | The input xml stream. |
| IgnoreFormTemplateChanges | boolean | If this parameter is true then all changes of the XFA form template will not be saved |

### fillField(String fieldName, String value, boolean fitFontSize) {#fillField-java.lang.String-java.lang.String-boolean-}
```
public abstract boolean fillField(String fieldName, String value, boolean fitFontSize)
```


FillField

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of field |
| value | java.lang.String | New value of the field |
| fitFontSize | boolean | If true, the font size in the edit boxes will be fitted. |

**Returns:**
boolean - 
