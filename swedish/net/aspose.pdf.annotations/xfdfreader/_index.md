---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.XfdfReader klass. Klass som utför läsning av XFDF-format
type: docs
weight: 2740
url: /sv/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader klass

Klass som utför läsning av XFDF-format.

```csharp
public sealed class XfdfReader
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XfdfReader](xfdfreader/)() | Standardkonstruktören. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Parserar XFDF-fil och returnerar information som hashtable. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Importerar anteckningar från XFDF-fil och lägger dem i dokumentet. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Importerar fältvärden från XFDF-fil. |

## Exempel

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### Se Även

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)