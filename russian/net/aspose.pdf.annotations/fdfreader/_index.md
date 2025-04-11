---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Annotations.FdfReader. Класс, который выполняет чтение формата FDF
type: docs
weight: 1700
url: /ru/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

Класс, который выполняет чтение формата FDF.

```csharp
public sealed class FdfReader
```

## Methods

| Name | Description |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Импортировать аннотации из FDF файла и поместить их в документ. |

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