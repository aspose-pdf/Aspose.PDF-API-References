---
title: CosPdfString
second_title: Aspose.PDF for Java API Reference
description: This class represents Pdf String object.
type: docs
weight: 14
url: /java/com.aspose.pdf.utils.publicdata/cospdfstring/
---
**Inheritance:**
java.lang.Object, [com.aspose.pdf.utils.publicdata.CosPdfPrimitive](../../com.aspose.pdf.utils.publicdata/cospdfprimitive)
```
public final class CosPdfString extends CosPdfPrimitive
```

This class represents Pdf String object.
## Constructors

| Constructor | Description |
| --- | --- |
| [CosPdfString(String value)](#CosPdfString-java.lang.String-) | Initializes a new instance of the [CosPdfString](../../com.aspose.pdf.utils.publicdata/cospdfstring) class. |
| [CosPdfString(String value, boolean isHexadecimal)](#CosPdfString-java.lang.String-boolean-) | Initializes a new instance of the [CosPdfString](../../com.aspose.pdf.utils.publicdata/cospdfstring) class. |
## Methods

| Method | Description |
| --- | --- |
| [isHexadecimal()](#isHexadecimal--) | Gets a value indicating whether this instance is hexadecimal. |
| [getValue()](#getValue--) | Gets the string (ANSII). |
| [toCosPdfString()](#toCosPdfString--) | Tries cast this instance to [CosPdfString](../../com.aspose.pdf.utils.publicdata/cospdfstring). |
| [toString()](#toString--) | Returns a String that represents the current [CosPdfString](../../com.aspose.pdf.utils.publicdata/cospdfstring). |
| [hashCode()](#hashCode--) | Get hashcode for current object. |
| [equals(Object obj)](#equals-java.lang.Object-) | Determines that the specified object is equal to the current object. |
### CosPdfString(String value) {#CosPdfString-java.lang.String-}
```
public CosPdfString(String value)
```


Initializes a new instance of the [CosPdfString](../../com.aspose.pdf.utils.publicdata/cospdfstring) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The value. |

### CosPdfString(String value, boolean isHexadecimal) {#CosPdfString-java.lang.String-boolean-}
```
public CosPdfString(String value, boolean isHexadecimal)
```


Initializes a new instance of the [CosPdfString](../../com.aspose.pdf.utils.publicdata/cospdfstring) class.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | The string. |
| isHexadecimal | boolean | if set to  true  [is hexadecimal]. |

### isHexadecimal() {#isHexadecimal--}
```
public final boolean isHexadecimal()
```


Gets a value indicating whether this instance is hexadecimal.

**Returns:**
boolean - boolean value. \*  true  if this instance is hexadecimal; otherwise,  false .
### getValue() {#getValue--}
```
public final String getValue()
```


Gets the string (ANSII).

Value: The string.

**Returns:**
java.lang.String - String value
### toCosPdfString() {#toCosPdfString--}
```
public CosPdfString toCosPdfString()
```


Tries cast this instance to [CosPdfString](../../com.aspose.pdf.utils.publicdata/cospdfstring).

**Returns:**
[CosPdfString](../../com.aspose.pdf.utils.publicdata/cospdfstring) - null if instance is not [CosPdfString](../../com.aspose.pdf.utils.publicdata/cospdfstring) else [CosPdfString](../../com.aspose.pdf.utils.publicdata/cospdfstring).
### toString() {#toString--}
```
public String toString()
```


Returns a String that represents the current [CosPdfString](../../com.aspose.pdf.utils.publicdata/cospdfstring).

**Returns:**
java.lang.String - A String that represents the current [CosPdfString](../../com.aspose.pdf.utils.publicdata/cospdfstring).
### hashCode() {#hashCode--}
```
public int hashCode()
```


Get hashcode for current object.

**Returns:**
int - A hash code for current object.
### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


Determines that the specified object is equal to the current object.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| obj | java.lang.Object | The object to compare with current object |

**Returns:**
boolean - true if specified object is equal to the current object; otherwise, false.
