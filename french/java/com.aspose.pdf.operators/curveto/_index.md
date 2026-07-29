---
title: "CurveTo"
linktitle: "CurveTo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur c (ajouter une courbe au chemin)."
type: docs
weight: 150
url: /fr/java/com.aspose.pdf.operators/curveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.CurveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.CurveTo

```
public class CurveTo extends Operator
```

Classe représentant l'opérateur c (ajouter une courbe au chemin).

## Champs

| Champ | Description |
| --- | --- |
| [X1](#X1) | Obtient ou définit la coordonnée X1. |
| [X2](#X2) | Obtient ou définit la coordonnée X2. |
| [X3](#X3) | Obtient ou définit la coordonnée X3. |
| [Y1](#Y1) | Obtient ou définit la coordonnée Y1. |
| [Y2](#Y2) | Obtient ou définit la coordonnée Y2. |
| [Y3](#Y3) | Obtient ou définit la coordonnée Y3. |

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [CurveTo](#CurveTo-double-double-double-double-double-double-) | Initialise l'opérateur de courbe. |
| [CurveTo](#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [toCommand](#toCommand--) | À usage interne uniquement ! |
| [toString](#toString--) | Renvoie la représentation texte de l'opérateur. |

### X1 {#X1}
```
public double X1
```

Obtient ou définit la coordonnée X1.

### X2 {#X2}
```
public double X2
```

Obtient ou définit la coordonnée X2.

### X3 {#X3}
```
public double X3
```

Obtient ou définit la coordonnée X3.

### Y1 {#Y1}
```
public double Y1
```

Obtient ou définit la coordonnée Y1.

### Y2 {#Y2}
```
public double Y2
```

Obtient ou définit la coordonnée Y2.

### Y3 {#Y3}
```
public double Y3
```

Obtient ou définit la coordonnée Y3.

### CurveTo {#CurveTo-double-double-double-double-double-double-}
```
public CurveTo(double x1, double y1, double x2, double y2, double x3, double y3)
```

Initialise l'opérateur de courbe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x1 |  | Abscisse du premier point. |
| y1 |  | Ordonnée du premier point. |
| x2 |  | Abscisse du deuxième point. |
| y2 |  | Ordonnée du deuxième point. |
| x3 |  | Abscisse du troisième point. |
| y3 |  | Ordonnée du troisième point. |

### CurveTo {#CurveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendCubicBezierCurve-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### toCommand {#toCommand--}
```
public com.aspose.pdf.engine.commondata.pagecontent.operators.commands.ICommand toCommand()
```

À usage interne uniquement !

**Returns:**
Valeur ICommand objet ICommand

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation texte de l'opérateur.

**Returns:**
Représentation textuelle de l'opérateur.
