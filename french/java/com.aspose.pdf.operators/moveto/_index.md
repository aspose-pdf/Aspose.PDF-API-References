---
title: "MoveTo"
linktitle: "MoveTo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant {@code operators.m} (déplacer vers et commencer un nouveau sous‑chemin)."
type: docs
weight: 410
url: /fr/java/com.aspose.pdf.operators/moveto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.MoveTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.MoveTo

```
public class MoveTo extends Operator
```

Classe représentant {@code operators.m} (déplacer vers et commencer un nouveau sous‑chemin).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [MoveTo](#MoveTo-double-double-) | Initialise un nouvel opérateur {@code Operator.m} (déplacement). |
| [MoveTo](#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getX](#getX--) | Coordonnée X |
| [getY](#getY--) | Coordonnée Y |
| [setX](#setX-double-) | Coordonnée X |
| [setY](#setY-double-) | Coordonnée Y |
| [toString](#toString--) | Renvoie la représentation textuelle de l'opérateur. |

### MoveTo {#MoveTo-double-double-}
```
public MoveTo(double x, double y)
```

Initialise un nouvel opérateur {@code Operator.m} (déplacement).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x |  | La coordonnée x. |
| y |  | La coordonnée y. |

### MoveTo {#MoveTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.BeginNewSubpath-}


### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getX {#getX--}
```
public double getX()
```

Coordonnée X

**Returns:**
valeur double

### getY {#getY--}
```
public double getY()
```

Coordonnée Y

**Returns:**
valeur double

### setX {#setX-double-}
```
public void setX(double value)
```

Coordonnée X

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordonnée Y

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation textuelle de l'opérateur.

**Returns:**
Représentation texte de l'opérateur.
