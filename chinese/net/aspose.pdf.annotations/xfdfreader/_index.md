---
title: XfdfReader
second_title: Aspose.PDF for .NET API 参考
description: 执行 XFDF 格式读取的类
type: docs
weight: 1280
url: /zh/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

执行 XFDF 格式读取的类。

```csharp
public sealed class XfdfReader
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [XfdfReader](xfdfreader)() | 默认构造函数。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements)(XmlReader) | 解析 XFDF 文件并将信息作为哈希表返回。 |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations)(Stream, Document) | 从 XFDF 文件中导入注释并将它们放入文档中。 |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields)(Stream, Document) | 从 XFDF 文件中导入字段值。 |

### 例子

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### 也可以看看

* 命名空间 [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* 部件 [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->