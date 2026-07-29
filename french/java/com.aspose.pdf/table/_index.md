---
title: "Tableau"
linktitle: "Tableau"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une table qui peut être ajoutée à la page."
type: docs
weight: 4790
url: /fr/java/com.aspose.pdf/table/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Table, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Table

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Table extends BaseParagraph
```

Représente une table qui peut être ajoutée à la page.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Table](#Table--) | Constructeur par défaut |

## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone](#deepClone--) | / * / * Importe un tableau unidimensionnel de données dans la table. L'importation place une cellule par chaque élément du tableau et / * commence à la ligne et à la colonne définies dans les paramètres. Pendant l'importation, si l'on détecte que les lignes nécessaires / * sont encore absentes (c.-à-d. que la table cible est trop petite pour absorber toutes les données), les lignes nécessaires seront créées / * / * |
| [drawRoundedRectangle](#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-) | Ajoute des opérateurs pour le rectangle. |
| [getAlignment](#getAlignment--) | Obtient l'alignement du tableau. |
| [getBackgroundColor](#getBackgroundColor--) | Obtient la couleur d'arrière-plan du tableau |
| [getBorder](#getBorder--) | Obtient la bordure. |
| [getBreakText](#getBreakText--) | Obtient le texte de rupture pour le tableau |
| [getBroken](#getBroken--) | Obtient ou définit la rupture verticale du tableau; |
| [getColumnAdjustment](#getColumnAdjustment--) | Obtient l'ajustement des colonnes du tableau. |
| [getColumnWidth](#getColumnWidth-java.lang.String-) | Obtenir la largeur de la colonne |
| [getColumnWidths](#getColumnWidths--) | Obtient les largeurs des colonnes du tableau. |
| [getCornerStyle](#getCornerStyle--) | Obtient les styles des coins de la bordure |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Obtient la bordure de cellule par défaut; |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Obtient le remplissage par défaut de la cellule. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtient l'état de texte par défaut de la cellule. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Obtient la bordure de cellule par défaut; |
| [getHeight](#getHeight--) | Obtenir la hauteur. |
| [getHeight](#getHeight-com.aspose.pdf.Page-) | Obtenir la hauteur. |
| [getLeft](#getLeft--) | Obtient la coordonnée gauche du tableau. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Obtient ou définit le nombre maximal de colonnes pour le tableau |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Obtient le nombre de premières lignes répété sur plusieurs pages |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Obtient le style des lignes répétées |
| [getRows](#getRows--) | Obtient les lignes du tableau. |
| [getTop](#getTop--) | Obtient la coordonnée supérieure du tableau. |
| [getWidth](#getWidth--) | Obtenir la largeur. |
| [isBordersIncluded](#isBordersIncluded--) | Obtient la bordure incluse dans les largeurs de colonne. |
| [isBroken](#isBroken--) | Obtient le tableau cassé - sera tronqué pour la page suivante. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Définit l'alignement du tableau. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Définit la couleur d'arrière-plan du tableau |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Définit la bordure. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Définit la bordure incluse dans les largeurs de colonne. |
| [setBreakText](#setBreakText-com.aspose.pdf.TextFragment-) | Définit le texte de rupture pour le tableau |
| [setBroken](#setBroken-boolean-) | Définit le tableau cassé - sera tronqué pour la page suivante. |
| [setBroken](#setBroken-int-) | Obtient ou définit la rupture verticale du tableau; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Définit l'ajustement des colonnes du tableau. |
| [setColumnTextState](#setColumnTextState-int-com.aspose.pdf.TextState-) | Définit la hauteur. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Obtient les largeurs des colonnes du tableau. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Obtient ou définit les styles des coins de la bordure |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Obtient la bordure de cellule par défaut; |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Définit le remplissage par défaut de la cellule. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Définit l'état du texte par défaut de la cellule. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Obtient la bordure de cellule par défaut; |
| [setLeft](#setLeft-float-) | Définit la coordonnée gauche du tableau. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Obtient ou définit le nombre maximal de colonnes pour le tableau |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Obtient le nombre de premières lignes répété sur plusieurs pages |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Obtient le style des lignes répétées |
| [setTop](#setTop-float-) | Définit la coordonnée supérieure du tableau. |

### Table {#Table--}
```
public Table()
```

Constructeur par défaut

### deepClone {#deepClone--}
```
public Object deepClone()
```

/ * / * Importe un tableau unidimensionnel de données dans la table. L'importation place une cellule par chaque élément du tableau et / * commence à la ligne et à la colonne définies dans les paramètres. Pendant l'importation, si l'on détecte que les lignes nécessaires / * sont encore absentes (c.-à-d. que la table cible est trop petite pour absorber toutes les données), les lignes nécessaires seront créées / * / *

**Returns:**
L'objet cloné

### drawRoundedRectangle {#drawRoundedRectangle-com.aspose.pdf.GraphInfo-com.aspose.pdf.Point-com.aspose.pdf.Point-java.util.List-double-}
Ajoute des opérateurs pour le rectangle.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Obtient l'alignement du tableau.

**Returns:**
Valeur HorizontalAlignment @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtient la couleur d'arrière-plan du tableau

**Returns:**
Objet Color

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Obtient la bordure.

**Returns:**
Objet BorderInfo

### getBreakText {#getBreakText--}
```
public final TextFragment getBreakText()
```

Obtient le texte de rupture pour le tableau

**Returns:**
Objet TextFragment

### getBroken {#getBroken--}
```
public final int getBroken()
```

Obtient ou définit la rupture verticale du tableau;

**Returns:**
Valeur TableBroken @see TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Obtient l'ajustement des colonnes du tableau.

**Returns:**
Valeur ColumnAdjustment @see ColumnAdjustment

### getColumnWidth {#getColumnWidth-java.lang.String-}
Obtenir la largeur de la colonne

### getColumnWidths {#getColumnWidths--}
```
public final String getColumnWidths()
```

Obtient les largeurs des colonnes du tableau.

**Returns:**
valeur String

### getCornerStyle {#getCornerStyle--}
```
public final BorderCornerStyle getCornerStyle()
```

Obtient les styles des coins de la bordure

**Returns:**
Valeur BorderCornerStyle @see BorderCornerStyle

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Obtient la bordure de cellule par défaut;

**Returns:**
Objet BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Obtient le remplissage par défaut de la cellule.

**Returns:**
Objet MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Obtient l'état de texte par défaut de la cellule.

**Returns:**
Valeur TextState

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Obtient la bordure de cellule par défaut;

**Returns:**
Objet String

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtenir la hauteur.

**Returns:**
La hauteur du tableau

### getHeight {#getHeight-com.aspose.pdf.Page-}
Obtenir la hauteur.

**Returns:**
La hauteur du tableau

### getLeft {#getLeft--}
```
public final float getLeft()
```

Obtient la coordonnée gauche du tableau.

**Returns:**
Valeur flottante

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Obtient ou définit le nombre maximal de colonnes pour le tableau

**Returns:**
valeur int

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Obtient le nombre de premières lignes répété sur plusieurs pages

**Returns:**
valeur int

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Obtient le style des lignes répétées

**Returns:**
Objet TextState

### getRows {#getRows--}
```
public final Rows getRows()
```

Obtient les lignes du tableau.

**Returns:**
Objet Rows

### getTop {#getTop--}
```
public final float getTop()
```

Obtient la coordonnée supérieure du tableau.

**Returns:**
Valeur flottante

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtenir la largeur.

**Returns:**
La largeur du tableau

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Obtient la bordure incluse dans les largeurs de colonne.

**Returns:**
valeur booléenne

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Obtient le tableau cassé - sera tronqué pour la page suivante.

**Returns:**
valeur booléenne

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Définit l'alignement du tableau.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Définit la couleur d'arrière-plan du tableau

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Définit la bordure.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Définit la bordure incluse dans les largeurs de colonne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setBreakText {#setBreakText-com.aspose.pdf.TextFragment-}
Définit le texte de rupture pour le tableau

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Définit le tableau cassé - sera tronqué pour la page suivante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Obtient ou définit la rupture verticale du tableau;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur TableBroken @see TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Définit l'ajustement des colonnes du tableau.

### setColumnTextState {#setColumnTextState-int-com.aspose.pdf.TextState-}
Définit la hauteur.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Obtient les largeurs des colonnes du tableau.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Obtient ou définit les styles des coins de la bordure

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Obtient la bordure de cellule par défaut;

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Définit le remplissage par défaut de la cellule.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Définit l'état du texte par défaut de la cellule.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Obtient la bordure de cellule par défaut;

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Définit la coordonnée gauche du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Obtient ou définit le nombre maximal de colonnes pour le tableau

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Obtient le nombre de premières lignes répété sur plusieurs pages

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Obtient le style des lignes répétées

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Définit la coordonnée supérieure du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |
