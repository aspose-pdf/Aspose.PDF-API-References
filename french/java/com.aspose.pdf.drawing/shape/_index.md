---
title: "Shape"
linktitle: "Shape"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la forme - l'objet graphique de base."
type: docs
weight: 130
url: /fr/java/com.aspose.pdf.drawing/shape/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.drawing.Shape

**All Implemented Interfaces:**
IBoundsCheckableItem

```
public abstract class Shape extends Object implements IBoundsCheckableItem
```

Représente la forme - l'objet graphique de base.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Shape](#Shape--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [checkBounds](#checkBounds-double-double-) | Vérifie si l'élément s'adapte aux dimensions du conteneur données (incluses). |
| [getGraphInfo](#getGraphInfo--) | Obtient l'objet qui indique les informations du graphique, telles que la couleur, l'épaisseur de ligne, etc. |
| [getText](#getText--) | Obtient ou définit un texte pour shape |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Définit l'objet qui indique les informations du graphique, telles que la couleur, l'épaisseur de ligne, etc. |
| [setText](#setText-com.aspose.pdf.TextFragment-) | Obtient ou définit un texte pour shape |

### Shape {#Shape--}
```
public Shape()
```



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

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Obtient l'objet qui indique les informations du graphique, telles que la couleur, l'épaisseur de ligne, etc.

**Returns:**
objet qui indique les informations du graphique.

### getText {#getText--}
```
public TextFragment getText()
```

Obtient ou définit un texte pour shape

**Returns:**
Objet TextFragment

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Définit l'objet qui indique les informations du graphique, telles que la couleur, l'épaisseur de ligne, etc.

### setText {#setText-com.aspose.pdf.TextFragment-}
Obtient ou définit un texte pour shape
