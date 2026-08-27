---
title: "Cell"
linktitle: "Cell"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une cellule de la ligne du tableau."
type: docs
weight: 510
url: /fr/java/com.aspose.pdf/cell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Cell

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Cell extends Object implements com.aspose.ms.System.ICloneable
```

Représente une cellule de la ligne du tableau.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Cell](#Cell--) | Initialise une nouvelle instance de la classe Cell. |
| [Cell](#Cell-com.aspose.pdf.Rectangle-) | Initialise une nouvelle instance de la classe Cell. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clone la cellule. |
| [getAlignment](#getAlignment--) | Obtient l'alignement. |
| [getBackgroundColor](#getBackgroundColor--) | Obtient la couleur d'arrière-plan. |
| [getBackgroundImage](#getBackgroundImage--) | Obtient ou définit l'image d'arrière-plan |
| [getBackgroundImageFile](#getBackgroundImageFile--) | Obtient le fichier d'image d'arrière-plan. |
| [getBorder](#getBorder--) | Obtient la bordure. |
| [getColSpan](#getColSpan--) | Obtient ou définit l'étendue de colonne. |
| [getDefaultCellTextState](#getDefaultCellTextState--) | Obtient l'état de texte par défaut de la cellule. |
| [getMargin](#getMargin--) | Obtient le remplissage. |
| [getParagraphs](#getParagraphs--) | Obtient le texte formaté de la cellule. |
| [getRowSpan](#getRowSpan--) | Obtient l'étendue de ligne. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtient l'alignement vertical. |
| [getWidth](#getWidth--) | Obtient la largeur de colonne. |
| [isNoBorder](#isNoBorder--) | Obtient si la cellule possède une bordure |
| [isOverrideByFragment](#isOverrideByFragment--) | Définit la propriété TextState de la cellule qui est remplacée par la propriété TextState de TextFragment. |
| [isWordWrapped](#isWordWrapped--) | Obtient le texte de la cellule avec retour à la ligne. |
| [setAlignment](#setAlignment-com.aspose.pdf.HorizontalAlignment-) | Définit l'alignement. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Obtient ou définit la couleur d'arrière-plan. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Obtient ou définit l'image d'arrière-plan |
| [setBackgroundImageFile](#setBackgroundImageFile-java.lang.String-) | Définit le fichier d'image d'arrière-plan. |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Définit la bordure. |
| [setColSpan](#setColSpan-int-) | Définit l'étendue de colonne. |
| [setDefaultCellTextState](#setDefaultCellTextState-com.aspose.pdf.TextState-) | Définit l'état du texte par défaut de la cellule. |
| [setMargin](#setMargin-com.aspose.pdf.MarginInfo-) | Définit le remplissage. |
| [setNoBorder](#setNoBorder-boolean-) | Définit si la cellule possède une bordure |
| [setOverrideByFragment](#setOverrideByFragment-boolean-) | Définit la propriété TextState de la cellule qui est remplacée par la propriété TextState de TextFragment. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Définit le texte formaté de la cellule. |
| [setRowSpan](#setRowSpan-int-) | Définit l'étendue de ligne. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Définit l'alignement vertical. |
| [setWidth](#setWidth-double-) | Définit la largeur de colonne. |
| [setWordWrapped](#setWordWrapped-boolean-) | Définit le texte de la cellule avec retour à la ligne. |

### Cell {#Cell--}
```
public Cell()
```

Initialise une nouvelle instance de la classe Cell.

### Cell {#Cell-com.aspose.pdf.Rectangle-}
Initialise une nouvelle instance de la classe Cell.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone la cellule.

**Returns:**
L'objet cloné

### getAlignment {#getAlignment--}
```
public HorizontalAlignment getAlignment()
```

Obtient l'alignement.

**Returns:**
Élément HorizontalAlignment @see HorizontalAlignment

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Obtient la couleur d'arrière-plan.

**Returns:**
Objet Color

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Obtient ou définit l'image d'arrière-plan

**Returns:**
Instance d'image

### getBackgroundImageFile {#getBackgroundImageFile--}
```
@Deprecated public String getBackgroundImageFile()
```

Obtient le fichier d'image d'arrière-plan.

**Returns:**
Valeur de chaîne @deprecated La propriété a été étendue veuillez utiliser BackgroundImage

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Obtient la bordure.

**Returns:**
Objet BorderInfo

### getColSpan {#getColSpan--}
```
public int getColSpan()
```

Obtient ou définit l'étendue de colonne.

**Returns:**
valeur int

### getDefaultCellTextState {#getDefaultCellTextState--}
```
public TextState getDefaultCellTextState()
```

Obtient l'état de texte par défaut de la cellule.

**Returns:**
Objet TextState

### getMargin {#getMargin--}
```
public MarginInfo getMargin()
```

Obtient le remplissage.

**Returns:**
Objet MarginInfo

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Obtient le texte formaté de la cellule.

**Returns:**
Objet Paragraphs

### getRowSpan {#getRowSpan--}
```
public int getRowSpan()
```

Obtient l'étendue de ligne.

**Returns:**
valeur int

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtient l'alignement vertical.

**Returns:**
Élément VerticalAlignment @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtient la largeur de colonne.

**Returns:**
valeur double

### isNoBorder {#isNoBorder--}
```
public boolean isNoBorder()
```

Obtient si la cellule possède une bordure

**Returns:**
valeur booléenne

### isOverrideByFragment {#isOverrideByFragment--}
```
public final boolean isOverrideByFragment()
```

Définit la propriété TextState de la cellule qui est remplacée par la propriété TextState de TextFragment.

**Returns:**
valeur booléenne

### isWordWrapped {#isWordWrapped--}
```
public boolean isWordWrapped()
```

Obtient le texte de la cellule avec retour à la ligne.

**Returns:**
valeur booléenne

### setAlignment {#setAlignment-com.aspose.pdf.HorizontalAlignment-}
Définit l'alignement.

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Obtient ou définit la couleur d'arrière-plan.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Obtient ou définit l'image d'arrière-plan

### setBackgroundImageFile {#setBackgroundImageFile-java.lang.String-}
Définit le fichier d'image d'arrière-plan.

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Définit la bordure.

### setColSpan {#setColSpan-int-}
```
public void setColSpan(int value)
```

Définit l'étendue de colonne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setDefaultCellTextState {#setDefaultCellTextState-com.aspose.pdf.TextState-}
Définit l'état du texte par défaut de la cellule.

### setMargin {#setMargin-com.aspose.pdf.MarginInfo-}
Définit le remplissage.

### setNoBorder {#setNoBorder-boolean-}
```
public void setNoBorder(boolean value)
```

Définit si la cellule possède une bordure

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setOverrideByFragment {#setOverrideByFragment-boolean-}
```
public final void setOverrideByFragment(boolean value)
```

Définit la propriété TextState de la cellule qui est remplacée par la propriété TextState de TextFragment.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Définit le texte formaté de la cellule.

### setRowSpan {#setRowSpan-int-}
```
public void setRowSpan(int value)
```

Définit l'étendue de ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Définit l'alignement vertical.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Définit la largeur de colonne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setWordWrapped {#setWordWrapped-boolean-}
```
public void setWordWrapped(boolean value)
```

Définit le texte de la cellule avec retour à la ligne.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
