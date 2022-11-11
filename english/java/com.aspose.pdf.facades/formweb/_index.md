---
title: FormWeb
second_title: Aspose.PDF for Java API Reference
description: Representing Acro form Interface.
type: docs
weight: 29
url: /java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.IVentureLicenseTarget, [com.aspose.pdf.facades.Facade](../../com.aspose.pdf.facades/facade), [com.aspose.pdf.facades.SaveableFacade](../../com.aspose.pdf.facades/saveablefacade), com.aspose.pdf.facades.AForm

**All Implemented Interfaces:**
[com.aspose.pdf.facades.IForm](../../com.aspose.pdf.facades/iform)
```
public final class FormWeb extends AForm implements IForm
```

Representing Acro form Interface.
## Constructors

| Constructor | Description |
| --- | --- |
| [FormWeb()](#FormWeb--) | Construtcor of FormWeb without parameters. |
| [FormWeb(IDocument document)](#FormWeb-com.aspose.pdf.IDocument-) | Initializes new  FormWeb  object on base of the  document . |
| [FormWeb(IDocument document, OutputStream destStream)](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | Initializes new  FormWeb  object on base of the  document . |
| [FormWeb(IDocument document, String destFileName)](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | Initializes new  FormWeb  object on base of the  document . |
| [FormWeb(InputStream srcStream)](#FormWeb-java.io.InputStream-) | Constructor for FormWeb. |
| [FormWeb(InputStream inputStream, HttpServletResponse response)](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | Creates FormWeb which will save result into HttpResponse object. |
| [FormWeb(InputStream srcStream, OutputStream destStream)](#FormWeb-java.io.InputStream-java.io.OutputStream-) | Constructor of FormWeb with two stream parameters. |
| [FormWeb(InputStream srcStream, String destFileName)](#FormWeb-java.io.InputStream-java.lang.String-) | Constructor of FormWeb |
| [FormWeb(String srcFileName)](#FormWeb-java.lang.String-) | Constructor of FormWeb. |
| [FormWeb(String inputFile, HttpServletResponse response)](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | Creates FormWeb which will save result into HttpResponse object. |
| [FormWeb(String srcFileName, OutputStream destStream)](#FormWeb-java.lang.String-java.io.OutputStream-) | Constructor of FormWeb. |
| [FormWeb(String srcFileName, String destFileName)](#FormWeb-java.lang.String-java.lang.String-) | Constructor of FormWeb class. |
## Methods

| Method | Description |
| --- | --- |
| [bindPdf(IDocument srcDoc)](#bindPdf-com.aspose.pdf.IDocument-) | Initializes the facade. |
| [bindPdf(InputStream srcStream)](#bindPdf-java.io.InputStream-) | Initializes the facade. |
| [bindPdf(InputStream srcStream, String password)](#bindPdf-java.io.InputStream-java.lang.String-) | Initializes the facade. |
| [bindPdf(String srcFile)](#bindPdf-java.lang.String-) | Initializes the facade. |
| [bindPdf(String srcFile, String password)](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [close()](#close--) | Closes all opened resources used by this document. |
| [dispose()](#dispose--) | Closes all opened resources used by this document. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
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
| [fillFields(String[] fieldNames, String[] fieldValues, OutputStream output)](#fillFields-java.lang.String---java.lang.String---java.io.OutputStream-) | Fills the text box fields with a text values and save the document. |
| [fillImageField(String fieldName, InputStream imageStream)](#fillImageField-java.lang.String-java.io.InputStream-) | Overloads function of FillImageField. |
| [fillImageField(String fieldName, String imageFileName)](#fillImageField-java.lang.String-java.lang.String-) | Pastes an image onto the existing button field as its appearance according to its fully qualified field name. |
| [flattenAllFields()](#flattenAllFields--) | Flattens all the fields. |
| [flattenField(String fieldName)](#flattenField-java.lang.String-) | Flattens a specified field with the fully qualified field name. |
| [getAttachmentName()](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getButtonOptionCurrentValue(String fieldName)](#getButtonOptionCurrentValue-java.lang.String-) | Returns the current value for radio button option fields. |
| [getButtonOptionValues(String fieldName)](#getButtonOptionValues-java.lang.String-) | Gets the radio button option fields and related values based on the field name. |
| [getButtonOptionValuesInternal(String fieldName)](#getButtonOptionValuesInternal-java.lang.String-) | Gets the radio button option fields and related values based on the field name. |
| [getClass()](#getClass--) |  |
| [getContentDisposition()](#getContentDisposition--) | Getshow content will be stored when result of operation is stored into HttpResponse object. |
| [getDestFileName()](#getDestFileName--) | Gets destination file name. |
| [getDestStream()](#getDestStream--) | Gets or sets destination stream. |
| [getDocument()](#getDocument--) | Gets the document facade is working on. |
| [getField(String fieldName)](#getField-java.lang.String-) | Gets the field's value according to its field name. |
| [getFieldFacade(String fieldName)](#getFieldFacade-java.lang.String-) | Returns FrofmFieldFacade object containing all appearance attributes. |
| [getFieldFlag(String fieldName)](#getFieldFlag-java.lang.String-) | Returns flags of the field. |
| [getFieldLimit(String fieldName)](#getFieldLimit-java.lang.String-) | Get the limitation of text field. |
| [getFieldNames()](#getFieldNames--) | Gets list of field names on the form. |
| [getFieldType(String fieldName)](#getFieldType-java.lang.String-) | Returns type of field. |
| [getFormSubmitButtonNames()](#getFormSubmitButtonNames--) | Gets all form submit button names. |
| [getFullFieldName(String fieldName)](#getFullFieldName-java.lang.String-) | Gets the full field name according to its short field name. |
| [getImportResult()](#getImportResult--) | Result of last import operation. |
| [getResponse()](#getResponse--) | Gets or sets Response object where result of operation will be stored. |
| [getRichText(String fieldName)](#getRichText-java.lang.String-) | Get a Rich Text field's value, including the formattinf information of every character. |
| [getSaveOptions()](#getSaveOptions--) | Gets or sets save options when result is stored as HttpResponse. |
| [getSrcFileName()](#getSrcFileName--) | Gets source file name. |
| [getSrcStream()](#getSrcStream--) | Gets source stream. |
| [getSubmitFlags(String fieldName)](#getSubmitFlags-java.lang.String-) | Returns the submit button's submission flags |
| [hashCode()](#hashCode--) |  |
| [importFdf(InputStream inputFdfStream)](#importFdf-java.io.InputStream-) | Imports the content of the fields from the fdf file and put them into the new pdf. |
| [importXfdf(InputStream inputXfdfStream)](#importXfdf-java.io.InputStream-) | Imports the content of the fields from the xfdf(xml) file and put them into the new pdf. |
| [importXml(InputStream inputXmlStream)](#importXml-java.io.InputStream-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [importXml(InputStream inputXmlStream, boolean IgnoreFormTemplateChanges)](#importXml-java.io.InputStream-boolean-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [importXml(String inputXml)](#importXml-java.lang.String-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [isRequiredField(String fieldName)](#isRequiredField-java.lang.String-) | Determines whether field is required or not. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [renameField(String fieldName, String newFieldName)](#renameField-java.lang.String-java.lang.String-) | Renames a field. |
| [save()](#save--) | Saves the value of the filled fields and close the opened Pdf document. |
| [save(OutputStream destStream)](#save-java.io.OutputStream-) | Saves document into specified stream. |
| [save(String destFile)](#save-java.lang.String-) | Saves document into specified file. |
| [setAttachmentName(String value)](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [setContentDisposition(int value)](#setContentDisposition-int-) | Sets how content will be stored when result of operation is stored into HttpResponse object. |
| [setConvertTo(PdfFormat value)](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets PDF file format. |
| [setDestFileName(String value)](#setDestFileName-java.lang.String-) | Sets destination file name. |
| [setDestStream(OutputStream value)](#setDestStream-java.io.OutputStream-) | Gets destination stream. |
| [setResponse(HttpServletResponse value)](#setResponse-javax.servlet.http.HttpServletResponse-) | Gets or sets Response object where result of operation will be stored. |
| [setSaveOptions(SaveOptions value)](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Gets or sets save options when result is stored as HttpResponse. |
| [setSrcFileName(String value)](#setSrcFileName-java.lang.String-) | Sets source file name. |
| [setSrcStream(InputStream value)](#setSrcStream-java.io.InputStream-) | Gets source stream. |
| [setXfaData(InputStream inputXmlStream)](#setXfaData-java.io.InputStream-) | Replaces XFA data with specified data packet. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### FormWeb() {#FormWeb--}
```
public FormWeb()
```


Construtcor of FormWeb without parameters.

--------------------

```
FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb();
 FormWeb.setSrcFileName("file.pdf");
```

### FormWeb(IDocument document) {#FormWeb-com.aspose.pdf.IDocument-}
```
public FormWeb(IDocument document)
```


Initializes new  FormWeb  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |

### FormWeb(IDocument document, OutputStream destStream) {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
```
public FormWeb(IDocument document, OutputStream destStream)
```


Initializes new  FormWeb  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| destStream | java.io.OutputStream | Destination stream. |

### FormWeb(IDocument document, String destFileName) {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
```
public FormWeb(IDocument document, String destFileName)
```


Initializes new  FormWeb  object on base of the  document .

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | Pdf document. |
| destFileName | java.lang.String | Path of the destination file. |

### FormWeb(InputStream srcStream) {#FormWeb-java.io.InputStream-}
```
public FormWeb(InputStream srcStream)
```


Constructor for FormWeb.

--------------------

```
FormWeb FormWeb = new FormWeb(new FileInputStream("PdfFormWeb.pdf"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | source stream. |

### FormWeb(InputStream inputStream, HttpServletResponse response) {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
```
public FormWeb(InputStream inputStream, HttpServletResponse response)
```


Creates FormWeb which will save result into HttpResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputStream | java.io.InputStream | Stream containing source document. |
| response | javax.servlet.http.HttpServletResponse | HttpResponse object where result will be saved. |

### FormWeb(InputStream srcStream, OutputStream destStream) {#FormWeb-java.io.InputStream-java.io.OutputStream-}
```
public FormWeb(InputStream srcStream, OutputStream destStream)
```


Constructor of FormWeb with two stream parameters. Specify same source and destination stream for incremental update.

--------------------

```
FormWeb FormWeb = new FormWeb(new FileInputStream("InFile.pdf"), new FileOutputStream("OutFile.pdf"));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | Source stream. |
| destStream | java.io.OutputStream | Destination stream. |

### FormWeb(InputStream srcStream, String destFileName) {#FormWeb-java.io.InputStream-java.lang.String-}
```
public FormWeb(InputStream srcStream, String destFileName)
```


Constructor of FormWeb

--------------------

```
FormWeb FormWeb = new FormWeb(new FileInputStream("PdfFormWeb.pdf"), "PdfFormWeb_Updated.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | Source stream. |
| destFileName | java.lang.String | Destination file path. |

### FormWeb(String srcFileName) {#FormWeb-java.lang.String-}
```
public FormWeb(String srcFileName)
```


Constructor of FormWeb.

--------------------

```
FormWeb FormWeb = new FormWeb("PdfFormWeb.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | Source file path. |

### FormWeb(String inputFile, HttpServletResponse response) {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
```
public FormWeb(String inputFile, HttpServletResponse response)
```


Creates FormWeb which will save result into HttpResponse object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputFile | java.lang.String | Name of input file. |
| response | javax.servlet.http.HttpServletResponse | HttpResponse object where result will be stored. |

### FormWeb(String srcFileName, OutputStream destStream) {#FormWeb-java.lang.String-java.io.OutputStream-}
```
public FormWeb(String srcFileName, OutputStream destStream)
```


Constructor of FormWeb.

--------------------

```
FormWeb FormWeb = new FormWeb("PdfFormWeb.pdf", "PdfFormWeb_Updated.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | Source file path. |
| destStream | java.io.OutputStream | Destination file path. |

### FormWeb(String srcFileName, String destFileName) {#FormWeb-java.lang.String-java.lang.String-}
```
public FormWeb(String srcFileName, String destFileName)
```


Constructor of FormWeb class. Specify same source file name and destination file name to perFormWeb incremental update.

--------------------

```
FormWeb FormWeb = new FormWeb("PdfFormWeb.pdf", "PdfFormWeb_Updated.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFileName | java.lang.String | Path of the source file. |
| destFileName | java.lang.String | Path of the destination file. |

### bindPdf(IDocument srcDoc) {#bindPdf-com.aspose.pdf.IDocument-}
```
public void bindPdf(IDocument srcDoc)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcDoc | [IDocument](../../com.aspose.pdf/idocument) | The Document object. |

### bindPdf(InputStream srcStream) {#bindPdf-java.io.InputStream-}
```
public void bindPdf(InputStream srcStream)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcStream | java.io.InputStream | The stream of PDF file. |

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

### bindPdf(String srcFile) {#bindPdf-java.lang.String-}
```
public void bindPdf(String srcFile)
```


Initializes the facade.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| srcFile | java.lang.String | The PDF file. |

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


Closes all opened resources used by this document.

### dispose() {#dispose--}
```
public void dispose()
```


Closes all opened resources used by this document.

This method is obsolete, use close() instead.

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**Returns:**
boolean
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


Fills the check box field with a boolean value. Notice: Only be applied to Check Box. Please note that Aspose.Pdf.Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name.

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
Form form = new Form("PdfForm.pdf");
 form.fillField("listboxField", 2);
 form.fillField("comboboxField", 2);
 form.fillField("radiobuttonField", 2);


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

### fillFields(String[] fieldNames, String[] fieldValues, OutputStream output) {#fillFields-java.lang.String---java.lang.String---java.io.OutputStream-}
```
public final boolean fillFields(String[] fieldNames, String[] fieldValues, OutputStream output)
```


Fills the text box fields with a text values and save the document. Relevant for signed documents. Notice: Only be applied to Text Box. Both the fields' name and values are case sensitive.

--------------------

```
Form form = new Form(dataDir + "SignedPdfForm.pdf");
 form.FillFields(new string[] {"Field1"}, new string[] {"+"}, stream);
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldNames | java.lang.String[] | Names of fields. |
| fieldValues | java.lang.String[] | New values of the fields. |
| output | java.io.OutputStream | Stream where document will be saved. |

**Returns:**
boolean - true if fields was found and successfully filled.
### fillImageField(String fieldName, InputStream imageStream) {#fillImageField-java.lang.String-java.io.InputStream-}
```
public void fillImageField(String fieldName, InputStream imageStream)
```


Overloads function of FillImageField. The input is a image stream.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
 form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read));
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name. |
| imageStream | java.io.InputStream | The image's stream. |

### fillImageField(String fieldName, String imageFileName) {#fillImageField-java.lang.String-java.lang.String-}
```
public void fillImageField(String fieldName, String imageFileName)
```


Pastes an image onto the existing button field as its appearance according to its fully qualified field name.

--------------------

```
Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf");
 form.fillImageField("fieldName", "file.jpg");
 form.save();
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | The fully qualified field name of the image button field. |
| imageFileName | java.lang.String | The path of the image file, relative and absolute are both ok. |

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
java.lang.String
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
### getButtonOptionValuesInternal(String fieldName) {#getButtonOptionValuesInternal-java.lang.String-}
```
public System.Collections.Generic.Dictionary<String,String> getButtonOptionValuesInternal(String fieldName)
```


Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups.

--------------------

```
Form form = new Form("PdfForm.pdf");
 Hashtable values = form.getButtonOptionValues("Color");
 System.out.println(values["White"].toString());
 System.out.println(values["Black"].toString());
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Field Name |

**Returns:**
[Dictionary](../../com.aspose.ms.system.collections.generic/dictionary) - Hash table of option values keyed by form item name
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getContentDisposition() {#getContentDisposition--}
```
public int getContentDisposition()
```


Getshow content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Returns:**
int
### getDestFileName() {#getDestFileName--}
```
public String getDestFileName()
```


Gets destination file name.

**Returns:**
java.lang.String - String object
### getDestStream() {#getDestStream--}
```
public OutputStream getDestStream()
```


Gets or sets destination stream.

**Returns:**
java.io.OutputStream
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


Gets the document facade is working on.

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument element
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
java.lang.String[]
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
    System.out.println("_Type of field is text");
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
java.lang.String[]
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


Result of last import operation. Array of objects which descibre result of import for each field.

**Returns:**
com.aspose.pdf.facades.AForm.FormImportResult[] - FormImportResult[] array
### getResponse() {#getResponse--}
```
public HttpServletResponse getResponse()
```


Gets or sets Response object where result of operation will be stored.

**Returns:**
javax.servlet.http.HttpServletResponse - HttpServletResponse object
### getRichText(String fieldName) {#getRichText-java.lang.String-}
```
public String getRichText(String fieldName)
```


Get a Rich Text field's value, including the formattinf information of every character.

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
[SaveOptions](../../com.aspose.pdf/saveoptions)
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
java.lang.String
### getSrcStream() {#getSrcStream--}
```
public InputStream getSrcStream()
```


Gets source stream.

**Returns:**
java.io.InputStream
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
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
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

### importXml(String inputXml) {#importXml-java.lang.String-}
```
public void importXml(String inputXml)
```


Imports the content of the fields from the xml file and put them into the new pdf.

--------------------

```
Form form = new Form("PdfForm.pdf");
 form.importXml("import.xml");
 form.save( "Form_Imported.pdf");
```

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputXml | java.lang.String | Stream from which XML for import is read. |

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
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
| value | int |  |

### setConvertTo(PdfFormat value) {#setConvertTo-com.aspose.pdf.PdfFormat-}
```
public void setConvertTo(PdfFormat value)
```


Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [PdfFormat](../../com.aspose.pdf/pdfformat) |  |

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
| value | java.lang.String |  |

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
| value | java.io.OutputStream |  |

### setResponse(HttpServletResponse value) {#setResponse-javax.servlet.http.HttpServletResponse-}
```
public void setResponse(HttpServletResponse value)
```


Gets or sets Response object where result of operation will be stored.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | javax.servlet.http.HttpServletResponse | HttpServletResponse object |

### setSaveOptions(SaveOptions value) {#setSaveOptions-com.aspose.pdf.SaveOptions-}
```
public void setSaveOptions(SaveOptions value)
```


Gets or sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [SaveOptions](../../com.aspose.pdf/saveoptions) |  |

### setSrcFileName(String value) {#setSrcFileName-java.lang.String-}
```
public void setSrcFileName(String value)
```


Sets source file name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

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
| value | java.io.InputStream |  |

### setXfaData(InputStream inputXmlStream) {#setXfaData-java.io.InputStream-}
```
public void setXfaData(InputStream inputXmlStream)
```


Replaces XFA data with specified data packet. Data packet may be extracted using ExtractXfaData.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| inputXmlStream | java.io.InputStream | Stream where XML is stored. |

### toString() {#toString--}
```
public String toString()
```




**Returns:**
java.lang.String
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |

