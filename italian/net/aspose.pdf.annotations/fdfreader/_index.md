---
title: "Classe FdfReader"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Annotations.FdfReader classe. Classe che esegue la lettura del formato FDF"
type: docs
weight: 1790
url: /it/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

Classe che esegue la lettura del formato FDF.

```csharp
public sealed class FdfReader
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Importa le annotazioni dal file FDF e inseriscile nel documento. |

## Esempi

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### Vedi anche

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


