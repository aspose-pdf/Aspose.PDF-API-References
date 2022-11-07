---
title: Field
second_title: Aspose.PDF for Java API Reference
description: Base class for acro form fields.
type: docs
weight: 92
url: /java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation)

**All Implemented Interfaces:**
com.aspose.ms.System.Collections.ICollection, java.lang.Cloneable
```
public class Field extends WidgetAnnotation implements System.Collections.ICollection, Cloneable
```

Base class for acro form fields.
## Constructors

| Constructor | Description |
| --- | --- |
| [Field(IPdfObject annotation, IDocument document)](#Field-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.IDocument-) |  |
## Fields

| Field | Description |
| --- | --- |
| [_Password](#-Password) |  |
| [_FileSelect](#-FileSelect) |  |
## Methods

| Method | Description |
| --- | --- |
| [getPartialName()](#getPartialName--) | Gets or sets partial name of the field. |
| [setPartialName(String value)](#setPartialName-java.lang.String-) |  |
| [getAlternateName()](#getAlternateName--) | Gets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). |
| [setAlternateName(String value)](#setAlternateName-java.lang.String-) | Sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). |
| [getMappingName()](#getMappingName--) | Gets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [setMappingName(String value)](#setMappingName-java.lang.String-) | Sets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [recalculate()](#recalculate--) |  |
| [getValue()](#getValue--) | Gets value of the field. |
| [setValue(String value)](#setValue-java.lang.String-) |  |
| [isSynchronized()](#isSynchronized--) | Returns true if dictionary is synchronized. |
| [size()](#size--) | Gets number of subfields in this field. |
| [getSyncRoot()](#getSyncRoot--) | Synchronization object. |
| [isGroup()](#isGroup--) | Gets s boolean value which indicates is this field non-terminal field i.e. group of fields. |
| [copyTo(System.Array array, int index)](#copyTo-com.aspose.ms.System.Array-int-) | Copies subfields of this field into array starting from specified index. |
| [iterator()](#iterator--) | Returns enumerator of contained fields. |
| [flatten()](#flatten--) | Removes this field and place its value directly on the page. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets subfield contained in this field by name of the subfield. |
| [get_Item(int index)](#get-Item-int-) | Gets subfield contained in this field by index. |
| [setPosition(Point point)](#setPosition-com.aspose.pdf.Point-) | Set position of the field. |
| [getPageIndex()](#getPageIndex--) |  |
| [updateAppearances()](#updateAppearances--) |  |
| [setFieldImage(System.IO.Stream image)](#setFieldImage-com.aspose.ms.System.IO.Stream-) |  |
| [getAnnotationIndex()](#getAnnotationIndex--) | Gets index of this anotation on the page. |
| [setAnnotationIndex(int value)](#setAnnotationIndex-int-) | Sets index of this anotation on the page. |
| [getRect()](#getRect--) | Gets or sets the field rectangle. |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) |  |
| [isSharedField()](#isSharedField--) | Property for Generator support. |
| [isSharedField(boolean value)](#isSharedField-boolean-) |  |
| [setFitIntoRectangle(boolean value)](#setFitIntoRectangle-boolean-) | If true then font size will reduced to fit text to specified rectangle. |
### Field(IPdfObject annotation, IDocument document) {#Field-com.aspose.pdf.engine.data.IPdfObject-com.aspose.pdf.IDocument-}
```
public Field(IPdfObject annotation, IDocument document)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| annotation | [IPdfObject](../../com.aspose.pdf.engine.data/ipdfobject) |  |
| document | [IDocument](../../com.aspose.pdf/idocument) |  |

### _Password {#-Password}
```
public static final int _Password
```


### _FileSelect {#-FileSelect}
```
public static final int _FileSelect
```


### getPartialName() {#getPartialName--}
```
public String getPartialName()
```


Gets or sets partial name of the field.

**Returns:**
java.lang.String - String value
### setPartialName(String value) {#setPartialName-java.lang.String-}
```
public void setPartialName(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### getAlternateName() {#getAlternateName--}
```
public String getAlternateName()
```


Gets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat.

**Returns:**
java.lang.String - String value
### setAlternateName(String value) {#setAlternateName-java.lang.String-}
```
public void setAlternateName(String value)
```


Sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). Alternate name is used as field tooltip in Adobe Acrobat.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### getMappingName() {#getMappingName--}
```
public String getMappingName()
```


Gets mapping name of the field that shall be used when exporting interactive form field data from the document.

**Returns:**
java.lang.String - String value
### setMappingName(String value) {#setMappingName-java.lang.String-}
```
public void setMappingName(String value)
```


Sets mapping name of the field that shall be used when exporting interactive form field data from the document.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### recalculate() {#recalculate--}
```
public void recalculate()
```




### getValue() {#getValue--}
```
public String getValue()
```


Gets value of the field.

**Returns:**
java.lang.String
### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String |  |

### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if dictionary is synchronized.

**Returns:**
boolean
### size() {#size--}
```
public int size()
```


Gets number of subfields in this field. (For example number of items in radio button field).

**Returns:**
int
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Synchronization object.

**Returns:**
java.lang.Object - Object
### isGroup() {#isGroup--}
```
public boolean isGroup()
```


Gets s boolean value which indicates is this field non-terminal field i.e. group of fields.

**Returns:**
boolean - boolean
### copyTo(System.Array array, int index) {#copyTo-com.aspose.ms.System.Array-int-}
```
public void copyTo(System.Array array, int index)
```


Copies subfields of this field into array starting from specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | com.aspose.ms.System.Array | Array where field must be copied. |
| index | int | Starting index where fields will be copied. |

### iterator() {#iterator--}
```
public System.Collections.IEnumerator iterator()
```


Returns enumerator of contained fields.

**Returns:**
com.aspose.ms.System.Collections.IEnumerator - Enumerator.
### flatten() {#flatten--}
```
public void flatten()
```


Removes this field and place its value directly on the page.

### get_Item(String name) {#get-Item-java.lang.String-}
```
public WidgetAnnotation get_Item(String name)
```


Gets subfield contained in this field by name of the subfield.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | java.lang.String | Contained subfield name. |

**Returns:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - Field instance.
### get_Item(int index) {#get-Item-int-}
```
public WidgetAnnotation get_Item(int index)
```


Gets subfield contained in this field by index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| index | int | Index of the reuqested subfield. |

**Returns:**
[WidgetAnnotation](../../com.aspose.pdf/widgetannotation) - Field instance.
### setPosition(Point point) {#setPosition-com.aspose.pdf.Point-}
```
public void setPosition(Point point)
```


Set position of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| point | [Point](../../com.aspose.pdf/point) | Point where field should be positioned. |

### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Gets index of page which contains annotation.

**Returns:**
int
### updateAppearances() {#updateAppearances--}
```
public void updateAppearances()
```




### setFieldImage(System.IO.Stream image) {#setFieldImage-com.aspose.ms.System.IO.Stream-}
```
public void setFieldImage(System.IO.Stream image)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| image | com.aspose.ms.System.IO.Stream |  |

### getAnnotationIndex() {#getAnnotationIndex--}
```
public int getAnnotationIndex()
```


Gets index of this anotation on the page.

**Returns:**
int - int value
### setAnnotationIndex(int value) {#setAnnotationIndex-int-}
```
public void setAnnotationIndex(int value)
```


Sets index of this anotation on the page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int |  |

### getRect() {#getRect--}
```
public Rectangle getRect()
```


Gets or sets the field rectangle.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle)
### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) |  |

### isSharedField() {#isSharedField--}
```
public boolean isSharedField()
```


Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page.

\* @return boolean value

**Returns:**
boolean
### isSharedField(boolean value) {#isSharedField-boolean-}
```
public void isSharedField(boolean value)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean |  |

### setFitIntoRectangle(boolean value) {#setFitIntoRectangle-boolean-}
```
public static void setFitIntoRectangle(boolean value)
```


If true then font size will reduced to fit text to specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

