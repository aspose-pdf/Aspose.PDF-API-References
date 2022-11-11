---
title: StructureAttribute
second_title: Aspose.PDF for Java API Reference
description: Represents attribute of structure element.
type: docs
weight: 17
url: /java/com.aspose.pdf.tagged.logicalstructure.elements/structureattribute/
---
**Inheritance:**
java.lang.Object
```
public class StructureAttribute
```

Represents attribute of structure element.
## Constructors

| Constructor | Description |
| --- | --- |
| [StructureAttribute(AttributeKey attributeKey)](#StructureAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-) | Initializes a new instance of the StructureAttribute. |
| [StructureAttribute(AttributeKey attributeKey, IPdfPrimitive pdfEntity)](#StructureAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-com.aspose.pdf.engine.data.IPdfPrimitive-) |  |
## Methods

| Method | Description |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getArrayNumberValue()](#getArrayNumberValue--) | Gets Value Number Array. |
| [getArrayValue()](#getArrayValue--) | Gets Value Name Array. |
| [getClass()](#getClass--) |  |
| [getKey()](#getKey--) | Gets attribute key. |
| [getNameValue()](#getNameValue--) | Gets Value Name. |
| [getNumberValue()](#getNumberValue--) | Gets Value Number. |
| [getStringValue()](#getStringValue--) | Gets Value String. |
| [hashCode()](#hashCode--) |  |
| [isInitializedValue()](#isInitializedValue--) | Gets status of structure attribute value. |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setArrayNumberValue(Double[][] arrayNumber)](#setArrayNumberValue-java.lang.Double-----) | Sets Value Number Array. |
| [setArrayValue(AttributeName[] array)](#setArrayValue-com.aspose.pdf.tagged.logicalstructure.AttributeName---) | Sets Value Name Array. |
| [setColorValue(Color color)](#setColorValue-com.aspose.pdf.Color-) | Sets Value Color. |
| [setNameValue(AttributeName name)](#setNameValue-com.aspose.pdf.tagged.logicalstructure.AttributeName-) | Sets Value Name. |
| [setNumberValue(double number)](#setNumberValue-double-) | Sets Value Number. |
| [setRectangleValue(Rectangle rectangle)](#setRectangleValue-com.aspose.pdf.Rectangle-) | Sets Value Rectangle. |
| [setStringValue(String value)](#setStringValue-java.lang.String-) | Sets Value String. |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### StructureAttribute(AttributeKey attributeKey) {#StructureAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-}
```
public StructureAttribute(AttributeKey attributeKey)
```


Initializes a new instance of the StructureAttribute.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attributeKey | [AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) | Attribute Key |

### StructureAttribute(AttributeKey attributeKey, IPdfPrimitive pdfEntity) {#StructureAttribute-com.aspose.pdf.tagged.logicalstructure.AttributeKey-com.aspose.pdf.engine.data.IPdfPrimitive-}
```
public StructureAttribute(AttributeKey attributeKey, IPdfPrimitive pdfEntity)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| attributeKey | [AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) |  |
| pdfEntity | [IPdfPrimitive](../../com.aspose.pdf.engine.data/ipdfprimitive) |  |

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
### getArrayNumberValue() {#getArrayNumberValue--}
```
public final Double[][] getArrayNumberValue()
```


Gets Value Number Array.

**Returns:**
java.lang.Double[][] - Value Number Array.
### getArrayValue() {#getArrayValue--}
```
public final AttributeName[] getArrayValue()
```


Gets Value Name Array.

**Returns:**
com.aspose.pdf.tagged.logicalstructure.AttributeName[] - Value Name Array.
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**Returns:**
java.lang.Class<?>
### getKey() {#getKey--}
```
public final AttributeKey getKey()
```


Gets attribute key.

Value: Attribute Key.

**Returns:**
[AttributeKey](../../com.aspose.pdf.tagged.logicalstructure/attributekey) - AttributeKey instance
### getNameValue() {#getNameValue--}
```
public final AttributeName getNameValue()
```


Gets Value Name.

**Returns:**
[AttributeName](../../com.aspose.pdf.tagged.logicalstructure/attributename) - Value Name.
### getNumberValue() {#getNumberValue--}
```
public final Double[] getNumberValue()
```


Gets Value Number.

**Returns:**
java.lang.Double[] - Value Number.
### getStringValue() {#getStringValue--}
```
public final String getStringValue()
```


Gets Value String.

**Returns:**
java.lang.String - Value String.
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**Returns:**
int
### isInitializedValue() {#isInitializedValue--}
```
public final boolean isInitializedValue()
```


Gets status of structure attribute value. True if value is set.

**Returns:**
boolean - boolean value
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setArrayNumberValue(Double[][] arrayNumber) {#setArrayNumberValue-java.lang.Double-----}
```
public final void setArrayNumberValue(Double[][] arrayNumber)
```


Sets Value Number Array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arrayNumber | java.lang.Double[][] | Array of Numbers. |

### setArrayValue(AttributeName[] array) {#setArrayValue-com.aspose.pdf.tagged.logicalstructure.AttributeName---}
```
public final void setArrayValue(AttributeName[] array)
```


Sets Value Name Array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [AttributeName\[\]](../../com.aspose.pdf.tagged.logicalstructure/attributename) | Array of allowable Value Names. |

### setColorValue(Color color) {#setColorValue-com.aspose.pdf.Color-}
```
public final void setColorValue(Color color)
```


Sets Value Color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.pdf/color) | Color. |

### setNameValue(AttributeName name) {#setNameValue-com.aspose.pdf.tagged.logicalstructure.AttributeName-}
```
public final void setNameValue(AttributeName name)
```


Sets Value Name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | [AttributeName](../../com.aspose.pdf.tagged.logicalstructure/attributename) | Allowable Value Name. |

### setNumberValue(double number) {#setNumberValue-double-}
```
public final void setNumberValue(double number)
```


Sets Value Number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | double | Value Number. |

### setRectangleValue(Rectangle rectangle) {#setRectangleValue-com.aspose.pdf.Rectangle-}
```
public final void setRectangleValue(Rectangle rectangle)
```


Sets Value Rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle. |

### setStringValue(String value) {#setStringValue-java.lang.String-}
```
public final void setStringValue(String value)
```


Sets Value String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value String. |

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

