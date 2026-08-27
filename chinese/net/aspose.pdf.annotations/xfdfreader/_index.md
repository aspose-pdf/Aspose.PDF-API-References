---
title: "类 XfdfReader"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Annotations.XfdfReader 类。该类执行 XFDF 格式的读取。"
type: docs
weight: 2840
url: /zh/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

执行读取 XFDF 格式的类。

```csharp
public sealed class XfdfReader
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [XfdfReader](xfdfreader/)() | 默认构造函数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | 解析 XFDF 文件并以哈希表形式返回信息。 |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | 从 XFDF 文件导入注释并将其放入文档中。 |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | 从 XFDF 文件导入字段值。 |

## 示例

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### 另请参见

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


