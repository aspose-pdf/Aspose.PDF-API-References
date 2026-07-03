---
title: FormWeb
second_title: Aspose.PDF for Java API Reference
description: Representing Acro form Interface.
type: docs
weight: 230
url: /java/com.aspose.pdf.facades/formweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IForm, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormWeb extends SaveableFacade implements IForm
```

Representing Acro form Interface.

## Constructors

| Constructor | Description |
| --- | --- |
| [FormWeb](#FormWeb--) | <p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-) | <p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-) | <p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.io.OutputStream-) | <p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.io.InputStream-java.lang.String-) | <p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-) | <p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.io.OutputStream-) | <p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |
| [FormWeb](#FormWeb-java.lang.String-java.lang.String-) | <p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre> |

## Methods

| Method | Description |
| --- | --- |
| [bindPdf](#bindPdf-java.io.InputStream-java.lang.String-) | Initializes the facade. |
| [bindPdf](#bindPdf-java.lang.String-java.lang.String-) | Initializes the facade. |
| [close](#close--) | Closes all opened resources used by this document. |
| [dispose](#dispose--) | Deprecated. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Exports the content of the fields of the pdf into the fdf stream. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Exports the content of the fields of the pdf into the xml stream. |
| [exportXml](#exportXml-java.io.OutputStream-) | Exports the content of the fields of the pdf into the xml stream. |
| [extractXfaData](#extractXfaData-java.io.OutputStream-) | Extracts XFA data packet |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Fill a barcode field according to its fully qualified field name. |
| [fillField](#fillField-java.lang.String-boolean-) | Fills the check box field with a boolean value. |
| [fillField](#fillField-java.lang.String-int-) | Fills the radio box field with a valid index value according to a fully qualified field name. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Fills the field with a valid value according to a fully qualified field name. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Fill a field with multiple selections.Note: only for AcroForm List Box Field. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | Fills field with specified value. |
| [fillFields](#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-) | Fills the text box fields with a text values and save the document. |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Overloads function of FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Pastes an image onto the existing button field as its appearance according to its fully qualified field name. |
| [flattenAllFields](#flattenAllFields--) | Flattens all the fields. |
| [flattenField](#flattenField-java.lang.String-) | Flattens a specified field with the fully qualified field name. |
| [getAttachmentName](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Returns the current value for radio button option fields. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Gets the radio button option fields and related values based on the field name. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Gets the radio button option fields and related values based on the field name. |
| [getContentDisposition](#getContentDisposition--) | Getshow content will be stored when result of operation is stored into HttpResponse object. |
| [getDestFileName](#getDestFileName--) | Deprecated. |
| [getDestStream](#getDestStream--) | Deprecated. |
| [getField](#getField-java.lang.String-) | Gets the field's value according to its field name. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Returns FrofmFieldFacade object containing all appearance attributes. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Returns flags of the field. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Get the limitation of text field. |
| [getFieldNames](#getFieldNames--) | Gets list of field names on the form. |
| [getFieldType](#getFieldType-java.lang.String-) | Returns type of field. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Gets all form submit button names. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Gets the full field name according to its short field name. |
| [getImportResult](#getImportResult--) | Result of last import operation. |
| [getResponse](#getResponse--) | Gets or sets Response object where result of operation will be stored. |
| [getRichText](#getRichText-java.lang.String-) | Get a Rich Text field's value, including the formattinf information of every character. |
| [getSaveOptions](#getSaveOptions--) | Gets or sets save options when result is stored as HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Deprecated. |
| [getSrcStream](#getSrcStream--) | Gets source stream. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Returns the submit button's submission flags |
| [importFdf](#importFdf-java.io.InputStream-) | Imports the content of the fields from the fdf file and put them into the new pdf. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Imports the content of the fields from the xfdf(xml) file and put them into the new pdf. |
| [importXml](#importXml-java.io.InputStream-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [importXml](#importXml-java.lang.String-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [isRequiredField](#isRequiredField-java.lang.String-) | Determines whether field is required or not. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Renames a field. |
| [save](#save--) | <p> Saves the value of the filled fields and close the opened Pdf document. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.io.OutputStream-) | <p> Saves the value of the filled fields and close the opened Pdf document. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [save](#save-java.lang.String-) | <p> Saves the value of the filled fields and close the opened Pdf document. </p> <hr> <pre> Form form = new Form("PdfForm.pdf", "PdfForm_Changed.pdf"); form.fillField("textField", "new value"); form.save(); </pre> |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Sets how content will be stored when result of operation is stored into HttpResponse object. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets PDF file format. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Deprecated. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Deprecated. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Gets or sets Response object where result of operation will be stored. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Gets or sets save options when result is stored as HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Deprecated. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Gets source stream. |
| [setXfaData](#setXfaData-java.io.InputStream-) | Replaces XFA data with specified data packet. |

### FormWeb {#FormWeb--}
```
public FormWeb()
```

<p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-}
<p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-}
<p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.io.OutputStream-}
<p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.io.InputStream-java.lang.String-}
<p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-}
<p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.io.OutputStream-}
<p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### FormWeb {#FormWeb-java.lang.String-java.lang.String-}
<p> Construtcor of FormWeb without parameters. </p> <hr> <pre> FormWeb FormWeb = new com.aspose.pdf.facades.FormWeb(); FormWeb.setSrcFileName("file.pdf"); </pre>

### bindPdf {#bindPdf-java.io.InputStream-java.lang.String-}
Initializes the facade.

### bindPdf {#bindPdf-java.lang.String-java.lang.String-}
Initializes the facade.

### close {#close--}
```
public void close()
```

Closes all opened resources used by this document.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Deprecated.

### exportFdf {#exportFdf-java.io.OutputStream-}
Exports the content of the fields of the pdf into the fdf stream.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Exports the content of the fields of the pdf into the xml stream.

### exportXml {#exportXml-java.io.OutputStream-}
Exports the content of the fields of the pdf into the xml stream.

### extractXfaData {#extractXfaData-java.io.OutputStream-}
Extracts XFA data packet

### fillBarcodeField {#fillBarcodeField-java.lang.String-java.lang.String-}
Fill a barcode field according to its fully qualified field name.

### fillField {#fillField-java.lang.String-boolean-}
Fills the check box field with a boolean value.

### fillField {#fillField-java.lang.String-int-}
Fills the radio box field with a valid index value according to a fully qualified field name.

### fillField {#fillField-java.lang.String-java.lang.String-}
Fills the field with a valid value according to a fully qualified field name.

### fillField {#fillField-java.lang.String-java.lang.String:A-}
Fill a field with multiple selections.Note: only for AcroForm List Box Field.

### fillField {#fillField-java.lang.String-java.lang.String-boolean-}
Fills field with specified value.

### fillFields {#fillFields-java.lang.String:A-java.lang.String:A-java.io.OutputStream-}
Fills the text box fields with a text values and save the document.

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Overloads function of FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Pastes an image onto the existing button field as its appearance according to its fully qualified field name.

### flattenAllFields {#flattenAllFields--}
```
public void flattenAllFields()
```

Flattens all the fields.

### flattenField {#flattenField-java.lang.String-}
Flattens a specified field with the fully qualified field name.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Gets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Returns:**
string object

### getButtonOptionCurrentValue {#getButtonOptionCurrentValue-java.lang.String-}
Returns the current value for radio button option fields.

### getButtonOptionValues {#getButtonOptionValues-java.lang.String-}
Gets the radio button option fields and related values based on the field name.

### getButtonOptionValuesInternal {#getButtonOptionValuesInternal-java.lang.String-}
Gets the radio button option fields and related values based on the field name.

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Getshow content will be stored when result of operation is stored into HttpResponse object.

**Returns:**
ContentDisposition element

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Deprecated.

**Returns:**
String object

### getDestStream {#getDestStream--}
```
@Deprecated public OutputStream getDestStream()
```

Deprecated.

**Returns:**
OutputStream object

### getField {#getField-java.lang.String-}
Gets the field's value according to its field name.

### getFieldFacade {#getFieldFacade-java.lang.String-}
Returns FrofmFieldFacade object containing all appearance attributes.

### getFieldFlag {#getFieldFlag-java.lang.String-}
Returns flags of the field.

### getFieldLimit {#getFieldLimit-java.lang.String-}
Get the limitation of text field.

### getFieldNames {#getFieldNames--}
```
public String [] getFieldNames()
```

Gets list of field names on the form.

**Returns:**
String[] object

### getFieldType {#getFieldType-java.lang.String-}
Returns type of field.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
public String [] getFormSubmitButtonNames()
```

