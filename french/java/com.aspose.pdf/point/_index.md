---
title: "Point"
linktitle: "Point"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un point avec des coordonnées fractionnaires."
type: docs
weight: 3870
url: /fr/java/com.aspose.pdf/point/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Point

```
public final class Point extends Object
```

Représente un point avec des coordonnées fractionnaires.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Point](#Point-double-double-) | Initialise une nouvelle instance de {@code Point}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [distance](#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-) | Calcule la distance entre deux points. |
| [getTrivial](#getTrivial--) | Obtient le point avec des coordonnées zéro. |
| [getX](#getX--) | Obtient la valeur de la coordonnée X. |
| [getY](#getY--) | Obtient la valeur de la coordonnée Y. |
| [setX](#setX-double-) | Définit la valeur de la coordonnée X. |
| [setY](#setY-double-) | Définit la valeur de la coordonnée Y. |
| [toPoint](#toPoint--) | Convertit le point en objet java.awt.geom.Point2D.Float. |
| [toString](#toString--) | Renvoie la représentation sous forme de chaîne du point actuel. |

### Point {#Point-double-double-}
```
public Point(double x, double y)
```

Initialise une nouvelle instance de {@code Point}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| x |  | Valeur de la coordonnée x. |
| y |  | Valeur de la coordonnée y. |

### distance {#distance-com.aspose.pdf.Point-com.aspose.pdf.Point-}
Calcule la distance entre deux points.

### getTrivial {#getTrivial--}
```
public static Point getTrivial()
```

Obtient le point avec des coordonnées zéro.

**Returns:**
Objet Point

### getX {#getX--}
```
public double getX()
```

Obtient la valeur de la coordonnée X.

**Returns:**
valeur double

### getY {#getY--}
```
public double getY()
```

Obtient la valeur de la coordonnée Y.

**Returns:**
valeur double

### setX {#setX-double-}
```
public void setX(double value)
```

Définit la valeur de la coordonnée X.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setY {#setY-double-}
```
public void setY(double value)
```

Définit la valeur de la coordonnée Y.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### toPoint {#toPoint--}
```
public Point2D.Float toPoint()
```

Convertit le point en objet java.awt.geom.Point2D.Float.

**Returns:**
Structure Float.

### toString {#toString--}
```
public String toString()
```

Renvoie la représentation sous forme de chaîne du point actuel.

**Returns:**
Chaîne, représentant le point actuel.
