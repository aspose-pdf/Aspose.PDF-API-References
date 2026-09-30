---
title: "XfdfReader Class"
linktitle: "XfdfReader"
articleTitle: "XfdfReader"
second_title: "Aspose.PDF for .NET API Reference"
description: "Aspose.Pdf.Annotations.XfdfReader class. Class which peroformes reading of XFDF format."
type: docs
weight: 1370
url: "/net/aspose.pdf.annotations/xfdfreader/"
keywords: "XfdfReader, Aspose.Pdf.Annotations, Aspose.PDF for .NET, Aspose.PDF API Reference"
product_version: "26.9.0"
---
## XfdfReader class

Class which peroformes reading of XFDF format.

```csharp
public sealed class XfdfReader
```

## Examples

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

## Constructors

| Name | Description |
| --- | --- |
| [XfdfReader](./xfdfreader/)() | The default constructor. |

## Methods

| Name | Description |
| --- | --- |
| static [GetElements](./getelements/)(XmlReader) | Parses XFDF file and returns information as hashtable. |
| static [ReadAnnotations](./readannotations/)(Stream, Document) | Import annotations from XFDF file and put them into document. |
| static [ReadFields](./readfields/)(Stream, Document) | Import field values from XFDF file. |

### See Also

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)

