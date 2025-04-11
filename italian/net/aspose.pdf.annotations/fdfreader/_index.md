---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.FdfReader. Classe che esegue la lettura del formato FDF
type: docs
weight: 1700
url: /it/net/aspose.pdf.annotations/fdfreader/
---
## Classe FdfReader

Classe che esegue la lettura del formato FDF.

```csharp
public sealed class FdfReader
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Importa annotazioni da un file FDF e le inserisce nel documento. |

## Esempi

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### Vedi Anche

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)