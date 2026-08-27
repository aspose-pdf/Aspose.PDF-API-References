---
title: "Tampon"
linktitle: "Tampon"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Une classe abstraite pour différents types de tampons qui sont des descendants."
type: docs
weight: 4620
url: /fr/java/com.aspose.pdf/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp

```
public abstract class Stamp extends Object
```

Une classe abstraite pour différents types de tampons qui sont des descendants.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Stamp](#Stamp--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBottomMargin](#getBottomMargin--) | Obtient la marge inférieure du tampon. |
| [getHeight](#getHeight--) | Obtient la hauteur souhaitée du tampon sur la page. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Obtient l'alignement horizontal du tampon sur la page. |
| [getLeftMargin](#getLeftMargin--) | Obtient la marge gauche du tampon. |
| [getOpacity](#getOpacity--) | Obtient une valeur indiquant l'opacité du tampon. La valeur est de 0.0 à 1.0. Par défaut, la valeur est 1.0. |
| [getOutlineOpacity](#getOutlineOpacity--) | Obtient une valeur indiquant l'opacité du contour du tampon. La valeur est de 0.0 à 1.0. Par défaut, la valeur est 1.0. |
| [getOutlineWidth](#getOutlineWidth--) | Obtient la valeur de la largeur du contour du tampon. Par défaut, la valeur est 1.0. |
| [getRightMargin](#getRightMargin--) | Obtient la marge droite du tampon. |
| [getRotate](#getRotate--) | Obtient la rotation du contenu du tampon selon les valeurs {@code Rotation}. Remarque : cette propriété sert à définir des angles qui sont des multiples de 90 degrés (0, 90, 180, 270 degrés). Pour définir un angle arbitraire, utilisez la propriété RotateAngle. Si l'angle défini par ArbitraryAngle n'est pas un multiple de 90, alors la propriété Rotate renvoie Rotation.None. |
| [getRotateAngle](#getRotateAngle--) | Obtient l'angle de rotation du tampon en degrés. Cette propriété permet de définir un angle de rotation arbitraire. |
| [getStampId](#getStampId--) | Obtient l'ID du tampon. |
| [getTopMargin](#getTopMargin--) | Obtient la marge supérieure du tampon. |
| [getVerticalAlignment](#getVerticalAlignment--) | Obtient l'alignement vertical du tampon sur la page. |
| [getWidth](#getWidth--) | Obtient la largeur souhaitée du tampon sur la page. |
| [getXIndent](#getXIndent--) | Obtient la coordonnée horizontale du tampon, en partant de la gauche. |
| [getYIndent](#getYIndent--) | Obtient la coordonnée verticale du tampon, en partant du bas. |
| [getZoom](#getZoom--) | Obtient le facteur de zoom du tampon. Permet de mettre à l'échelle le tampon. Veuillez noter que la paire de propriétés ZoomX et ZoomY permet de définir le facteur de zoom pour chaque axe séparément. La définition de cette propriété modifie à la fois les propriétés ZoomX et ZoomY. Si ZoomX et ZoomY sont différents, alors la propriété Zoom renvoie la valeur de ZoomX. |
| [getZoomX](#getZoomX--) | Obtient le facteur de zoom horizontal du tampon. Permet de mettre à l'échelle le tampon horizontalement. |
| [getZoomY](#getZoomY--) | Obtient le facteur de zoom vertical du tampon. Permet de mettre à l'échelle le tampon verticalement. |
| [isBackground](#isBackground--) | Obtient une valeur booléenne indiquant que le contenu est tamponné en arrière-plan. Si la valeur est vraie, le contenu du tampon est placé en bas. Par défaut, la valeur est fausse, le contenu du tampon est placé en haut. |
| [put](#put-com.aspose.pdf.Page-) | Ajoute un tampon sur la page. |
| [setBackground](#setBackground-boolean-) | Définit une valeur booléenne indiquant que le contenu est tamponné en arrière-plan. Si la valeur est vraie, le contenu du tampon est placé en bas. Par défaut, la valeur est fausse, le contenu du tampon est placé en haut. |
| [setBottomMargin](#setBottomMargin-double-) | Définit la marge inférieure du tampon. |
| [setHeight](#setHeight-double-) | Définit la hauteur souhaitée du tampon sur la page. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Définit l'alignement horizontal du tampon sur la page. |
| [setLeftMargin](#setLeftMargin-double-) | Définit la marge gauche du tampon. |
| [setOpacity](#setOpacity-double-) | Définit une valeur indiquant l'opacité du tampon. La valeur est comprise entre 0,0 et 1,0. Par défaut, la valeur est 1,0. |
| [setOutlineOpacity](#setOutlineOpacity-double-) | Définit une valeur indiquant l'opacité du contour du tampon. La valeur est comprise entre 0,0 et 1,0. Par défaut, la valeur est 1,0. |
| [setOutlineWidth](#setOutlineWidth-double-) | Définit une valeur de la largeur du contour du tampon. Par défaut, la valeur est 1,0. |
| [setRightMargin](#setRightMargin-double-) | Définit la marge droite du tampon. |
| [setRotate](#setRotate-com.aspose.pdf.Rotation-) | Définit la rotation du contenu du tampon selon les valeurs {@code Rotation}. Remarque : cette propriété sert à définir des angles qui sont des multiples de 90 degrés (0, 90, 180, 270 degrés). Pour définir un angle arbitraire, utilisez la propriété RotateAngle. Si l'angle défini par ArbitraryAngle n'est pas un multiple de 90, alors la propriété Rotate renvoie Rotation.None. |
| [setRotateAngle](#setRotateAngle-double-) | Définit l'angle de rotation du tampon en degrés. Cette propriété permet de définir un angle de rotation arbitraire. |
| [setStampId](#setStampId-int-) | Définit l'ID du tampon. |
| [setTopMargin](#setTopMargin-double-) | Définit la marge supérieure du tampon. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Définit l'alignement vertical du tampon sur la page. |
| [setWidth](#setWidth-double-) | Définit la largeur souhaitée du tampon sur la page. |
| [setXIndent](#setXIndent-double-) | Définit la coordonnée horizontale du tampon, en partant de la gauche. |
| [setYIndent](#setYIndent-double-) | Définit la coordonnée verticale du tampon, en partant du bas. |
| [setZoom](#setZoom-double-) | Obtient le facteur de zoom du tampon. Permet de mettre à l'échelle le tampon. Veuillez noter que la paire de propriétés ZoomX et ZoomY permet de définir le facteur de zoom pour chaque axe séparément. La définition de cette propriété modifie à la fois les propriétés ZoomX et ZoomY. Si ZoomX et ZoomY sont différents, alors la propriété Zoom renvoie la valeur de ZoomX. |
| [setZoomX](#setZoomX-double-) | Définit le facteur de zoom horizontal du tampon. Permet de mettre à l'échelle le tampon horizontalement. |
| [setZoomY](#setZoomY-double-) | Définit le facteur de zoom vertical du tampon. Permet de mettre à l'échelle le tampon verticalement. |

### Stamp {#Stamp--}
```
public Stamp()
```



### getBottomMargin {#getBottomMargin--}
```
public double getBottomMargin()
```

Obtient la marge inférieure du tampon.

**Returns:**
valeur double

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtient la hauteur souhaitée du tampon sur la page.

**Returns:**
valeur double

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Obtient l'alignement horizontal du tampon sur la page.

**Returns:**
Valeur HorizontalAlignment @see HorizontalAlignment

### getLeftMargin {#getLeftMargin--}
```
public double getLeftMargin()
```

Obtient la marge gauche du tampon.

**Returns:**
valeur double

### getOpacity {#getOpacity--}
```
public double getOpacity()
```

Obtient une valeur indiquant l'opacité du tampon. La valeur est de 0.0 à 1.0. Par défaut, la valeur est 1.0.

**Returns:**
valeur double

### getOutlineOpacity {#getOutlineOpacity--}
```
public double getOutlineOpacity()
```

Obtient une valeur indiquant l'opacité du contour du tampon. La valeur est de 0.0 à 1.0. Par défaut, la valeur est 1.0.

**Returns:**
valeur double

### getOutlineWidth {#getOutlineWidth--}
```
public double getOutlineWidth()
```

Obtient la valeur de la largeur du contour du tampon. Par défaut, la valeur est 1.0.

**Returns:**
valeur double

### getRightMargin {#getRightMargin--}
```
public double getRightMargin()
```

Obtient la marge droite du tampon.

**Returns:**
valeur double

### getRotate {#getRotate--}
```
public Rotation getRotate()
```

Obtient la rotation du contenu du tampon selon les valeurs {@code Rotation}. Remarque : cette propriété sert à définir des angles qui sont des multiples de 90 degrés (0, 90, 180, 270 degrés). Pour définir un angle arbitraire, utilisez la propriété RotateAngle. Si l'angle défini par ArbitraryAngle n'est pas un multiple de 90, alors la propriété Rotate renvoie Rotation.None.

**Returns:**
Valeur de rotation @see Rotation

### getRotateAngle {#getRotateAngle--}
```
public double getRotateAngle()
```

Obtient l'angle de rotation du tampon en degrés. Cette propriété permet de définir un angle de rotation arbitraire.

**Returns:**
valeur double

### getStampId {#getStampId--}
```
public int getStampId()
```

Obtient l'ID du tampon.

**Returns:**
Identifiant du tampon.

### getTopMargin {#getTopMargin--}
```
public double getTopMargin()
```

Obtient la marge supérieure du tampon.

**Returns:**
valeur double

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Obtient l'alignement vertical du tampon sur la page.

**Returns:**
Valeur VerticalAlignment @see VerticalAlignment

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtient la largeur souhaitée du tampon sur la page.

**Returns:**
valeur double

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Obtient la coordonnée horizontale du tampon, en partant de la gauche.

**Returns:**
valeur double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Obtient la coordonnée verticale du tampon, en partant du bas.

**Returns:**
valeur double

### getZoom {#getZoom--}
```
public double getZoom()
```

Obtient le facteur de zoom du tampon. Permet de mettre à l'échelle le tampon. Veuillez noter que la paire de propriétés ZoomX et ZoomY permet de définir le facteur de zoom pour chaque axe séparément. La définition de cette propriété modifie à la fois les propriétés ZoomX et ZoomY. Si ZoomX et ZoomY sont différents, alors la propriété Zoom renvoie la valeur de ZoomX.

**Returns:**
valeur double

### getZoomX {#getZoomX--}
```
public double getZoomX()
```

Obtient le facteur de zoom horizontal du tampon. Permet de mettre à l'échelle le tampon horizontalement.

**Returns:**
valeur double

### getZoomY {#getZoomY--}
```
public double getZoomY()
```

Obtient le facteur de zoom vertical du tampon. Permet de mettre à l'échelle le tampon verticalement.

**Returns:**
valeur double

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Obtient une valeur booléenne indiquant que le contenu est tamponné en arrière-plan. Si la valeur est vraie, le contenu du tampon est placé en bas. Par défaut, la valeur est fausse, le contenu du tampon est placé en haut.

**Returns:**
valeur booléenne

### put {#put-com.aspose.pdf.Page-}
Ajoute un tampon sur la page.

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Définit une valeur booléenne indiquant que le contenu est tamponné en arrière-plan. Si la valeur est vraie, le contenu du tampon est placé en bas. Par défaut, la valeur est fausse, le contenu du tampon est placé en haut.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setBottomMargin {#setBottomMargin-double-}
```
public void setBottomMargin(double value)
```

Définit la marge inférieure du tampon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Définit la hauteur souhaitée du tampon sur la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Définit l'alignement horizontal du tampon sur la page.

### setLeftMargin {#setLeftMargin-double-}
```
public void setLeftMargin(double value)
```

Définit la marge gauche du tampon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setOpacity {#setOpacity-double-}
```
public void setOpacity(double value)
```

Définit une valeur indiquant l'opacité du tampon. La valeur est comprise entre 0,0 et 1,0. Par défaut, la valeur est 1,0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setOutlineOpacity {#setOutlineOpacity-double-}
```
public void setOutlineOpacity(double value)
```

Définit une valeur indiquant l'opacité du contour du tampon. La valeur est comprise entre 0,0 et 1,0. Par défaut, la valeur est 1,0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setOutlineWidth {#setOutlineWidth-double-}
```
public void setOutlineWidth(double value)
```

Définit une valeur de la largeur du contour du tampon. Par défaut, la valeur est 1,0.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setRightMargin {#setRightMargin-double-}
```
public void setRightMargin(double value)
```

Définit la marge droite du tampon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setRotate {#setRotate-com.aspose.pdf.Rotation-}
Définit la rotation du contenu du tampon selon les valeurs {@code Rotation}. Remarque : cette propriété sert à définir des angles qui sont des multiples de 90 degrés (0, 90, 180, 270 degrés). Pour définir un angle arbitraire, utilisez la propriété RotateAngle. Si l'angle défini par ArbitraryAngle n'est pas un multiple de 90, alors la propriété Rotate renvoie Rotation.None.

### setRotateAngle {#setRotateAngle-double-}
```
public void setRotateAngle(double value)
```

Définit l'angle de rotation du tampon en degrés. Cette propriété permet de définir un angle de rotation arbitraire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | angle de rotation |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Définit l'ID du tampon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | Nouvelle valeur de l'ID du tampon. |

### setTopMargin {#setTopMargin-double-}
```
public void setTopMargin(double value)
```

Définit la marge supérieure du tampon.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Définit l'alignement vertical du tampon sur la page.

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Définit la largeur souhaitée du tampon sur la page.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Définit la coordonnée horizontale du tampon, en partant de la gauche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Définit la coordonnée verticale du tampon, en partant du bas.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setZoom {#setZoom-double-}
```
public void setZoom(double value)
```

Obtient le facteur de zoom du tampon. Permet de mettre à l'échelle le tampon. Veuillez noter que la paire de propriétés ZoomX et ZoomY permet de définir le facteur de zoom pour chaque axe séparément. La définition de cette propriété modifie à la fois les propriétés ZoomX et ZoomY. Si ZoomX et ZoomY sont différents, alors la propriété Zoom renvoie la valeur de ZoomX.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setZoomX {#setZoomX-double-}
```
public void setZoomX(double value)
```

Définit le facteur de zoom horizontal du tampon. Permet de mettre à l'échelle le tampon horizontalement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setZoomY {#setZoomY-double-}
```
public void setZoomY(double value)
```

Définit le facteur de zoom vertical du tampon. Permet de mettre à l'échelle le tampon verticalement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |
