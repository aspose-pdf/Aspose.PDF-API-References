---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.XfdfReader 类。执行 XFDF 格式的读取
type: docs
weight: 2740
url: /zh/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

执行 XFDF 格式的读取。

```csharp
public sealed class XfdfReader
```

## Constructors

| Name | Description |
| --- | --- |
| [XfdfReader](xfdfreader/)() | 默认构造函数。 |

## Methods

| Name | Description |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | 解析 XFDF 文件并返回信息作为哈希表。 |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | 从 XFDF 文件导入注释并将其放入文档中。 |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | 从 XFDF 文件导入字段值。 |

## Examples

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### See Also

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)