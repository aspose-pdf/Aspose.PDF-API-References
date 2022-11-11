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
| [add(Field field)](#add-com.aspose.pdf.Field-) | Adds field on the form. |
| [add(Field field, int pageNumber)](#add-com.aspose.pdf.Field-int-) | Adds field on the form. |
| [add(Field field, String partialName, int pageNumber)](#add-com.aspose.pdf.Field-java.lang.String-int-) | Adds new field to the form; If this field is already placed on other or this form, the copy of field is created. |
| [add(WidgetAnnotation field)](#add-com.aspose.pdf.WidgetAnnotation-) | Adds field on the form. |
| [addFieldAppearance(Field field, int pageNumber, Rectangle rect)](#addFieldAppearance-com.aspose.pdf.Field-int-com.aspose.pdf.Rectangle-) | Adds additional appearance of the field to specified page of the document in the specified location. |
| [addFieldToAcroForm(Field field)](#addFieldToAcroForm-com.aspose.pdf.Field-) | Adds additional appearance of the field to specified page of the document. |
| [assignXfa(System.Xml.XmlDocument xml)](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) | Sets XFA of the form to specified value. |
| [clear()](#clear--) | Deletes all fields from form. |
| [contains(WidgetAnnotation field)](#contains-com.aspose.pdf.WidgetAnnotation-) | Determines if field is presented on form.. |
| [copyTo(Field[] array, int index)](#copyTo-com.aspose.pdf.Field---int-) | Copies fields placed on the form into array. |
| [copyTo(WidgetAnnotation[] array, int arrayIndex)](#copyTo-com.aspose.pdf.WidgetAnnotation---int-) | Copies form's fields to array. |
| [delete(Field field)](#delete-com.aspose.pdf.Field-) | Delete field from the form. |
| [delete(String fieldName)](#delete-java.lang.String-) | Deletes field from the form by its name. |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [flatten()](#flatten--) | Removes all static form fields and place their values directly on the page. |
| [get(int index)](#get-int-) |  |
| [get(String name)](#get-java.lang.String-) | Searches field by field name. |
| [getAutoRecalculate()](#getAutoRecalculate--) | If set, all form fields will be recalculated when any field is changed. |
| [getAutoRestoreForm()](#getAutoRestoreForm--) | If set, absent form fields will be automatically created if they present in annotations. |
| [getClass()](#getClass--) |  |
| [getDefaultAppearance()](#getDefaultAppearance--) | Gets default appearance of the form (object which describes default font, text size and color for fields on the form). |
| [getDefaultResources()](#getDefaultResources--) | Gets default resources placed on this form. |
| [getDocument()](#getDocument--) | For internal usage only |
| [getEmulateRequierdGroups()](#getEmulateRequierdGroups--) | If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogies for the exclGroup during conversion Xfa representation of forms to standard. |
| [getFields()](#getFields--) | Gets list of all fields in lowest level of hierarhical form. |
| [getFieldsInRect(Rectangle rect)](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Returns fields inside of specified rectangle. |
| [getIgnoreNeedsRendering()](#getIgnoreNeedsRendering--) | If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. |
| [getRemovePermission()](#getRemovePermission--) | If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. |
| [getSignDependentElementsRenderingModeWhenConverted()](#getSignDependentElementsRenderingModeWhenConverted--) | Forms can contain signing information, i.e. can be signed or unsigned. |
| [getSignaturesAppendOnly()](#getSignaturesAppendOnly--) | If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update. |
| [getSignaturesExist()](#getSignaturesExist--) | If set, the document contains at least one signature field. |
| [getSyncRoot()](#getSyncRoot--) | Returns synchronization object. |
| [getType()](#getType--) | Gets type of the form. |
| [getXFA()](#getXFA--) | Gets XFA data of the form (if presents). |
| [get_Item(int index)](#get-Item-int-) | Gets field of the form by field index. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets field of the form by field name. |
| [get_xfa()](#get-xfa--) | For internal usage only |
| [hasField(Field field)](#hasField-com.aspose.pdf.Field-) | Check if the form already has specified field. |
| [hasField(String fieldName)](#hasField-java.lang.String-) | Determines if the field with specified name already added to the Form. |
| [hasXfa()](#hasXfa--) | Returns true if hasXfa |
| [hashCode()](#hashCode--) |  |
| [isReadOnly()](#isReadOnly--) | Determines if collection is readonly. |
| [isSynchronized()](#isSynchronized--) | Returns true if object is thread-safe. |
| [iterator()](#iterator--) | Gets enumeration of form fields. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [remove(WidgetAnnotation field)](#remove-com.aspose.pdf.WidgetAnnotation-) | Deletes field from the form. |
| [setAutoRecalculate(boolean value)](#setAutoRecalculate-boolean-) | If set, all form fields will be recalculated when any field is changed. |
| [setAutoRestoreForm(boolean value)](#setAutoRestoreForm-boolean-) | If set, absent form fields will be automatically created if they present in annotations. |
| [setCalculatedFields(List<Field> value)](#setCalculatedFields-java.util.List-com.aspose.pdf.Field--) | Allows to set order of field calculation. |
| [setDefaultAppearance(DefaultAppearance value)](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Sets default appearance of the form (object which describes default font, text size and color for fields on the form). |
| [setEmulateRequierdGroups(boolean value)](#setEmulateRequierdGroups-boolean-) | If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogies for the exclGroup during conversion Xfa representation of forms to standard. |
| [setIgnoreNeedsRendering(boolean value)](#setIgnoreNeedsRendering-boolean-) | If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. |
| [setRemovePermission(boolean value)](#setRemovePermission-boolean-) | If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. |
| [setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)](#setSignDependentElementsRenderingModeWhenConverted-int-) | Forms can contain signing information, i.e. can be signed or unsigned. |
| [setSignaturesAppendOnly(boolean value)](#setSignaturesAppendOnly-boolean-) | If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update. |
| [setSignaturesExist(boolean value)](#setSignaturesExist-boolean-) | If set, the document contains at least one signature field. |
| [setType(int value)](#setType-int-) | Gets type of the form. |
| [size()](#size--) | Gets number of the fields on this form. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Form(IDocument document) {#Form-com.aspose.pdf.IDocument-}
```
public Form(IDocument document)
```


Constructor

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) | IDocument object |

### add(Field field) {#add-com.aspose.pdf.Field-}
```
public void add(Field field)
```


Adds field on the form.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) | Field which must be added. |

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

### assignXfa(System.Xml.XmlDocument xml) {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
```
public void assignXfa(System.Xml.XmlDocument xml)
```


Sets XFA of the form to specified value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xml | com.aspose.ms.System.Xml.XmlDocument | Xml document which concains new XFA data. |

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
### flatten() {#flatten--}
```
public void flatten()
```


Removes all static form fields and place their values directly on the page.

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
### getAutoRecalculate() {#getAutoRecalculate--}
```
public final boolean getAutoRecalculate()
```


If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields.

**Returns:**
boolean - boolean value
### getAutoRestoreForm() {#getAutoRestoreForm--}
```
public final boolean getAutoRestoreForm()
```


If set, absent form fields will be automatically created if they present in annotations.

**Returns:**
boolean - boolean value
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getDefaultAppearance() {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```


Gets default appearance of the form (object which describes default font, text size and color for fields on the form).

**Returns:**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance) - DefaultAppearance object
### getDefaultResources() {#getDefaultResources--}
```
public Resources getDefaultResources()
```


Gets default resources placed on this form.

**Returns:**
[Resources](../../com.aspose.pdf/resources) - Resources value
### getDocument() {#getDocument--}
```
public IDocument getDocument()
```


For internal usage only

**Returns:**
[IDocument](../../com.aspose.pdf/idocument) - IDocument object
### getEmulateRequierdGroups() {#getEmulateRequierdGroups--}
```
public boolean getEmulateRequierdGroups()
```


If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogies for the exclGroup during conversion Xfa representation of forms to standard. It is false by default.

**Returns:**
boolean - boolean value
### getFields() {#getFields--}
```
public Field[] getFields()
```


Gets list of all fields in lowest level of hierarhical form.

**Returns:**
com.aspose.pdf.Field[] - Array with found fields.
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
### getIgnoreNeedsRendering() {#getIgnoreNeedsRendering--}
```
public boolean getIgnoreNeedsRendering()
```


If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. It is false by default.

**Returns:**
boolean - boolean value
### getRemovePermission() {#getRemovePermission--}
```
public boolean getRemovePermission()
```


If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of mandatory fields in Adobe Acrobat reader. It is false by default.

**Returns:**
boolean - boolean value
### getSignDependentElementsRenderingModeWhenConverted() {#getSignDependentElementsRenderingModeWhenConverted--}
```
public int getSignDependentElementsRenderingModeWhenConverted()
```


Forms can contain signing information, i.e. can be signed or unsigned. And form's view sometimes must depend on whether form is signed or not. This property tells to form's converter (f.e. during conversion XFA form to Standard form) whether result form must be rendered as signed or as unsigned.

**Returns:**
int - SignDependentElementsRenderingModes element
### getSignaturesAppendOnly() {#getSignaturesAppendOnly--}
```
public final boolean getSignaturesAppendOnly()
```


If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update.

**Returns:**
boolean - boolean value
### getSignaturesExist() {#getSignaturesExist--}
```
public final boolean getSignaturesExist()
```


If set, the document contains at least one signature field.

**Returns:**
boolean - boolean value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Returns synchronization object.

**Returns:**
java.lang.Object - Object for synchronization
### getType() {#getType--}
```
public int getType()
```


Gets type of the form. Possible values are: Standard, Static, Dynamic.

**Returns:**
int - FormType value
### getXFA() {#getXFA--}
```
public XFA getXFA()
```


Gets XFA data of the form (if presents).

**Returns:**
[XFA](../../com.aspose.pdf/xfa) - XFA value
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
### get_xfa() {#get-xfa--}
```
public XFA get_xfa()
```


For internal usage only

**Returns:**
[XFA](../../com.aspose.pdf/xfa) - XFA object
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
### hasXfa() {#hasXfa--}
```
public boolean hasXfa()
```


Returns true if hasXfa

**Returns:**
boolean - boolean value
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```


Determines if collection is readonly. Always returns false.

**Returns:**
boolean - boolean value
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if object is thread-safe.

**Returns:**
boolean - boolean value
### iterator() {#iterator--}
```
public Iterator<WidgetAnnotation> iterator()
```


Gets enumeration of form fields.

**Returns:**
java.util.Iterator<com.aspose.pdf.WidgetAnnotation> - Field enumerator.
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




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
### setAutoRecalculate(boolean value) {#setAutoRecalculate-boolean-}
```
public final void setAutoRecalculate(boolean value)
```


If set, all form fields will be recalculated when any field is changed. Default value is true. Set to false in order to increase performance when filling form with large amount of calculated fields.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setAutoRestoreForm(boolean value) {#setAutoRestoreForm-boolean-}
```
public final void setAutoRestoreForm(boolean value)
```


If set, absent form fields will be automatically created if they present in annotations.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setCalculatedFields(List<Field> value) {#setCalculatedFields-java.util.List-com.aspose.pdf.Field--}
```
public void setCalculatedFields(List<Field> value)
```


Allows to set order of field calculation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.List<com.aspose.pdf.Field> | java.util.List   object. |

### setDefaultAppearance(DefaultAppearance value) {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
```
public void setDefaultAppearance(DefaultAppearance value)
```


Sets default appearance of the form (object which describes default font, text size and color for fields on the form).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) | DefaultAppearance object |

### setEmulateRequierdGroups(boolean value) {#setEmulateRequierdGroups-boolean-}
```
public void setEmulateRequierdGroups(boolean value)
```


If this property is true then additional red boundary rectangles will be drawn for required Xfa exclGroup elements containers This property was introduced because absences of analogies for the exclGroup during conversion Xfa representation of forms to standard. It is false by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setIgnoreNeedsRendering(boolean value) {#setIgnoreNeedsRendering-boolean-}
```
public void setIgnoreNeedsRendering(boolean value)
```


If this property is true the value of NeedsRendering key will be ignored during conversion XFA form to Standard form. It is false by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setRemovePermission(boolean value) {#setRemovePermission-boolean-}
```
public void setRemovePermission(boolean value)
```


If this property is true the "Perms" dictionary will be removed from the pdf document after conversion dynamic documents to standard. The "Perms" dictionary can contain a rules that disturb displaying selection of mandatory fields in Adobe Acrobat reader. It is false by default.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted) {#setSignDependentElementsRenderingModeWhenConverted-int-}
```
public void setSignDependentElementsRenderingModeWhenConverted(int signDependentElementsRenderingModeWhenConverted)
```


Forms can contain signing information, i.e. can be signed or unsigned. And form's view sometimes must depend on whether form is signed or not. This property tells to form's converter (f.e. during conversion XFA form to Standard form) whether result form must be rendered as signed or as unsigned.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| signDependentElementsRenderingModeWhenConverted | int | SignDependentElementsRenderingModes element |

### setSignaturesAppendOnly(boolean value) {#setSignaturesAppendOnly-boolean-}
```
public final void setSignaturesAppendOnly(boolean value)
```


If set, the document contains signatures that may be invalidated if the file is saved (written) in a way that alters its previous contents, as opposed to an incremental update.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setSignaturesExist(boolean value) {#setSignaturesExist-boolean-}
```
public final void setSignaturesExist(boolean value)
```


If set, the document contains at least one signature field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### setType(int value) {#setType-int-}
```
public void setType(int value)
```


Gets type of the form. Possible values are: Standard, Static, Dynamic.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | FormType value |

### size() {#size--}
```
public final int size()
```


Gets number of the fields on this form.

**Returns:**
int - int value
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

