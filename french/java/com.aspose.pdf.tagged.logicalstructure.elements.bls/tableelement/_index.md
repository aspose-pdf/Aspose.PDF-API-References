---
title: "TableElement"
linktitle: "TableElement"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente l'élément de structure Tableau dans la structure logique."
type: docs
weight: 170
url: /fr/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tableelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.BLSElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableElement

**All Implemented Interfaces:**
IAdjustPosition

```
public final class TableElement extends BLSElement implements IAdjustPosition
```

Représente l'élément de structure Tableau dans la structure logique.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TableElement](#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | constructeur à usage interne uniquement |

## Méthodes

| Méthode | Description |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Ajuster la position. |
| [createTBody](#createTBody--) | Crée {@link TableTHeadElement} et l'ajoute à la table actuelle. |
| [createTFoot](#createTFoot--) | Crée {@link TableTFootElement} et l'ajoute à la table actuelle. |
| [createTHead](#createTHead--) | Crée {@link TableTHeadElement} et l'ajoute à la table actuelle. |
| [getAlignment](#getAlignment--) | Obtient ou définit l'alignement du tableau. |
| [getBackgroundColor](#getBackgroundColor--) | Obtient ou définit la couleur d'arrière-plan du tableau. |
| [getBorder](#getBorder--) | Obtient ou définit la bordure du tableau. |
| [getBroken](#getBroken--) | Obtient ou définit la rupture verticale du tableau ; |
| [getColumnAdjustment](#getColumnAdjustment--) | Obtient ou définit l'ajustement des colonnes du tableau. |
| [getColumnWidths](#getColumnWidths--) | Obtient les largeurs des colonnes du tableau. |
| [getCornerStyle](#getCornerStyle--) | Obtient ou définit les styles des coins de la bordure |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Obtient la bordure par défaut des cellules. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Obtient ou définit le remplissage par défaut des cellules. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtient ou définit l'état de texte par défaut de la cellule. |
| [getDefaultColumnWidth](#getDefaultColumnWidth--) | Obtient ou définit la largeur par défaut des colonnes. |
| [getLeft](#getLeft--) | Obtient ou définit la coordonnée gauche du tableau. |
| [getRepeatingColumnsCount](#getRepeatingColumnsCount--) | Obtient ou définit le nombre maximal de colonnes du tableau. |
| [getRepeatingRowsCount](#getRepeatingRowsCount--) | Obtient le nombre de premières lignes répétées sur plusieurs pages. |
| [getRepeatingRowsStyle](#getRepeatingRowsStyle--) | Obtient le style des lignes répétées. |
| [getTable](#getTable--) |  |
| [getTop](#getTop--) | Obtient ou définit la coordonnée supérieure du tableau. |
| [isBordersIncluded](#isBordersIncluded--) | Obtient ou définit la bordure incluse dans les largeurs des colonnes. |
| [isBroken](#isBroken--) | Obtient ou définit si le tableau est rompu - il sera tronqué pour la page suivante. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Obtient ou définit l'alignement du tableau. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtient ou définit la couleur d'arrière-plan du tableau. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Obtient ou définit la bordure du tableau. |
| [setBordersIncluded](#setBordersIncluded-boolean-) | Obtient ou définit la bordure incluse dans les largeurs des colonnes. |
| [setBroken](#setBroken-boolean-) | Obtient ou définit si le tableau est rompu - il sera tronqué pour la page suivante. |
| [setBroken](#setBroken-int-) | Obtient ou définit la rupture verticale du tableau ; |
| [setColumnAdjustment](#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-) | Obtient ou définit l'ajustement des colonnes du tableau. |
| [setColumnWidths](#setColumnWidths-java.lang.String-) | Obtient les largeurs des colonnes du tableau. |
| [setCornerStyle](#setCornerStyle-com.aspose.pdf.BorderCornerStyle-) | Obtient ou définit les styles des coins de la bordure |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Obtient la bordure par défaut des cellules. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Obtient ou définit le remplissage par défaut des cellules. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Obtient ou définit l'état de texte par défaut de la cellule. |
| [setDefaultColumnWidth](#setDefaultColumnWidth-java.lang.String-) | Obtient ou définit la largeur par défaut des colonnes. |
| [setLeft](#setLeft-float-) | Obtient ou définit la coordonnée gauche du tableau. |
| [setRepeatingColumnsCount](#setRepeatingColumnsCount-int-) | Obtient ou définit le nombre maximal de colonnes du tableau. |
| [setRepeatingRowsCount](#setRepeatingRowsCount-int-) | Obtient le nombre de premières lignes répétées sur plusieurs pages. |
| [setRepeatingRowsStyle](#setRepeatingRowsStyle-com.aspose.pdf.TextState-) | Obtient le style des lignes répétées. |
| [setTop](#setTop-float-) | Obtient ou définit la coordonnée supérieure du tableau. |

### TableElement {#TableElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
constructeur à usage interne uniquement

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Ajuster la position.

### createTBody {#createTBody--}
```
public final TableTBodyElement createTBody()
```

Crée {@link TableTHeadElement} et l'ajoute à la table actuelle.

**Returns:**
Élément de structure créé.

### createTFoot {#createTFoot--}
```
public final TableTFootElement createTFoot()
```

Crée {@link TableTFootElement} et l'ajoute à la table actuelle.

**Returns:**
Élément de structure créé.

### createTHead {#createTHead--}
```
public final TableTHeadElement createTHead()
```

Crée {@link TableTHeadElement} et l'ajoute à la table actuelle.

**Returns:**
Élément de structure créé.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Obtient ou définit l'alignement du tableau.

**Returns:**
Élément HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtient ou définit la couleur d'arrière-plan du tableau.

**Returns:**
Instance de Couleur

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Obtient ou définit la bordure du tableau.

**Returns:**
Instance BorderInfo

### getBroken {#getBroken--}
```
public final int getBroken()
```

Obtient ou définit la rupture verticale du tableau ;

**Returns:**
Élément TableBroken

### getColumnAdjustment {#getColumnAdjustment--}
```
public final ColumnAdjustment getColumnAdjustment()
```

Obtient ou définit l'ajustement des colonnes du tableau.

**Returns:**
ColumnAdjustment élément

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

Obtient ou définit les styles des coins de la bordure

**Returns:**
BorderCornerStyle élément

### getDefaultCellBorder {#getDefaultCellBorder--}
```
public final BorderInfo getDefaultCellBorder()
```

Obtient la bordure par défaut des cellules.

**Returns:**
Instance BorderInfo

### getDefaultCellPadding {#getDefaultCellPadding--}
```
public final MarginInfo getDefaultCellPadding()
```

Obtient ou définit le remplissage par défaut des cellules.

**Returns:**
Instance MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Obtient ou définit l'état de texte par défaut de la cellule.

**Returns:**
instance TextState

### getDefaultColumnWidth {#getDefaultColumnWidth--}
```
public final String getDefaultColumnWidth()
```

Obtient ou définit la largeur par défaut des colonnes.

**Returns:**
valeur String

### getLeft {#getLeft--}
```
public final float getLeft()
```

Obtient ou définit la coordonnée gauche du tableau.

**Returns:**
Valeur flottante

### getRepeatingColumnsCount {#getRepeatingColumnsCount--}
```
public final int getRepeatingColumnsCount()
```

Obtient ou définit le nombre maximal de colonnes du tableau.

**Returns:**
valeur int

### getRepeatingRowsCount {#getRepeatingRowsCount--}
```
public final int getRepeatingRowsCount()
```

Obtient le nombre de premières lignes répétées sur plusieurs pages.

**Returns:**
valeur int

### getRepeatingRowsStyle {#getRepeatingRowsStyle--}
```
public final TextState getRepeatingRowsStyle()
```

Obtient le style des lignes répétées.

**Returns:**
instance TextState

### getTable {#getTable--}
```
public final Table getTable()
```



### getTop {#getTop--}
```
public final float getTop()
```

Obtient ou définit la coordonnée supérieure du tableau.

**Returns:**
Valeur flottante

### isBordersIncluded {#isBordersIncluded--}
```
public final boolean isBordersIncluded()
```

Obtient ou définit la bordure incluse dans les largeurs des colonnes.

**Returns:**
valeur booléenne

### isBroken {#isBroken--}
```
public final boolean isBroken()
```

Obtient ou définit si le tableau est rompu - il sera tronqué pour la page suivante.

**Returns:**
valeur booléenne

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Obtient ou définit l'alignement du tableau.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtient ou définit la couleur d'arrière-plan du tableau.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Obtient ou définit la bordure du tableau.

### setBordersIncluded {#setBordersIncluded-boolean-}
```
public final void setBordersIncluded(boolean value)
```

Obtient ou définit la bordure incluse dans les largeurs des colonnes.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setBroken {#setBroken-boolean-}
```
public final void setBroken(boolean value)
```

Obtient ou définit si le tableau est rompu - il sera tronqué pour la page suivante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setBroken {#setBroken-int-}
```
public final void setBroken(int value)
```

Obtient ou définit la rupture verticale du tableau ;

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Élément TableBroken |

### setColumnAdjustment {#setColumnAdjustment-com.aspose.pdf.ColumnAdjustment-}
Obtient ou définit l'ajustement des colonnes du tableau.

### setColumnWidths {#setColumnWidths-java.lang.String-}
Obtient les largeurs des colonnes du tableau.

### setCornerStyle {#setCornerStyle-com.aspose.pdf.BorderCornerStyle-}
Obtient ou définit les styles des coins de la bordure

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Obtient la bordure par défaut des cellules.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Obtient ou définit le remplissage par défaut des cellules.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Obtient ou définit l'état de texte par défaut de la cellule.

### setDefaultColumnWidth {#setDefaultColumnWidth-java.lang.String-}
Obtient ou définit la largeur par défaut des colonnes.

### setLeft {#setLeft-float-}
```
public final void setLeft(float value)
```

Obtient ou définit la coordonnée gauche du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |

### setRepeatingColumnsCount {#setRepeatingColumnsCount-int-}
```
public final void setRepeatingColumnsCount(int value)
```

Obtient ou définit le nombre maximal de colonnes du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setRepeatingRowsCount {#setRepeatingRowsCount-int-}
```
public final void setRepeatingRowsCount(int value)
```

Obtient le nombre de premières lignes répétées sur plusieurs pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setRepeatingRowsStyle {#setRepeatingRowsStyle-com.aspose.pdf.TextState-}
Obtient le style des lignes répétées.

### setTop {#setTop-float-}
```
public final void setTop(float value)
```

Obtient ou définit la coordonnée supérieure du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Valeur flottante |
