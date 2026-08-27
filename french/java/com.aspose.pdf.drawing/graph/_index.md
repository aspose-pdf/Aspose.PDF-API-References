---
title: "Graph"
linktitle: "Graph"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente le graphique - paragraphe du générateur graphique."
type: docs
weight: 70
url: /fr/java/com.aspose.pdf.drawing/graph/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.drawing.Graph, com.aspose.pdf.BaseParagraph, com.aspose.pdf.drawing.Graph

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Graph extends BaseParagraph
```

Représente le graphique - paragraphe du générateur graphique.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Graph](#Graph--) | Pour usage interne uniquement |
| [Graph](#Graph-double-double-) | Initialise une nouvelle instance de la classe {@link Graph}. |
| [Graph](#Graph-float-float-) | Initialise une nouvelle instance de la classe {@code Graph}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clone le graphique. |
| [getBorder](#getBorder--) | Obtient la bordure. |
| [getGraphInfo](#getGraphInfo--) | Obtient un objet {@code GraphInfo} qui indique les informations du graphique, telles que la couleur, la largeur de ligne, etc. |
| [getHeight](#getHeight--) | Obtient la valeur flottante qui indique la hauteur du graphique. L'unité est le point. Dans XML, l'unité par défaut est le point, mais le cm et le pouce sont également pris en charge. Par exemple, GraphHeight="10cm" ou GraphHeight="5inch". |
| [getLeft](#getLeft--) | Obtient la coordonnée gauche du tableau. |
| [getShapes](#getShapes--) | Obtient une collection qui indique toutes les formes du graphique. |
| [getTitle](#getTitle--) | Obtient la valeur chaîne qui indique le titre du graphique. |
| [getTop](#getTop--) | Obtient la coordonnée supérieure du tableau. |
| [getWidth](#getWidth--) | Obtient la valeur flottante qui indique la largeur du graphique. L'unité est le point. Dans XML, l'unité par défaut est le point, mais le cm et le pouce sont également pris en charge. Par exemple, GraphWidth="10cm" ou GraphWidth="5inch". |
| [isChangePosition](#isChangePosition--) | Obtient le changement de position actuelle après le traitement du paragraphe.(valeur par défaut true) |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Définit la bordure. |
| [setChangePosition](#setChangePosition-boolean-) | Définit le changement de position actuelle après le traitement du paragraphe.(valeur par défaut true) |
| [setGraphInfo](#setGraphInfo-com.aspose.pdf.GraphInfo-) | Obtient ou définit un objet {@code GraphInfo} qui indique les informations du graphique, telles que la couleur, la largeur de ligne, etc. |
| [setHeight](#setHeight-double-) | Définit la valeur flottante qui indique la hauteur du graphique. L'unité est le point. Dans XML, l'unité par défaut est le point, mais le cm et le pouce sont également pris en charge. Par exemple, GraphHeight="10cm" ou GraphHeight="5inch". |
| [setLeft](#setLeft-double-) | Définit la coordonnée gauche du tableau. |
| [setShapes](#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-) | Définit une collection qui indique toutes les formes du graphique. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Définit la valeur chaîne qui indique le titre du graphique. |
| [setTop](#setTop-double-) | Définit la coordonnée supérieure du tableau. |
| [setWidth](#setWidth-double-) | Définit la valeur flottante qui indique la largeur du graphique. L'unité est le point. Dans XML, l'unité par défaut est le point, mais le cm et le pouce sont également pris en charge. Par exemple, GraphWidth="10cm" ou GraphWidth="5inch". |

### Graph {#Graph--}
```
public Graph()
```

Pour usage interne uniquement

### Graph {#Graph-double-double-}
```
public Graph(double width, double height)
```

Initialise une nouvelle instance de la classe {@link Graph}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | La largeur du graphique. |
| hauteur |  | La hauteur du graphique. |

### Graph {#Graph-float-float-}
```
@Deprecated public Graph(float width, float height)
```

Initialise une nouvelle instance de la classe {@code Graph}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | La largeur du graphique. |
| hauteur |  | La hauteur du graphique. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone le graphique.

**Returns:**
L'objet cloné

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Obtient la bordure.

**Returns:**
Élément BorderInfo

### getGraphInfo {#getGraphInfo--}
```
public GraphInfo getGraphInfo()
```

Obtient un objet {@code GraphInfo} qui indique les informations du graphique, telles que la couleur, la largeur de ligne, etc.

**Returns:**
Objet GraphInfo

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtient la valeur flottante qui indique la hauteur du graphique. L'unité est le point. Dans XML, l'unité par défaut est le point, mais le cm et le pouce sont également pris en charge. Par exemple, GraphHeight="10cm" ou GraphHeight="5inch".

**Returns:**
valeur qui indique la hauteur du graphique.

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtient la coordonnée gauche du tableau.

**Returns:**
coordonnée gauche du tableau.

### getShapes {#getShapes--}
```
public final BoundsCheckableList < Shape > getShapes()
```

Obtient une collection qui indique toutes les formes du graphique.

**Returns:**
BoundsCheckableList de Shapes.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Obtient la valeur chaîne qui indique le titre du graphique.

**Returns:**
titre du graphique.

### getTop {#getTop--}
```
public double getTop()
```

Obtient la coordonnée supérieure du tableau.

**Returns:**
coordonnée supérieure du tableau.

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtient la valeur flottante qui indique la largeur du graphique. L'unité est le point. Dans XML, l'unité par défaut est le point, mais le cm et le pouce sont également pris en charge. Par exemple, GraphWidth="10cm" ou GraphWidth="5inch".

**Returns:**
valeur flottante qui indique la largeur du graphique.

### isChangePosition {#isChangePosition--}
```
public boolean isChangePosition()
```

Obtient le changement de position actuelle après le traitement du paragraphe.(valeur par défaut true)

**Returns:**
valeur booléenne

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Définit la bordure.

### setChangePosition {#setChangePosition-boolean-}
```
public void setChangePosition(boolean value)
```

Définit le changement de position actuelle après le traitement du paragraphe.(valeur par défaut true)

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setGraphInfo {#setGraphInfo-com.aspose.pdf.GraphInfo-}
Obtient ou définit un objet {@code GraphInfo} qui indique les informations du graphique, telles que la couleur, la largeur de ligne, etc.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Définit la valeur flottante qui indique la hauteur du graphique. L'unité est le point. Dans XML, l'unité par défaut est le point, mais le cm et le pouce sont également pris en charge. Par exemple, GraphHeight="10cm" ou GraphHeight="5inch".

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | qui indique la hauteur du graphique. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Définit la coordonnée gauche du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | coordonnée gauche du tableau. |

### setShapes {#setShapes-com.aspose.pdf.boundscheckablelist.BoundsCheckableList-}
Définit une collection qui indique toutes les formes du graphique.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Définit la valeur chaîne qui indique le titre du graphique.

### setTop {#setTop-double-}
```
public void setTop(double value)
```

Définit la coordonnée supérieure du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | coordonnée supérieure du tableau. |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Définit la valeur flottante qui indique la largeur du graphique. L'unité est le point. Dans XML, l'unité par défaut est le point, mais le cm et le pouce sont également pris en charge. Par exemple, GraphWidth="10cm" ou GraphWidth="5inch".

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur flottante qui indique la largeur du graphique. |
