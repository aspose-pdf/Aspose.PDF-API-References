---
title: FormEditorWeb
linktitle: FormEditorWeb
second_title: Aspose.PDF for Java API Reference
description: Class for editing forms (ading/deleting field etc)
type: docs
weight: 210
url: /java/com.aspose.pdf.facades/formeditorweb/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.SaveableFacade com.aspose.pdf.facades.FormEditorWeb, com.aspose.pdf.facades.SaveableFacade, com.aspose.pdf.facades.FormEditorWeb

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, IFormEditor, ISaveableFacade, Closeable, AutoCloseable

```
public final class FormEditorWeb extends SaveableFacade implements IFormEditor
```

Class for editing forms (ading/deleting field etc)

## Constructors

| Constructor | Description |
| --- | --- |
| [FormEditorWeb](#FormEditorWeb--) | <p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-) | <p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-) | <p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-) | <p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-) | <p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.io.InputStream-java.io.OutputStream-) | <p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-) | <p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |
| [FormEditorWeb](#FormEditorWeb-java.lang.String-java.lang.String-) | <p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre> |

## Methods

| Method | Description |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Add field of specified type to the form. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Add field of specified type to the form. |
| [addFieldScript](#addFieldScript-java.lang.String-java.lang.String-) | Add JavaScript for a PushButton field. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Adds new item to the list box. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Add a new item with Export value to the existing list box field, only for AcroForm combo box field. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Add submit button on the form. |
| [close](#close--) | Closes all resources used by this document. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Copies an existing field to the same position in specified page number. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copies an existing field to a new position specified by both page number and ordinates. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Copies an existing field from one PDF document to another document with original page number and ordinates. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Copies an existing field from one PDF document to another document with specified page number and original ordinates. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copies an existing field from one PDF document to another document with specified page number and ordinates. |
| [decorateField](#decorateField--) | Changes visual attributes of all fields in the PDF document. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Changes visual attributes of all fields with the specified field type. |
| [decorateField](#decorateField-java.lang.String-) | Changes visual attributes of the specified field. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Delete item from the list field. |
| [dispose](#dispose--) | Deprecated. |
| [getAttachmentName](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getContentDisposition](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpResponse object. |
| [getDestFileName](#getDestFileName--) | Deprecated. |
| [getDestStream](#getDestStream--) | Gets destination stream. |
| [getExportItems](#getExportItems--) | Gets options for combo box with export values. |
| [getFacade](#getFacade--) | Gets visual attributes of the field. |
| [getFieldAppearance](#getFieldAppearance-java.lang.String-) | Get field flags. |
| [getItems](#getItems--) | Returns item array |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Gets or sets size of radio button item size (when new radio button field is added). |
| [getRadioGap](#getRadioGap--) | Get the member to record the gap between two neighboring radio buttons in pixels,default is 50. |
| [getRadioHoriz](#getRadioHoriz--) | Get the flag to indicate whether the radios are arranged horizontally or vertically, default value is true. |
| [getResponse](#getResponse--) | Gets Response object where result of operation will be stored. |
| [getSaveOptions](#getSaveOptions--) | Gets save options when result is stored as HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Deprecated. |
| [getSrcStream](#getSrcStream--) | Gets source stream. |
| [getSubmitFlag](#getSubmitFlag--) | Get the submit button's submission flags |
| [moveField](#moveField-java.lang.String-float-float-float-float-) | Set new position of field. |
| [removeField](#removeField-java.lang.String-) | Remove field from the form. |
| [removeFieldAction](#removeFieldAction-java.lang.String-) | Remove submit action of the field. |
| [renameField](#renameField-java.lang.String-java.lang.String-) | Change name of the field. |
| [resetFacade](#resetFacade--) | Reset all visual attributes to empty value. |
| [resetInnerFacade](#resetInnerFacade--) | Reset all visual attributes of inner facade to empty value. |
| [save](#save--) | Saves changes into destination file. |
| [setAttachmentName](#setAttachmentName-java.lang.String-) | Sets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [setContentDisposition](#setContentDisposition-com.aspose.pdf.ContentDisposition-) | Sets how content will be stored when result of operation is stored into HttpResponse object. |
| [setConvertTo](#setConvertTo-com.aspose.pdf.PdfFormat-) | Sets PdfFormat PDF file format. |
| [setDestFileName](#setDestFileName-java.lang.String-) | Deprecated. |
| [setDestStream](#setDestStream-java.io.OutputStream-) | Sets destination stream. |
| [setExportItems](#setExportItems-java.lang.String:A:A-) | Sets options for combo box with export values. |
| [setFacade](#setFacade-com.aspose.pdf.facades.FormFieldFacade-) | Sets visual attributes of the field. |
| [setFieldAlignment](#setFieldAlignment-java.lang.String-int-) | Set the alignment style of a text field. |
| [setFieldAlignmentV](#setFieldAlignmentV-java.lang.String-int-) | Set the vertical alignment style of a text field. |
| [setFieldAppearance](#setFieldAppearance-java.lang.String-int-) | Set field flags |
| [setFieldAttribute](#setFieldAttribute-java.lang.String-int-) | Set attributes of field. |
| [setFieldCombNumber](#setFieldCombNumber-java.lang.String-int-) | Sets number of combs for a regular single-line text field (the field is automatically divided into as many equally spaced positions, or combs, as the value of combNumber parameter). |
| [setFieldLimit](#setFieldLimit-java.lang.String-int-) | Sets maximum character count of the text field. |
| [setFieldScript](#setFieldScript-java.lang.String-java.lang.String-) | Set JavaScript for a PushButton field. |
| [setItems](#setItems-java.lang.String:A-) | Sets items which will be added to newly created list box or combo box. |
| [setRadioButtonItemSize](#setRadioButtonItemSize-double-) | Gets or sets size of radio button item size (when new radio button field is added). |
| [setRadioGap](#setRadioGap-float-) | Set the member to record the gap between two neighboring radio buttons in pixels,default is 50. |
| [setRadioHoriz](#setRadioHoriz-boolean-) | Set the flag to indicate whether the radios are arranged horizontally or vertically, default value is true. |
| [setResponse](#setResponse-javax.servlet.http.HttpServletResponse-) | Sets Response object where result of operation will be stored. |
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Deprecated. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Sets source stream. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Set submit flag of submit button. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Set the submit button's submission flags |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Sets URL of the button. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Change a single-lined text field to a multiple-lined one. |

### FormEditorWeb {#FormEditorWeb--}
```
public FormEditorWeb()
```

<p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-}
<p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.io.OutputStream-}
<p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-com.aspose.pdf.IDocument-java.lang.String-}
<p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-javax.servlet.http.HttpServletResponse-}
<p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.io.InputStream-java.io.OutputStream-}
<p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-javax.servlet.http.HttpServletResponse-}
<p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### FormEditorWeb {#FormEditorWeb-java.lang.String-java.lang.String-}
<p> Constructor for FormEditorWeb. </p> <hr> <pre> FormEditorWeb FormEditorWeb = new FormEditorWeb(); </pre>

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Add field of specified type to the form.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Add field of specified type to the form.

### addFieldScript {#addFieldScript-java.lang.String-java.lang.String-}
Add JavaScript for a PushButton field.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Adds new item to the list box.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Add a new item with Export value to the existing list box field, only for AcroForm combo box field.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Add submit button on the form.

### close {#close--}
```
public void close()
```

Closes all resources used by this document.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-}
Copies an existing field to the same position in specified page number.

### copyInnerField {#copyInnerField-java.lang.String-java.lang.String-int-float-float-}
Copies an existing field to a new position specified by both page number and ordinates.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-}
Copies an existing field from one PDF document to another document with original page number and ordinates.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-}
Copies an existing field from one PDF document to another document with specified page number and original ordinates.

### copyOuterField {#copyOuterField-java.lang.String-java.lang.String-int-float-float-}
Copies an existing field from one PDF document to another document with specified page number and ordinates.

### decorateField {#decorateField--}
```
public void decorateField()
```

Changes visual attributes of all fields in the PDF document.

### decorateField {#decorateField-com.aspose.pdf.facades.FieldType-}
Changes visual attributes of all fields with the specified field type.

### decorateField {#decorateField-java.lang.String-}
Changes visual attributes of the specified field.

### delListItem {#delListItem-java.lang.String-java.lang.String-}
Delete item from the list field.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Deprecated.

### getAttachmentName {#getAttachmentName--}
```
public String getAttachmentName()
```

Gets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Returns:**
String object

### getContentDisposition {#getContentDisposition--}
```
public ContentDisposition getContentDisposition()
```

Gets how content will be stored when result of operation is stored into HttpResponse object.

**Returns:**
ContentDisposition element

### getDestFileName {#getDestFileName--}
```
@Deprecated public String getDestFileName()
```

Deprecated.

**Returns:**
string value

### getDestStream {#getDestStream--}
```
public OutputStream getDestStream()
```

Gets destination stream.

**Returns:**
OutputStream object

### getExportItems {#getExportItems--}
```
public String [][] getExportItems()
```

Gets options for combo box with export values.

**Returns:**
String[][] array

### getFacade {#getFacade--}
```
public FormFieldFacade getFacade()
```

Gets visual attributes of the field.

**Returns:**
FormFieldFacade object

### getFieldAppearance {#getFieldAppearance-java.lang.String-}
Get field flags.

### getItems {#getItems--}
```
public String [] getItems()
```

Returns item array

**Returns:**
String[] object

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
public double getRadioButtonItemSize()
```

Gets or sets size of radio button item size (when new radio button field is added).

**Returns:**
double value

### getRadioGap {#getRadioGap--}
```
public float getRadioGap()
```

Get the member to record the gap between two neighboring radio buttons in pixels,default is 50.

**Returns:**
float value

### getRadioHoriz {#getRadioHoriz--}
```
public boolean getRadioHoriz()
```

Get the flag to indicate whether the radios are arranged horizontally or vertically, default value is true.

**Returns:**
boolean value

### getResponse {#getResponse--}
```
public javax.servlet.http.HttpServletResponse getResponse()
```

Gets Response object where result of operation will be stored.

**Returns:**
HttpServletResponse object

### getSaveOptions {#getSaveOptions--}
```
public SaveOptions getSaveOptions()
```

Gets save options when result is stored as HttpResponse.

**Returns:**
SaveOptions object

### getSrcFileName {#getSrcFileName--}
```
@Deprecated public String getSrcFileName()
```

Deprecated.

**Returns:**
string value

### getSrcStream {#getSrcStream--}
```
public InputStream getSrcStream()
```

Gets source stream.

**Returns:**
InputStream object

### getSubmitFlag {#getSubmitFlag--}
```
public SubmitFormFlag getSubmitFlag()
```

Get the submit button's submission flags

**Returns:**
SubmitFormFlag element

### moveField {#moveField-java.lang.String-float-float-float-float-}
Set new position of field.

### removeField {#removeField-java.lang.String-}
Remove field from the form.

### removeFieldAction {#removeFieldAction-java.lang.String-}
Remove submit action of the field.

### renameField {#renameField-java.lang.String-java.lang.String-}
Change name of the field.

### resetFacade {#resetFacade--}
```
public void resetFacade()
```

Reset all visual attributes to empty value.

### resetInnerFacade {#resetInnerFacade--}
```
public void resetInnerFacade()
```

Reset all visual attributes of inner facade to empty value.

### save {#save--}
```
public void save()
```

Saves changes into destination file.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Sets how content will be stored when result of operation is stored into HttpResponse object.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Sets PdfFormat PDF file format.

### setDestFileName {#setDestFileName-java.lang.String-}
Deprecated.

### setDestStream {#setDestStream-java.io.OutputStream-}
Sets destination stream.

### setExportItems {#setExportItems-java.lang.String:A:A-}
Sets options for combo box with export values.

### setFacade {#setFacade-com.aspose.pdf.facades.FormFieldFacade-}
Sets visual attributes of the field.

### setFieldAlignment {#setFieldAlignment-java.lang.String-int-}
Set the alignment style of a text field.

### setFieldAlignmentV {#setFieldAlignmentV-java.lang.String-int-}
Set the vertical alignment style of a text field.

### setFieldAppearance {#setFieldAppearance-java.lang.String-int-}
Set field flags

### setFieldAttribute {#setFieldAttribute-java.lang.String-int-}
Set attributes of field.

### setFieldCombNumber {#setFieldCombNumber-java.lang.String-int-}
Sets number of combs for a regular single-line text field (the field is automatically divided into as many equally spaced positions, or combs, as the value of combNumber parameter).

### setFieldLimit {#setFieldLimit-java.lang.String-int-}
Sets maximum character count of the text field.

### setFieldScript {#setFieldScript-java.lang.String-java.lang.String-}
Set JavaScript for a PushButton field.

### setItems {#setItems-java.lang.String:A-}
Sets items which will be added to newly created list box or combo box.

### setRadioButtonItemSize {#setRadioButtonItemSize-double-}
```
public void setRadioButtonItemSize(double value)
```

Gets or sets size of radio button item size (when new radio button field is added).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setRadioGap {#setRadioGap-float-}
```
public void setRadioGap(float value)
```

Set the member to record the gap between two neighboring radio buttons in pixels,default is 50.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
public void setRadioHoriz(boolean value)
```

Set the flag to indicate whether the radios are arranged horizontally or vertically, default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setResponse {#setResponse-javax.servlet.http.HttpServletResponse-}
Sets Response object where result of operation will be stored.

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sets save options when result is stored as HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Deprecated.

### setSrcStream {#setSrcStream-java.io.InputStream-}
Sets source stream.

### setSubmitFlag {#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-}
Set submit flag of submit button.

### setSubmitFlag {#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-}
Set the submit button's submission flags

### setSubmitUrl {#setSubmitUrl-java.lang.String-java.lang.String-}
Sets URL of the button.

### single2Multiple {#single2Multiple-java.lang.String-}
Change a single-lined text field to a multiple-lined one.
