---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.XfdfReader class. Class which peroformes reading of XFDF format
type: docs
weight: 2740
url: /net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

Class which peroformes reading of XFDF format.

```csharp
public sealed class XfdfReader
```

## Constructors

| Name | Description |
| --- | --- |
| [XfdfReader](xfdfreader/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Parses XFDF file and returns information as hashtable. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Import annotations from XFDF file and put them into document. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Import field values from XFDF file. |

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


