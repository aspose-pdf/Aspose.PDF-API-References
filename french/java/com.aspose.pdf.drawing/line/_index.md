---
title: "Line"
linktitle: "Line"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une ligne."
type: docs
weight: 90
url: /fr/java/com.aspose.pdf.drawing/line/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape com.aspose.pdf.drawing.Line, com.aspose.pdf.drawing.Shape, com.aspose.pdf.drawing.Line

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public final class Line extends Shape
```

Représente une ligne.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Line](#Line--) | Pour usage interne uniquement |
| [Line](#Line-float:A-) | Initialise une nouvelle instance de la classe {@code Line}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Vérifie si l'élément s'adapte aux dimensions du conteneur données (incluses). |
| [getPositionArray](#getPositionArray--) | Obtient l'objet qui indique le tableau de positions. Le tableau est composé des coordonnées de chaque point de contrôle de la ligne, directement. |
| [setPositionArray](#setPositionArray-float:A-) | Définit l'objet qui indique le tableau de positions. Le tableau est composé des coordonnées de chaque point de contrôle de la ligne, directement. |

### Line {#Line--}
```
public Line()
```

Pour usage interne uniquement

### Line {#Line-float:A-}
```
public Line(float[] positionArray)
```

Initialise une nouvelle instance de la classe {@code Line}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| positionArray |  | Le tableau de positions de la ligne. |

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

Obtient l'objet qui indique le tableau de positions. Le tableau est composé des coordonnées de chaque point de contrôle de la ligne, directement.

**Returns:**
qui indique le tableau de positions.

### setPositionArray {#setPositionArray-float:A-}
```
public void setPositionArray(float[] value)
```

Définit l'objet qui indique le tableau de positions. Le tableau est composé des coordonnées de chaque point de contrôle de la ligne, directement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | qui indique le tableau de positions. |
