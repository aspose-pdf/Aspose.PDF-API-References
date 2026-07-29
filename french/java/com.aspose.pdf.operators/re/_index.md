---
title: "Re"
linktitle: "Re"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'opérateur re (ajouter un rectangle au tracé)."
type: docs
weight: 460
url: /fr/java/com.aspose.pdf.operators/re/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Operator com.aspose.pdf.operators.Re, com.aspose.pdf.Operator, com.aspose.pdf.operators.Re

```
public class Re extends Operator
```

Classe représentant l'opérateur re (ajouter un rectangle au tracé).

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Re](#Re--) | Constructeur pour extraire les objectifs. |
| [Re](#Re-double-double-double-double-) | Constructeur pour le programme d'écriture. |
| [Re](#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-) | Constructeur pour extraire les objectifs. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [accept](#accept-com.aspose.pdf.IOperatorSelector-) | Accepte l'objet visiteur pour traiter l'opérateur. |
| [getHeight](#getHeight--) | Hauteur du rectangle. |
| [getWidth](#getWidth--) | Obtient la largeur du rectangle. |
| [getX](#getX--) | Coordonnée X du côté le plus à gauche du rectangle. |
| [getY](#getY--) | Coordonnée Y du côté inférieur du rectangle. |
| [setHeight](#setHeight-double-) | Hauteur du rectangle. |
| [setWidth](#setWidth-double-) | Définit la largeur du rectangle. |
| [setX](#setX-double-) | Coordonnée X du côté le plus à gauche du rectangle. |
| [setY](#setY-double-) | Coordonnée Y du côté inférieur du rectangle. |
| [toString](#toString--) | Renvoie la représentation textuelle de l'opérateur. |

### Re {#Re--}
```
public Re()
```

Constructeur pour extraire les objectifs.

### Re {#Re-double-double-double-double-}
```
public Re(double x, double y, double width, double height)
```

Constructeur pour le programme d'écriture.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x |  | La coordonnée x du coin inférieur gauche du rectangle. |
| y |  | La coordonnée y du coin inférieur gauche du rectangle. |
| largeur |  | La largeur du rectangle. |
| hauteur |  | La hauteur du rectangle. |

### Re {#Re-int-com.aspose.pdf.engine.commondata.pagecontent.operators.pathconstructionoperators.AppendRectangle-}
Constructeur pour extraire les objectifs.

### accept {#accept-com.aspose.pdf.IOperatorSelector-}
Accepte l'objet visiteur pour traiter l'opérateur.

### getHeight {#getHeight--}
```
public double getHeight()
```

Hauteur du rectangle.

**Returns:**
Hauteur du rectangle.

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtient la largeur du rectangle.

**Returns:**
largeur du rectangle.

### getX {#getX--}
```
public double getX()
```

Coordonnée X du côté le plus à gauche du rectangle.

**Returns:**
valeur double

### getY {#getY--}
```
public double getY()
```

Coordonnée Y du côté inférieur du rectangle.

**Returns:**
valeur double

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Hauteur du rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Hauteur du rectangle. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Définit la largeur du rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | largeur du rectangle. |

### setX {#setX-double-}
```
public void setX(double value)
```

Coordonnée X du côté le plus à gauche du rectangle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setY {#setY-double-}
```
public void setY(double value)
```

Coordonnée Y du côté inférieur du rectangle.

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
