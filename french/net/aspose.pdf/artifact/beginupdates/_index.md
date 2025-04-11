---
title: Artifact.BeginUpdates
second_title: Aspose.PDF for .NET API Reference
description: Méthode Artifact. Commencer les mises à jour différées. Utilisez cette fonctionnalité si vous devez apporter plusieurs modifications au même artefact pour améliorer les performances. En général, les opérateurs d'artefact sont modifiés chaque fois qu'une propriété d'artefact est changée. Cela entraîne un changement du contenu de la page chaque fois que l'artefact est modifié. Pour éviter cet effet, placez toutes les mises à jour d'artefact entre les appels StartUpdates/SaveUpdates. Cela permet de changer le contenu de la page une seule fois.
type: docs
weight: 230
url: /fr/net/aspose.pdf/artifact/beginupdates/
---
## Méthode Artifact.BeginUpdates

Commencer les mises à jour différées. Utilisez cette fonctionnalité si vous devez apporter plusieurs modifications au même artefact pour améliorer les performances. En général, les opérateurs d'artefact sont modifiés chaque fois qu'une propriété d'artefact est changée. Cela entraîne un changement du contenu de la page chaque fois que l'artefact est modifié. Pour éviter cet effet, placez toutes les mises à jour d'artefact entre les appels StartUpdates/SaveUpdates. Cela permet de changer le contenu de la page une seule fois.

```csharp
public void BeginUpdates()
```

## Exemples

```csharp
Artifact art = doc.Pages[1].Artifacts[1];
art.BeginUpdates();
art.Opacity = 0.3f;
art.Position = new Point(10,10);
art.Rotation = 30;
art.SaveUpdates();
```

### Voir aussi

* classe [Artifact](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)