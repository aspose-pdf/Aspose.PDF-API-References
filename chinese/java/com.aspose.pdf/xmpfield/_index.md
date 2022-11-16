---
title: XmpField
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示 XMP 字段。
type: docs
weight: 417
url: /zh/java/com.aspose.pdf/xmpfield/
---
**遗产：**
java.lang.Object
```
public class XmpField
```

表示 XMP 字段。
## 方法

| 方法 | 描述 |
| --- | --- |
| [dispose()](#dispose--) |  |
| [equals(Object obj)](#equals-java.lang.Object-) | 指示此实例和指定对象是否相等。 |
| [getClass()](#getClass--) |  |
| [getEmpty()](#getEmpty--) | 获取空 xmp 字段。 |
| [getFieldType()](#getFieldType--) | 获取字段的类型。 |
| [getLang()](#getLang--) | 该字段表示 xml:lang 限定符。 |
| [getLocalName()](#getLocalName--) | 获取或设置本地的名称。 |
| [getName()](#getName--) | 获取名称。 |
| [getNamespaceUri()](#getNamespaceUri--) | 获取命名空间 URI。 |
| [getPrefix()](#getPrefix--) | 获取前缀。 |
| [getValue()](#getValue--) | 获取值。 |
| [hashCode()](#hashCode--) | 返回此实例的哈希码。 |
| [isEmpty()](#isEmpty--) | 获取一个值，该值指示此实例是否为空。 |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [op_Equality(XmpField field1, XmpField field2)](#op-Equality-com.aspose.pdf.XmpField-com.aspose.pdf.XmpField-) | 实现运算符==. |
| [op_Inequality(XmpField field1, XmpField field2)](#op-Inequality-com.aspose.pdf.XmpField-com.aspose.pdf.XmpField-) | 实施运营商！ |
| [setLocalName_Rename_Namesake(String value)](#setLocalName-Rename-Namesake-java.lang.String-) | 仅供内部使用 |
| [setNamespaceUri_Rename_Namesake(String value)](#setNamespaceUri-Rename-Namesake-java.lang.String-) | 仅供内部使用 |
| [setPrefix_Rename_Namesake(String value)](#setPrefix-Rename-Namesake-java.lang.String-) | 仅供内部使用 |
| [toArray()](#toArray--) | 获取数组形式的值。 |
| [toString()](#toString--) |  |
| [toStructure()](#toStructure--) | 获取作为结构的值。 |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### dispose() {#dispose--}
```
public static void dispose()
```




### equals(Object obj) {#equals-java.lang.Object-}
```
public boolean equals(Object obj)
```


指示此实例和指定对象是否相等。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| obj | java.lang.Object | 要比较的另一个对象。 2个  |

**退货：**
boolean - 如果 obj 和此实例是同一类型并表示相同的值，则为真；否则，假的。
### getClass() {#getClass--}
```
public final native Class<?> getClass()
```




**退货：**
java.lang.Class<?>
### getEmpty() {#getEmpty--}
```
public static XmpField getEmpty()
```


获取空 xmp 字段。

**退货：**
[XmpField](../../com.aspose.pdf/xmpfield) - XmpField 实例
### getFieldType() {#getFieldType--}
```
public int getFieldType()
```


获取字段的类型。

**退货：**
int - int：字段的类型。
### getLang() {#getLang--}
```
public static XmpField getLang()
```


该字段表示 xml:lang 限定符。

**退货：**
[XmpField](../../com.aspose.pdf/xmpfield) - XmpField 实例
### getLocalName() {#getLocalName--}
```
public String getLocalName()
```


获取或设置本地的名称。

**退货：**
java.lang.String - 字符串：本地的名称。
### getName() {#getName--}
```
public String getName()
```


获取名称。

**退货：**
java.lang.String - 值：名称。
### getNamespaceUri() {#getNamespaceUri--}
```
public String getNamespaceUri()
```


获取命名空间 URI。

**退货：**
java.lang.String - 值：名称空间 URI。
### getPrefix() {#getPrefix--}
```
public String getPrefix()
```


获取前缀。

**退货：**
java.lang.String - 值：前缀。
### getValue() {#getValue--}
```
public XmpValue getValue()
```


获取值。

**退货：**
[XmpValue](../../com.aspose.pdf/xmpvalue) - XmpValue：值。
### hashCode() {#hashCode--}
```
public int hashCode()
```


返回此实例的哈希码。

**退货：**
int - 此实例的哈希码，适用于哈希算法和哈希表等数据结构。
### isEmpty() {#isEmpty--}
```
public boolean isEmpty()
```


获取一个值，该值指示此实例是否为空。

**退货：**
boolean - 布尔值：如果此实例为空则为真；否则，假的。
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### op_Equality(XmpField field1, XmpField field2) {#op-Equality-com.aspose.pdf.XmpField-com.aspose.pdf.XmpField-}
```
public static boolean op_Equality(XmpField field1, XmpField field2)
```


实现运算符==.

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field1 | [XmpField](../../com.aspose.pdf/xmpfield) | 领域1。 |
| field2 | [XmpField](../../com.aspose.pdf/xmpfield) | 领域2。 |

**退货：**
boolean - 运算符的结果。
### op_Inequality(XmpField field1, XmpField field2) {#op-Inequality-com.aspose.pdf.XmpField-com.aspose.pdf.XmpField-}
```
public static boolean op_Inequality(XmpField field1, XmpField field2)
```


实现运算符 !=。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| field1 | [XmpField](../../com.aspose.pdf/xmpfield) | 领域1。 |
| field2 | [XmpField](../../com.aspose.pdf/xmpfield) | 领域2。 |

**退货：**
boolean - 运算符的结果。
### setLocalName_Rename_Namesake(String value) {#setLocalName-Rename-Namesake-java.lang.String-}
```
public void setLocalName_Rename_Namesake(String value)
```


仅供内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 仅供内部使用 |

### setNamespaceUri_Rename_Namesake(String value) {#setNamespaceUri-Rename-Namesake-java.lang.String-}
```
public void setNamespaceUri_Rename_Namesake(String value)
```


仅供内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 仅供内部使用 |

### setPrefix_Rename_Namesake(String value) {#setPrefix-Rename-Namesake-java.lang.String-}
```
public void setPrefix_Rename_Namesake(String value)
```


仅供内部使用

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.String | 仅供内部使用 |

### toArray() {#toArray--}
```
public XmpValue[] toArray()
```


获取数组形式的值。

**退货：**
com.aspose.pdf.XmpValue[] - XmpValue 数组（数组）
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### toStructure() {#toStructure--}
```
public XmpField[] toStructure()
```


获取作为结构的值。

**退货：**
com.aspose.pdf.XmpField[] - XmpField 数组（结构）
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
