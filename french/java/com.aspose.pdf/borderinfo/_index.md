---
title: "BorderInfo"
linktitle: "BorderInfo"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe représente la bordure pour les éléments graphiques."
type: docs
weight: 370
url: /fr/java/com.aspose.pdf/borderinfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BorderInfo

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class BorderInfo extends Object implements com.aspose.ms.System.ICloneable
```

Cette classe représente la bordure pour les éléments graphiques.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BorderInfo](#BorderInfo--) | Initialise une nouvelle instance de la classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-) | Initialise une nouvelle instance de la classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.Color-) | Initialise une nouvelle instance de la classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-) | Initialise une nouvelle instance de la classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-float-com.aspose.pdf.Color-) | Initialise une nouvelle instance de la classe {@code BorderInfo}. |
| [BorderInfo](#BorderInfo-int-com.aspose.pdf.GraphInfo-) | Initialise une nouvelle instance de la classe {@code BorderInfo}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clone un nouvel objet BorderInfo. |
| [getBottom](#getBottom--) | Obtient l'objet qui indique le bas de la bordure. |
| [getLeft](#getLeft--) | Obtient l'objet {@code GraphInfo} qui indique la gauche de la bordure. |
| [getRight](#getRight--) | Obtient l'objet {@code GraphInfo} qui indique la droite de la bordure. |
| [getRoundedBorderRadius](#getRoundedBorderRadius--) | Obtient le rayon arrondi de la bordure. |
| [getTop](#getTop--) | Obtient l'objet {@code GraphInfo} qui indique le haut de la bordure. |
| [setBottom](#setBottom-com.aspose.pdf.GraphInfo-) | Définit l'objet qui indique le bas de la bordure. |
| [setLeft](#setLeft-com.aspose.pdf.GraphInfo-) | Définit l'objet {@code GraphInfo} qui indique la gauche de la bordure. |
| [setRight](#setRight-com.aspose.pdf.GraphInfo-) | Définit l'objet {@code GraphInfo} qui indique la droite de la bordure. |
| [setRoundedBorderRadius](#setRoundedBorderRadius-double-) | Définit le rayon arrondi de la bordure. |
| [setTop](#setTop-com.aspose.pdf.GraphInfo-) | Définit l'objet {@code GraphInfo} qui indique le haut de la bordure. |

### BorderInfo {#BorderInfo--}
```
public BorderInfo()
```

Initialise une nouvelle instance de la classe {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-}
```
public BorderInfo(int borderSide)
```

Initialise une nouvelle instance de la classe {@code BorderInfo}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| borderSide |  | Indique les informations des côtés de la bordure. Par exemple : (BorderSide.Left \ | BorderSide.Top). |

### BorderInfo {#BorderInfo-int-com.aspose.pdf.Color-}
Initialise une nouvelle instance de la classe {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-float-}
```
public BorderInfo(int borderSide, float borderWidth)
```

Initialise une nouvelle instance de la classe {@code BorderInfo}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| borderSide |  | Indique les informations des côtés de la bordure. Par exemple : (BorderSide.Left \ | BorderSide.Top). |
| borderWidth |  | La largeur de la bordure. |

### BorderInfo {#BorderInfo-int-float-com.aspose.pdf.Color-}
Initialise une nouvelle instance de la classe {@code BorderInfo}.

### BorderInfo {#BorderInfo-int-com.aspose.pdf.GraphInfo-}
Initialise une nouvelle instance de la classe {@code BorderInfo}.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone un nouvel objet BorderInfo.

**Returns:**
Le nouvel objet BorderInfo.

### getBottom {#getBottom--}
```
public GraphInfo getBottom()
```

Obtient l'objet qui indique le bas de la bordure.

**Returns:**
bas

### getLeft {#getLeft--}
```
public GraphInfo getLeft()
```

Obtient l'objet {@code GraphInfo} qui indique la gauche de la bordure.

**Returns:**
objet qui indique le côté gauche de la bordure.

### getRight {#getRight--}
```
public GraphInfo getRight()
```

Obtient l'objet {@code GraphInfo} qui indique la droite de la bordure.

**Returns:**
objet qui indique le côté droit de la bordure.

### getRoundedBorderRadius {#getRoundedBorderRadius--}
```
public double getRoundedBorderRadius()
```

Obtient le rayon arrondi de la bordure.

**Returns:**
valeur

### getTop {#getTop--}
```
public GraphInfo getTop()
```

Obtient l'objet {@code GraphInfo} qui indique le haut de la bordure.

**Returns:**
objet qui indique la bordure supérieure

### setBottom {#setBottom-com.aspose.pdf.GraphInfo-}
Définit l'objet qui indique le bas de la bordure.

### setLeft {#setLeft-com.aspose.pdf.GraphInfo-}
Définit l'objet {@code GraphInfo} qui indique la gauche de la bordure.

### setRight {#setRight-com.aspose.pdf.GraphInfo-}
Définit l'objet {@code GraphInfo} qui indique la droite de la bordure.

### setRoundedBorderRadius {#setRoundedBorderRadius-double-}
```
public void setRoundedBorderRadius(double value)
```

Définit le rayon arrondi de la bordure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setTop {#setTop-com.aspose.pdf.GraphInfo-}
Définit l'objet {@code GraphInfo} qui indique le haut de la bordure.
