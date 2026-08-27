---
title: "Classe FdfReader"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Annotations.FdfReader class. Classe qui effectue la lecture du format FDF"
type: docs
weight: 1790
url: /fr/net/aspose.pdf.annotations/fdfreader/
---
## FdfReader class

Classe qui effectue la lecture du format FDF.

```csharp
public sealed class FdfReader
```

## Méthodes

| Nom | Description |
| --- | --- |
| static [ReadAnnotations](../../aspose.pdf.annotations/fdfreader/readannotations/)(Stream, Document) | Importe les annotations du fichier FDF et les place dans le document. |

## Exemples

```csharp
Document doc = new Document("example.pdf");
Stream fdfStream = File.OpenRead("file.fdf");
FdfReader.ReadAnnotations(fdfStream, doc);
fdfStream.Close();
doc.Save("example_out.pdf");
```

### Voir aussi

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


