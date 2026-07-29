---
title: "Image"
linktitle: "Image"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente une image."
type: docs
weight: 2280
url: /fr/java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Image, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Image

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Image extends BaseParagraph
```

Représente une image.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [Image](#Image--) | constructeur par défaut |

## Méthodes

| Méthode | Description |
| --- | --- |
| [convertToJpeg](#convertToJpeg-java.io.InputStream-) | Essayer de convertir le flux d'image bmp/png/gif/tiff en flux d'image au format JPG. |
| [deepClone](#deepClone--) | Cloner l'image. |
| [getBitmapInfo](#getBitmapInfo--) | Obtient ou définit les octets d'image non compressés. |
| [getBitmapSize](#getBitmapSize--) | Obtient la taille du bitmap de l'image. |
| [getBufferedImage](#getBufferedImage--) | Obtient l'image java awt. |
| [getFile](#getFile--) | Obtient le fichier image. |
| [getFileType](#getFileType--) | Obtient le type de fichier image. |
| [getFixHeight](#getFixHeight--) | Obtient la hauteur de l'image. |
| [getFixWidth](#getFixWidth--) | Obtient la largeur de l'image. |
| [getImageScale](#getImageScale--) | Obtient l'échelle de l'image. |
| [getImageStream](#getImageStream--) | Obtient le flux de l'image. |
| [getMimeType](#getMimeType-com.aspose.ms.System.Drawing.Image-) | Renvoie le type MIME de l'image. |
| [getTitle](#getTitle--) | Obtient une valeur chaîne qui indique le titre de l'image. |
| [isApplyResolution](#isApplyResolution--) | Obtient ou définit une valeur booléenne qui indique si l'image utilise la résolution lors de la génération |
| [isBlackWhite](#isBlackWhite--) | Obtient une valeur booléenne qui indique si l'image est forcée d'être en noir et blanc. Si une image TIFF du sous-format CCITT est utilisée, cette propriété doit être définie sur true. |
| [isBlackWhiteForGrayScale](#isBlackWhiteForGrayScale--) | Essaye de détecter et d'utiliser l'encodage 1bpp pour les images en niveaux de gris. Valeur par défaut == FALSE |
| [setApplyResolution](#setApplyResolution-boolean-) | Obtient ou définit une valeur booléenne qui indique si l'image utilise la résolution lors de la génération |
| [setBitmapInfo](#setBitmapInfo-com.aspose.pdf.BitmapInfo-) | Obtient ou définit les octets d'image non compressés. |
| [setBlackWhite](#setBlackWhite-boolean-) | Définit une valeur booléenne qui indique si l'image est forcée d'être en noir et blanc. Si une image TIFF du sous-format CCITT est utilisée, cette propriété doit être définie sur true. |
| [setBlackWhiteForGrayScale](#setBlackWhiteForGrayScale-boolean-) | Essaye de détecter et d'utiliser l'encodage 1bpp pour les images en niveaux de gris. Valeur par défaut == FALSE |
| [setBufferedImage](#setBufferedImage-java.awt.image.BufferedImage-) | Définit l'image java awt. |
| [setFile](#setFile-java.lang.String-) | Définit le fichier image. |
| [setFileType](#setFileType-com.aspose.pdf.ImageFileType-) | Définit le type de fichier image. |
| [setFixHeight](#setFixHeight-double-) | Définit la hauteur de l'image. |
| [setFixWidth](#setFixWidth-double-) | Définit la largeur de l'image. |
| [setImageScale](#setImageScale-double-) | Définit l'échelle de l'image. |
| [setImageStream](#setImageStream-java.io.InputStream-) | Définit le flux de l'image. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Définit une valeur chaîne qui indique le titre de l'image. |

### Image {#Image--}
```
public Image()
```

constructeur par défaut

### convertToJpeg {#convertToJpeg-java.io.InputStream-}
Essayer de convertir le flux d'image bmp/png/gif/tiff en flux d'image au format JPG.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Cloner l'image.

**Returns:**
L'objet cloné

### getBitmapInfo {#getBitmapInfo--}
```
public final BitmapInfo getBitmapInfo()
```

Obtient ou définit les octets d'image non compressés.

**Returns:**
Instance BitmapInfo

### getBitmapSize {#getBitmapSize--}
```
public final Rectangle getBitmapSize()
```

Obtient la taille du bitmap de l'image.

**Returns:**
Instance de Rectangle

### getBufferedImage {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```

