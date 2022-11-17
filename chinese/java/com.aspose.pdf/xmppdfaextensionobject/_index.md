---
title: XmpPdfAExtensionObject
second_title: 用于 Java API 参考的 Aspose.PDF
description: 表示字段属性值类型实例的基类。
type: docs
weight: 421
url: /zh/java/com.aspose.pdf/xmppdfaextensionobject/
---
**遗产：**
java.lang.Object
```
public abstract class XmpPdfAExtensionObject
```

表示字段、属性、值类型实例的基类。
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDescription()](#getDescription--) | 获取描述。 |
| [getValue()](#getValue--) | 获取值。 |
| [getXmlInternal(System.Xml.XmlDocument xmlDocument)](#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-) | 返回表示 xml 树中对象的 xml 元素列表。 |
| [getXml_(System.Xml.XmlDocument xmlDocument)](#getXml--com.aspose.ms.System.Xml.XmlDocument-) | 返回表示 xml 树中对象的 xml 元素列表。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [setValue(String value)](#setValue-java.lang.String-) | 设置值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
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
### getValue() {#getValue--}
```
public String getValue()
```


获取值。

**退货：**
java.lang.String - 字符串
### getXmlInternal(System.Xml.XmlDocument xmlDocument) {#getXmlInternal-com.aspose.ms.System.Xml.XmlDocument-}
```
public abstract System.Collections.Generic.List<System.Xml.XmlElement> getXmlInternal(System.Xml.XmlDocument xmlDocument)
```


返回表示 xml 树中对象的 xml 元素列表。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | 源 xml 文档。 |

**退货：**
com.aspose.ms.System.Collections.Generic.List<com.aspose.ms.System.Xml.XmlElement> - xml 元素列表。
### getXml_(System.Xml.XmlDocument xmlDocument) {#getXml--com.aspose.ms.System.Xml.XmlDocument-}
```
public abstract List<System.Xml.XmlElement> getXml_(System.Xml.XmlDocument xmlDocument)
```


返回表示 xml 树中对象的 xml 元素列表。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| xmlDocument | com.aspose.ms.System.Xml.XmlDocument | 源 xml 文档。 |

**退货：**
java.util.List<com.aspose.ms.System.Xml.XmlElement> - xml 元素列表。
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
