---
title: IForm
second_title: Aspose.PDF for Java API Reference
description: Class representing Acro form object.
type: docs
weight: 250
url: /java/com.aspose.pdf.facades/iform/
---
```
public interface IForm extends com.aspose.ms.System.IDisposable, Closeable
```

Class representing Acro form object.

## Methods

| Method | Description |
| --- | --- |
| [close](#close--) | Closes opened files without any changes. |
| [exportFdf](#exportFdf-java.io.OutputStream-) | Exports the content of the fields of the pdf into the fdf stream. |
| [exportXfdf](#exportXfdf-java.io.OutputStream-) | Exports the content of the fields of the pdf into the xml stream. |
| [exportXml](#exportXml-java.io.OutputStream-) | Exports the content of the fields of the pdf into the xml stream. |
| [fillBarcodeField](#fillBarcodeField-java.lang.String-java.lang.String-) | Fill a barcode field according to its fully qualified field name. |
| [fillField](#fillField-java.lang.String-boolean-) | Fills the check box field with a boolean value. |
| [fillField](#fillField-java.lang.String-int-) | Fills the radio box field with a valid index value according to a fully qualified field name. |
| [fillField](#fillField-java.lang.String-java.lang.String-) | Fills the field with a valid value according to a fully qualified field name. |
| [fillField](#fillField-java.lang.String-java.lang.String:A-) | Fill a field with multiple selections.Note: only for AcroForm List Box Field. |
| [fillField](#fillField-java.lang.String-java.lang.String-boolean-) | FillField |
| [fillImageField](#fillImageField-java.lang.String-java.io.InputStream-) | Overloads function of FillImageField. |
| [fillImageField](#fillImageField-java.lang.String-java.lang.String-) | Pastes an image onto the existing button field as its appearance according to its fully qualified field name. |
| [flattenAllFields](#flattenAllFields--) | Flattens all the fields. |
| [flattenField](#flattenField-java.lang.String-) | Flattens a specified field with the fully qualified field name. |
| [getAttachmentName](#getAttachmentName--) | Gets or sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getButtonOptionCurrentValue](#getButtonOptionCurrentValue-java.lang.String-) | Returns the current value for radio button option fields. |
| [getButtonOptionValues](#getButtonOptionValues-java.lang.String-) | Gets the radio button option fields and related values based on the field name. |
| [getButtonOptionValuesInternal](#getButtonOptionValuesInternal-java.lang.String-) | Gets the radio button option fields and related values based on the field name. |
| [getContentDisposition](#getContentDisposition--) | Gets or sets how content will be stored when result of operation is stored into HttpResponse object. |
| [getDestFileName](#getDestFileName--) | Gets destination file name. |
| [getDestStream](#getDestStream--) | Gets destination stream. |
| [getDocument](#getDocument--) | Gets the document Form is working on. |
| [getField](#getField-java.lang.String-) | Gets the field's value according to its field name. |
| [getFieldFacade](#getFieldFacade-java.lang.String-) | Returns FrofmFieldFacade object containing all appearance attributes. |
| [getFieldFlag](#getFieldFlag-java.lang.String-) | Returns flags of the field. |
| [getFieldLimit](#getFieldLimit-java.lang.String-) | Get the limitation of text field. |
| [getFieldNames](#getFieldNames--) | Gets list of field names on the form. |
| [getFieldType](#getFieldType-java.lang.String-) | Returns type of field. |
| [getFormSubmitButtonNames](#getFormSubmitButtonNames--) | Gets all form submit button names. |
| [getFullFieldName](#getFullFieldName-java.lang.String-) | Gets the full field name according to its short field name. |
| [getRichText](#getRichText-java.lang.String-) | Get a Rich Text field's value, including the formattinf information of every character. |
| [getSaveOptions](#getSaveOptions--) | Gets or sets save options when result is stored as HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Gets source file name. |
| [getSrcStream](#getSrcStream--) | Gets source stream. |
| [getSubmitFlags](#getSubmitFlags-java.lang.String-) | Returns the submit button's submission flags |
| [importFdf](#importFdf-java.io.InputStream-) | Imports the content of the fields from the fdf file and put them into the new pdf. |
| [importXfdf](#importXfdf-java.io.InputStream-) | Imports the content of the fields from the xfdf(xml) file and put them into the new pdf. |
| [importXml](#importXml-java.io.InputStream-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [importXml](#importXml-java.io.InputStream-boolean-) | Imports the content of the fields from the xml file and put them into the new pdf. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Renames a field. |
| [save](#save--) | Saves the value of the filled fields and close the opened Pdf document. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Sets how content will be stored when result of operation is stored into HttpResponse object. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets PDF file format. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Sets destination file name. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Gets destination stream. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Gets or sets save options when result is stored as HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Sets source file name. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Gets source stream. |

### close {#close--}
```
void close()
```

Closes opened files without any changes.

### exportFdf {#exportFdf-java.io.OutputStream-}
Exports the content of the fields of the pdf into the fdf stream.

### exportXfdf {#exportXfdf-java.io.OutputStream-}
Exports the content of the fields of the pdf into the xml stream.

### exportXml {#exportXml-java.io.OutputStream-}
Exports the content of the fields of the pdf into the xml stream.

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
FillField

### fillImageField {#fillImageField-java.lang.String-java.io.InputStream-}
Overloads function of FillImageField.

### fillImageField {#fillImageField-java.lang.String-java.lang.String-}
Pastes an image onto the existing button field as its appearance according to its fully qualified field name.

### flattenAllFields {#flattenAllFields--}
```
void flattenAllFields()
```

Flattens all the fields.

### flattenField {#flattenField-java.lang.String-}
Flattens a specified field with the fully qualified field name.

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Gets or sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

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
ContentDisposition getContentDisposition()
```

Gets or sets how content will be stored when result of operation is stored into HttpResponse object.

**Returns:**
ContentDisposition element

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Gets destination file name.

**Returns:**
String object

### getDestStream {#getDestStream--}
```
OutputStream getDestStream()
```

Gets destination stream.

**Returns:**
OutputStream object

### getDocument {#getDocument--}
```
IDocument getDocument()
```

Gets the document Form is working on.

**Returns:**
IDocument object

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
String [] getFieldNames()
```

Gets list of field names on the form.

**Returns:**
String[] object

### getFieldType {#getFieldType-java.lang.String-}
Returns type of field.

### getFormSubmitButtonNames {#getFormSubmitButtonNames--}
```
String [] getFormSubmitButtonNames()
```

Gets all form submit button names.

**Returns:**
String[] object

### getFullFieldName {#getFullFieldName-java.lang.String-}
Gets the full field name according to its short field name.

### getRichText {#getRichText-java.lang.String-}
Get a Rich Text field's value, including the formattinf information of every character.

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Gets or sets save options when result is stored as HttpResponse.

**Returns:**
SaveOptions object

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Gets source file name.

**Returns:**
String object

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
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

### renameField {#renameField-java.lang.String-java.lang.String-}
Renames a field.

### save {#save--}
```
void save()
```

Saves the value of the filled fields and close the opened Pdf document.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Sets how content will be stored when result of operation is stored into HttpResponse object.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Sets PDF file format.

### setDestFileName {#setDestFileName-java.lang.String-}
Sets destination file name.

### setDestStream {#setDestStream-java.io.OutputStream-}
Gets destination stream.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Gets or sets save options when result is stored as HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Sets source file name.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Gets source stream.
