---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FdfReader klass. Klass som utför läsning av FDF-format
type: docs
weight: 1700
url: /sv/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader klass

Klass som utför läsning av FDF-format.

```csharp
public sealed class FdfReader
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Importera anteckningar från FDF-fil och placera dem i dokumentet. |

## Exempel

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### Se Även

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)