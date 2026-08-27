---
title: "XfdfReader"
linktitle: "XfdfReader"
second_title: "Aspose.PDF for Java API 参考"
description: "<p> 执行 XFDF 格式读取的类。 </p> <hr> <p> <code> Document doc = new Document(\\\"example.pdf\\\"); InputStream xfdfStream = new FileInputStream(\\\"filename\\\")."
type: docs
weight: 5570
url: /zh/java/com.aspose.pdf/xfdfreader/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XfdfReader

```
public final class XfdfReader extends Object
```

<p> 执行读取 XFDF 格式的类。 </p> <hr> <p> <code> Document doc = new Document("example.pdf"); InputStream xfdfStream = new FileInputStream("filename"); XfdfReader.readAnnotations(xfdfStream, doc); xfdfStream.close(); doc.save("example_out.pdf"); </code> </p>

## 构造函数

| 构造函数 | 描述 |
| --- | --- |
| [XfdfReader](#XfdfReader--) |  |

## 方法

| 方法 | 描述 |
| --- | --- |
| [getElements](#getElements-com.aspose.ms.System.Xml.XmlReader-) | 解析 XFDF 文件并以哈希表返回信息。 |
| [readAnnotations](#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-) | 从 XFDF 文件导入批注并将其放入文档。 |
| [readFields](#readFields-java.io.InputStream-com.aspose.pdf.IDocument-) | 从 XFDF 文件导入字段值。 |

### XfdfReader {#XfdfReader--}
```
public XfdfReader()
```



### getElements {#getElements-com.aspose.ms.System.Xml.XmlReader-}
解析 XFDF 文件并以哈希表返回信息。

### readAnnotations {#readAnnotations-java.io.InputStream-com.aspose.pdf.IDocument-}
从 XFDF 文件导入批注并将其放入文档。

### readFields {#readFields-java.io.InputStream-com.aspose.pdf.IDocument-}
从 XFDF 文件导入字段值。
