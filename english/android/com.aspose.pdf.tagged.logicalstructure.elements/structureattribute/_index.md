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
| [getKey()](#getKey--) | Gets attribute key. |
| [getNameValue()](#getNameValue--) | Gets Value Name. |
| [getStringValue()](#getStringValue--) | Gets Value String. |
| [getNumberValue()](#getNumberValue--) | Gets Value Number. |
| [getArrayValue()](#getArrayValue--) | Gets Value Name Array. |
| [getArrayNumberValue()](#getArrayNumberValue--) | Gets Value Number Array. |
| [setNameValue(AttributeName name)](#setNameValue-com.aspose.pdf.tagged.logicalstructure.AttributeName-) | Sets Value Name. |
| [setStringValue(String value)](#setStringValue-java.lang.String-) | Sets Value String. |
| [setNumberValue(double number)](#setNumberValue-double-) | Sets Value Number. |
| [setArrayValue(AttributeName[] array)](#setArrayValue-com.aspose.pdf.tagged.logicalstructure.AttributeName---) | Sets Value Name Array. |
| [setArrayNumberValue(Double[][] arrayNumber)](#setArrayNumberValue-java.lang.Double-----) | Sets Value Number Array. |
| [setColorValue(Color color)](#setColorValue-com.aspose.pdf.Color-) | Sets Value Color. |
| [setRectangleValue(Rectangle rectangle)](#setRectangleValue-com.aspose.pdf.Rectangle-) | Sets Value Rectangle. |
| [isInitializedValue()](#isInitializedValue--) | Gets status of structure attribute value. |
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
### getStringValue() {#getStringValue--}
```
public final String getStringValue()
```


Gets Value String.

**Returns:**
java.lang.String - Value String.
### getNumberValue() {#getNumberValue--}
```
public final Double[] getNumberValue()
```


Gets Value Number.

**Returns:**
java.lang.Double[] - Value Number.
### getArrayValue() {#getArrayValue--}
```
public final AttributeName[] getArrayValue()
```


Gets Value Name Array.

**Returns:**
com.aspose.pdf.tagged.logicalstructure.AttributeName[] - Value Name Array.
### getArrayNumberValue() {#getArrayNumberValue--}
```
public final Double[][] getArrayNumberValue()
```


Gets Value Number Array.

**Returns:**
java.lang.Double[][] - Value Number Array.
### setNameValue(AttributeName name) {#setNameValue-com.aspose.pdf.tagged.logicalstructure.AttributeName-}
```
public final void setNameValue(AttributeName name)
```


Sets Value Name.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| name | [AttributeName](../../com.aspose.pdf.tagged.logicalstructure/attributename) | Allowable Value Name. |

### setStringValue(String value) {#setStringValue-java.lang.String-}
```
public final void setStringValue(String value)
```


Sets Value String.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | Value String. |

### setNumberValue(double number) {#setNumberValue-double-}
```
public final void setNumberValue(double number)
```


Sets Value Number.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| number | double | Value Number. |

### setArrayValue(AttributeName[] array) {#setArrayValue-com.aspose.pdf.tagged.logicalstructure.AttributeName---}
```
public final void setArrayValue(AttributeName[] array)
```


Sets Value Name Array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [AttributeName\[\]](../../com.aspose.pdf.tagged.logicalstructure/attributename) | Array of allowable Value Names. |

### setArrayNumberValue(Double[][] arrayNumber) {#setArrayNumberValue-java.lang.Double-----}
```
public final void setArrayNumberValue(Double[][] arrayNumber)
```


Sets Value Number Array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| arrayNumber | java.lang.Double[][] | Array of Numbers. |

### setColorValue(Color color) {#setColorValue-com.aspose.pdf.Color-}
```
public final void setColorValue(Color color)
```


Sets Value Color.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| color | [Color](../../com.aspose.pdf/color) | Color. |

### setRectangleValue(Rectangle rectangle) {#setRectangleValue-com.aspose.pdf.Rectangle-}
```
public final void setRectangleValue(Rectangle rectangle)
```


Sets Value Rectangle.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| rectangle | [Rectangle](../../com.aspose.pdf/rectangle) | Rectangle. |

### isInitializedValue() {#isInitializedValue--}
```
public final boolean isInitializedValue()
```


Gets status of structure attribute value. True if value is set.

**Returns:**
boolean - boolean value
