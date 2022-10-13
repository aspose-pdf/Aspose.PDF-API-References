---
title: XmpValue
second_title: Aspose.PDF for Java API Reference
description: Represents XMP value
type: docs
weight: 344
url: /java/com.aspose.pdf/xmpvalue/
---
**Inheritance:**
java.lang.Object
```
public class XmpValue
```

Represents XMP value
## Constructors

| Constructor | Description |
| --- | --- |
| [XmpValue(String value)](#XmpValue-java.lang.String-) | Constructor for string value. |
| [XmpValue(int value)](#XmpValue-int-) | Consructor for integer value. |
| [XmpValue(double value)](#XmpValue-double-) | Constructor for floating point Value. |
| [XmpValue(Date value)](#XmpValue-java.util.Date-) | Constructor for date time value. |
| [XmpValue(XmpValue[] array)](#XmpValue-com.aspose.pdf.XmpValue---) | Constructor for array value. |
| [XmpValue(Object value)](#XmpValue-java.lang.Object-) |  |
## Methods

| Method | Description |
| --- | --- |
| [isString()](#isString--) | Returns true if value is string. |
| [isInteger()](#isInteger--) | Returns true if value is integer. |
| [isDouble()](#isDouble--) | Returns true if value is floating point value. |
| [isDateTime()](#isDateTime--) | Returns true if value is DateTime. |
| [isField()](#isField--) | Returns true if XmpValue is field. |
| [isNamedValue()](#isNamedValue--) | Returns true if XmpValue is named value. |
| [isNamedValues()](#isNamedValues--) | Returns true is XmpValue represents named values. |
| [isStructure()](#isStructure--) | Returns true is XmpValue represents structure. |
| [isArray()](#isArray--) | Returns true is XmpValue is array. |
| [toStringValue()](#toStringValue--) | Converts to string. |
| [toInteger()](#toInteger--) | Converts to integer. |
| [toDouble()](#toDouble--) | Converts to double. |
| [toDateTime()](#toDateTime--) | Converts to date time. |
| [toArray()](#toArray--) | Returns array. |
| [toStructure()](#toStructure--) | Returns XMP value as structure (set of fields). |
| [toField()](#toField--) | Returns XMP value as XMP field. |
| [toNamedValue()](#toNamedValue--) | Returns XMP value as named value. |
| [toNamedValueInternal()](#toNamedValueInternal--) | For Internal usage only |
| [toNamedValues()](#toNamedValues--) | Returns XMP value as named value collection. |
| [toNamedValuesInternal()](#toNamedValuesInternal--) | For Internal usage only |
| [toString()](#toString--) | Returs string representation of XmpValue. |
| [toString(System.IFormatProvider formatProvider)](#toString-com.aspose.ms.System.IFormatProvider-) | Returns string representation. |
| [to_XmpValue(String value)](#to-XmpValue-java.lang.String-) | Convers string to XmpValue. |
| [to_XmpValue(int value)](#to-XmpValue-int-) | Converts integer into XmpValue. |
| [to_XmpValue(double value)](#to-XmpValue-double-) | Converts double into XmpValue. |
| [to_XmpValue(Date value)](#to-XmpValue-java.util.Date-) | Converts DateTime into XmpValue. |
| [to_XmpValue(Object[] value)](#to-XmpValue-java.lang.Object---) | Converts array to XmpValue. |
| [to_Array(XmpValue value)](#to-Array-com.aspose.pdf.XmpValue-) | Converts XmpValue to array. |
| [to_(XmpValue value)](#to--com.aspose.pdf.XmpValue-) | Converts XmpValue into array. |
| [to_String(XmpValue value)](#to-String-com.aspose.pdf.XmpValue-) | Converts XmpValue into string. |
| [to_KeyValuePair(XmpValue value)](#to-KeyValuePair-com.aspose.pdf.XmpValue-) | Converts XmpValue to named value. |
| [to_Generic(XmpValue value)](#to-Generic-com.aspose.pdf.XmpValue-) | Get KeyValuePair array |
### XmpValue(String value) {#XmpValue-java.lang.String-}
```
public XmpValue(String value)
```


Constructor for string value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value. |

### XmpValue(int value) {#XmpValue-int-}
```
public XmpValue(int value)
```


Consructor for integer value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | Integer value. |

### XmpValue(double value) {#XmpValue-double-}
```
public XmpValue(double value)
```


Constructor for floating point Value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | Double value. |

### XmpValue(Date value) {#XmpValue-java.util.Date-}
```
public XmpValue(Date value)
```


Constructor for date time value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date time value. |

### XmpValue(XmpValue[] array) {#XmpValue-com.aspose.pdf.XmpValue---}
```
public XmpValue(XmpValue[] array)
```


Constructor for array value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| array | [XmpValue\[\]](../../com.aspose.pdf/xmpvalue) | Array value. |

### XmpValue(Object value) {#XmpValue-java.lang.Object-}
```
public XmpValue(Object value)
```


**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object |  |

### isString() {#isString--}
```
public boolean isString()
```


Returns true if value is string.

**Returns:**
boolean - boolean value
### isInteger() {#isInteger--}
```
public boolean isInteger()
```


Returns true if value is integer.

**Returns:**
boolean - boolean value
### isDouble() {#isDouble--}
```
public boolean isDouble()
```


Returns true if value is floating point value.

**Returns:**
boolean - boolean value
### isDateTime() {#isDateTime--}
```
public boolean isDateTime()
```


Returns true if value is DateTime.

**Returns:**
boolean - boolean value
### isField() {#isField--}
```
public boolean isField()
```


Returns true if XmpValue is field.

**Returns:**
boolean - boolean value
### isNamedValue() {#isNamedValue--}
```
public boolean isNamedValue()
```


Returns true if XmpValue is named value.

**Returns:**
boolean - boolean value
### isNamedValues() {#isNamedValues--}
```
public boolean isNamedValues()
```


Returns true is XmpValue represents named values.

**Returns:**
boolean - boolean value
### isStructure() {#isStructure--}
```
public boolean isStructure()
```


Returns true is XmpValue represents structure.

**Returns:**
boolean - boolean value
### isArray() {#isArray--}
```
public boolean isArray()
```


Returns true is XmpValue is array.

**Returns:**
boolean - boolean value
### toStringValue() {#toStringValue--}
```
public String toStringValue()
```


Converts to string.

**Returns:**
java.lang.String - String value
### toInteger() {#toInteger--}
```
public int toInteger()
```


Converts to integer.

**Returns:**
int - int value
### toDouble() {#toDouble--}
```
public double toDouble()
```


Converts to double.

**Returns:**
double - double value
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


Converts to date time.

**Returns:**
[Date](../../java.util/date) - Date instance
### toArray() {#toArray--}
```
public XmpValue[] toArray()
```


Returns array.

**Returns:**
com.aspose.pdf.XmpValue[] - XmpValue array
### toStructure() {#toStructure--}
```
public XmpField[] toStructure()
```


Returns XMP value as structure (set of fields).

**Returns:**
com.aspose.pdf.XmpField[] - XmpField array
### toField() {#toField--}
```
public XmpField toField()
```


Returns XMP value as XMP field.

**Returns:**
[XmpField](../../com.aspose.pdf/xmpfield) - XmpField instance
### toNamedValue() {#toNamedValue--}
```
public HashMap<String,XmpValue> toNamedValue()
```


Returns XMP value as named value.

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.pdf.XmpValue> - HashMap instance with String Key and XmpValue value
### toNamedValueInternal() {#toNamedValueInternal--}
```
public System.Collections.Generic.KeyValuePair<String,XmpValue> toNamedValueInternal()
```


For Internal usage only

**Returns:**
[KeyValuePair](../../com.aspose.ms.system.collections.generic/keyvaluepair) - For Internal usage only
### toNamedValues() {#toNamedValues--}
```
public HashMap<String,XmpValue> toNamedValues()
```


Returns XMP value as named value collection.

**Returns:**
java.util.HashMap<java.lang.String,com.aspose.pdf.XmpValue> - HashMap instance with String Key and XmpValue value
### toNamedValuesInternal() {#toNamedValuesInternal--}
```
public System.Collections.Generic.KeyValuePair<String,XmpValue>[] toNamedValuesInternal()
```


For Internal usage only

**Returns:**
com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>[] - For Internal usage only
### toString() {#toString--}
```
public String toString()
```


Returs string representation of XmpValue.

**Returns:**
java.lang.String - String value
### toString(System.IFormatProvider formatProvider) {#toString-com.aspose.ms.System.IFormatProvider-}
```
public String toString(System.IFormatProvider formatProvider)
```


Returns string representation.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| formatProvider | com.aspose.ms.System.IFormatProvider | IFormatProvider instance |

**Returns:**
java.lang.String - String value
### to_XmpValue(String value) {#to-XmpValue-java.lang.String-}
```
public static XmpValue to_XmpValue(String value)
```


Convers string to XmpValue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.String | String value |

**Returns:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - XmpValue instance
### to_XmpValue(int value) {#to-XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```


Converts integer into XmpValue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | int | int value |

**Returns:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - XmpValue instance
### to_XmpValue(double value) {#to-XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```


Converts double into XmpValue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | double | double value |

**Returns:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - XmpValue instance
### to_XmpValue(Date value) {#to-XmpValue-java.util.Date-}
```
public static XmpValue to_XmpValue(Date value)
```


Converts DateTime into XmpValue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.util.Date | Date instance |

**Returns:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - XmpValue instance
### to_XmpValue(Object[] value) {#to-XmpValue-java.lang.Object---}
```
public static XmpValue to_XmpValue(Object[] value)
```


Converts array to XmpValue.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | java.lang.Object[] | Array of Objects |

**Returns:**
[XmpValue](../../com.aspose.pdf/xmpvalue) - XmpValue instance
### to_Array(XmpValue value) {#to-Array-com.aspose.pdf.XmpValue-}
```
public static XmpValue[] to_Array(XmpValue value)
```


Converts XmpValue to array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | XmpValue instance |

**Returns:**
com.aspose.pdf.XmpValue[] - XmpValue array
### to_(XmpValue value) {#to--com.aspose.pdf.XmpValue-}
```
public static XmpValue[] to_(XmpValue value)
```


Converts XmpValue into array.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | XmpValue instance |

**Returns:**
com.aspose.pdf.XmpValue[] - XmpValue array
### to_String(XmpValue value) {#to-String-com.aspose.pdf.XmpValue-}
```
public static String to_String(XmpValue value)
```


Converts XmpValue into string.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | XmpValue instance |

**Returns:**
java.lang.String - String value
### to_KeyValuePair(XmpValue value) {#to-KeyValuePair-com.aspose.pdf.XmpValue-}
```
public static System.Collections.Generic.KeyValuePair<String,XmpValue> to_KeyValuePair(XmpValue value)
```


Converts XmpValue to named value.

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | XmpValue instance |

**Returns:**
[KeyValuePair](../../com.aspose.ms.system.collections.generic/keyvaluepair) - Internal Array
### to_Generic(XmpValue value) {#to-Generic-com.aspose.pdf.XmpValue-}
```
public static System.Collections.Generic.KeyValuePair<String,XmpValue>[] to_Generic(XmpValue value)
```


Get KeyValuePair array

**Parameters:**
| Parameter | Type | Description |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | XmpValue instance |

**Returns:**
com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>[] - Internal Array
