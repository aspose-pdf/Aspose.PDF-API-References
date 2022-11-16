---
title: XmpValue
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 XMP 值
type: docs
weight: 426
url: /zh/java/com.aspose.pdf/xmpvalue/
---
**遗产：**
java.lang.Object
```
public class XmpValue
```

表示 XMP 值
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpValue(String value)](#XmpValue-java.lang.String-) | 字符串值的构造函数。 |
| [XmpValue(int value)](#XmpValue-int-) | 整数值的构造函数。 |
| [XmpValue(double value)](#XmpValue-double-) | 浮点值的构造函数。 |
| [XmpValue(Date value)](#XmpValue-java.util.Date-) | 日期时间值的构造函数。 |
| [XmpValue(XmpValue[] array)](#XmpValue-com.aspose.pdf.XmpValue---) | 数组值的构造函数。 |
| [XmpValue(Object value)](#XmpValue-java.lang.Object-) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [hashCode()](#hashCode--) |  |
| [isArray()](#isArray--) | 返回 true 是 XmpValue 是数组。 |
| [isDateTime()](#isDateTime--) | 如果值为 DateTime，则返回 true。 |
| [isDouble()](#isDouble--) | 如果值是浮点值，则返回 true。 |
| [isField()](#isField--) | 如果 XmpValue 是字段，则返回 true。 |
| [isInteger()](#isInteger--) | 如果值为整数，则返回 true。 |
| [isNamedValue()](#isNamedValue--) | 如果 XmpValue 被命名为 value，则返回 true。 |
| [isNamedValues()](#isNamedValues--) | 返回 true 是 XmpValue 表示命名值。 |
| [isRaw()](#isRaw--) | 值不受支持/未知，并且提供了原始 XML 代码。 |
| [isString()](#isString--) | 如果值为字符串，则返回 true。 |
| [isStructure()](#isStructure--) | 返回 true 是 XmpValue 表示的结构。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [toArray()](#toArray--) | 返回数组。 |
| [toDateTime()](#toDateTime--) | 转换为日期时间。 |
| [toDictionary()](#toDictionary--) | 返回包含命名值的字典。 |
| [toDouble()](#toDouble--) | 转换为双。 |
| [toField()](#toField--) | 返回 XMP 值作为 XMP 字段。 |
| [toInteger()](#toInteger--) | 转换为整数。 |
| [toNamedValue()](#toNamedValue--) | 将 XMP 值作为命名值返回。 |
| [toNamedValueInternal()](#toNamedValueInternal--) | 仅供内部使用 |
| [toNamedValues()](#toNamedValues--) | 将 XMP 值作为命名值集合返回。 |
| [toNamedValuesInternal()](#toNamedValuesInternal--) |  |
| [toRaw()](#toRaw--) | 未知/不受支持的值的原始 XML 代码。 |
| [toString()](#toString--) | 返回 XmpValue 的字符串表示形式。 |
| [toString(System.IFormatProvider formatProvider)](#toString-com.aspose.ms.System.IFormatProvider-) | 返回字符串表示。 |
| [toStringValue()](#toStringValue--) | 转换为字符串。 |
| [toStructure()](#toStructure--) | 将 XMP 值作为结构（字段集）返回。 |
| [to_(XmpValue value)](#to--com.aspose.pdf.XmpValue-) | 将 XmpValue 转换为数组。 |
| [to_Array(XmpValue value)](#to-Array-com.aspose.pdf.XmpValue-) | 将 XmpValue 转换为数组。 |
| [to_Generic(XmpValue value)](#to-Generic-com.aspose.pdf.XmpValue-) | 获取 KeyValuePair 数组 |
| [to_KeyValuePair(XmpValue value)](#to-KeyValuePair-com.aspose.pdf.XmpValue-) | 将 XmpValue 转换为命名值。 |
| [to_String(XmpValue value)](#to-String-com.aspose.pdf.XmpValue-) | 将 XmpValue 转换为字符串。 |
| [to_XmpValue(double value)](#to-XmpValue-double-) | 将 double 转换为 XmpValue。 |
| [to_XmpValue(int value)](#to-XmpValue-int-) | 将整数转换为 XmpValue。 |
| [to_XmpValue(Object[] value)](#to-XmpValue-java.lang.Object---) | 将数组转换为 XmpValue。 |
| [to_XmpValue(String value)](#to-XmpValue-java.lang.String-) | 将字符串转换为 XmpValue。 |
| [to_XmpValue(Date value)](#to-XmpValue-java.util.Date-) | 将 DateTime 转换为 XmpValue。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpValue(String value) {#XmpValue-java.lang.String-}
```
public XmpValue(String value)
```


字符串值的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值。 |

### XmpValue(int value) {#XmpValue-int-}
```
public XmpValue(int value)
```


整数值的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | 整数值。 |

### XmpValue(double value) {#XmpValue-double-}
```
public XmpValue(double value)
```


浮点值的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双重价值。 |

### XmpValue(Date value) {#XmpValue-java.util.Date-}
```
public XmpValue(Date value)
```


日期时间值的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 日期时间值。 |

### XmpValue(XmpValue[] array) {#XmpValue-com.aspose.pdf.XmpValue---}
```
public XmpValue(XmpValue[] array)
```


数组值的构造函数。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| array | [XmpValue\[\]](../../com.aspose.pdf/xmpvalue) | 数组值。 |

### XmpValue(Object value) {#XmpValue-java.lang.Object-}
```
public XmpValue(Object value)
```


**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object |  |

### equals(Object arg0) {#equals-java.lang.Object-}
```
public boolean equals(Object arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Object |  |

**退货：**
布尔值
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### isArray() {#isArray--}
```
public boolean isArray()
```


返回 true 是 XmpValue 是数组。

**退货：**
boolean - 布尔值
### isDateTime() {#isDateTime--}
```
public boolean isDateTime()
```


如果值为 DateTime，则返回 true。

**退货：**
boolean - 布尔值
### isDouble() {#isDouble--}
```
public boolean isDouble()
```


如果值是浮点值，则返回 true。

**退货：**
boolean - 布尔值
### isField() {#isField--}
```
public boolean isField()
```


如果 XmpValue 是字段，则返回 true。

**退货：**
boolean - 布尔值
### isInteger() {#isInteger--}
```
public boolean isInteger()
```


如果值为整数，则返回 true。

**退货：**
boolean - 布尔值
### isNamedValue() {#isNamedValue--}
```
public boolean isNamedValue()
```


如果 XmpValue 被命名为 value，则返回 true。

**退货：**
boolean - 布尔值
### isNamedValues() {#isNamedValues--}
```
public boolean isNamedValues()
```


返回 true 是 XmpValue 表示命名值。

**退货：**
boolean - 布尔值
### isRaw() {#isRaw--}
```
public final boolean isRaw()
```


值不受支持/未知，并且提供了原始 XML 代码。

**退货：**
boolean - 如果值作为原始数据返回则为真。
### isString() {#isString--}
```
public boolean isString()
```


如果值为字符串，则返回 true。

**退货：**
boolean - 布尔值
### isStructure() {#isStructure--}
```
public boolean isStructure()
```


返回 true 是 XmpValue 表示的结构。

**退货：**
boolean - 布尔值
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### toArray() {#toArray--}
```
public XmpValue[] toArray()
```


返回数组。

**退货：**
com.aspose.pdf.XmpValue[] - XmpValue 数组
### toDateTime() {#toDateTime--}
```
public Date toDateTime()
```


转换为日期时间。

**退货：**
[Date](../../java.util/date) - 日期实例
### toDictionary() {#toDictionary--}
```
public final System.Collections.Generic.Dictionary<String,XmpValue> toDictionary()
```


返回包含命名值的字典。

**退货：**
[Dictionary](../../com.aspose.ms.system.collections.generic/dictionary) 词典
### toDouble() {#toDouble--}
```
public double toDouble()
```


转换为双。

**退货：**
双倍价值
### toField() {#toField--}
```
public XmpField toField()
```


返回 XMP 值作为 XMP 字段。

**退货：**
[XmpField](../../com.aspose.pdf/xmpfield) - XmpField 实例
### toInteger() {#toInteger--}
```
public int toInteger()
```


转换为整数。

**退货：**
int - 整数值
### toNamedValue() {#toNamedValue--}
```
public HashMap<String,XmpValue> toNamedValue()
```


将 XMP 值作为命名值返回。

**退货：**
java.util.HashMap<java.lang.String,com.aspose.pdf.XmpValue> -（命名值）具有字符串键和 XmpValue 值的 HashMap 实例
### toNamedValueInternal() {#toNamedValueInternal--}
```
public System.Collections.Generic.KeyValuePair<String,XmpValue> toNamedValueInternal()
```


仅供内部使用

**退货：**
[KeyValuePair](../../com.aspose.ms.system.collections.generic/keyvaluepair) 仅供内部使用
### toNamedValues() {#toNamedValues--}
```
public HashMap<String,XmpValue> toNamedValues()
```


将 XMP 值作为命名值集合返回。

**退货：**
java.util.HashMap<java.lang.String,com.aspose.pdf.XmpValue> -（命名集合值）具有字符串键和 XmpValue 值的 HashMap 实例
### toNamedValuesInternal() {#toNamedValuesInternal--}
```
public System.Collections.Generic.KeyValuePair<String,XmpValue>[] toNamedValuesInternal()
```




**退货：**
com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>[]
### toRaw() {#toRaw--}
```
public final System.Xml.XmlNode toRaw()
```


未知/不受支持的值的原始 XML 代码。

**退货：**
com.aspose.ms.System.Xml.XmlNode - 此值的 XML 节点。
### toString() {#toString--}
```
public String toString()
```


返回 XmpValue 的字符串表示形式。

**退货：**
java.lang.String - 字符串表示
### toString(System.IFormatProvider formatProvider) {#toString-com.aspose.ms.System.IFormatProvider-}
```
public String toString(System.IFormatProvider formatProvider)
```


返回字符串表示。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| formatProvider | com.aspose.ms.System.IFormatProvider | IFormatProvider 实例（格式提供者） |

**退货：**
java.lang.String - 字符串表示
### toStringValue() {#toStringValue--}
```
public String toStringValue()
```


转换为字符串。

**退货：**
java.lang.String - 字符串值
### toStructure() {#toStructure--}
```
public XmpField[] toStructure()
```


将 XMP 值作为结构（字段集）返回。

**退货：**
com.aspose.pdf.XmpField[] - XmpField 数组
### to_(XmpValue value) {#to--com.aspose.pdf.XmpValue-}
```
public static XmpValue[] to_(XmpValue value)
```


将 XmpValue 转换为数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | XmpValue 实例（要转换的值） |

**退货：**
com.aspose.pdf.XmpValue[] - XmpValue 数组
### to_Array(XmpValue value) {#to-Array-com.aspose.pdf.XmpValue-}
```
public static XmpValue[] to_Array(XmpValue value)
```


将 XmpValue 转换为数组。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | XmpValue 实例（要转换的值） |

**退货：**
com.aspose.pdf.XmpValue[] - XmpValue 数组
### to_Generic(XmpValue value) {#to-Generic-com.aspose.pdf.XmpValue-}
```
public static System.Collections.Generic.KeyValuePair<String,XmpValue>[] to_Generic(XmpValue value)
```


获取 KeyValuePair 数组

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | XmpValue 实例（要转换的值） |

**退货：**
com.aspose.ms.System.Collections.Generic.KeyValuePair<java.lang.String,com.aspose.pdf.XmpValue>[] - 内部数组
### to_KeyValuePair(XmpValue value) {#to-KeyValuePair-com.aspose.pdf.XmpValue-}
```
public static System.Collections.Generic.KeyValuePair<String,XmpValue> to_KeyValuePair(XmpValue value)
```


将 XmpValue 转换为命名值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | XmpValue 实例（要转换的值） |

**退货：**
[KeyValuePair](../../com.aspose.ms.system.collections.generic/keyvaluepair) 内部数组
### to_String(XmpValue value) {#to-String-com.aspose.pdf.XmpValue-}
```
public static String to_String(XmpValue value)
```


将 XmpValue 转换为字符串。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | [XmpValue](../../com.aspose.pdf/xmpvalue) | XmpValue 实例（要转换的值） |

**退货：**
java.lang.String - 字符串值
### to_XmpValue(double value) {#to-XmpValue-double-}
```
public static XmpValue to_XmpValue(double value)
```


将 double 转换为 XmpValue。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | double | 双精度值（要转换的值） |

**退货：**
[XmpValue](../../com.aspose.pdf/xmpvalue) - XmpValue 实例
### to_XmpValue(int value) {#to-XmpValue-int-}
```
public static XmpValue to_XmpValue(int value)
```


将整数转换为 XmpValue。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | int | int 值（要转换的值） |

**退货：**
[XmpValue](../../com.aspose.pdf/xmpvalue) - XmpValue 实例
### to_XmpValue(Object[] value) {#to-XmpValue-java.lang.Object---}
```
public static XmpValue to_XmpValue(Object[] value)
```


将数组转换为 XmpValue。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.Object[] | 对象数组（要转换的值） |

**退货：**
[XmpValue](../../com.aspose.pdf/xmpvalue) - XmpValue 实例
### to_XmpValue(String value) {#to-XmpValue-java.lang.String-}
```
public static XmpValue to_XmpValue(String value)
```


将字符串转换为 XmpValue。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 字符串值（要转换的值） |

**退货：**
[XmpValue](../../com.aspose.pdf/xmpvalue) - XmpValue 实例
### to_XmpValue(Date value) {#to-XmpValue-java.util.Date-}
```
public static XmpValue to_XmpValue(Date value)
```


将 DateTime 转换为 XmpValue。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.util.Date | 日期实例（要转换的值） |

**退货：**
[XmpValue](../../com.aspose.pdf/xmpvalue) - XmpValue 实例
### wait() {#wait--}
```
public final void wait()
```




### wait(long arg0) {#wait-long-}
```
public final native void wait(long arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |

### wait(long arg0, int arg1) {#wait-long-int-}
```
public final void wait(long arg0, int arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | long |  |
| arg1 | int |  |
