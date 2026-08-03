---
title: "Klass XfdfReader"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Annotations.XfdfReader-klass. Klass som utför läsning av XFDF-format"
type: docs
weight: 2840
url: /sv/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

Klass som utför läsning av XFDF‑format.

```csharp
public sealed class XfdfReader
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [XfdfReader](xfdfreader/)() | Standardkonstruktorn. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Analyserar XFDF-fil och returnerar information som hashtabell. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Importera annotationer från XFDF-fil och placera dem i dokumentet. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Importera fältvärden från XFDF-fil. |

## Exempel

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### Se även

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


