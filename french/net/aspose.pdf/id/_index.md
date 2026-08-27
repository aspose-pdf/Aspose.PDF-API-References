---
title: "Classe Id"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Aspose.Pdf.Id class. Représente la structure d'identifiant de fichier"
type: docs
weight: 5980
url: /fr/net/aspose.pdf/id/
---
## Id class

Représente la structure d'identifiant de fichier.

```csharp
public class Id
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Modified](../../aspose.pdf/id/modified/) { get; } | Modification de l'identifiant en fonction du contenu du document au moment de sa dernière mise à jour. |
| [Original](../../aspose.pdf/id/original/) { get; } | Identifiant permanent basé sur le contenu du document au moment où il a été créé à l'origine. |

## Exemples

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### Voir aussi

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


