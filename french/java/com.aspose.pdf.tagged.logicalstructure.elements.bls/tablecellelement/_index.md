---
title: "TableCellElement"
linktitle: "TableCellElement"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une classe de base pour les éléments de cellule de tableau (TH et TD) dans la structure logique."
type: docs
weight: 150
url: /fr/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tablecellelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableCellElement

**All Implemented Interfaces:**
IAdjustPosition, ITextElement

```
public abstract class TableCellElement extends TableChildElement implements ITextElement , IAdjustPosition
```

Représente une classe de base pour les éléments de cellule de tableau (TH et TD) dans la structure logique.

## Méthodes

| Méthode | Description |
| --- | --- |
| [adjustPosition](#adjustPosition-com.aspose.pdf.tagged.PositionSettings-) | Ajuster la position. |
| [getAlignment](#getAlignment--) | Obtient ou définit l'alignement de la cellule. |
| [getBackgroundColor](#getBackgroundColor--) | Obtient ou définit la couleur d'arrière-plan de la cellule. |
| [getBorder](#getBorder--) | Obtient ou définit la bordure de la cellule. |
| [getCell](#getCell--) |  |
| [getColSpan](#getColSpan--) | Obtient ou définit l'étendue de colonne. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtient ou définit l'état de texte par défaut de la cellule. |
| [getMargin](#getMargin--) | Obtient ou définit le remplissage. |
| [getRowSpan](#getRowSpan--) | Obtient ou définit la portée de la ligne. |
| [getStructureTextState](#getStructureTextState--) | Obtient l'objet {@code /Aspose.Pdf.LogicalStructure.StructureTextState} pour l'élément actuel. Valeur : {@code /Aspose.Pdf.LogicalStructure.StructureTextState} objet pour l'élément actuel. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtient ou définit l'alignement vertical. |
| [isNoBorder](#isNoBorder--) | Obtient ou définit si la cellule a une bordure. |
| [isWordWrapped](#isWordWrapped--) | Obtient ou définit le renvoi à la ligne du texte de la cellule. |
| [preSave](#preSave--) |  |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Obtient ou définit l'alignement de la cellule. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtient ou définit la couleur d'arrière-plan de la cellule. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Obtient ou définit la bordure de la cellule. |
| [setColSpan](#setColSpan-int-) | Obtient ou définit l'étendue de colonne. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Obtient ou définit l'état de texte par défaut de la cellule. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Obtient ou définit le remplissage. |
| [setNoBorder](#setNoBorder-boolean-) | Obtient ou définit si la cellule a une bordure. |
| [setRowSpan](#setRowSpan-int-) | Obtient ou définit la portée de la ligne. |
| [setText](#setText-java.lang.String-) | Ajoute du contenu texte à l'élément texte actuel. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Obtient ou définit l'alignement vertical. |
| [setWordWrapped](#setWordWrapped-boolean-) | Obtient ou définit le renvoi à la ligne du texte de la cellule. |

### adjustPosition {#adjustPosition-com.aspose.pdf.tagged.PositionSettings-}
Ajuster la position.

### getAlignment {#getAlignment--}
```
public final HorizontalAlignment getAlignment()
```

Obtient ou définit l'alignement de la cellule.

**Returns:**
Élément HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtient ou définit la couleur d'arrière-plan de la cellule.

**Returns:**
Instance de Couleur

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Obtient ou définit la bordure de la cellule.

**Returns:**
Instance BorderInfo

### getCell {#getCell--}
```
public final Cell getCell()
```



### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Obtient ou définit l'étendue de colonne.

**Returns:**
valeur int

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Obtient ou définit l'état de texte par défaut de la cellule.

**Returns:**
instance TextState

### getMargin {#getMargin--}
```
public final MarginInfo getMargin()
```

Obtient ou définit le remplissage.

**Returns:**
Instance MarginInfo

### getRowSpan {#getRowSpan--}
```
public final int getRowSpan()
```

Obtient ou définit la portée de la ligne.

**Returns:**
valeur int

### getStructureTextState {#getStructureTextState--}
```
public final StructureTextState getStructureTextState()
```

Obtient l'objet {@code /Aspose.Pdf.LogicalStructure.StructureTextState} pour l'élément actuel. Valeur : {@code /Aspose.Pdf.LogicalStructure.StructureTextState} objet pour l'élément actuel.

**Returns:**
StructureTextState instance

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Obtient ou définit l'alignement vertical.

**Returns:**
Élément VerticalAlignment

### isNoBorder {#isNoBorder--}
```
public final boolean isNoBorder()
```

Obtient ou définit si la cellule a une bordure.

**Returns:**
valeur booléenne

### isWordWrapped {#isWordWrapped--}
```
public final boolean isWordWrapped()
```

Obtient ou définit le renvoi à la ligne du texte de la cellule.

**Returns:**
valeur booléenne

### preSave {#preSave--}
```
public void preSave()
```



### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Obtient ou définit l'alignement de la cellule.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtient ou définit la couleur d'arrière-plan de la cellule.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Obtient ou définit la bordure de la cellule.

### setColSpan {#setColSpan-int-}
```
public final void setColSpan(int value)
```

Obtient ou définit l'étendue de colonne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Obtient ou définit l'état de texte par défaut de la cellule.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Obtient ou définit le remplissage.

### setNoBorder {#setNoBorder-boolean-}
```
public final void setNoBorder(boolean value)
```

Obtient ou définit si la cellule a une bordure.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setRowSpan {#setRowSpan-int-}
```
public final void setRowSpan(int value)
```

Obtient ou définit la portée de la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setText {#setText-java.lang.String-}
Ajoute du contenu texte à l'élément texte actuel.

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Obtient ou définit l'alignement vertical.

### setWordWrapped {#setWordWrapped-boolean-}
```
public final void setWordWrapped(boolean value)
```

Obtient ou définit le renvoi à la ligne du texte de la cellule.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
