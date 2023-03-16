---
title: Form
second_title: Aspose.PDF for Java API Reference
description: Class representing form object.
type: docs
weight: 139
url: /java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
java.lang.Iterable
```
public final class Form implements Iterable<WidgetAnnotation>
```

Class representing form object.
## Constructors

| Constructor | Description |
| --- | --- |
| [Form(IDocument document)](#Form-com.aspose.pdf.IDocument-) | Constructor |
## Methods

| Method | Description |
| --- | --- |
| [getSignDependentElementsRenderingModeWhenConverted()](#getSignDependentElementsRenderingModeWhenConverted--) | Forms can contain signing information, i.e. can be signed or unsigned. |
| [setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)](#setSignDependentElementsRenderingModeWhenConverted-int-) | Forms can contain signing information, i.e. can be signed or unsigned. |
| [getDocument()](#getDocument--) | For internal usage only |
| [get_xfa()](#get-xfa--) | For internal usage only |
| [isSynchronized()](#isSynchronized--) | Returns true if object is thread-safe. |
| [getSyncRoot()](#getSyncRoot--) | Returns synchronization object. |
| [getAutoRecalculate()](#getAutoRecalculate--) | If set, all form fields will be recalculated when any field is changed. |
| [setAutoRecalculate(boolean value)](#setAutoRecalculate-boolean-) | If set, all form fields will be recalculated when any field is changed. |
| [getAutoRestoreForm()](#getAutoRestoreForm--) | If set, absent form fields will be automatically created if they present in annotations. |
| [setAutoRestoreForm(boolean value)](#setAutoRestoreForm-boolean-) | If set, absent form fields will be automatically created if they present in annotations. |
| [size()](#size--) | Gets number of the fields on this form. |
| [getDefaultResources()](#getDefaultResources--) | Gets default resources placed on this form. |
| [getDefaultAppearance()](#getDefaultAppearance--) | Gets default appearance of the form (object which describes default font, text size and color for fields on the form). |
| [setDefaultAppearance(DefaultAppearance value)](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Sets default appearance of the form (object which describes default font, text size and color for fields on the form). |
| [getXFA()](#getXFA--) | Gets XFA data of the form (if presents). |
| [getIgnoreNeedsRendering()](#getIgnoreNeedsRendering--) | If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. |
| [setIgnoreNeedsRendering(boolean value)](#setIgnoreNeedsRendering-boolean-) | If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. |
| [getRemovePermission()](#getRemovePermission--) | If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. |
| [setRemovePermission(boolean value)](#setRemovePermission-boolean-) | If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. |
| [getEmulateRequierdGroups()](#getEmulateRequierdGroups--) | If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogies for the exclGroup during conversion Xfa representation of forms to standard. |
| [setEmulateRequierdGroups(boolean value)](#setEmulateRequierdGroups-boolean-) | If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogies for the exclGroup during conversion Xfa representation of forms to standard. |
| [getType()](#getType--) | Gets type of the form. |
| [setType(FormType value)](#setType-com.aspose.pdf.FormType-) | Gets type of the form. |
| [copyTo(Field[] array, int index)](#copyTo-com.aspose.pdf.Field---int-) | Copies fields placed on the form into array. |
| [iterator()](#iterator--) | Gets enumeration of form fields. |
| [get(String name)](#get-java.lang.String-) | Searches field by field name. |
| [get(int index)](#get-int-) |  |
| [delete(Field field)](#delete-com.aspose.pdf.Field-) | Delete field from the form. |
| [delete(String fieldName)](#delete-java.lang.String-) | Deletes field from the form by its name. |
| [flatten()](#flatten--) | Removes all static form fields and place their values directly on the page. |
| [add(WidgetAnnotation field)](#add-com.aspose.pdf.WidgetAnnotation-) | Adds field on the form. |
| [clear()](#clear--) | Deletes all fields from form. |
| [contains(WidgetAnnotation field)](#contains-com.aspose.pdf.WidgetAnnotation-) | Determines if field is presented on form.. |
| [copyTo(WidgetAnnotation[] array, int arrayIndex)](#copyTo-com.aspose.pdf.WidgetAnnotation---int-) | Copies form's fields to array. |
| [isReadOnly()](#isReadOnly--) | Determines if collection is readonly. |
| [remove(WidgetAnnotation field)](#remove-com.aspose.pdf.WidgetAnnotation-) | Deletes field from the form. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets field of the form by field name. |
| [get_Item(int index)](#get-Item-int-) | Gets field of the form by field index. |
| [add(Field field, int pageNumber)](#add-com.aspose.pdf.Field-int-) | Adds field on the form. |
| [add(Field field)](#add-com.aspose.pdf.Field-) | Adds field on the form. |
| [add(Field field, String partialName, int pageNumber)](#add-com.aspose.pdf.Field-java.lang.String-int-) | Adds new field to the form; If this field is already placed on other or this form, the copy of field is created. |
| [addFieldAppearance(Field field, int pageNumber, Rectangle rect)](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | Adds additional appearance of the field to specified page of the document in the specified location. |
| [addFieldToAcroForm(Field field)](#addFieldToAcroForm-com.aspose.pdf.Field-) | Adds additional appearance of the field to specified page of the document. |
| [hasXfa()](#hasXfa--) | Returns true if hasXfa |
| [assignXfa(System.Xml.XmlDocument xml)](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | Sets XFA of the form to specified value. |
| [getFields()](#getFields--) | Gets list of all fields in lowest level of hierarhical form. |
| [hasField(Field field)](#hasField-com.aspose.pdf.Field-) | Check if the form already has specified field. |
| [hasField(String fieldName)](#hasField-java.lang.String-) | Determines if the field with specified name already added to the Form. |
| [getFieldsInRect(Rectangle rect)](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Returns fields inside of specified rectangle. |
| [setCalculatedFields(List<Field> value)](#setCalculatedFields-java.util.List-com.aspose.pdf.Field--) | Allows to set order of field calculation. |
| [getSignaturesExist()](#getSignaturesExist--) | If set, the document contains at least one signature field. |
| [setSignaturesExist(boolean value)](#setSignaturesExist-boolean-) | If set, the document contains at least one signature field. |
| [getSignaturesAppendOnly()](#getSignaturesAppendOnly--) | If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update. |
| [setSignaturesAppendOnly(boolean value)](#setSignaturesAppendOnly-boolean-) | If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update. |
### Form(IDocument document) {#Form-com.aspose.pdf.IDocument-}
```
public Form(IDocument document)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | IDocument object |

### getSignDependentElementsRenderingModeWhenConverted() {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```


Forms can contain signing information, i.e. can be signed or unsigned. And form's view sometimes must depend on whether form is signed or not. This property tells to form's converter (f.e. during conversion XFA form to Standard form) whether result form must be rendered as signed or as unsigned.

**Returns:**
int - SignDependentElementsRenderingModes element
### setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted) {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```


Forms can contain signing information, i.e. can be signed or unsigned. And form's view sometimes must depend on whether form is signed or not. This property tells to form's converter (f.e. during conversion XFA form to Standard form) whether result form must be rendered as signed or as unsigned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted | int | SignDependentElementsRenderingModes element |

### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


For internal usage only

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument object
### get_xfa() {#get-xfa--}
```
public XFA get_xfa()
```


For internal usage only

**Returns:**
[XFA](../../com.aspose.pdf/xfa) - XFA object
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if object is thread-safe.

**Returns:**
boolean - boolean value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Returns synchronization object.

**Returns:**
java.lang.Object - Object for synchronization
### getAutoRecalculate() {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```


If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields.

**Returns:**
boolean - boolean value
### setAutoRecalculate(boolean value) {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```


If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getAutoRestoreForm() {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```


If set, absent form fields will be automatically created if they present in annotations.

**Returns:**
boolean - boolean value
### setAutoRestoreForm(boolean value) {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```


If set, absent form fields will be automatically created if they present in annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### size() {#size--}
```
public final int size()
```


Gets number of the fields on this form.

**Returns:**
int - int value
### getDefaultResources() {#getDefaultResources--}
```
public Resources getDefaultResources()
```


Gets default resources placed on this form.

**Returns:**
[Resources](../../com.aspose.pdf/resources) - Resources value
### getDefaultAppearance() {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```


Gets default appearance of the form (object which describes default font, text size and color for fields on the form).

**Returns:**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance) - DefaultAppearance object
### setDefaultAppearance(DefaultAppearance value) {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
```
public void setDefaultAppearance(DefaultAppearance value)
```


Sets default appearance of the form (object which describes default font, text size and color for fields on the form).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | DefaultAppearance object |

### getXFA() {#getXFA--}
```
public XFA getXFA()
```


Gets XFA data of the form (if presents).

**Returns:**
[XFA](../../com.aspose.pdf/xfa) - XFA value
### getIgnoreNeedsRendering() {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```


If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. It is false by default.

**Returns:**
boolean - boolean value
### setIgnoreNeedsRendering(boolean value) {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```


If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. It is false by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getRemovePermission() {#getRemovePermission--}
```
public boolean getRemovePermission()
```


If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of mandatory fields in Adobe Acrobat reader. It is false by default.

**Returns:**
boolean - boolean value
### setRemovePermission(boolean value) {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```


If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of mandatory fields in Adobe Acrobat reader. It is false by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getEmulateRequierdGroups() {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```


If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogies for the exclGroup during conversion Xfa representation of forms to standard. It is false by default.

**Returns:**
boolean - boolean value
### setEmulateRequierdGroups(boolean value) {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```


If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogies for the exclGroup during conversion Xfa representation of forms to standard. It is false by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getType() {#getType--}
```
public FormType getType()
```


Gets type of the form. Possible values are: Standard, Static, Dynamic.

**Returns:**
[FormType](../../com.aspose.pdf/formtype) - FormType value
### setType(FormType value) {#setType-com.aspose.pdf.FormType-}
```
public void setType(FormType value)
```


Gets type of the form. Possible values are: Standard, Static, Dynamic.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [FormType](../../com.aspose.pdf/formtype) | FormType value |

### copyTo(Field[] array, int index) {#copyTo-com.aspose.pdf.Field---int-}
```
public void copyTo(Field[] array, int index)
```


Copies fields placed on the form into array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [Field\[\]](../../com.aspose.pdf/field) | Array where fields must be placed. |
| index | int | Starting index. |

### iterator() {#iterator--}
```
public Iterator<WidgetAnnotation> iterator()
```


Gets enumeration of form fields.

**Returns:**
java.util.Iterator<com.aspose.pdf.WidgetAnnotation> - Field enumerator.
### get(String name) {#get-java.lang.String-}
```
public WidgetAnnotation get(String name)
```


Searches field by field name. Returns null if field was not found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Field name. |

**Returns:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - Field object.
### get(int index) {#get-int-}
```
public WidgetAnnotation get(int index)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int |  |

**Returns:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation)
### delete(Field field) {#delete-com.aspose.pdf.Field-}
```
public void delete(Field field)
```


Delete field from the form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Field which must be deleted. |

### delete(String fieldName) {#delete-java.lang.String-}
```
public void delete(String fieldName)
```


Deletes field from the form by its name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | Name of the filed which must be deleted. |

### flatten() {#flatten--}
```
public void flatten()
```


Removes all static form fields and place their values directly on the page.

### add(WidgetAnnotation field) {#add-com.aspose.pdf.WidgetAnnotation-}
```
public boolean add(WidgetAnnotation field)
```


Adds field on the form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | Field which must be added. |

**Returns:**
boolean - boolean value
### clear() {#clear--}
```
public void clear()
```


Deletes all fields from form. Not supported.

### contains(WidgetAnnotation field) {#contains-com.aspose.pdf.WidgetAnnotation-}
```
public boolean contains(WidgetAnnotation field)
```


Determines if field is presented on form..

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | Field to search. |

**Returns:**
boolean - boolean value
### copyTo(WidgetAnnotation[] array, int arrayIndex) {#copyTo-com.aspose.pdf.WidgetAnnotation---int-}
```
public void copyTo(WidgetAnnotation[] array, int arrayIndex)
```


Copies form's fields to array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [WidgetAnnotation\[\]](../../com.aspose.pdf/widgetannotation) | Array to copy. |
| arrayIndex | int | Index of array's item where copying begins. |

### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Determines if collection is readonly. Always returns false.

**Returns:**
boolean - boolean value
### remove(WidgetAnnotation field) {#remove-com.aspose.pdf.WidgetAnnotation-}
```
public boolean remove(WidgetAnnotation field)
```


Deletes field from the form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) | Field to delete. |

**Returns:**
boolean - True if field was deleted. False if field was not found on form.
### get_Item(String name) {#get-Item-java.lang.String-}
```
public WidgetAnnotation get_Item(String name)
```


Gets field of the form by field name. Throws excpetion if the field was not found.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Name of the field. |

**Returns:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - Retreived field.
### get_Item(int index) {#get-Item-int-}
```
public WidgetAnnotation get_Item(int index)
```


Gets field of the form by field index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the field. |

**Returns:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - Retreived field.
### add(Field field, int pageNumber) {#add-com.aspose.pdf.Field-int-}
```
public void add(Field field, int pageNumber)
```


Adds field on the form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Field which must be added. |
| pageNumber | int | Page index where added field will be placed. |

### add(Field field) {#add-com.aspose.pdf.Field-}
```
public void add(Field field)
```


Adds field on the form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Field which must be added. |

### add(Field field, String partialName, int pageNumber) {#add-com.aspose.pdf.Field-java.lang.String-int-}
```
public Field add(Field field, String partialName, int pageNumber)
```


Adds new field to the form; If this field is already placed on other or this form, the copy of field is created.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Field name. |
| partialName | java.lang.String | Name of field on the form. |
| pageNumber | int | Page number where field will be added. |

**Returns:**
[Field](../../com.aspose.pdf/field) - Added field returned. If copy of the field was created it will be returned.
### addFieldAppearance(Field field, int pageNumber, Rectangle rect) {#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-}
```
public void addFieldAppearance(Field field, int pageNumber, Rectangle rect)
```


Adds additional appearance of the field to specified page of the document in the specified location.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Field which appearance should be added on form. |
| pageNumber | int | Number of the page where field must be placed. |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle where field will be placed. |

### addFieldToAcroForm(Field field) {#addFieldToAcroForm-com.aspose.pdf.Field-}
```
public void addFieldToAcroForm(Field field)
```


Adds additional appearance of the field to specified page of the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Field object |

### hasXfa() {#hasXfa--}
```
public boolean hasXfa()
```


Returns true if hasXfa

**Returns:**
boolean - boolean value
### assignXfa(System.Xml.XmlDocument xml) {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
```
public void assignXfa(System.Xml.XmlDocument xml)
```


Sets XFA of the form to specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xml | com.aspose.ms.System.Xml.XmlDocument | Xml document which concains new XFA data. |

### getFields() {#getFields--}
```
public Field[] getFields()
```


Gets list of all fields in lowest level of hierarhical form.

**Returns:**
com.aspose.pdf.Field[] - Array with found fields.
### hasField(Field field) {#hasField-com.aspose.pdf.Field-}
```
public final boolean hasField(Field field)
```


Check if the form already has specified field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Field to check. |

**Returns:**
boolean -  true  if the specified field name added to Form; otherwise,  false .
### hasField(String fieldName) {#hasField-java.lang.String-}
```
public final boolean hasField(String fieldName)
```


Determines if the field with specified name already added to the Form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | java.lang.String | PartialName of the field. |

**Returns:**
boolean -  true  if the specified field name added to Form; otherwise,  false .
### getFieldsInRect(Rectangle rect) {#getFieldsInRect-com.aspose.pdf.Rectangle-}
```
public Field[] getFieldsInRect(Rectangle rect)
```


Returns fields inside of specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rect | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle where fields should be found. |

**Returns:**
com.aspose.pdf.Field[] - Array with found fields.
### setCalculatedFields(List<Field> value) {#setCalculatedFields-java.util.List-com.aspose.pdf.Field--}
```
public void setCalculatedFields(List<Field> value)
```


Allows to set order of field calculation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.aspose.pdf.Field> | java.util.List   object. |

### getSignaturesExist() {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```


If set, the document contains at least one signature field.

**Returns:**
boolean - boolean value
### setSignaturesExist(boolean value) {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```


If set, the document contains at least one signature field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getSignaturesAppendOnly() {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```


If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update.

**Returns:**
boolean - boolean value
### setSignaturesAppendOnly(boolean value) {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```


If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

