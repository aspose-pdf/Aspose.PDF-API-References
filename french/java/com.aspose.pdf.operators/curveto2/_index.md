---
title: "CurveTo2"
linktitle: "CurveTo2"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur y (ajouter une courbe au chemin, point final répliqué)."
type: docs
weight: 170
url: /fr/java/com.aspose.pdf.operators/curveto2/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo2, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo2

```
public class CurveTo2 extends Operator
```

Classe représentant l'opérateur y (ajouter une courbe au chemin, point final répliqué).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CurveTo2](#CurveTo2-double-double-double-double-) | Initialise l'opérateur de courbe. |
| [CurveTo2](#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getPoints](#getPoints--) | Points de la courbe. |

### CurveTo2 {#CurveTo2-double-double-double-double-}
```
public CurveTo2(double x1, double y1, double x3, double y3)
```

Initialise l'opérateur de courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 |  | Abscisse du deuxième point. |
| y1 |  | Ordonnée du deuxième point. |
| x3 |  | Abscisse du troisième point. |
| y3 |  | Ordonnée du troisième point. |

### CurveTo2 {#CurveTo2-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve2-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getPoints {#getPoints--}
```
public Point [] getPoints()
```

Points de la courbe.

**Returns:**
tableau d'instances de Point
