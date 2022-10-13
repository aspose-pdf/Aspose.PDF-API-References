---
title: Form
second_title: Aspose.PDF for Java API Reference
description: Class representing form object.
type: docs
weight: 118
url: /java/com.aspose.pdf/form/
---
**Inheritance:**
java.lang.Object

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.ICollection
```
public final class Form implements System.Collections.ICollection
```

Class representing form object.
## Constructors

| Constructor | Description |
| --- | --- |
| [Form(IDocument document)](#Form-com.aspose.pdf.IDocument-) |  |
## Methods

| Method | Description |
| --- | --- |
| [getDocument()](#getDocument--) |  |
| [get_xfa()](#get-xfa--) |  |
| [isSynchronized()](#isSynchronized--) | Returns true if object is thread-safe. |
| [getSyncRoot()](#getSyncRoot--) | Returns synchronization object. |
| [size()](#size--) | Gets number of the fields on this form. |
| [getDefaultResources()](#getDefaultResources--) | Gets default resources placed on this form. |
| [getDefaultAppearance()](#getDefaultAppearance--) | Gets default appearance of the form (object which describes default font, text size and color for fields on the form). |
| [setDefaultAppearance(DefaultAppearance value)](#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-) | Sets default appearance of the form (object which describes default font, text size and color for fields on the form). |
| [getXFA()](#getXFA--) | Gets XFA data of the form (if presents). |
| [getType()](#getType--) | Gets type of the form. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies fields placed on the form into array. |
| [iterator()](#iterator--) | Gets enumeration of form fields. |
| [get(String name)](#get-java.lang.String-) | Searches field by field name. |
| [add(Field field, int pageNumber)](#add-com.aspose.pdf.Field-int-) | Adds field on the form. |
| [delete(Field field)](#delete-com.aspose.pdf.Field-) | Delete field from the form. |
| [delete(String fieldName)](#delete-java.lang.String-) | Deletes field from the form by its name. |
| [flatten()](#flatten--) | Removes all form fields and place their values directly on the page. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets field of the form by field name. |
| [get_Item(int index)](#get-Item-int-) | Gets field of the form by field index. |
| [add(Field field, String partialName, int pageNumber)](#add-com.aspose.pdf.Field-java.lang.String-int-) | Adds new field to the form; If this field is already placed on other or this form, the copy of field is created. |
| [addFieldToAcroForm(Field field)](#addFieldToAcroForm-com.aspose.pdf.Field-) |  |
| [hasXfa()](#hasXfa--) |  |
| [assignXfa(System.Xml.XmlDocument xml)](#assignXfa-com.aspose.ms.System.Xml.XmlDocument-) |  |
| [getFields()](#getFields--) | Gets list of all fields in lowest level of hierarhical form. |
| [getFieldsInRect(Rectangle rect)](#getFieldsInRect-com.aspose.pdf.Rectangle-) | Returns fields inside of specified rectangle. |
### Form(IDocument document) {#Form-com.aspose.pdf.IDocument-}
```
public Form(IDocument document)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| document | [IDocument](../../com.aspose.pdf/idocument) |  |

### getDocument() {#getDocument--}
```
public IDocument getDocument()
```




**Returns:**
[IDocument](../../com.aspose.pdf/idocument)
### get_xfa() {#get-xfa--}
```
public XFA get_xfa()
```




**Returns:**
[XFA](../../com.aspose.pdf/xfa)
### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if object is thread-safe.

**Returns:**
boolean
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Returns synchronization object.

**Returns:**
java.lang.Object
### size() {#size--}
```
public int size()
```


Gets number of the fields on this form.

**Returns:**
int
### getDefaultResources() {#getDefaultResources--}
```
public Resources getDefaultResources()
```


Gets default resources placed on this form.

**Returns:**
[Resources](../../com.aspose.pdf/resources)
### getDefaultAppearance() {#getDefaultAppearance--}
```
public DefaultAppearance getDefaultAppearance()
```


Gets default appearance of the form (object which describes default font, text size and color for fields on the form).

**Returns:**
[DefaultAppearance](../../com.aspose.pdf/defaultappearance)
### setDefaultAppearance(DefaultAppearance value) {#setDefaultAppearance-com.aspose.pdf.DefaultAppearance-}
```
public void setDefaultAppearance(DefaultAppearance value)
```


Sets default appearance of the form (object which describes default font, text size and color for fields on the form).

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [DefaultAppearance](../../com.aspose.pdf/defaultappearance) |  |

### getXFA() {#getXFA--}
```
public XFA getXFA()
```


Gets XFA data of the form (if presents).

**Returns:**
[XFA](../../com.aspose.pdf/xfa)
### getType() {#getType--}
```
public int getType()
```


Gets type of the form. Possible values are: Standard, Static, Dynamic.

**Returns:**
int
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array array, int index)
```


Copies fields placed on the form into array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array where fields must be placed. |
| index | int | Starting index. |

### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Gets enumeration of form fields.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Field enumerator.
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


Removes all form fields and place their values directly on the page.

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
### addFieldToAcroForm(Field field) {#addFieldToAcroForm-com.aspose.pdf.Field-}
```
public void addFieldToAcroForm(Field field)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| field | [Field](../../com.aspose.pdf/field) |  |

### hasXfa() {#hasXfa--}
```
public boolean hasXfa()
```




**Returns:**
boolean
### assignXfa(System.Xml.XmlDocument xml) {#assignXfa-com.aspose.ms.System.Xml.XmlDocument-}
```
public void assignXfa(System.Xml.XmlDocument xml)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| xml | com.aspose.ms.System.Xml.XmlDocument |  |

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
