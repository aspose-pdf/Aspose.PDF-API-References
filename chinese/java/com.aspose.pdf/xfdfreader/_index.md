---
title: XfdfReader
second_title: 用于 Java API 参考的 Aspose.PDF
description: 执行 XFDF 格式读取的类。
type: docs
weight: 413
url: /zh/java/com.aspose.pdf/xfdfreader/
---
**遗产：**
java.lang.Object
```
public final class XfdfReader
```

执行 XFDF 格式读取的类。

--------------------

`Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf");`
## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XfdfReader()](#XfdfReader--) |  |
## 方法

| 方法 | 描述 |
| --- | --- |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getElements(System.Xml.XmlReader reader)](#getElements-com.aspose.ms.System.Xml.XmlReader-) | 解析 XFDF 文件并将信息作为哈希表返回。 |
| [hashCode()](#hashCode--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [readAnnotations(InputStream stream, IDocument document)](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | 从 XFDF 文件中导入注释并将其放入文档中。 |
| [readFields(InputStream stream, IDocument document)](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | 从 XFDF 文件导入字段值。 |
| [toString()](#toString--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### XfdfReader() {#XfdfReader--}
```
public XfdfReader()
```


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
### getElements(System.Xml.XmlReader reader) {#getElements-com.aspose.ms.System.Xml.XmlReader-}
```
public static Map getElements(System.Xml.XmlReader reader)
```


解析 XFDF 文件并将信息作为哈希表返回。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| reader | com.aspose.ms.System.Xml.XmlReader | 源文件的 XmlReader。 |

**退货：**
java.util.Map - 包含从 XFDF 文件解析的信息的哈希表。
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




### readAnnotations(InputStream stream, IDocument document) {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
```
public static void readAnnotations(InputStream stream, IDocument document)
```


从 XFDF 文件中导入注释并将其放入文档中。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含 XFDF 文件的源流。 |
| document | [IDocument](../../com.aspose.pdf/idocument) | 将在其中添加注释的文档。 |

### readFields(InputStream stream, IDocument document) {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
```
public static void readFields(InputStream stream, IDocument document)
```


从 XFDF 文件导入字段值。

**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| stream | java.io.InputStream | 包含 XFDF 数据的流。 |
| document | [IDocument](../../com.aspose.pdf/idocument) | 将导入字段数据的文档。 |

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
