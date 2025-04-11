---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: فئة Aspose.Pdf.Annotations.FdfReader. فئة تقوم بقراءة تنسيق FDF
type: docs
weight: 1700
url: /ar/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

فئة تقوم بقراءة تنسيق FDF.

```csharp
public sealed class FdfReader
```

## Methods

| Name | Description |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | استيراد التعليقات التوضيحية من ملف FDF ووضعها في المستند. |

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