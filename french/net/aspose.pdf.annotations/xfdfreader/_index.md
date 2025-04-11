---
title: Class XfdfReader
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.XfdfReader. Classe qui effectue la lecture du format XFDF
type: docs
weight: 2740
url: /fr/net/aspose.pdf.annotations/xfdfreader/
---
## Classe XfdfReader

Classe qui effectue la lecture du format XFDF.

```csharp
public sealed class XfdfReader
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [XfdfReader](xfdfreader/)() | Le constructeur par défaut. |

## Méthodes

| Nom | Description |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements/)(XmlReader) | Analyse le fichier XFDF et renvoie les informations sous forme de table de hachage. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations/)(Stream, Document) | Importe les annotations du fichier XFDF et les place dans le document. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields/)(Stream, Document) | Importe les valeurs des champs du fichier XFDF. |

## Exemples

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### Voir aussi

* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)