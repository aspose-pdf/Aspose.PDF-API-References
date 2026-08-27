---
title: "Row"
linktitle: "Row"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une ligne du tableau."
type: docs
weight: 4330
url: /fr/java/com.aspose.pdf/row/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Row

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Row extends Object implements com.aspose.ms.System.ICloneable
```

Représente une ligne du tableau.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Row](#Row--) | Initialise une nouvelle instance de la classe Row. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone](#deepClone--) | Cloner la ligne. |
| [getBackgroundColor](#getBackgroundColor--) | Obtient la couleur d'arrière-plan. |
| [getBorder](#getBorder--) | Obtient la bordure. |
| [getCells](#getCells--) | Obtient le getCells() de la ligne. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Obtient la bordure de cellule par défaut; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Obtient la marge par défaut pour le getCells() de la ligne. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtient ou définit l'état de texte par défaut pour le getCells() de la ligne Obtient l'état de texte par défaut pour le getCells() de la ligne |
| [getFixedRowHeight](#getFixedRowHeight--) | Obtient la hauteur fixe de la ligne - la ligne peut avoir une hauteur fixe; |
| [getMinRowHeight](#getMinRowHeight--) | Obtient la hauteur de la ligne; |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtient ou définit l'alignement vertical. |
| [isInNewPage](#isInNewPage--) | Obtient si la ligne fixe se trouve sur une nouvelle page - la page avec cette propriété doit être imprimée sur la page suivante Valeur par défaut false; |
| [isRowBroken](#isRowBroken--) | Obtient si la ligne peut être interrompue entre deux pages |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Définit la couleur d'arrière-plan. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Définit la bordure. |
| [setCells](#setCells-com.aspose.pdf.Cells-) | Définit le getCells() de la ligne. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Définit la bordure de cellule par défaut; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Définit la marge par défaut pour le getCells() de la ligne |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Définit l'état de texte par défaut pour le getCells() de la ligne |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Définit la hauteur fixe de la ligne - la ligne peut avoir une hauteur fixe; |
| [setInNewPage](#setInNewPage-boolean-) | Définit si la ligne peut être interrompue entre deux pages |
| [setMinRowHeight](#setMinRowHeight-double-) | Définit la hauteur de la ligne; |
| [setRowBroken](#setRowBroken-boolean-) | Définit si la ligne peut être interrompue entre deux pages |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Obtient ou définit l'alignement vertical. |

### Row {#Row--}
```
public Row()
```

Initialise une nouvelle instance de la classe Row.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Cloner la ligne.

**Returns:**
L'objet cloné

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Obtient la couleur d'arrière-plan.

**Returns:**
Valeur de couleur

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Obtient la bordure.

**Returns:**
Valeur BorderInfo

### getCells {#getCells--}
```
public Cells getCells()
```

Obtient le getCells() de la ligne.

**Returns:**
Valeur getCells()

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public BorderInfo getDefaultCellBorder()
```

Obtient la bordure de cellule par défaut;

**Returns:**
Valeur BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public MarginInfo getDefaultCellPadding()
```

Obtient la marge par défaut pour le getCells() de la ligne.

**Returns:**
Valeur MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Obtient ou définit l'état de texte par défaut pour le getCells() de la ligne Obtient l'état de texte par défaut pour le getCells() de la ligne

**Returns:**
Valeur TextState

### getFixedRowHeight {#getFixedRowHeight--}
```
public double getFixedRowHeight()
```

Obtient la hauteur fixe de la ligne - la ligne peut avoir une hauteur fixe;

**Returns:**
valeur double

### getMinRowHeight {#getMinRowHeight--}
```
public double getMinRowHeight()
```

Obtient la hauteur de la ligne;

**Returns:**
valeur double

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtient ou définit l'alignement vertical.

**Returns:**
Élément VerticalAlignment @see VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public boolean isInNewPage()
```

Obtient si la ligne fixe se trouve sur une nouvelle page - la page avec cette propriété doit être imprimée sur la page suivante Valeur par défaut false;

**Returns:**
valeur booléenne

### isRowBroken {#isRowBroken--}
```
public boolean isRowBroken()
```

Obtient si la ligne peut être interrompue entre deux pages

**Returns:**
valeur booléenne

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Définit la couleur d'arrière-plan.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Définit la bordure.

### setCells {#setCells-com.aspose.pdf.Cells-}
Définit le getCells() de la ligne.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Définit la bordure de cellule par défaut;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Définit la marge par défaut pour le getCells() de la ligne

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Définit l'état de texte par défaut pour le getCells() de la ligne

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public void setFixedRowHeight(double value)
```

Définit la hauteur fixe de la ligne - la ligne peut avoir une hauteur fixe;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setInNewPage {#setInNewPage-boolean-}
```
public void setInNewPage(boolean value)
```

Définit si la ligne peut être interrompue entre deux pages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMinRowHeight {#setMinRowHeight-double-}
```
public void setMinRowHeight(double value)
```

Définit la hauteur de la ligne;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setRowBroken {#setRowBroken-boolean-}
```
public void setRowBroken(boolean value)
```

Définit si la ligne peut être interrompue entre deux pages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Obtient ou définit l'alignement vertical.
