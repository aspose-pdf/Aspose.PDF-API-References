---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FdfReader class. Class which performes reading of FDF format
type: docs
weight: 1790
url: /net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

Class which performes reading of FDF format.

```csharp
public sealed class FdfReader
```

## Methods

| Name | Description |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Import annotations from FDF file and put them into document. |

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


