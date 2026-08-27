---
title: "Cercle"
linktitle: "Cercle"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un cercle."
type: docs
weight: 20
url: /fr/java/com.aspose.pdf.drawing/circle/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Circle, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Circle

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Circle extends Shape
```

Représente un cercle.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Circle](#Circle--) | Pour usage interne uniquement |
| [Circle](#Circle-float-float-float-) | Initialise une nouvelle instance de la classe {@code Circle}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Vérifie si l'élément s'adapte aux dimensions du conteneur données (incluses). |
| [getPosX](#getPosX--) | Obtient la valeur float qui indique la coordonnée x du centre de l'arc. |
| [getPosY](#getPosY--) | Obtient la valeur float qui indique la coordonnée y du centre de l'arc. |
| [getRadius](#getRadius--) | Obtient la valeur float qui indique le rayon du cercle. |
| [setPosX](#setPosX-double-) | Définit la valeur float qui indique la coordonnée x du centre de l'arc. |
| [setPosY](#setPosY-double-) | Définit la valeur float qui indique la coordonnée y du centre de l'arc. |
| [setRadius](#setRadius-double-) | Définit la valeur float qui indique le rayon du cercle. |

### Circle {#Circle--}
```
public Circle()
```

Pour usage interne uniquement

### Circle {#Circle-float-float-float-}
```
public Circle(float posX, float posY, float radius)
```

Initialise une nouvelle instance de la classe {@code Circle}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| posX |  | La coordonnée x du centre du cercle. |
| posY |  | La coordonnée y du centre du cercle. |
| radius |  | Le rayon du cercle. |

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

Obtient la valeur float qui indique le rayon du cercle.

**Returns:**
valeur qui indique le rayon du cercle.

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

Définit la valeur float qui indique le rayon du cercle.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | qui indique le rayon du cercle. |
