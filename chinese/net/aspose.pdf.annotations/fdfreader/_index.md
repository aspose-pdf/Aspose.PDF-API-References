---
title: "类 FdfReader"
second_title: "Aspose.PDF for .NET API 参考"
description: "Aspose.Pdf.Annotations.FdfReader 类。执行 FDF 格式读取的类"
type: docs
weight: 1790
url: /zh/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

执行读取 FDF 格式的类。

```csharp
public sealed class FdfReader
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | 从 FDF 文件导入注释并将其放入文档。 |

## 示例

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### 另请参见

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


