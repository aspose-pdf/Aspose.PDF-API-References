---
title: "Artifact.BeginUpdates"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Artifact. Démarrer les mises à jour différées. Utilisez cette fonctionnalité si vous devez effectuer plusieurs modifications du même artifact afin d'améliorer les performances. Habituellement, les opérateurs d'artifact sont modifiés à tout moment lorsqu'une propriété d'artifact a été modifiée. Cela entraîne la modification du contenu de la page chaque fois que l'artifact est modifié. Pour éviter cet effet, placez toutes les mises à jour d'artifact entre les appels StartUpdates/SaveUpdates. Cela permet de modifier le contenu de la page une seule fois"
type: docs
weight: 230
url: /fr/net/aspose.pdf/artifact/beginupdates/
---
## Artifact.BeginUpdates method

Démarrer les mises à jour différées. Utilisez cette fonctionnalité si vous devez effectuer plusieurs modifications du même artefact afin d'améliorer les performances. Généralement, les opérateurs d'artefact sont modifiés chaque fois qu'une propriété d'artefact a été modifiée. Cela entraîne la modification du contenu de la page à chaque modification de l'artefact. Pour éviter cet effet, placez toutes les mises à jour d'artefact entre les appels StartUpdates/SaveUpdates. Cela permet de modifier le contenu de la page une seule fois.

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

* class [Artifact](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


