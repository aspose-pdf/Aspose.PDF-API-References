---
title: SaveFormat
second_title: 用于 Java API 参考的 Aspose.PDF
description: 指定格式
type: docs
weight: 445
url: /zh/java/com.aspose.pdf/saveformat/
---
**遗产：**
java.lang.Object, java.lang.Enum
```
public enum SaveFormat extends Enum<SaveFormat>
```

指定格式
## 领域

| 场地 | 描述 |
| --- | --- |
| [Aps](#Aps) | 另存为 APS XML 文件。 |
| [Doc](#Doc) | 表示以DOC格式保存 |
| [DocX](#DocX) | 表示以DOCX格式保存 |
| [Epub](#Epub) | 表示以EPUB格式保存（电子书的特殊格式） |
| [Excel](#Excel) | 表示保存为 MsExcel 格式 |
| [Html](#Html) | 表示以 HTML 格式保存 |
| [MobiXml](#MobiXml) | 表示保存为MobiXML格式（电子书专用格式） |
| [None](#None) | 表示不改变格式保存，即保存为 PDF 已过时，最终将被删除，请改用 'SaveFormat.Pdf' |
| [Pdf](#Pdf) | 意味着保存而不改变格式，即作为 PDF 请使用它而不是 'SaveFormat.None'，这是过时的 |
| [PdfXml](#PdfXml) | XML 格式的内部 PDF 文档结构 |
| [Plugin](#Plugin) | 意味着借助插件进行保存 |
| [Pptx](#Pptx) | 表示保存在 MHT(WebArchieve) /// |
| [Svg](#Svg) | 表示以SVG格式保存 |
| [TeX](#TeX) | 表示以 TEX 格式保存，即适合 Latex 文本编辑器的格式 |
| [Xml](#Xml) | 表示以XML格式保存 |
| [Xps](#Xps) | 表示以 XPS 格式保存 |
## 方法

| 方法 | 描述 |
| --- | --- |
| [<T>valueOf(Class<T> arg0, String arg1)](#-T-valueOf-java.lang.Class-T--java.lang.String-) |  |
| [compareTo(E arg0)](#compareTo-E-) |  |
| [equals(Object arg0)](#equals-java.lang.Object-) |  |
| [getClass()](#getClass--) |  |
| [getDeclaringClass()](#getDeclaringClass--) |  |
| [getValue()](#getValue--) |  |
| [hashCode()](#hashCode--) |  |
| [name()](#name--) |  |
| [notify()](#notify--) |  |
| [notifyAll()](#notifyAll--) |  |
| [ordinal()](#ordinal--) |  |
| [toString()](#toString--) |  |
| [valueOf(String name)](#valueOf-java.lang.String-) |  |
| [values()](#values--) |  |
| [wait()](#wait--) |  |
| [wait(long arg0)](#wait-long-) |  |
| [wait(long arg0, int arg1)](#wait-long-int-) |  |
### Aps {#Aps}
```
public static final SaveFormat Aps
```


另存为 APS XML 文件。

### Doc {#Doc}
```
public static final SaveFormat Doc
```


表示以DOC格式保存

### DocX {#DocX}
```
public static final SaveFormat DocX
```


表示以DOCX格式保存

### Epub {#Epub}
```
public static final SaveFormat Epub
```


表示以EPUB格式保存（电子书的特殊格式）

### Excel {#Excel}
```
public static final SaveFormat Excel
```


表示保存为 MsExcel 格式

### Html {#Html}
```
public static final SaveFormat Html
```


表示以 HTML 格式保存

### MobiXml {#MobiXml}
```
public static final SaveFormat MobiXml
```


表示保存为MobiXML格式（电子书专用格式）

### None {#None}
```
public static final SaveFormat None
```


表示不改变格式保存，即保存为 PDF 已过时，最终将被删除，请改用 'SaveFormat.Pdf'

### Pdf {#Pdf}
```
public static final SaveFormat Pdf
```


意味着保存而不改变格式，即作为 PDF 请使用它而不是 'SaveFormat.None'，这是过时的

### PdfXml {#PdfXml}
```
public static final SaveFormat PdfXml
```


XML 格式的内部 PDF 文档结构

### Plugin {#Plugin}
```
public static final SaveFormat Plugin
```


意味着借助插件进行保存

### Pptx {#Pptx}
```
public static final SaveFormat Pptx
```


表示保存在 MHT(WebArchieve) ///

将文档转换为 Mht 格式。此代码是在与相关工作期间使用的实验性代码https://pdf.aspose.com/jira/browse/PDFNEWNET-36340不会投入生产，因为创建的 MHT 存在跨浏览器问题 - 因此，如果最终有必要创建 MHT 本身，它可以在将来使用。 PDFNEWNET-36340 已通过使用 DataSceme URL（将数据嵌入 HTMLhttp://en.wikipedia.org/wiki/Data\_URI\_scheme) 所以，这个转换现在真的没有用过。

表示保存为PPTX格式

### Svg {#Svg}
```
public static final SaveFormat Svg
```


表示以SVG格式保存

### TeX {#TeX}
```
public static final SaveFormat TeX
```


表示以 TEX 格式保存，即适合 Latex 文本编辑器的格式

### Xml {#Xml}
```
public static final SaveFormat Xml
```


表示以XML格式保存

### Xps {#Xps}
```
public static final SaveFormat Xps
```


表示以 XPS 格式保存

### <T>valueOf(Class<T> arg0, String arg1) {#-T-valueOf-java.lang.Class-T--java.lang.String-}
```
public static T <T>valueOf(Class<T> arg0, String arg1)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | java.lang.Class<T> |  |
| arg1 | java.lang.String |  |

**退货：**
吨
### compareTo(E arg0) {#compareTo-E-}
```
public final int compareTo(E arg0)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| arg0 | E |  |

**退货：**
整数
### equals(Object arg0) {#equals-java.lang.Object-}
```
public final boolean equals(Object arg0)
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
### getDeclaringClass() {#getDeclaringClass--}
```
public final Class<E> getDeclaringClass()
```




**退货：**
java.lang.类<E>
### getValue() {#getValue--}
```
public int getValue()
```




**退货：**
整数
### hashCode() {#hashCode--}
```
public final int hashCode()
```




**退货：**
整数
### name() {#name--}
```
public final String name()
```




**退货：**
java.lang.字符串
### notify() {#notify--}
```
public final native void notify()
```




### notifyAll() {#notifyAll--}
```
public final native void notifyAll()
```




### ordinal() {#ordinal--}
```
public final int ordinal()
```




**退货：**
整数
### toString() {#toString--}
```
public String toString()
```




**退货：**
java.lang.字符串
### valueOf(String name) {#valueOf-java.lang.String-}
```
public static SaveFormat valueOf(String name)
```




**参数：**

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| name | java.lang.String |  |

**退货：**
[SaveFormat](../../com.aspose.pdf/saveformat)
### values() {#values--}
```
public static SaveFormat[] values()
```




**退货：**
com.aspose.pdf.保存格式[]
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
