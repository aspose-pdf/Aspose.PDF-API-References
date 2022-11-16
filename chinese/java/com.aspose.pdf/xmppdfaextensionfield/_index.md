---
title: XmpPdfAExtensionField
second_title: 用于 Java API 参考的 Aspose.PDF
description: 此架构描述结构化类型中的字段。
type: docs
weight: 420
url: /zh/java/com.aspose.pdf/xmppdfaextensionfield/
---
**遗产：**
java.lang.Object, [com.aspose.pdf.XmpPdfAExtensionObject](../../com.aspose.pdf/xmppdfaextensionobject)
```
public class XmpPdfAExtensionField extends XmpPdfAExtensionObject
```

此架构描述结构化类型中的字段。它与 PDF/A 属性值类型模式非常相似，但在结构中定义了一个字段而不是属性。架构命名空间 URI：http://www.aiim.org/pdfa/ns/field\# 必需的架构命名空间前缀：pdfaField。
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XmpPdfAExtensionField(String name, String value, String valueType, String description)](#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-) | 初始化对象。 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 获取描述。 |
| [getName()](#getName--) | 字段名称。 |
| [getValue()](#getValue--) | 获取值。 |
| [getValueType()](#getValueType--) | 取自 XMP Specification 2004 的字段值类型，或嵌入式 PDF/A 值类型扩展架构。 |
| [getXmlInternal(System.Xml.XmlDocument xmlDocument)](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | 返回表示 xml 树中字段的 xml 元素列表。 |
| [getXml_(System.Xml.XmlDocument xmlDocument)](#getXml--com.aspose.ms.System.Xml.XmlDocument-) | 返回表示 xml 树中字段的 xml 元素列表。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(String value)](#setValue-java.lang.String-) | 设置值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XmpPdfAExtensionField(String name, String value, String valueType, String description) {#XmpPdfAExtensionField-java.lang.String-java.lang.String-java.lang.String-java.lang.String-}
```
public XmpPdfAExtensionField(String name, String value, String valueType, String description)
```


初始化对象。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String | 字段名称。 |
| value | java.lang.String | 字段值。 |
| valueType | java.lang.String | 字段值类型。 |
| description | java.lang.String | 字段说明。 |

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
### getDescription() {#getDescription--}
```
public String getDescription()
```


获取描述。

**退货：**
java.lang.String - 字符串
### getName() {#getName--}
```
public String getName()
```


字段名称。字段名称必须是有效的 XML 元素名称。

**退货：**
java.lang.String - 字符串
### getValue() {#getValue--}
```
public String getValue()
```


获取值。

**退货：**
java.lang.String - 字符串
### getValueType() {#getValueType--}
```
public String getValueType()
```


取自 XMP Specification 2004 的字段值类型，或嵌入式 PDF/A 值类型扩展架构。预定义的 XMP 类型名称或自定义类型的名称。

**退货：**
java.lang.String - 字符串
### getXmlInternal(System.Xml.XmlDocument xmlDocument) {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
```
public System.Collections.Generic.List<System.Xml.XmlElement> getXmlInternal(System.Xml.XmlDocument xmlDocument)
```


返回表示 xml 树中字段的 xml 元素列表。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | 源 xml 文档。 |

**退货：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Xml.XmlElement> - 字段列表。
### getXml_(System.Xml.XmlDocument xmlDocument) {#getXml--com.aspose.ms.System.Xml.XmlDocument-}
```
public List<System.Xml.XmlElement> getXml_(System.Xml.XmlDocument xmlDocument)
```


返回表示 xml 树中字段的 xml 元素列表。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | 源 xml 文档。 |

**退货：**
java.util.List<com.aspose.ms.System.Xml.XmlElement> - 字段列表。
### hashCode() {#hashCode--}
```
public native int hashCode()
```




**退货：**
整数
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### setValue(String value) {#setValue-java.lang.String-}
```
public void setValue(String value)
```


设置值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| value | java.lang.细绳 | String |

### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
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
