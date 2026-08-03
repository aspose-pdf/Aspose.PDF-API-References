---
title: "Klass FdfReader"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.Annotations.FdfReader-klass. Klass som utför läsning av FDF-format"
type: docs
weight: 1790
url: /sv/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

Klass som läser FDF-format.

```csharp
public sealed class FdfReader
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Importera annotationer från FDF-fil och placera dem i dokumentet. |

## Exempel

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### Se även

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


