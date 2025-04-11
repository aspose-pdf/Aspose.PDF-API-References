---
title: Class FdfReader
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.FdfReader. Classe qui effectue la lecture du format FDF
type: docs
weight: 1700
url: /fr/net/aspose.pdf.annotations/fdfreader/
---
## Classe FdfReader

Classe qui effectue la lecture du format FDF.

```csharp
public sealed class FdfReader
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Importer des annotations à partir d'un fichier FDF et les placer dans le document. |

## Exemples

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### Voir aussi

* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)