---
title: Class Id
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Id. Représente la structure de l'identifiant de fichier
type: docs
weight: 5850
url: /fr/net/aspose.pdf/id/
---
## Classe Id

Représente la structure de l'identifiant de fichier.

```csharp
public class Id
```

## Propriétés

| Nom | Description |
| --- | --- |
| [Modifié](../../aspose.pdf/id/modified/) { get; } | Identifiant changeant basé sur le contenu du document au moment de sa dernière mise à jour. |
| [Original](../../aspose.pdf/id/original/) { get; } | Identifiant permanent basé sur le contenu du document au moment de sa création initiale. |

## Exemples

```csharp
Document doc = new Document("example.pdf");
string original = doc.Id.Original;
string modified = doc.Id.Modified;
```

### Voir aussi

* espace de noms [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)