---
title: Field
second_title: Aspose.PDF for Java API Reference
description: Base class for acro form fields.
type: docs
weight: 108
url: /java/com.aspose.pdf/field/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.BaseParagraph](../../com.aspose.pdf/baseparagraph), [com.aspose.pdf.Annotation](../../com.aspose.pdf/annotation), [com.aspose.pdf.WidgetAnnotation](../../com.aspose.pdf/widgetannotation)

**All Implemented Interfaces:**
java.lang.Iterable, java.lang.Cloneable
```
public class Field extends WidgetAnnotation implements Iterable<WidgetAnnotation>, Cloneable
```

Base class for acro form fields.
## Constructors

| Constructor | Description |
| --- | --- |
| [Field(IDocument doc)](#Field-com.aspose.pdf.IDocument-) | Creates field for use in Generator. |
## Fields

| Field | Description |
| --- | --- |
| [_Password](#-Password) | \_Password |
| [_FileSelect](#-FileSelect) | \_FileSelect |
## Methods

| Method | Description |
| --- | --- |
| [getPartialName()](#getPartialName--) | Gets partial name of the field. |
| [setPartialName(String value)](#setPartialName-java.lang.String-) | Sets partial name of the field. |
| [getAlternateName()](#getAlternateName--) | Gets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). |
| [setAlternateName(String value)](#setAlternateName-java.lang.String-) | Sets alternate name of the field (An alternate field name that shall be used in place of the actual field name wherever the field shall be identified in the user interface). |
| [getMappingName()](#getMappingName--) | Gets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [setMappingName(String value)](#setMappingName-java.lang.String-) | Sets mapping name of the field that shall be used when exporting interactive form field data from the document. |
| [recalculate()](#recalculate--) | Recaculates all calculated fields on the form. |
| [getValue()](#getValue--) | Gets value of the field. |
| [setValue(String value)](#setValue-java.lang.String-) | Set value. |
| [isSynchronized()](#isSynchronized--) | Returns true if dictionary is synchronized. |
| [size()](#size--) | Gets number of subfields in this field. |
| [getSyncRoot()](#getSyncRoot--) | Synchronization object. |
| [isGroup()](#isGroup--) | Gets boolean value which indicates is this field non-terminal field i.e. group of fields. |
| [copyTo(Field[] array, int index)](#copyTo-com.aspose.pdf.Field---int-) | Copies subfields of this field into array starting from specified index. |
| [iterator()](#iterator--) | Returns enumerator of contained fields. |
| [flatten()](#flatten--) | Removes this field and place its value directly on the page. |
| [get_Item(String name)](#get-Item-java.lang.String-) | Gets subfield contained in this field by name of the subfield. |
| [get_Item(int index)](#get-Item-int-) | Gets subfield contained in this field by index. |
| [setPosition(Point point)](#setPosition-com.aspose.pdf.Point-) | Set position of the field. |
| [updateAppearances()](#updateAppearances--) | Update appearances value. |
| [getAnnotationIndex()](#getAnnotationIndex--) | Gets index of this anotation on the page. |
| [setAnnotationIndex(int value)](#setAnnotationIndex-int-) | Sets index of this anotation on the page. |
| [getPageIndex()](#getPageIndex--) | Gets index of page which contains this field. |
| [getRect()](#getRect--) | Gets the field rectangle. |
| [setRect(Rectangle value)](#setRect-com.aspose.pdf.Rectangle-) | Sets the field rectangle. |
| [isSharedField()](#isSharedField--) | Property for Generator support. |
| [setSharedField(boolean value)](#setSharedField-boolean-) | Property for Generator support. |
| [isFitIntoRectangle()](#isFitIntoRectangle--) | If true then font size will reduced to fit text to specified rectangle. |
| [setFitIntoRectangle(boolean value)](#setFitIntoRectangle-boolean-) | If true then font size will reduced to fit text to specified rectangle. |
| [getMaxFontSize()](#getMaxFontSize--) | Maximal font size which can be used for field contents. -1 to don't check size. |
| [setMaxFontSize(double value)](#setMaxFontSize-double-) | Maximal font size which can be used for field contents. -1 to don't check size. |
| [getMinFontSize()](#getMinFontSize--) | Minimal font size which can be used for field contents. -1 to don't check size. |
| [setMinFontSize(double value)](#setMinFontSize-double-) | Minimal font size which can be used for field contents. -1 to don't check size. |
| [getTabOrder()](#getTabOrder--) | Gets or sets tab order of the field. |
| [setTabOrder(int value)](#setTabOrder-int-) | Gets or sets tab order of the field. |
| [add(WidgetAnnotation item)](#add-com.aspose.pdf.WidgetAnnotation-) |  |
| [clear()](#clear--) |  |
| [contains(WidgetAnnotation item)](#contains-com.aspose.pdf.WidgetAnnotation-) |  |
| [copyTo(WidgetAnnotation[] array, int arrayIndex)](#copyTo-com.aspose.pdf.WidgetAnnotation---int-) |  |
| [isReadOnly()](#isReadOnly--) |  |
| [remove(WidgetAnnotation item)](#remove-com.aspose.pdf.WidgetAnnotation-) |  |
### Field(IDocument doc) {#Field-com.aspose.pdf.IDocument-}
```
public Field(IDocument doc)
```


Creates field for use in Generator.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| doc | [IDocument](../../com.aspose.pdf/idocument) | Document where field will be created. |

### _Password {#-Password}
```
public static final int _Password
```


\_Password

### _FileSelect {#-FileSelect}
```
public static final int _FileSelect
```


\_FileSelect

### getPartialName() {#getPartialName--}
```
public String getPartialName()
```


Gets partial name of the field.

**Returns:**
java.lang.String - String value
### setPartialName(String value) {#setPartialName-java.lang.String-}
```
public void setPartialName(String value)
```


Sets partial name of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

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
public boolean recalculate()
```


Recaculates all calculated fields on the form.

**Returns:**
boolean - true if field value was changed during recalculation.
### getValue() {#getValue--}
```
public String getValue()
```


Gets value of the field.

**Returns:**
java.lang.String - String value
### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


Set value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

### isSynchronized() {#isSynchronized--}
```
public boolean isSynchronized()
```


Returns true if dictionary is synchronized.

**Returns:**
boolean - boolean value
### size() {#size--}
```
public int size()
```


Gets number of subfields in this field. (For example number of items in radio button field).

**Returns:**
int - int value
### getSyncRoot() {#getSyncRoot--}
```
public Object getSyncRoot()
```


Synchronization object.

**Returns:**
java.lang.Object - object value
### isGroup() {#isGroup--}
```
public boolean isGroup()
```


Gets boolean value which indicates is this field non-terminal field i.e. group of fields.

**Returns:**
boolean - boolean value
### copyTo(Field[] array, int index) {#copyTo-com.aspose.pdf.Field---int-}
```
public void copyTo(Field[] array, int index)
```


Copies subfields of this field into array starting from specified index.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [Field\[\]](../../com.aspose.pdf/field) | Array where field must be copied. |
| index | int | Starting index where fields will be copied. |

### iterator() {#iterator--}
```
public Iterator<WidgetAnnotation> iterator()
```


Returns enumerator of contained fields.

**Returns:**
java.util.Iterator<com.aspose.pdf.WidgetAnnotation> - Enumerator object.
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

### updateAppearances() {#updateAppearances--}
```
public void updateAppearances()
```


Update appearances value.

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
| value | int | int value |

### getPageIndex() {#getPageIndex--}
```
public int getPageIndex()
```


Gets index of page which contains this field.

**Returns:**
int - int value
### getRect() {#getRect--}
```
public Rectangle getRect()
```


Gets the field rectangle.

**Returns:**
[Rectangle](../../com.aspose.pdf/rectangle) - the field rectangle.
### setRect(Rectangle value) {#setRect-com.aspose.pdf.Rectangle-}
```
public void setRect(Rectangle value)
```


Sets the field rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [Rectangle](../../com.aspose.pdf/rectangle) | the field rectangle. |

### isSharedField() {#isSharedField--}
```
public boolean isSharedField()
```


Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page.

**Returns:**
boolean - boolean value
### setSharedField(boolean value) {#setSharedField-boolean-}
```
public void setSharedField(boolean value)
```


Property for Generator support. Used when field is added to header or footer. If true, this field will created once and it's appearance will be visible on all pages of the document. If false, separated field will be created for every document page.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### isFitIntoRectangle() {#isFitIntoRectangle--}
```
public static synchronized boolean isFitIntoRectangle()
```


If true then font size will reduced to fit text to specified rectangle.

**Returns:**
boolean - boolean value
### setFitIntoRectangle(boolean value) {#setFitIntoRectangle-boolean-}
```
public static synchronized void setFitIntoRectangle(boolean value)
```


If true then font size will reduced to fit text to specified rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | boolean | boolean value |

### getMaxFontSize() {#getMaxFontSize--}
```
public static synchronized double getMaxFontSize()
```


Maximal font size which can be used for field contents. -1 to don't check size.

**Returns:**
double - double value
### setMaxFontSize(double value) {#setMaxFontSize-double-}
```
public static synchronized void setMaxFontSize(double value)
```


Maximal font size which can be used for field contents. -1 to don't check size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getMinFontSize() {#getMinFontSize--}
```
public static double getMinFontSize()
```


Minimal font size which can be used for field contents. -1 to don't check size.

**Returns:**
double - double value
### setMinFontSize(double value) {#setMinFontSize-double-}
```
public static void setMinFontSize(double value)
```


Minimal font size which can be used for field contents. -1 to don't check size.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

### getTabOrder() {#getTabOrder--}
```
public int getTabOrder()
```


Gets or sets tab order of the field.

**Returns:**
int - int value
### setTabOrder(int value) {#setTabOrder-int-}
```
public void setTabOrder(int value)
```


Gets or sets tab order of the field.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

### add(WidgetAnnotation item) {#add-com.aspose.pdf.WidgetAnnotation-}
```
public void add(WidgetAnnotation item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) |  |

### clear() {#clear--}
```
public void clear()
```




### contains(WidgetAnnotation item) {#contains-com.aspose.pdf.WidgetAnnotation-}
```
public boolean contains(WidgetAnnotation item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) |  |

**Returns:**
boolean
### copyTo(WidgetAnnotation[] array, int arrayIndex) {#copyTo-com.aspose.pdf.WidgetAnnotation---int-}
```
public void copyTo(WidgetAnnotation[] array, int arrayIndex)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [WidgetAnnotation\[\]](../../com.aspose.pdf/widgetannotation) |  |
| arrayIndex | int |  |

### isReadOnly() {#isReadOnly--}
```
public boolean isReadOnly()
```




**Returns:**
boolean
### remove(WidgetAnnotation item) {#remove-com.aspose.pdf.WidgetAnnotation-}
```
public boolean remove(WidgetAnnotation item)
```




**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| item | [WidgetAnnotation](../../com.aspose.pdf/widgetannotation) |  |

**Returns:**
boolean
