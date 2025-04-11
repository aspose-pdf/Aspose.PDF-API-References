---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FdfReader 类。执行 FDF 格式读取的类
type: docs
weight: 1700
url: /zh/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

执行 FDF 格式读取的类。

```csharp
public sealed class FdfReader
```

## Methods

| Name | Description |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | 从 FDF 文件导入注释并将其放入文档中。 |

## Examples

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### See Also

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)