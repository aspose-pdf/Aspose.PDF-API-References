---
title: "Page.IsBlank"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Page. Obtient le drapeau indiquant si la page est vide ou non"
type: docs
weight: 490
url: /fr/net/aspose.pdf/page/isblank/
---
## Page.IsBlank method

Obtient le drapeau indiquant si la Page est vide ou non.

```csharp
public bool IsBlank(double fillThresholdFactor)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fillThresholdFactor | Double | La valeur du seuil de remplissage qui gère la sensibilité de la détection. Doit être dans la plage [0..1). |

### Valeur de retour

Vrai - si la page est vide ; sinon, faux.

## Remarques

Pour déterminer si une page est vide ou non, le rapport entre l'espace rempli et l'espace total de la page est calculé. Ce rapport est comparé au paramètre fillThresholdFactor et, s'il est inférieur, la page est considérée comme vide.

### Voir aussi

* class [Page](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


