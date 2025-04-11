---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Annotations.FdfReader-Klasse. Klasse, die das Lesen des FDF-Formats durchführt
type: docs
weight: 1700
url: /de/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader-Klasse

Klasse, die das Lesen des FDF-Formats durchführt.

```csharp
public sealed class FdfReader
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Importiert Anmerkungen aus der FDF-Datei und fügt sie in das Dokument ein. |

## Beispiele

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### Siehe auch

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)