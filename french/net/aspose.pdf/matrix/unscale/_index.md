---
title: Matrix.UnScale
second_title: Aspose.PDF for .NET API Reference
description: Méthode de matrice. Rétablit x1 et y1 et renvoie x et y avant la transformation de la matrice en utilisant la formule suivante x  D  x1  C  y1 / A  D  C  B y  A y1  B x1 / A D  C B
type: docs
weight: 220
url: /fr/net/aspose.pdf/matrix/unscale/
---
## Méthode Matrix.UnScale

Rétablit x1 et y1 et renvoie x et y avant la transformation de la matrice en utilisant la formule suivante : x = (D * x1 - C * y1) / (A * D - C * B); y = (A* y1 - B* x1) / (A* D - C* B);

```csharp
public void UnScale(double x1, double y1, out double x, out double y)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| x1 | Double | Coordonnée X d'entrée |
| y1 | Double | Coordonnée Y d'entrée |
| x | Double& | Coordonnée X de sortie |
| y | Double& | Coordonnée Y de sortie |

### Voir aussi

* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)