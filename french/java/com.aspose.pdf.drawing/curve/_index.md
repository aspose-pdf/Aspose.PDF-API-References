---
title: "Curve"
linktitle: "Curve"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une courbe de Bézier."
type: docs
weight: 30
url: /fr/java/com.aspose.pdf.drawing/curve/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Curve, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Curve

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Curve extends Shape
```

Représente une courbe de Bézier.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Curve](#Curve--) | Pour usage interne uniquement |
| [Curve](#Curve-float:A-) | Initialise une nouvelle instance de la classe {@code Curve}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Vérifie si l'élément s'adapte aux dimensions du conteneur données (incluses). |
| [getPositionArray](#getPositionArray--) | Obtient un tableau de positions flottantes. |
| [setPositionArray](#setPositionArray-float:A-) | Définit un tableau de positions flottantes. |

### Curve {#Curve--}
```
public Curve()
```

Pour usage interne uniquement

### Curve {#Curve-float:A-}
```
public Curve(float[] positionArray)
```

Initialise une nouvelle instance de la classe {@code Curve}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| positionArray |  | Le tableau de positions des points de contrôle de la courbe. Il devrait y avoir quatre points de contrôle, donc la longueur du tableau devrait être huit. |

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

### getPositionArray {#getPositionArray--}
```
public float[] getPositionArray()
```

Obtient un tableau de positions flottantes.

**Returns:**
float[] tableau

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Définit un tableau de positions flottantes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | float[] tableau |
