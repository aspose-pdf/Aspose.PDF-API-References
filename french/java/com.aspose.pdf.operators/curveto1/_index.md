---
title: "CurveTo1"
linktitle: "CurveTo1"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur v (ajouter une courbe au chemin, point initial répliqué)."
type: docs
weight: 160
url: /fr/java/com.aspose.pdf.operators/curveto1/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo1, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo1

```
public class CurveTo1 extends Operator
```

Classe représentant l'opérateur v (ajouter une courbe au chemin, point initial répliqué).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CurveTo1](#CurveTo1-double-double-double-double-) | Initialise l'opérateur de courbe. |
| [CurveTo1](#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte le sélecteur d'opérateur. |
| [getPoints](#getPoints--) | Points de la courbe. |

### CurveTo1 {#CurveTo1-double-double-double-double-}
```
public CurveTo1(double x2, double y2, double x3, double y3)
```

Initialise l'opérateur de courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x2 |  | Abscisse du deuxième point. |
| y2 |  | Ordonnée du deuxième point. |
| x3 |  | Abscisse du troisième point. |
| y3 |  | Ordonnée du troisième point. |

### CurveTo1 {#CurveTo1-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve1-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte le sélecteur d'opérateur.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Points de la courbe.

**Returns:**
tableau d'instances de Point
