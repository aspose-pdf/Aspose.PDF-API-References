---
title: "ImageStamp"
linktitle: "ImageStamp"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un tampon graphique."
type: docs
weight: 2360
url: /fr/java/com.aspose.pdf/imagestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.ImageStamp, com.aspose.pdf.Stamp, com.aspose.pdf.ImageStamp

```
public final class ImageStamp extends Stamp
```

Représente un tampon graphique.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageStamp](#ImageStamp-java.io.InputStream-) | Initialise une nouvelle instance de la classe {@code ImageStamp}. |
| [ImageStamp](#ImageStamp-java.lang.String-) | Crée un tampon d'image à partir d'une image dans le fichier spécifié. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [close](#close--) | Ferme cette instance. |
| [getAlternativeText](#getAlternativeText--) | Obtient le texte alternatif pour le tampon d'image. |
| [getHeight](#getHeight--) | Obtient la hauteur de l'image. Modifier cette image permet de la mettre à l'échelle verticalement. |
| [getImage](#getImage--) | Obtient le flux d'image utilisé pour le tamponnage. |
| [getQuality](#getQuality--) | Obtient la qualité du tampon d'image en pourcentage. Les valeurs valides sont 0..100%. |
| [getWidth](#getWidth--) | Obtient la largeur de l'image. Modifier cette propriété permet de mettre l'image à l'échelle horizontalement. |
| [getXIndent](#getXIndent--) | Obtient et définit la coordonnée horizontale du tampon, en partant de la gauche. |
| [getYIndent](#getYIndent--) | Obtient et définit la coordonnée verticale du tampon, en partant du bas. |
| [put](#put-com.aspose.pdf.Page-) | Ajoute un tampon graphique sur la page. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Définit le texte alternatif pour le tampon d'image. |
| [setHeight](#setHeight-double-) | Définit la hauteur de l'image. Modifier cette image permet de la mettre à l'échelle verticalement. |
| [setQuality](#setQuality-int-) | Définit la qualité du tampon d'image en pourcentage. Les valeurs valides sont 0..100%. |
| [setWidth](#setWidth-double-) | Définit la largeur de l'image. Modifier cette propriété permet de mettre l'image à l'échelle horizontalement. |
| [setXIndent](#setXIndent-double-) | Obtient et définit la coordonnée horizontale du tampon, en partant de la gauche. |
| [setYIndent](#setYIndent-double-) | Obtient et définit la coordonnée verticale du tampon, en partant du bas. |

### ImageStamp {#ImageStamp-java.io.InputStream-}
Initialise une nouvelle instance de la classe {@code ImageStamp}.

### ImageStamp {#ImageStamp-java.lang.String-}
Crée un tampon d'image à partir d'une image dans le fichier spécifié.

### close {#close--}
```
public void close()
```

Ferme cette instance.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Obtient le texte alternatif pour le tampon d'image.

**Returns:**
valeur String

### getHeight {#getHeight--}
```
public double getHeight()
```

Obtient la hauteur de l'image. Modifier cette image permet de la mettre à l'échelle verticalement.

**Returns:**
valeur double

### getImage {#getImage--}
```
public InputStream getImage()
```

Obtient le flux d'image utilisé pour le tamponnage.

**Returns:**
Objet InputStream

### getQuality {#getQuality--}
```
public int getQuality()
```

Obtient la qualité du tampon d'image en pourcentage. Les valeurs valides sont 0..100%.

**Returns:**
valeur int

### getWidth {#getWidth--}
```
public double getWidth()
```

Obtient la largeur de l'image. Modifier cette propriété permet de mettre l'image à l'échelle horizontalement.

**Returns:**
valeur double

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Obtient et définit la coordonnée horizontale du tampon, en partant de la gauche.

**Returns:**
valeur double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Obtient et définit la coordonnée verticale du tampon, en partant du bas.

**Returns:**
valeur double

### put {#put-com.aspose.pdf.Page-}
Ajoute un tampon graphique sur la page.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Définit le texte alternatif pour le tampon d'image.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Définit la hauteur de l'image. Modifier cette image permet de la mettre à l'échelle verticalement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Définit la qualité du tampon d'image en pourcentage. Les valeurs valides sont 0..100%.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Définit la largeur de l'image. Modifier cette propriété permet de mettre l'image à l'échelle horizontalement.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Obtient et définit la coordonnée horizontale du tampon, en partant de la gauche.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Obtient et définit la coordonnée verticale du tampon, en partant du bas.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |
