---
title: "FloatingBox"
linktitle: "FloatingBox"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un FloatingBox dans un document Pdf. FloatingBox est positionné de façon personnalisée."
type: docs
weight: 1610
url: /fr/java/com.aspose.pdf/floatingbox/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.FloatingBox, com.aspose.pdf.BaseParagraph, com.aspose.pdf.FloatingBox

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public class FloatingBox extends BaseParagraph
```

Représente un FloatingBox dans un document Pdf. FloatingBox est positionné de façon personnalisée.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [FloatingBox](#FloatingBox--) | Initialise une nouvelle instance de la classe {@code FloatingBox}. |
| [FloatingBox](#FloatingBox-float-float-) | Initialise une nouvelle instance de la classe {@code FloatingBox} avec la largeur et la hauteur spécifiées. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [deepClone](#deepClone--) | Clone un nouvel objet {@code FloatingBox}. Les paragraphes dans la boîte flottante ne sont pas clonés. |
| [getBackgroundColor](#getBackgroundColor--) | Obtient un objet qui indique la couleur d'arrière-plan de la boîte flottante. |
| [getBackgroundImage](#getBackgroundImage--) | Obtient ou définit l'image d'arrière-plan de la page (uniquement pour le générateur, non remplie lors de la lecture du document). |
| [getBorder](#getBorder--) | Obtient un objet qui indique les informations de bordure de la boîte flottante. |
| [getColumnInfo](#getColumnInfo--) | Obtient une information de colonne |
| [getHeight](#getHeight--) | Obtient une valeur flottante qui indique la hauteur de la boîte flottante. |
| [getLeft](#getLeft--) | Obtient la coordonnée gauche du tableau. |
| [getPadding](#getPadding--) | Obtient un objet qui indique le remplissage de la boîte flottante. |
| [getParagraphs](#getParagraphs--) | Obtient une collection qui indique tous les paragraphes dans la cellule. |
| [getPositioningMode](#getPositioningMode--) | Spécifie la variante pour déterminer l'emplacement du FloatingBox sur la page. |
| [getTop](#getTop--) | Obtient la coordonnée supérieure du tableau. |
| [getWidth](#getWidth--) | Obtient une valeur flottante qui indique la largeur de la boîte flottante. |
| [isNeedRepeating](#isNeedRepeating--) | Obtient une valeur booléenne qui indique si le paragraphe doit être répété sur la page suivante. La valeur par défaut est true. L'attribut n'est valide que lorsque le paragraphe lui‑-même et l'objet auquel son ReferenceParagraphID fait référence sont tous deux inclus dans RepeatingRows. |
| [setBackgroundColor](#setBackgroundColor-com.aspose.pdf.Color-) | Définit un objet qui indique la couleur d'arrière-plan de la boîte flottante. |
| [setBackgroundImage](#setBackgroundImage-com.aspose.pdf.Image-) | Obtient ou définit l'image d'arrière-plan de la page (uniquement pour le générateur, non remplie lors de la lecture du document). |
| [setBorder](#setBorder-com.aspose.pdf.BorderInfo-) | Définit un objet qui indique les informations de bordure de la boîte flottante. |
| [setColumnInfo](#setColumnInfo-com.aspose.pdf.ColumnInfo-) | Définit une information de colonne |
| [setHeight](#setHeight-double-) | Définit une valeur flottante qui indique la hauteur de la boîte flottante. |
| [setLeft](#setLeft-double-) | Définit la coordonnée gauche du tableau. |
| [setNeedRepeating](#setNeedRepeating-boolean-) | Définit une valeur booléenne qui indique si le paragraphe doit être répété sur la page suivante. La valeur par défaut est true. L'attribut n'est valide que lorsque le paragraphe lui‑-même et l'objet auquel son ReferenceParagraphID fait référence sont tous deux inclus dans RepeatingRows. |
| [setPadding](#setPadding-com.aspose.pdf.MarginInfo-) | Définit un objet qui indique le remplissage de la boîte flottante. |
| [setParagraphs](#setParagraphs-com.aspose.pdf.Paragraphs-) | Définit une collection qui indique tous les paragraphes dans la cellule. |
| [setPositioningMode](#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-) | Spécifie la variante pour déterminer l'emplacement du FloatingBox sur la page. |
| [setTop](#setTop-double-) | Définit la coordonnée supérieure du tableau. |
| [setWidth](#setWidth-double-) | Définit une valeur flottante qui indique la largeur de la boîte flottante. |

### FloatingBox {#FloatingBox--}
```
public FloatingBox()
```

Initialise une nouvelle instance de la classe {@code FloatingBox}.

### FloatingBox {#FloatingBox-float-float-}
```
public FloatingBox(float width, float height)
```

Initialise une nouvelle instance de la classe {@code FloatingBox} avec la largeur et la hauteur spécifiées.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | La largeur de la boîte. |
| hauteur |  | La hauteur de la boîte. |

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clone un nouvel objet {@code FloatingBox}. Les paragraphes dans la boîte flottante ne sont pas clonés.

**Returns:**
Le nouvel objet {@code FloatingBox}.

### getBackgroundColor {#getBackgroundColor--}
```
public Color getBackgroundColor()
```

Obtient un objet qui indique la couleur d'arrière-plan de la boîte flottante.

**Returns:**
objet qui indique la couleur d'arrière-plan.

### getBackgroundImage {#getBackgroundImage--}
```
public final Image getBackgroundImage()
```

Obtient ou définit l'image d'arrière-plan de la page (uniquement pour le générateur, non remplie lors de la lecture du document).

**Returns:**
Instance d'image

### getBorder {#getBorder--}
```
public BorderInfo getBorder()
```

Obtient un objet qui indique les informations de bordure de la boîte flottante.

**Returns:**
objet qui indique les informations de bordure.

### getColumnInfo {#getColumnInfo--}
```
public ColumnInfo getColumnInfo()
```

Obtient une information de colonne

**Returns:**
objet ColumnInfo

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtient une valeur flottante qui indique la hauteur de la boîte flottante.

**Returns:**
valeur qui indique la hauteur.

### getLeft {#getLeft--}
```
public double getLeft()
```

Obtient la coordonnée gauche du tableau.

**Returns:**
coordonnée gauche du tableau.

### getPadding {#getPadding--}
```
public MarginInfo getPadding()
```

Obtient un objet qui indique le remplissage de la boîte flottante.

**Returns:**
objet qui indique le remplissage.

### getParagraphs {#getParagraphs--}
```
public Paragraphs getParagraphs()
```

Obtient une collection qui indique tous les paragraphes dans la cellule.

**Returns:**
collection qui indique tous les paragraphes.

### getPositioningMode {#getPositioningMode--}
```
public final ParagraphPositioningMode getPositioningMode()
```

Spécifie la variante pour déterminer l'emplacement du FloatingBox sur la page.

**Returns:**
élément ParagraphPositioningMode

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

Obtient une valeur flottante qui indique la largeur de la boîte flottante.

**Returns:**
valeur double

### isNeedRepeating {#isNeedRepeating--}
```
public boolean isNeedRepeating()
```

Obtient une valeur booléenne qui indique si le paragraphe doit être répété sur la page suivante. La valeur par défaut est true. L'attribut n'est valide que lorsque le paragraphe lui‑-même et l'objet auquel son ReferenceParagraphID fait référence sont tous deux inclus dans RepeatingRows.

**Returns:**
valeur booléenne

### setBackgroundColor {#setBackgroundColor-com.aspose.pdf.Color-}
Définit un objet qui indique la couleur d'arrière-plan de la boîte flottante.

### setBackgroundImage {#setBackgroundImage-com.aspose.pdf.Image-}
Obtient ou définit l'image d'arrière-plan de la page (uniquement pour le générateur, non remplie lors de la lecture du document).

### setBorder {#setBorder-com.aspose.pdf.BorderInfo-}
Définit un objet qui indique les informations de bordure de la boîte flottante.

### setColumnInfo {#setColumnInfo-com.aspose.pdf.ColumnInfo-}
Définit une information de colonne

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Définit une valeur flottante qui indique la hauteur de la boîte flottante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur qui indique la hauteur. |

### setLeft {#setLeft-double-}
```
public void setLeft(double value)
```

Définit la coordonnée gauche du tableau.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | coordonnée gauche du tableau. |

### setNeedRepeating {#setNeedRepeating-boolean-}
```
public void setNeedRepeating(boolean value)
```

Définit une valeur booléenne qui indique si le paragraphe doit être répété sur la page suivante. La valeur par défaut est true. L'attribut n'est valide que lorsque le paragraphe lui‑-même et l'objet auquel son ReferenceParagraphID fait référence sont tous deux inclus dans RepeatingRows.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setPadding {#setPadding-com.aspose.pdf.MarginInfo-}
Définit un objet qui indique le remplissage de la boîte flottante.

### setParagraphs {#setParagraphs-com.aspose.pdf.Paragraphs-}
Définit une collection qui indique tous les paragraphes dans la cellule.

### setPositioningMode {#setPositioningMode-com.aspose.pdf.ParagraphPositioningMode-}
Spécifie la variante pour déterminer l'emplacement du FloatingBox sur la page.

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

Définit une valeur flottante qui indique la largeur de la boîte flottante.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |
