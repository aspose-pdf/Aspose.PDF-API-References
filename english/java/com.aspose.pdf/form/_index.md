---
title: Form
second_title: Aspose.PDF for Java API Reference
description: Class representing form object.
type: docs
weight: 1740
url: /java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Form

**All Implemented Interfaces:**
Iterable < WidgetAnnotation >

```
public final class Form extends Object implements Iterable < WidgetAnnotation >
```

Class representing form object.

## Constructors

| Constructor | Description |
| --- | --- |
| [Form](#Form-com.aspose.pdf.IDocument-) | Constructor |

## Methods

| Method | Description |
| --- | --- |
| [add](#add-com.aspose.pdf.Field-) | Adds field on the form. |
| [add](#add-com.aspose.pdf.Field-int-) | Adds field on the form. |
| [add](#add-com.aspose.pdf.Field-java.lang.String-int-) | Adds new field to the form; If this field is already placed on other or this form, the copy of field is created. |
| [add](#add-com.aspose.pdf.WidgetAnnotation-) | Adds field on the form. |
| [addFieldAppearance](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | Adds additional appearance of the field to specified page of the document in the specified location. |
| [addFieldToAcroForm](#addFieldToAcroForm-com.aspose.pdf.Field-) | Adds additional appearance of the field to specified page of the document. |
| [assignXfa](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | Sets XFA of the form to specified value. |
| [clear](#clear--) | Deletes all fields from form. Not supported. |
| [contains](#contains-com.aspose.pdf.WidgetAnnotation-) | Determines if field is presented on form.. |
| [copyTo](#copyTo-com.aspose.pdf.Field:A-int-) | Copies fields placed on the form into array. |
| [copyTo](#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-) | Copies form's fields to array. |
| [delete](#delete-com.aspose.pdf.Field-) | Delete field from the form. |
| [delete](#delete-java.lang.String-) | Deletes field from the form by its name. |
| [flatten](#flatten--) | Removes all static form fields and place their values directly on the page. |
| [get_Item](#get_Item-int-) | Gets field of the form by field index. |
| [get_Item](#get_Item-java.lang.String-) | Gets field of the form by field name. Throws excpetion if the field was not found. |
| [get_xfa](#get_xfa--) | For internal usage only |
| [get](#get-int-) |  |
| [get](#get-java.lang.String-) | Searches field by field name. Returns null if field was not found. |
| [getAutoRecalculate](#getAutoRecalculate--) | If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields. |
| [getAutoRestoreForm](#getAutoRestoreForm--) | If set, absent form fields will be automatically created if they present in annotations. |
| [getDefaultAppearance](#getDefaultAppearance--) | Gets default appearance of the form (object which describes default font, text size and color for fields on the form). |
| [getDefaultResources](#getDefaultResources--) | Gets default resources placed on this form. |
| [getDocument](#getDocument--) | For internal usage only |
| [getEmulateRequierdGroups](#getEmulateRequierdGroups--) | If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogies for the exclGroup during conversion Xfa representation of forms to standard. It is false by default. |
| [getFields](#getFields--) | Gets list of all fields in lowest level of hierarhical form. |
| [getFieldsInRect](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Returns fields inside of specified rectangle. |
| [getIgnoreNeedsRendering](#getIgnoreNeedsRendering--) | If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. It is false by default. |
| [getNeedsRendering](#getNeedsRendering--) | Gets a value indicating whether the document requires the removal of the dynamic XFA form. This property was introduced to determine if {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) should be used to remove the XFA form in cases where the XFA form is present and {@code NeedsRendering}({@link #getNeedsRendering}) is false. |
| [getRemovePermission](#getRemovePermission--) | If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of mandatory fields in Adobe Acrobat reader. It is false by default. |
| [getSignaturesAppendOnly](#getSignaturesAppendOnly--) | If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update. |
| [getSignaturesExist](#getSignaturesExist--) | If set, the document contains at least one signature field. |
| [getSignDependentElementsRenderingModeWhenConverted](#getSignDependentElementsRenderingModeWhenConverted--) | Forms can contain signing information, i.e. can be signed or unsigned. And form's view sometimes must depend on whether form is signed or not. This property tells to form's converter (f.e. during conversion XFA form to Standard form) whether result form must be rendered as signed or as unsigned. |
| [getSyncRoot](#getSyncRoot--) | Returns synchronization object. |
| [getType](#getType--) | Gets type of the form. Possible values are: Standard, Static, Dynamic. |
| [getXFA](#getXFA--) | Gets XFA data of the form (if presents). |
| [hasField](#hasField-com.aspose.pdf.Field-) | Check if the form already has specified field. |
| [hasField](#hasField-java.lang.String-) | Determines if the field with specified name already added to the Form. |
| [hasField](#hasField-java.lang.String-boolean-) | Determines if the field with specified name already added to the Form, with ability to look into children hierarchy of fields. |
| [hasXfa](#hasXfa--) | Gets a value indicating whether the document contains XFA form. This property was introduced to determine if {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) should be used to remove the XFA form in cases where the XFA form is present and {@code NeedsRendering}({@link #getNeedsRendering}) is false. |
| [isReadOnly](#isReadOnly--) | Determines if collection is readonly. Always returns false. |
| [isSynchronized](#isSynchronized--) | Returns true if object is thread-safe. |
| [iterator](#iterator--) | Gets enumeration of form fields. |
| [makeFormAnnotationsIndependent](#makeFormAnnotationsIndependent-com.aspose.pdf.Page-) | / * / * Exports the PDF form fields to JSON format and writes the result to the provided stream. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / * |
| [remove](#remove-com.aspose.pdf.WidgetAnnotation-) | Deletes field from the form. |
| [removeFieldAppearance](#removeFieldAppearance-com.aspose.pdf.Field-int-) | Removes appearance of the field at specified index. If only one child appearance left, method embeds it into the field. |
| [setAutoRecalculate](#setAutoRecalculate-boolean-) | If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields. |
| [setAutoRestoreForm](#setAutoRestoreForm-boolean-) | If set, absent form fields will be automatically created if they present in annotations. |
| [setCalculatedFields](#setCalculatedFields-java.util.List-) | Allows to set order of field calculation. |
| [setDefaultAppearance](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Sets default appearance of the form (object which describes default font, text size and color for fields on the form). |
| [setEmulateRequierdGroups](#setEmulateRequierdGroups-boolean-) | If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogies for the exclGroup during conversion Xfa representation of forms to standard. It is false by default. |
| [setIgnoreNeedsRendering](#setIgnoreNeedsRendering-boolean-) | If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. It is false by default. |
| [setRemovePermission](#setRemovePermission-boolean-) | If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of mandatory fields in Adobe Acrobat reader. It is false by default. |
| [setSignaturesAppendOnly](#setSignaturesAppendOnly-boolean-) | If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update. |
| [setSignaturesExist](#setSignaturesExist-boolean-) | If set, the document contains at least one signature field. |
| [setSignDependentElementsRenderingModeWhenConverted](#setSignDependentElementsRenderingModeWhenConverted-int-) | Forms can contain signing information, i.e. can be signed or unsigned. And form's view sometimes must depend on whether form is signed or not. This property tells to form's converter (f.e. during conversion XFA form to Standard form) whether result form must be rendered as signed or as unsigned. |
| [setType](#setType-com.aspose.pdf.FormType-) | Gets type of the form. Possible values are: Standard, Static, Dynamic. |
| [size](#size--) | Gets number of the fields on this form. |

### Form {#Form-com.aspose.pdf.IDocument-}
Constructor

### add {#add-com.aspose.pdf.Field-}
Adds field on the form.

### add {#add-com.aspose.pdf.Field-int-}
Adds field on the form.

### add {#add-com.aspose.pdf.Field-java.lang.String-int-}
Adds new field to the form; If this field is already placed on other or this form, the copy of field is created.

### add {#add-com.aspose.pdf.WidgetAnnotation-}
Adds field on the form.

### addFieldAppearance {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
Adds additional appearance of the field to specified page of the document in the specified location.

### addFieldToAcroForm {#addFieldToAcroForm-com.aspose.pdf.Field-}
Adds additional appearance of the field to specified page of the document.

### assignXfa {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
Sets XFA of the form to specified value.

### clear {#clear--}
```
public void clear()
```

Deletes all fields from form. Not supported.

### contains {#contains-com.aspose.pdf.WidgetAnnotation-}
Determines if field is presented on form..

### copyTo {#copyTo-com.aspose.pdf.Field:A-int-}
Copies fields placed on the form into array.

### copyTo {#copyTo-com.aspose.pdf.WidgetAnnotation:A-int-}
Copies form's fields to array.

### delete {#delete-com.aspose.pdf.Field-}
Delete field from the form.

### delete {#delete-java.lang.String-}
Deletes field from the form by its name.

### flatten {#flatten--}
```
public void flatten()
```

Removes all static form fields and place their values directly on the page.

### get_Item {#get_Item-int-}
```
public WidgetAnnotation get_Item(int index)
```

Gets field of the form by field index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  | Index of the field. |

**Returns:**
Retreived field.

### get_Item {#get_Item-java.lang.String-}
Gets field of the form by field name. Throws excpetion if the field was not found.

### get_xfa {#get_xfa--}
```
public XFA get_xfa()
```

For internal usage only

**Returns:**
XFA object

### get {#get-int-}
```
public WidgetAnnotation get(int index)
```



**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index |  |  |

### get {#get-java.lang.String-}
Searches field by field name. Returns null if field was not found.

### getAutoRecalculate {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```

If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields.

**Returns:**
boolean value

### getAutoRestoreForm {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```

If set, absent form fields will be automatically created if they present in annotations.

**Returns:**
boolean value

### getDefaultAppearance {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```

Gets default appearance of the form (object which describes default font, text size and color for fields on the form).

**Returns:**
DefaultAppearance object

### getDefaultResources {#getDefaultResources--}
```
public Resources getDefaultResources()
```

Gets default resources placed on this form.

**Returns:**
Resources value

### getDocument {#getDocument--}
```
public IDocument getDocument()
```

For internal usage only

**Returns:**
IDocument object

### getEmulateRequierdGroups {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```

If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogies for the exclGroup during conversion Xfa representation of forms to standard. It is false by default.

**Returns:**
boolean value

### getFields {#getFields--}
```
public Field [] getFields()
```

Gets list of all fields in lowest level of hierarhical form.

**Returns:**
Array with found fields.

### getFieldsInRect {#getFieldsInRect-com.aspose.pdf.Rectangle-}
Returns fields inside of specified rectangle.

### getIgnoreNeedsRendering {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```

If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. It is false by default.

**Returns:**
boolean value

### getNeedsRendering {#getNeedsRendering--}
```
public final boolean getNeedsRendering()
```

Gets a value indicating whether the document requires the removal of the dynamic XFA form. This property was introduced to determine if {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) should be used to remove the XFA form in cases where the XFA form is present and {@code NeedsRendering}({@link #getNeedsRendering}) is false.

**Returns:**
boolean value

### getRemovePermission {#getRemovePermission--}
```
public boolean getRemovePermission()
```

If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of mandatory fields in Adobe Acrobat reader. It is false by default.

**Returns:**
boolean value

### getSignaturesAppendOnly {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```

If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update.

**Returns:**
boolean value

### getSignaturesExist {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```

If set, the document contains at least one signature field.

**Returns:**
boolean value

### getSignDependentElementsRenderingModeWhenConverted {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```

Forms can contain signing information, i.e. can be signed or unsigned. And form's view sometimes must depend on whether form is signed or not. This property tells to form's converter (f.e. during conversion XFA form to Standard form) whether result form must be rendered as signed or as unsigned.

**Returns:**
SignDependentElementsRenderingModes element @see SignDependentElementsRenderingModes

### getSyncRoot {#getSyncRoot--}
```
public Object getSyncRoot()
```

Returns synchronization object.

**Returns:**
Object for synchronization

### getType {#getType--}
```
public FormType getType()
```

Gets type of the form. Possible values are: Standard, Static, Dynamic.

**Returns:**
FormType value @see FormType

### getXFA {#getXFA--}
```
public XFA getXFA()
```

Gets XFA data of the form (if presents).

**Returns:**
XFA value

### hasField {#hasField-com.aspose.pdf.Field-}
Check if the form already has specified field.

### hasField {#hasField-java.lang.String-}
Determines if the field with specified name already added to the Form.

### hasField {#hasField-java.lang.String-boolean-}
Determines if the field with specified name already added to the Form, with ability to look into children hierarchy of fields.

### hasXfa {#hasXfa--}
```
public final boolean hasXfa()
```

Gets a value indicating whether the document contains XFA form. This property was introduced to determine if {@code IgnoreNeedsRendering}({@link #getIgnoreNeedsRendering}/{@link #setIgnoreNeedsRendering(boolean)}) should be used to remove the XFA form in cases where the XFA form is present and {@code NeedsRendering}({@link #getNeedsRendering}) is false.

**Returns:**
boolean value

### isReadOnly {#isReadOnly--}
```
public boolean isReadOnly()
```

Determines if collection is readonly. Always returns false.

**Returns:**
boolean value

### isSynchronized {#isSynchronized--}
```
public boolean isSynchronized()
```

Returns true if object is thread-safe.

**Returns:**
boolean value

### iterator {#iterator--}
```
public com.aspose.ms.System.Collections.Generic.List.Enumerator< WidgetAnnotation > iterator()
```

Gets enumeration of form fields.

**Returns:**
Field enumerator.

### makeFormAnnotationsIndependent {#makeFormAnnotationsIndependent-com.aspose.pdf.Page-}
/ * / * Exports the PDF form fields to JSON format and writes the result to the provided stream. / * / * Document document = new Document("PdfDoc.pdf"); / * FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write); / * document.Form.ExportFormFieldsToJson(fs); / * fs.Close(); / *

### remove {#remove-com.aspose.pdf.WidgetAnnotation-}
Deletes field from the form.

### removeFieldAppearance {#removeFieldAppearance-com.aspose.pdf.Field-int-}
Removes appearance of the field at specified index. If only one child appearance left, method embeds it into the field.

### setAutoRecalculate {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```

If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setAutoRestoreForm {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```

If set, absent form fields will be automatically created if they present in annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setCalculatedFields {#setCalculatedFields-java.util.List-}
Allows to set order of field calculation.

### setDefaultAppearance {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
Sets default appearance of the form (object which describes default font, text size and color for fields on the form).

### setEmulateRequierdGroups {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```

If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogies for the exclGroup during conversion Xfa representation of forms to standard. It is false by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setIgnoreNeedsRendering {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```

If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. It is false by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setRemovePermission {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```

If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of mandatory fields in Adobe Acrobat reader. It is false by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSignaturesAppendOnly {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```

If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSignaturesExist {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```

If set, the document contains at least one signature field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value |  | boolean value |

### setSignDependentElementsRenderingModeWhenConverted {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```

Forms can contain signing information, i.e. can be signed or unsigned. And form's view sometimes must depend on whether form is signed or not. This property tells to form's converter (f.e. during conversion XFA form to Standard form) whether result form must be rendered as signed or as unsigned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted |  | SignDependentElementsRenderingModes element @see SignDependentElementsRenderingModes |

### setType {#setType-com.aspose.pdf.FormType-}
Gets type of the form. Possible values are: Standard, Static, Dynamic.

### size {#size--}
```
public final int size()
```

Gets number of the fields on this form.

**Returns:**
int value
