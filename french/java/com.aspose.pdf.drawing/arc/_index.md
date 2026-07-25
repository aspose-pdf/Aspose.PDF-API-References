---
title: "Arc"
linktitle: "Arc"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un arc."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.drawing/arc/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Arc, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Arc

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Arc extends Shape
```

Représente un arc.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Arc](#Arc--) | Pour usage interne uniquement |
| [Arc](#Arc-double-double-double-double-double-) | Initialise une nouvelle instance de la classe {@code Arc}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Vérifie si l'élément s'adapte aux dimensions du conteneur données (incluses). |
| [getAlpha](#getAlpha--) | Obtient la valeur float qui indique le degré d'angle de départ de l'arc. |
| [getBeta](#getBeta--) | Obtient la valeur float qui indique le degré d'angle de fin de l'arc. |
| [getPosX](#getPosX--) | Obtient la valeur float qui indique la coordonnée x du centre de l'arc. |
| [getPosY](#getPosY--) | Obtient la valeur float qui indique la coordonnée y du centre de l'arc. |
| [getRadius](#getRadius--) | Obtient la valeur float qui indique le rayon de l'arc. |
| [setAlpha](#setAlpha-double-) | Définit la valeur float qui indique le degré d'angle de départ de l'arc. |
| [setBeta](#setBeta-double-) | Définit la valeur float qui indique le degré d'angle de fin de l'arc. |
| [setPosX](#setPosX-double-) | Définit la valeur float qui indique la coordonnée x du centre de l'arc. |
| [setPosY](#setPosY-double-) | Définit la valeur float qui indique la coordonnée y du centre de l'arc. |
| [setRadius](#setRadius-double-) | Définit la valeur float qui indique le rayon de l'arc. |

### Arc {#Arc--}
```
public Arc()
```

Pour usage interne uniquement

### Arc {#Arc-double-double-double-double-double-}
```
public Arc(double posX, double posY, double radius, double alpha, double beta)
```

Initialise une nouvelle instance de la classe {@code Arc}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| posX |  | La coordonnée x du point central de l'arc. |
| posY |  | La coordonnée y du point central de l'arc. |
| radius |  | La valeur du rayon de l'arc. |
| alpha |  | La valeur de l'angle de départ de l'arc. |
| beta |  | La valeur de l'angle de fin de l'arc. |

### checkBounds {#checkBounds-double-double-}
```
public boolean checkBounds(double containerWidth, double containerHeight)
```

Vérifie si l'élément s'adapte aux dimensions du conteneur données (incluses).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| containerWidth |  |  |
| containerHeight |  |  |

**Returns:**
Vrai si s'adapte ; sinon, faux.

### getAlpha {#getAlpha--}
```
public double getAlpha()
```

Obtient la valeur float qui indique le degré d'angle de départ de l'arc.

**Returns:**
valeur alpha.

### getBeta {#getBeta--}
```
public double getBeta()
```

Obtient la valeur float qui indique le degré d'angle de fin de l'arc.

**Returns:**
valeur beta

### getPosX {#getPosX--}
```
public double getPosX()
```

Obtient la valeur float qui indique la coordonnée x du centre de l'arc.

**Returns:**
coordonnée x du centre de l'arc.

### getPosY {#getPosY--}
```
public double getPosY()
```

Obtient la valeur float qui indique la coordonnée y du centre de l'arc.

**Returns:**
coordonnée y du centre de l'arc.

### getRadius {#getRadius--}
```
public double getRadius()
```

Obtient la valeur float qui indique le rayon de l'arc.

**Returns:**
valeur qui indique le rayon de l'arc.

### setAlpha {#setAlpha-double-}
```
public void setAlpha(double value)
```

Définit la valeur float qui indique le degré d'angle de départ de l'arc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur alpha. |

### setBeta {#setBeta-double-}
```
public void setBeta(double value)
```

Définit la valeur float qui indique le degré d'angle de fin de l'arc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur beta |

### setPosX {#setPosX-double-}
```
public void setPosX(double value)
```

Définit la valeur float qui indique la coordonnée x du centre de l'arc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | coordonnée x du centre de l'arc. |

### setPosY {#setPosY-double-}
```
public void setPosY(double value)
```

Définit la valeur float qui indique la coordonnée y du centre de l'arc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | coordonnée y du centre de l'arc. |

### setRadius {#setRadius-double-}
```
public void setRadius(double value)
```

Définit la valeur float qui indique le rayon de l'arc.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | qui indique le rayon de l'arc. |
