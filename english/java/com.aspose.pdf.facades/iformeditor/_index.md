---
title: IFormEditor
second_title: Aspose.PDF for Java API Reference
description: Class for editing forms (adding/deleting field etc)
type: docs
weight: 260
url: /java/com.aspose.pdf.facades/iformeditor/
---
```
public interface IFormEditor extends Closeable
```

Class for editing forms (adding/deleting field etc)

## Methods

| Method | Description |
| --- | --- |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-) | Add field of specified type to the form. |
| [addField](#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-) | Add field of specified type to the form. |
| [addListItem](#addListItem-java.lang.String-java.lang.String-) | Adds new item to the list box. |
| [addListItem](#addListItem-java.lang.String-java.lang.String:A-) | Add a new item with Export value to the existing list box field, only for AcroForm combo box field. |
| [addSubmitBtn](#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-) | Add submit button on the form. |
| [close](#close--) | Closes object |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-) | Copies an existing field to the same position in specified page number. |
| [copyInnerField](#copyInnerField-java.lang.String-java.lang.String-int-float-float-) | Copies an existing field to a new position specified by both page number and ordinates. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-) | Copies an existing field from one PDF document to another document with original page number and ordinates. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-) | Copies an existing field from one PDF document to another document with specified page number and original ordinates. |
| [copyOuterField](#copyOuterField-java.lang.String-java.lang.String-int-float-float-) | Copies an existing field from one PDF document to another document with specified page number and ordinates. |
| [decorateField](#decorateField--) | Changes visual attributes of all fields in the PDF document. |
| [decorateField](#decorateField-com.aspose.pdf.facades.FieldType-) | Changes visual attributes of all fields with the specified field type. |
| [decorateField](#decorateField-java.lang.String-) | Changes visual attributes of the specified field. |
| [delListItem](#delListItem-java.lang.String-java.lang.String-) | Delete item from the list field. |
| [dispose](#dispose--) | Closes object |
| [getAttachmentName](#getAttachmentName--) | Gets name of attachment when result of operation is stored into HttpResponse objects as attachment. |
| [getContentDisposition](#getContentDisposition--) | Gets how content will be stored when result of operation is stored into HttpResponse object. |
| [getDestFileName](#getDestFileName--) | Gets destination file name. |
| [getDestStream](#getDestStream--) | Gets destination stream. |
| [getDocument](#getDocument--) | Gets the document FormEditor is working on. |
| [getExportItems](#getExportItems--) | Gets options for combo box with export values. |
| [getFacade](#getFacade--) | Gets visual attributes of the field. |
| [getItems](#getItems--) | Returns item array |
| [getRadioButtonItemSize](#getRadioButtonItemSize--) | Gets or sets size of radio button item size (when new radio button field is added). |
| [getRadioGap](#getRadioGap--) | Get the member to record the gap between two neighboring radio buttons in pixels,default is 50. |
| [getRadioHoriz](#getRadioHoriz--) | Get the flag to indicate whether the radios are arranged horizontally or vertically, default value is true. |
| [getSaveOptions](#getSaveOptions--) | Gets save options when result is stored as HttpResponse. |
| [getSrcFileName](#getSrcFileName--) | Gets name of source file. |
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
| [setDestFileName](#setDestFileName-java.lang.String-) | Sets destination file name. |
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
| [setSaveOptions](#setSaveOptions-com.aspose.pdf.SaveOptions-) | Sets save options when result is stored as HttpResponse. |
| [setSrcFileName](#setSrcFileName-java.lang.String-) | Sets name of source file. |
| [setSrcStream](#setSrcStream-java.io.InputStream-) | Sets source stream. |
| [setSubmitFlag](#setSubmitFlag-java.lang.String-com.aspose.pdf.facades.SubmitFormFlag-) | Set submit flag of submit button. |
| [setSubmitFlag](#setSubmitFlag-com.aspose.pdf.facades.SubmitFormFlag-) | Set the submit button's submission flags |
| [setSubmitUrl](#setSubmitUrl-java.lang.String-java.lang.String-) | Sets URL of the button. |
| [single2Multiple](#single2Multiple-java.lang.String-) | Change a single-lined text field to a multiple-lined one. |

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-int-float-float-float-float-}
Add field of specified type to the form.

### addField {#addField-com.aspose.pdf.facades.FieldType-java.lang.String-java.lang.String-int-float-float-float-float-}
Add field of specified type to the form.

### addListItem {#addListItem-java.lang.String-java.lang.String-}
Adds new item to the list box.

### addListItem {#addListItem-java.lang.String-java.lang.String:A-}
Add a new item with Export value to the existing list box field, only for AcroForm combo box field.

### addSubmitBtn {#addSubmitBtn-java.lang.String-int-java.lang.String-java.lang.String-float-float-float-float-}
Add submit button on the form.

### close {#close--}
```
void close()
```

Closes object

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
void decorateField()
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
void dispose()
```

Closes object

### getAttachmentName {#getAttachmentName--}
```
String getAttachmentName()
```

Gets name of attachment when result of operation is stored into HttpResponse objects as attachment.

**Returns:**
String object

### getContentDisposition {#getContentDisposition--}
```
ContentDisposition getContentDisposition()
```

Gets how content will be stored when result of operation is stored into HttpResponse object.

**Returns:**
ContentDisposition element

### getDestFileName {#getDestFileName--}
```
String getDestFileName()
```

Gets destination file name.

**Returns:**
string value

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

Gets the document FormEditor is working on.

**Returns:**
IDocument object

### getExportItems {#getExportItems--}
```
String [][] getExportItems()
```

Gets options for combo box with export values.

**Returns:**
String[][] object

### getFacade {#getFacade--}
```
FormFieldFacade getFacade()
```

Gets visual attributes of the field.

**Returns:**
FormFieldFacade object

### getItems {#getItems--}
```
String [] getItems()
```

Returns item array

**Returns:**
String[] object

### getRadioButtonItemSize {#getRadioButtonItemSize--}
```
double getRadioButtonItemSize()
```

Gets or sets size of radio button item size (when new radio button field is added).

**Returns:**
boolean value

### getRadioGap {#getRadioGap--}
```
float getRadioGap()
```

Get the member to record the gap between two neighboring radio buttons in pixels,default is 50.

**Returns:**
float value

### getRadioHoriz {#getRadioHoriz--}
```
boolean getRadioHoriz()
```

Get the flag to indicate whether the radios are arranged horizontally or vertically, default value is true.

**Returns:**
boolean value

### getSaveOptions {#getSaveOptions--}
```
SaveOptions getSaveOptions()
```

Gets save options when result is stored as HttpResponse.

**Returns:**
SaveOptions object

### getSrcFileName {#getSrcFileName--}
```
String getSrcFileName()
```

Gets name of source file.

**Returns:**
string value

### getSrcStream {#getSrcStream--}
```
InputStream getSrcStream()
```

Gets source stream.

**Returns:**
InputStream object

### getSubmitFlag {#getSubmitFlag--}
```
SubmitFormFlag getSubmitFlag()
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
void resetFacade()
```

Reset all visual attributes to empty value.

### resetInnerFacade {#resetInnerFacade--}
```
void resetInnerFacade()
```

Reset all visual attributes of inner facade to empty value.

### save {#save--}
```
void save()
```

Saves changes into destination file.

### setAttachmentName {#setAttachmentName-java.lang.String-}
Sets name of attachment when result of operation is stored into HttpResponse objects as attachment.

### setContentDisposition {#setContentDisposition-com.aspose.pdf.ContentDisposition-}
Sets how content will be stored when result of operation is stored into HttpResponse object.

### setConvertTo {#setConvertTo-com.aspose.pdf.PdfFormat-}
Sets PdfFormat PDF file format.

### setDestFileName {#setDestFileName-java.lang.String-}
Sets destination file name.

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
void setRadioButtonItemSize(double value)
```

Gets or sets size of radio button item size (when new radio button field is added).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | double value |

### setRadioGap {#setRadioGap-float-}
```
void setRadioGap(float value)
```

Set the member to record the gap between two neighboring radio buttons in pixels,default is 50.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | float value |

### setRadioHoriz {#setRadioHoriz-boolean-}
```
void setRadioHoriz(boolean value)
```

Set the flag to indicate whether the radios are arranged horizontally or vertically, default value is true.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSaveOptions {#setSaveOptions-com.aspose.pdf.SaveOptions-}
Sets save options when result is stored as HttpResponse.

### setSrcFileName {#setSrcFileName-java.lang.String-}
Sets name of source file.

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