Obtient l'image java awt.

**Returns:**
Objet BufferedImage

### getFile {#getFile--}
```
public String getFile()
```

Obtient le fichier image.

**Returns:**
valeur String

### getFileType {#getFileType--}
```
public ImageFileType getFileType()
```

Obtient le type de fichier image.

**Returns:**
valeur int @see ImageFileType

### getFixHeight {#getFixHeight--}
```
public double getFixHeight()
```

Obtient la hauteur de l'image.

**Returns:**
valeur double

### getFixWidth {#getFixWidth--}
```
public double getFixWidth()
```

Obtient la largeur de l'image.

**Returns:**
valeur double

### getImageScale {#getImageScale--}
```
public double getImageScale()
```

Obtient l'échelle de l'image.

**Returns:**
valeur double

### getImageStream {#getImageStream--}
```
public InputStream getImageStream()
```

Obtient le flux de l'image.

**Returns:**
Objet InputStream

### getMimeType {#getMimeType-com.aspose.ms.System.Drawing.Image-}
Renvoie le type MIME de l'image.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Obtient une valeur chaîne qui indique le titre de l'image.

**Returns:**
Valeur TextFragment

### isApplyResolution {#isApplyResolution--}
```
public boolean isApplyResolution()
```

Obtient ou définit une valeur booléenne qui indique si l'image utilise la résolution lors de la génération

**Returns:**
valeur booléenne

### isBlackWhite {#isBlackWhite--}
```
public boolean isBlackWhite()
```

Obtient une valeur booléenne qui indique si l'image est forcée d'être en noir et blanc. Si une image TIFF du sous-format CCITT est utilisée, cette propriété doit être définie sur true.

**Returns:**
valeur booléenne

### isBlackWhiteForGrayScale {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```

Essaye de détecter et d'utiliser l'encodage 1bpp pour les images en niveaux de gris. Valeur par défaut == FALSE

**Returns:**
valeur booléenne

### setApplyResolution {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```

Obtient ou définit une valeur booléenne qui indique si l'image utilise la résolution lors de la génération

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setBitmapInfo {#setBitmapInfo-com.aspose.pdf.BitmapInfo-}
Obtient ou définit les octets d'image non compressés.

### setBlackWhite {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```

Définit une valeur booléenne qui indique si l'image est forcée d'être en noir et blanc. Si une image TIFF du sous-format CCITT est utilisée, cette propriété doit être définie sur true.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |

### setBlackWhiteForGrayScale {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```

Essaye de détecter et d'utiliser l'encodage 1bpp pour les images en niveaux de gris. Valeur par défaut == FALSE

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| blackWhiteForGrayScale |  | valeur booléenne |

### setBufferedImage {#setBufferedImage-java.awt.image.BufferedImage-}
Définit l'image java awt.

### setFile {#setFile-java.lang.String-}
Définit le fichier image.

### setFileType {#setFileType-com.aspose.pdf.ImageFileType-}
Définit le type de fichier image.

### setFixHeight {#setFixHeight-double-}
```
public void setFixHeight(double value)
```

Définit la hauteur de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setFixWidth {#setFixWidth-double-}
```
public void setFixWidth(double value)
```

Définit la largeur de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setImageScale {#setImageScale-double-}
```
public void setImageScale(double value)
```

Définit l'échelle de l'image.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur double |

### setImageStream {#setImageStream-java.io.InputStream-}
Définit le flux de l'image.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Définit une valeur chaîne qui indique le titre de l'image.
