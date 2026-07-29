---
title: "LineTo"
linktitle: "LineTo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur l (ajouter une ligne au tracé)."
type: docs
weight: 380
url: /fr/java/com.aspose.pdf.operators/lineto/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.LineTo, com.aspose.pdf.Operator, com.aspose.pdf.operators.LineTo

```
public class LineTo extends Operator
```

Classe représentant l'opérateur l (ajouter une ligne au tracé).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [LineTo](#LineTo-double-double-) | Initialise l'opérateur de ligne. |
| [LineTo](#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-) | Constructeur de la classe opérateur. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getX](#getX--) | Coordonnée X du point de ligne. |
| [getY](#getY--) | Coordonnée Y du point de ligne. |
| [setX](#setX-double-) | Coordonnée X du point de ligne. |
| [setY](#setY-double-) | Coordonnée Y du point de ligne. |
| [toString](#toString--) | Renvoie la représentation textuelle de l'opérateur. |

### LineTo {#LineTo-double-double-}
```
public LineTo(double x, double y)
```

Initialise l'opérateur de ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x |  | Coordonnée X. |
| y |  | Coordonnée Y. |

### LineTo {#LineTo-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendStraightLineSegment-}
Constructeur de la classe opérateur.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getX {#getX--}
```
public double getX()
```

Coordonnée X du point de ligne.

**Returns:**
valeur double

### getY {#getY--}
```
public double getY()
```

Coordonnée Y du point de ligne.

**Returns:**
valeur double

### setX {#setX-double-}
```
public void setX(double value)
```

Coordonnée X du point de ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordonnée Y du point de ligne.

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
