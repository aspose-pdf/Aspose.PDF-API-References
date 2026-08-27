---
title: "XmpValue"
linktitle: "XmpValue"
second_title: "Aspose.PDF for Java API 参考"
description: "表示 XMP 值"
type: docs
weight: 5750
url: /zh/java/com.aspose.pdf/xmpvalue/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XmpValue

```
public class XmpValue extends Object
```

表示 XMP 值

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpValue](#XmpValue-java.util.Date-) | 日期时间值的构造函数。 |
| [XmpValue](#XmpValue-double-) | 浮点值的构造函数。 |
| [XmpValue](#XmpValue-int-) | 整数值的构造函数。 |
| [XmpValue](#XmpValue-java.lang.Object-) |  |
| [XmpValue](#XmpValue-java.lang.String-) | 字符串值的构造函数。 |
| [XmpValue](#XmpValue-java.lang.String-boolean-) | 初始化新的字符串 XMP 值。 |
| [XmpValue](#XmpValue-com.aspose.pdf.XmpValue:A-) | 数组值的构造函数。 |

## 方法

| 方法 | 描述 |
| --- | --- |
| [isArray](#isArray--) | 如果 XmpValue 是数组，则返回 true。 |
| [isDateTime](#isDateTime--) | 如果值是 DateTime，则返回 true。 |
| [isDouble](#isDouble--) | 如果值是浮点数，则返回 true。 |
| [isField](#isField--) | 如果 XmpValue 是字段，则返回 true。 |
| [isInteger](#isInteger--) | 如果值是整数，则返回 true。 |
| [isNamedValue](#isNamedValue--) | 如果 XmpValue 是命名值，则返回 true。 |
| [isNamedValues](#isNamedValues--) | 如果 XmpValue 表示命名值，则返回 true。 |
| [isRaw](#isRaw--) | 值不受支持/未知，并提供原始 XML 代码。 |
| [isString](#isString--) | 如果值是字符串，则返回 true。 |
| [isStructure](#isStructure--) | 如果 XmpValue 表示结构，则返回 true。 |
| [to_](#to_-com.aspose.pdf.XmpValue-) | 将 XmpValue 转换为数组。 |
| [to_Array](#to_Array-com.aspose.pdf.XmpValue-) | 将 XmpValue 转换为数组。 |
| [to_Generic](#to_Generic-com.aspose.pdf.XmpValue-) | 获取 KeyValuePair 数组 |
| [to_KeyValuePair](#to_KeyValuePair-com.aspose.pdf.XmpValue-) | 将 XmpValue 转换为命名值。 |
| [to_String](#to_String-com.aspose.pdf.XmpValue-) | 将 XmpValue 转换为字符串。 |
| [to_XmpValue](#to_XmpValue-java.util.Date-) | 将 DateTime 转换为 XmpValue。 |
| [to_XmpValue](#to_XmpValue-double-) | 将 double 转换为 XmpValue。 |
| [to_XmpValue](#to_XmpValue-int-) | 将 integer 转换为 XmpValue。 |
| [to_XmpValue](#to_XmpValue-java.lang.Object:A-) | 将数组转换为 XmpValue。 |
| [to_XmpValue](#to_XmpValue-java.lang.String-) | 将字符串转换为 XmpValue。 |
| [toArray](#toArray--) | 返回数组。 |
| [toDateTime](#toDateTime--) | 转换为日期时间。 |
| [toDateTimeOffset](#toDateTimeOffset--) | 将当前 XMP 值转换为 {@link DateTimeOffset} 表示。 |
| [toDictionary](#toDictionary--) | 返回包含命名值的字典。 |
| [toDouble](#toDouble--) | 转换为 double。 |
| [toField](#toField--) | 返回 XMP 值作为 XMP 字段。 |
| [toInteger](#toInteger--) | 转换为整数。 |
| [toNamedValue](#toNamedValue--) | 返回 XMP 值作为命名值。 |
| [toNamedValueInternal](#toNamedValueInternal--) | 仅供内部使用 |
| [toNamedValues](#toNamedValues--) | 返回 XMP 值作为命名值集合。 |
| [toNamedValuesInternal](#toNamedValuesInternal--) |  |
| [toRaw](#toRaw--) | 未知/不受支持值的原始 XML 代码。 |
| [toString](#toString--) | 返回 XmpValue 的字符串表示形式。 |
| [toString](#toString-com.aspose.ms.System.IFormatProvider-) | 返回 XmpValue 的字符串表示形式。 |
| [toStringValue](#toStringValue--) | 转换为字符串。 |
| [toStructure](#toStructure--) | 返回 XMP 值作为结构（字段集合）。 |

### XmpValue {#XmpValue-java.util.Date-}
日期时间值的构造函数。

### XmpValue {#XmpValue-double-}
```
public XmpValue(double value)
```

浮点值的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | Double 值。 |

### XmpValue {#XmpValue-int-}
```
public XmpValue(int value)
```

整数值的构造函数。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | Integer 值。 |

### XmpValue {#XmpValue-java.lang.Object-}


### XmpValue {#XmpValue-java.lang.String-}
字符串值的构造函数。

### XmpValue {#XmpValue-java.lang.String-boolean-}
初始化新的字符串 XMP 值。

### XmpValue {#XmpValue-com.aspose.pdf.XmpValue:A-}
数组值的构造函数。

### isArray {#isArray--}
```
public boolean isArray()
```

如果 XmpValue 是数组，则返回 true。

**Returns:**
布尔值

### isDateTime {#isDateTime--}
```
public boolean isDateTime()
```

如果值是 DateTime，则返回 true。

**Returns:**
布尔值

### isDouble {#isDouble--}
```
public boolean isDouble()
```

如果值是浮点数，则返回 true。

**Returns:**
布尔值

### isField {#isField--}
```
public boolean isField()
```

如果 XmpValue 是字段，则返回 true。

**Returns:**
布尔值

### isInteger {#isInteger--}
```
public boolean isInteger()
```

如果值是整数，则返回 true。

**Returns:**
布尔值

### isNamedValue {#isNamedValue--}
```
public boolean isNamedValue()
```

如果 XmpValue 是命名值，则返回 true。

**Returns:**
布尔值

### isNamedValues {#isNamedValues--}
```
public boolean isNamedValues()
```

如果 XmpValue 表示命名值，则返回 true。

**Returns:**
布尔值

### isRaw {#isRaw--}
```
public final boolean isRaw()
```

值不受支持/未知，并提供原始 XML 代码。

**Returns:**
如果值作为原始数据返回，则为 True。

### isString {#isString--}
```
public boolean isString()
```

如果值是字符串，则返回 true。

**Returns:**
布尔值

### isStructure {#isStructure--}
```
public boolean isStructure()
```

如果 XmpValue 表示结构，则返回 true。

**Returns:**
布尔值

### to_ {#to_-com.aspose.pdf.XmpValue-}
将 XmpValue 转换为数组。

### to_Array {#to_Array-com.aspose.pdf.XmpValue-}
将 XmpValue 转换为数组。

### to_Generic {#to_Generic-com.aspose.pdf.XmpValue-}
获取 KeyValuePair 数组

### to_KeyValuePair {#to_KeyValuePair-com.aspose.pdf.XmpValue-}
将 XmpValue 转换为命名值。

### to_String {#to_String-com.aspose.pdf.XmpValue-}
将 XmpValue 转换为字符串。

### to_XmpValue {#to_XmpValue-java.util.Date-}
将 DateTime 转换为 XmpValue。

### to_XmpValue {#to_XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```

将 double 转换为 XmpValue。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | double 值（要转换的值） |

**Returns:**
XmpValue 实例

### to_XmpValue {#to_XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```

将 integer 转换为 XmpValue。

**Parameters:**
| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 值 |  | int 值（要转换的值） |

**Returns:**
XmpValue 实例

### to_XmpValue {#to_XmpValue-java.lang.Object:A-}
将数组转换为 XmpValue。

### to_XmpValue {#to_XmpValue-java.lang.String-}
将字符串转换为 XmpValue。

### toArray {#toArray--}
```
public XmpValue [] toArray()
```

返回数组。

**Returns:**
XmpValue 数组

### toDateTime {#toDateTime--}
```
public Date toDateTime()
```

转换为日期时间。

**Returns:**
Date 实例

### toDateTimeOffset {#toDateTimeOffset--}
```
public final com.aspose.ms.System.DateTimeOffset toDateTimeOffset()
```

将当前 XMP 值转换为 {@link DateTimeOffset} 表示。

**Returns:**
一个 {@link DateTimeOffset}，表示当前的 XMP 值。

### toDictionary {#toDictionary--}
```
public final com.aspose.ms.System.Collections.Generic.Dictionary< String , XmpValue > toDictionary()
```

返回包含命名值的字典。

**Returns:**
字典

### toDouble {#toDouble--}
```
public double toDouble()
```

转换为 double。

**Returns:**
double 值

### toField {#toField--}
```
public XmpField toField()
```

返回 XMP 值作为 XMP 字段。

**Returns:**
XmpField 实例

### toInteger {#toInteger--}
```
public int toInteger()
```

转换为整数。

**Returns:**
int 值

### toNamedValue {#toNamedValue--}
```
public HashMap < String , XmpValue > toNamedValue()
```

返回 XMP 值作为命名值。

**Returns:**
(命名值) HashMap 实例，键为 String，值为 XmpValue。

### toNamedValueInternal {#toNamedValueInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue > toNamedValueInternal()
```

仅供内部使用

**Returns:**
仅供内部使用

### toNamedValues {#toNamedValues--}
```
public HashMap < String , XmpValue > toNamedValues()
```

返回 XMP 值作为命名值集合。

**Returns:**
(命名集合值) HashMap 实例，键为 String，值为 XmpValue。

### toNamedValuesInternal {#toNamedValuesInternal--}
```
public com.aspose.ms.System.Collections.Generic.KeyValuePair< String , XmpValue >[] toNamedValuesInternal()
```



### toRaw {#toRaw--}
```
public final com.aspose.ms.System.Xml.XmlNode toRaw()
```

未知/不受支持值的原始 XML 代码。

**Returns:**
此值的 XML 节点。

### toString {#toString--}
```
public String toString()
```

返回 XmpValue 的字符串表示形式。

**Returns:**
字符串表示形式

### toString {#toString-com.aspose.ms.System.IFormatProvider-}
返回 XmpValue 的字符串表示形式。

**Returns:**
字符串表示形式

### toStringValue {#toStringValue--}
```
public String toStringValue()
```

转换为字符串。

**Returns:**
字符串值

### toStructure {#toStructure--}
```
public XmpField [] toStructure()
```

返回 XMP 值作为结构（字段集合）。

**Returns:**
XmpField 数组
