---
title: XfdfReader
second_title: Référence de l'API Aspose.PDF pour .NET
description: Classe qui peroforme la lecture du format XFDF.
type: docs
weight: 1280
url: /fr/net/aspose.pdf.annotations/xfdfreader/
---
## XfdfReader class

Classe qui peroforme la lecture du format XFDF.

```csharp
public sealed class XfdfReader
```

## Constructeurs

| Nom | La description |
| --- | --- |
| [XfdfReader](xfdfreader)() | Default_Constructor |

## Méthodes

| Nom | La description |
| --- | --- |
| static [GetElements](../../aspose.pdf.annotations/xfdfreader/getelements)(XmlReader) | Analyse le fichier XFDF et renvoie les informations sous forme de table de hachage. |
| static [ReadAnnotations](../../aspose.pdf.annotations/xfdfreader/readannotations)(Stream, Document) | Importez des annotations à partir du fichier XFDF et placez-les dans le document. |
| static [ReadFields](../../aspose.pdf.annotations/xfdfreader/readfields)(Stream, Document) | Importer les valeurs de champ du fichier XFDF. |

### Exemples

```csharp
Document doc = new Document("example.pdf");
Stream xfdfStream = File.OpenRead("file.xfdf");
XfdfReader.ReadAnnotations(xfdfStream, doc);
xfdfStream.Close();
doc.Save("example_out.pdf");
```

### Voir également

* espace de noms [Aspose.Pdf.Annotations](../../aspose.pdf.annotations)
* Assemblée [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->