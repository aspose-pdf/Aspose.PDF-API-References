---
title: Matrix.Scale
second_title: Aspose.PDF for .NET API Reference
description: Méthode de la matrice. Échelle x et y avec la matrice en utilisant la formule suivante x1  Ax  Cy y1  Bx  Dy
type: docs
weight: 190
url: /fr/net/aspose.pdf/matrix/scale/
---
## Scale(double, double, out double, out double)

Échelle x et y avec la matrice en utilisant la formule suivante : x1 = A*x + C*y ; y1 = B*x + D*y ;

```csharp
public void Scale(double x, double y, out double x1, out double y1)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| x | Double | Coordonnée X d'entrée |
| y | Double | Coordonnée Y d'entrée |
| x1 | Double& | Coordonnée X de sortie |
| y1 | Double& | Coordonnée Y de sortie |

### Voir aussi

* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Scale(double, double, Matrix)

Applique une mise à l'échelle à la matrice donnée.

```csharp
public static Matrix Scale(double sx, double sy, Matrix source)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| sx | Double | Le facteur de mise à l'échelle pour l'axe X. |
| sy | Double | Le facteur de mise à l'échelle pour l'axe Y. |
| source | Matrix | La matrice à mettre à l'échelle. |

### Valeur de retour

Une nouvelle matrice qui est le résultat de la mise à l'échelle de la matrice source.

### Voir aussi

* classe [Matrix](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)