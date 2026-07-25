---
title: "TableTRElement"
linktitle: "TableTRElement"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente l'élément de structure TR dans la structure logique du tableau."
type: docs
weight: 240
url: /fr/java/com.aspose.pdf.tagged.logicalstructure.elements.bls/tabletrelement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.tagged.logicalstructure.elements.Element com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.Element, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.StructureElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableChildElement, com.aspose.pdf.tagged.logicalstructure.elements.bls.TableTRElement

```
public final class TableTRElement extends TableChildElement
```

Représente l'élément de structure TR dans la structure logique du tableau.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TableTRElement](#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-) | constructeur à usage interne uniquement |

## Méthodes

| Méthode | Description |
| --- | --- |
| [createTD](#createTD--) | Crée {@link TableTHElement} et l'ajoute à la table actuelle. |
| [createTH](#createTH--) | Crée {@link TableTHElement} et l'ajoute à la table actuelle. |
| [getBackgroundColor](#getBackgroundColor--) | Obtient ou définit la couleur d'arrière-plan de la ligne. |
| [getBorder](#getBorder--) | Obtient ou définit la bordure de la ligne. |
| [getDefaultCellBorder](#getDefaultCellBorder--) | Obtient la bordure par défaut des cellules. |
| [getDefaultCellPadding](#getDefaultCellPadding--) | Obtient ou définit la marge par défaut pour les cellules de ligne. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtient ou définit l'état de texte par défaut pour les cellules de ligne |
| [getFixedRowHeight](#getFixedRowHeight--) | Obtient la hauteur fixe de la ligne - la ligne peut avoir une hauteur fixe. |
| [getMinRowHeight](#getMinRowHeight--) | Obtient la hauteur de la ligne. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtient ou définit l'alignement vertical. |
| [isInNewPage](#isInNewPage--) | Obtient si la ligne fixe se trouve sur une nouvelle page - la page avec cette propriété doit être imprimée sur la page suivante. Valeur par défaut false. |
| [isRowBroken](#isRowBroken--) | Obtient si la ligne peut être interrompue entre deux pages. |
| [preSave](#preSave--) |  |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtient ou définit la couleur d'arrière-plan de la ligne. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Obtient ou définit la bordure de la ligne. |
| [setDefaultCellBorder](#setDefaultCellBorder-com.aspose.pdf.BorderInfo-) | Obtient la bordure par défaut des cellules. |
| [setDefaultCellPadding](#setDefaultCellPadding-com.aspose.pdf.MarginInfo-) | Obtient ou définit la marge par défaut pour les cellules de ligne. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Obtient ou définit l'état de texte par défaut pour les cellules de ligne |
| [setFixedRowHeight](#setFixedRowHeight-double-) | Obtient la hauteur fixe de la ligne - la ligne peut avoir une hauteur fixe. |
| [setInNewPage](#setInNewPage-boolean-) | Obtient si la ligne fixe se trouve sur une nouvelle page - la page avec cette propriété doit être imprimée sur la page suivante. Valeur par défaut false. |
| [setMinRowHeight](#setMinRowHeight-double-) | Obtient la hauteur de la ligne. |
| [setRowBroken](#setRowBroken-boolean-) | Obtient si la ligne peut être interrompue entre deux pages. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Obtient ou définit l'alignement vertical. |

### TableTRElement {#TableTRElement-com.aspose.pdf.tagged.TaggedContext-com.aspose.pdf.engine.data.IPdfPrimitive-}
constructeur à usage interne uniquement

### createTD {#createTD--}
```
public final TableTDElement createTD()
```

Crée {@link TableTHElement} et l'ajoute à la table actuelle.

**Returns:**
Élément de structure créé.

### createTH {#createTH--}
```
public final TableTHElement createTH()
```

Crée {@link TableTHElement} et l'ajoute à la table actuelle.

**Returns:**
Élément de structure créé.

### getBackgroundColor {#getBackgroundColor--}
```
public final Color getBackgroundColor()
```

Obtient ou définit la couleur d'arrière-plan de la ligne.

**Returns:**
Instance de Couleur

### getBorder {#getBorder--}
```
public final BorderInfo getBorder()
```

Obtient ou définit la bordure de la ligne.

**Returns:**
Instance BorderInfo

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

Obtient ou définit la marge par défaut pour les cellules de ligne.

**Returns:**
Instance MarginInfo

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public final TextState getDefaultCellTextState()
```

Obtient ou définit l'état de texte par défaut pour les cellules de ligne

**Returns:**
instance TextState

### getFixedRowHeight {#getFixedRowHeight--}
```
public final double getFixedRowHeight()
```

Obtient la hauteur fixe de la ligne - la ligne peut avoir une hauteur fixe.

**Returns:**
valeur double

### getMinRowHeight {#getMinRowHeight--}
```
public final double getMinRowHeight()
```

Obtient la hauteur de la ligne.

**Returns:**
valeur double

### getVerticalAlignment {#getVerticalAlignment--}
```
public final VerticalAlignment getVerticalAlignment()
```

Obtient ou définit l'alignement vertical.

**Returns:**
Élément VerticalAlignment

### isInNewPage {#isInNewPage--}
```
public final boolean isInNewPage()
```

Obtient si la ligne fixe se trouve sur une nouvelle page - la page avec cette propriété doit être imprimée sur la page suivante. Valeur par défaut false.

**Returns:**
valeur booléenne

### isRowBroken {#isRowBroken--}
```
public final boolean isRowBroken()
```

Obtient si la ligne peut être interrompue entre deux pages.

**Returns:**
valeur booléenne

### preSave {#preSave--}
```
public void preSave()
```



### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtient ou définit la couleur d'arrière-plan de la ligne.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Obtient ou définit la bordure de la ligne.

### setDefaultCellBorder {#setDefaultCellBorder-com.aspose.pdf.BorderInfo-}
Obtient la bordure par défaut des cellules.

### setDefaultCellPadding {#setDefaultCellPadding-com.aspose.pdf.MarginInfo-}
Obtient ou définit la marge par défaut pour les cellules de ligne.

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Obtient ou définit l'état de texte par défaut pour les cellules de ligne

### setFixedRowHeight {#setFixedRowHeight-double-}
```
public final void setFixedRowHeight(double value)
```

Obtient la hauteur fixe de la ligne - la ligne peut avoir une hauteur fixe.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setInNewPage {#setInNewPage-boolean-}
```
public final void setInNewPage(boolean value)
```

Obtient si la ligne fixe se trouve sur une nouvelle page - la page avec cette propriété doit être imprimée sur la page suivante. Valeur par défaut false.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setMinRowHeight {#setMinRowHeight-double-}
```
public final void setMinRowHeight(double value)
```

Obtient la hauteur de la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setRowBroken {#setRowBroken-boolean-}
```
public final void setRowBroken(boolean value)
```

Obtient si la ligne peut être interrompue entre deux pages.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Obtient ou définit l'alignement vertical.