Gets all form submit button names.

**Returns:**
String[] object

### getFullFieldName {#getFullFieldName-java.lang.String-}
Gets the full field name according to its short field name.

### getImportResult {#getImportResult--}
```
public com.aspose.pdf.facades.AForm.FormImportResult[] getImportResult()
```

Result of last import operation.

**Returns:**
FormImportResult[] array

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Gets or sets Response object where result of operation will be stored.

**Returns:**
HttpServletResponse object

### getRichText {#getRichText-java.lang.String-}
Get a Rich Text field's value, including the formattinf information of every character.

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Gets or sets save options when result is stored as HttpResponse.

**Returns:**
SaveOptions object

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Deprecated.

**Returns:**
String object

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Gets source stream.

**Returns:**
InputStream object

### getSubmitFlags {#getSubmitFlags-java.lang.String-}
Returns the submit button's submission flags

### importFdf {#importFdf-java.io.InputStream-}
Imports the content of the fields from the fdf file and put them into the new pdf.

### importXfdf {#importXfdf-java.io.InputStream-}
Imports the content of the fields from the xfdf(xml) file and put them into the new pdf.

### importXml {#importXml-java.io.InputStream-}
Imports the content of the fields from the xml file and put them into the new pdf.

### importXml {#importXml-java.io.InputStream-boolean-}
Imports the content of the fields from the xml file and put them into the new pdf.

### importXml {#importXml-java.lang.String-}
Imports the content of the fields from the xml file and put them into the new pdf.

### isRequiredField {#isRequiredField-java.lang.String-}
Determines whether field is required or not.

### renameField {#renameField-java.lang.String-java.lang.String-}
Renames a field.

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
Sets how content will be stored when result of operation is stored into HttpResponse object.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Sets PDF file format.

### setDestFileName {#setDestFileName-java.lang.String-}
Deprecated.

### setDestStream {#setDestStream-java.io.OutputStream-}
Deprecated.

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Gets or sets Response object where result of operation will be stored.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Gets or sets save options when result is stored as HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Deprecated.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Gets source stream.

### setXfaData {#setXfaData-java.io.InputStream-}
Replaces XFA data with specified data packet.
