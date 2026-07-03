---
title: Form
second_title: Aspose.PDF for Java API Reference
description: Class representing Acro form object.
type: docs
weight: 170
url: /java/com.aspose.pdf.facades/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.Form, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.Form

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class Form extends SaveableFacade
```

Class representing Acro form object.

## Constructors

| Constructor | Description |
| --- | --- |
| [Form](#Form--) | <p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-) | <p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-com.aspose.pdf.IDocument-java.lang.String-) | <p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.io.InputStream-) | <p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.io.InputStream-java.io.OutputStream-) | <p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.io.InputStream-java.lang.String-) | <p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.lang.String-) | <p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.lang.String-java.io.OutputStream-) | <p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |
| [Form](#Form-java.lang.String-java.lang.String-) | <p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre> |

## Methods

| Method | Description |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Initializes the facade. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [close](#close--) | Closes opened files without any changes. |
| [dispose](#dispose--) | Closes all opened resources. This method is obsolete, use close() instead. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | <p> Exports the content of the fields of the pdf into the fdf stream. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); OutputStream stream = new FileOutputStream("export.fdf"); form.exportFdf(stream); stream.close(); </pre> |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | <p> Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); FileInputStream fs = new FileInputStream("export.xfdf", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre> |
| [exportXml](#exportXml-java.io.OutputStream-) | <p> Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported. </p> <hr> <pre> Form form = new Form("PdfForm.pdf")); OutputStream fs = new FileOutputStream("export.xml"); form.exportXml(fs); fs.close(); </pre> |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Extracts XFA data packet |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | <p> Fill a barcode field according to its fully qualified field name. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillBarcodeField("textField", "42207252"); </pre> |
| [fillField](#fillField-java.lang.String-boolean-) | <p> Fills the check box field with a boolean value. Notice: Only be applied to Check Box. Please note that Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("checkboxField", true); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("CheckBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-int-) | <p> Fills the radio box field with a valid index value according to a fully qualified field name. Before filling the fields, only field's name must be known. While the value can be specified by its index. Notice: Only be applied to Radio Box, Combo Box and List Box fields. Please note that Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.ListBoxField" you should specify full name and not "ListBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name. </p> <hr> <pre> //1 Form form = new Form("PdfForm.pdf"); form.fillField("listboxField", 2); form.fillField("comboboxField", 2); form.fillField("radiobuttonField", 2); //2 //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("ListBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-) | <p> Fills the field with a valid value according to a fully qualified field name. Before filling the fields, every field's names and its corresponding valid values must be known. Both the fields' name and values are case sensitive. Please note that Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.TextField" you should specify full name and not "TextField". You can use FieldNames property to explore existing field names and search required field by its partial name. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("FirstName", "John"); form.fillField("LastName", "Smith"); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("TextField")) { System.out.println("Full name is: " + fieldName); } } </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | <p> Fill a field with multiple selections.Note: only for AcroForm List Box Field. </p> <hr> <pre> Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf"); form.fillField("ListBox1", new String[] { "Three", "One" }); form.save(); </pre> |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Fills field with specified value. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Fills the text box fields with a text values and save the document. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | <p> Overloads function of FillImageField. The input is a image stream. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read)); </pre> |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | <p> Pastes an image onto the existing button field as its appearance according to its fully qualified field name. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", "file.jpg"); form.save(); </pre> |
| [flattenAllFields](#flattenAllFields--) | <p> Flattens all the fields. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenAllFields(); </pre> |
| [flattenField](#flattenField-java.lang.String-) | <p> Flattens a specified field with the fully qualified field name. Any other field will remain unchangeable. If the fieldName is invalid, all the fields will remain unchangeable. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre> |
| [getAttachmentName](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | <p> Returns the current value for radio button option fields. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre> |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | <p> Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre> |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | <p> Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre> |
| [getContentDisposition](#getContentDisposition--) | Gets or sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [getDestFileName](#getDestFileName--) | Gets destination file name. |
| [getDestStream](#getDestStream--) | Gets or sets destination stream. |
| [getField](#getField-java.lang.String-) | <p> Gets the field's value according to its field name. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre> |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | <p> Returns FormFieldFacade object containing all appearance attributes. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre> |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | <p> Returns flags of the field. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre> |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | <p> Get the limitation of text field. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre> |
| [getFieldNames](#getFieldNames--) | <p> Gets list of field names on the form. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre> |
| [getFieldType](#getFieldType-java.lang.String-) | <p> Returns type of field. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre> |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | <p> Gets all form submit button names. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre> |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | <p> Gets the full field name according to its short field name. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre> |
| [getImportResult](#getImportResult--) | Result of last import operation. Array of objects which describe result of import for each field. |
| [getRichText](#getRichText-java.lang.String-) | <p> Get a Rich Text field's value, including the formatting information of every character. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre> |
| [getSaveOptions](#getSaveOptions--) | Gets or sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions. |
| [getSrcFileName](#getSrcFileName--) | <p> Gets source file name. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre> |
| [getSrcStream](#getSrcStream--) | Gets source stream. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | <p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") \| SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") \| SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") \| SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre> |
| [importFdf](#importFdf-java.io.InputStream-) | <p> Imports the content of the fields from the fdf file and put them into the new pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre> |
| [importXfdf](#importXfdf-java.io.InputStream-) | <p> Imports the content of the fields from the xfdf(xml) file and put them into the new pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre> |
| [importXml](#importXml-java.io.InputStream-) | <p> Imports the content of the fields from the xml file and put them into the new pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre> |
| [importXml](#importXml-java.io.InputStream-boolean-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [importXml](#importXml-java.lang.String-) | <p> Imports the content of the fields from the xml file and put them into the new pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre> |
| [isRequiredField](#isRequiredField-java.lang.String-) | Determines whether field is required or not. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | <p> Renames a field. Either AcroForm field or XFA field is OK. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf"); form.renameField("field", "field1"); form.save(); </pre> |
| [save](#save--) | <p> Saves the value of the filled fields and close the opened Pdf document. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Saves the value of the filled fields and close the opened Pdf document. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Saves the value of the filled fields and close the opened Pdf document. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion. |
| [setDestFileName](#setDestFileName-java.lang.String-) | <p> Sets destination file name. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName("file.pdf"); </pre> |
| [setDestStream](#setDestStream-java.io.OutputStream-) | <p> Gets destination stream. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream("file.pdf")); </pre> |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Gets or sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Sets source file name. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | <p> Gets source stream. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream("source.pdf"))); </pre> |
| [setXfaData](#setXfaData-java.io.InputStream-) | Replaces XFA data with specified data packet. Data packet may be extracted using ExtractXfaData. |

### Form {#Form--}
```
public Form()
```

<p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-}
<p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-com.aspose.pdf.IDocument-java.lang.String-}
<p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.io.InputStream-}
<p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.io.InputStream-java.io.OutputStream-}
<p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.io.InputStream-java.lang.String-}
<p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.lang.String-}
<p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.lang.String-java.io.OutputStream-}
<p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### Form {#Form-java.lang.String-java.lang.String-}
<p> Construtcor of Form without parameters. </p> <hr> <pre> Form form = new com.aspose.pdf.facades.Form(); form.setSrcFileName( "file.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Initializes the facade.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initializes the facade.

### close {#close--}
```
public void close()
```

Closes opened files without any changes.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Closes all opened resources. This method is obsolete, use close() instead.

### exportFdf {#exportFdf-java.io.OutputStream-}
<p> Exports the content of the fields of the pdf into the fdf stream. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); OutputStream stream = new FileOutputStream("export.fdf"); form.exportFdf(stream); stream.close(); </pre>

### exportXfdf {#exportXfdf-java.io.OutputStream-}
<p> Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); FileInputStream fs = new FileInputStream("export.xfdf", FileMode.Create, FileAccess.Write); form.exportXfdf(fs); fs.close(); </pre>

### exportXml {#exportXml-java.io.OutputStream-}
<p> Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported. </p> <hr> <pre> Form form = new Form("PdfForm.pdf")); OutputStream fs = new FileOutputStream("export.xml"); form.exportXml(fs); fs.close(); </pre>

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Extracts XFA data packet

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
<p> Fill a barcode field according to its fully qualified field name. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillBarcodeField("textField", "42207252"); </pre>

### fillField {#fillField-java.lang.String-boolean-}
<p> Fills the check box field with a boolean value. Notice: Only be applied to Check Box. Please note that Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.CheckBoxField" you should specify full name and not "CheckBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("checkboxField", true); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("CheckBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-int-}
<p> Fills the radio box field with a valid index value according to a fully qualified field name. Before filling the fields, only field's name must be known. While the value can be specified by its index. Notice: Only be applied to Radio Box, Combo Box and List Box fields. Please note that Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.ListBoxField" you should specify full name and not "ListBoxField". You can use FieldNames property to explore existing field names and search required field by its partial name. </p> <hr> <pre> //1 Form form = new Form("PdfForm.pdf"); form.fillField("listboxField", 2); form.fillField("comboboxField", 2); form.fillField("radiobuttonField", 2); //2 //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("ListBoxField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String-}
<p> Fills the field with a valid value according to a fully qualified field name. Before filling the fields, every field's names and its corresponding valid values must be known. Both the fields' name and values are case sensitive. Please note that Facades supports only full field names and does not work with partial field names in contrast with Aspose.Pdf.Kit; For example if field has full name "Form.Subform.TextField" you should specify full name and not "TextField". You can use FieldNames property to explore existing field names and search required field by its partial name. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.fillField("FirstName", "John"); form.fillField("LastName", "Smith"); //how to search field by its partial name: Form form = new Form("input.pdf", "output.pdf"); for(String fieldName : form.getFieldNames()) { if (fieldName.endsWith("TextField")) { System.out.println("Full name is: " + fieldName); } } </pre>

### fillField {#fillField-java.lang.String-java.lang.String:A-}
<p> Fill a field with multiple selections.Note: only for AcroForm List Box Field. </p> <hr> <pre> Form form = new com.aspose.pdf.Form("PdfForm.pdf", "Form_Updated.pdf"); form.fillField("ListBox1", new String[] { "Three", "One" }); form.save(); </pre>

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Fills field with specified value.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Fills the text box fields with a text values and save the document.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
<p> Overloads function of FillImageField. The input is a image stream. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", new FileInputStream("file.jpg", FileMode.Open, FileAccess.Read)); </pre>

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
<p> Pastes an image onto the existing button field as its appearance according to its fully qualified field name. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_filled.pdf"); form.fillImageField("fieldName", "file.jpg"); form.save(); </pre>

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

<p> Flattens all the fields. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenAllFields(); </pre>

### flattenField {#flattenField-java.lang.String-}
<p> Flattens a specified field with the fully qualified field name. Any other field will remain unchangeable. If the fieldName is invalid, all the fields will remain unchangeable. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.flattenField("textField"); </pre>

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Gets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Returns:**
string object

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
<p> Returns the current value for radio button option fields. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.GetButtonOptionCurrentValue("btnField")); </pre>

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
<p> Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); java.util.Map values = form.getButtonOptionValues("Color"); System.out.println(values.get("White").toString()); System.out.println(values.get("Black").toString()); </pre>

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
<p> Gets the radio button option fields and related values based on the field name. This method has meaning for radio button groups. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); Hashtable values = form.getButtonOptionValues("Color"); System.out.println(values["White"].toString()); System.out.println(values["Black"].toString()); </pre>

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Gets or sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

**Returns:**
ContentDisposition element @see ContentDisposition

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Gets destination file name.

**Returns:**
string object

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Gets or sets destination stream.

**Returns:**
OutputStream object

### getField {#getField-java.lang.String-}
<p> Gets the field's value according to its field name. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Field value = " + form.getField("Field1")); </pre>

### getFieldFacade {#getFieldFacade-java.lang.String-}
<p> Returns FormFieldFacade object containing all appearance attributes. </p> <hr> <pre> com.aspose.pdf.facades.Form form = new com.aspose.pdf.facades.Form("form.pdf")); FormFieldFacade field = form.getFieldFacade("field1"); System.out.println("Color of field border: " + field.getBorderColor()); </pre>

### getFieldFlag {#getFieldFlag-java.lang.String-}
<p> Returns flags of the field. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldFlag("textField") == ProptyFlag.ReadOnly) { System.out.println("Field is read-only"); } </pre>

### getFieldLimit {#getFieldLimit-java.lang.String-}
<p> Get the limitation of text field. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getFieldLimit("textfieldBox")); </pre>

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

<p> Gets list of field names on the form. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] fields = form.getFieldNames(); for(String field : fields) { System.out.println(field); } </pre>

**Returns:**
String[] object

### getFieldType {#getFieldType-java.lang.String-}
<p> Returns type of field. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); if (form.getFieldType("textField") == FieldType.Text) { System.out.println("Type of field is text"); } </pre>

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

<p> Gets all form submit button names. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); String[] submits = form.getFormSubmitButtonNames(); for(String btn : submits) { System.out.println(btn); } </pre>

**Returns:**
String[] object

### getFullFieldName {#getFullFieldName-java.lang.String-}
<p> Gets the full field name according to its short field name. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println("Full field name is : " + form.getFullFieldName("textField")); </pre>

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Result of last import operation. Array of objects which describe result of import for each field.

**Returns:**
FormImportResult[] array

### getRichText {#getRichText-java.lang.String-}
<p> Get a Rich Text field's value, including the formatting information of every character. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println(form.getRichText("txtDescriptionRTF")); </pre>

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Gets or sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

**Returns:**
SaveOptions object

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

<p> Gets source file name. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcFileName("file.pdf"); </pre>

**Returns:**
string object

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Gets source stream.

**Returns:**
InputStream object

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
<p> Returns the submit button's submission flags </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Xfdf != 0) ? " XFDF" : " "); /// System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Fdf != 0) ? " FDF" : " "); System.out.println( ( form.getSubmitFlags("btnSubmit") | SubmitFormFlag.Pdf != 0) ? " PDF" : " "); </pre>

### importFdf {#importFdf-java.io.InputStream-}
<p> Imports the content of the fields from the fdf file and put them into the new pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf"); form.importFdf(new FileInputStream("data.fdf")); form.save(); </pre>

### importXfdf {#importXfdf-java.io.InputStream-}
<p> Imports the content of the fields from the xfdf(xml) file and put them into the new pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf"); InputStream fs = new FileInputStream("export_old.xfdf"); form.importXfdf(fs); fs.close(); form.save(); </pre>

### importXml {#importXml-java.io.InputStream-}
<p> Imports the content of the fields from the xml file and put them into the new pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); InputStream fs = new FileInputStream("import.xml"); form.importXml(fs); form.save("Form_Imported.pdf"); </pre>

### importXml {#importXml-java.io.InputStream-boolean-}
Imports the content of the fields from the xml file and put them into the new pdf.

### importXml {#importXml-java.lang.String-}
<p> Imports the content of the fields from the xml file and put them into the new pdf. </p> <hr> <pre> Form form = new Form("PdfForm.pdf"); form.importXml("import.xml"); form.save( "Form_Imported.pdf"); </pre>

### isRequiredField {#isRequiredField-java.lang.String-}
Determines whether field is required or not.

### renameField {#renameField-java.lang.String-java.lang.String-}
<p> Renames a field. Either AcroForm field or XFA field is OK. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf"); form.renameField("field", "field1"); form.save(); </pre>

### save {#save--}
```
public void save()
```

<p> Saves the value of the filled fields and close the opened Pdf document. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### save {#save-java.io.OutputStream-}
<p> Saves the value of the filled fields and close the opened Pdf document. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### save {#save-java.lang.String-}
<p> Saves the value of the filled fields and close the opened Pdf document. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre>

### setAttachmentName {#setAttachmentName-java.lang.String-}
Sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Sets how content will be stored when result of operation is stored into HttpResponse object. Possible value: inline / attachment. Default: inline.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Sets PDF file format. Result file will be saved in specified file format. If this property is not specified then file will be save in default PDF format without conversion.

### setDestFileName {#setDestFileName-java.lang.String-}
<p> Sets destination file name. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestFileName("file.pdf"); </pre>

### setDestStream {#setDestStream-java.io.OutputStream-}
<p> Gets destination stream. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setDestStream (new FileInputStream("file.pdf")); </pre>

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Gets or sets save options when result is stored as HttpResponse. Default value: PdfSaveOptions.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Sets source file name.

### setSrcStream {#setSrcStream-java.io.InputStream-}
<p> Gets source stream. </p> <hr> <pre> Form form = new com.aspose.pdf.Form(); form.setSrcStream (new FileInputStream("source.pdf"))); </pre>

### setXfaData {#setXfaData-java.io.InputStream-}
Replaces XFA data with specified data packet. Data packet may be extracted using ExtractXfaData.
