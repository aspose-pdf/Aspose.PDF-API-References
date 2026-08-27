---
title: "XImage"
linktitle: "XImage"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe représentant l'objet image X-Object."
type: docs
weight: 5610
url: /fr/java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImage

```
public final class XImage extends Object
```

Classe représentant l'objet image X-Object.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [XImage](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | pour usage interne uniquement |

## Méthodes

| Méthode | Description |
| --- | --- |
| [addStencilMask](#addStencilMask-java.io.InputStream-) | Ajoute un masque pochoir à l'XImage. |
| [containsTransparency](#containsTransparency--) | Si l'image contient de la transparence alors renvoie true ; sinon false. |
| [delete](#delete--) | Supprime l'image de la collection parent. |
| [detectColorType](#detectColorType-java.awt.image.BufferedImage-) | Renvoie le type de couleur de l'image. |
| [getAlternativeText](#getAlternativeText-com.aspose.pdf.Page-) | Renvoie une liste de chaînes avec le texte alternatif pour un XImage. |
| [getColorType](#getColorType--) | Renvoie le type de couleur de l'image. |
| [getEngineImg](#getEngineImg--) | Objet IPdfImage qui décrit l'image. Usage interne uniquement |
| [getFilterType](#getFilterType--) | Obtient le type de filtre d'image. |
| [getGrayscaled](#getGrayscaled--) | Obtient la version en niveaux de gris de l'image. |
| [getHeight](#getHeight--) | Obtient la hauteur de l'image. |
| [getImage](#getImage--) | Pour usage interne uniquement |
| [getMetadata](#getMetadata--) | Métadonnées de l'image. |
| [getName](#getName--) | Obtient le nom de l'image. Veuillez noter que si vous changez le nom de l'image qui possède des références dans le contenu des pages, le document peut devenir incorrect. Veuillez utiliser la méthode XImage.Rename dans ce cas. |
| [getNameInCollection](#getNameInCollection--) | Renvoie le nom de l'image dans sa collection. |
| [getRawBytes](#getRawBytes--) | Renvoie les octets bruts de l'image sans décodage. |
| [getRawImageData](#getRawImageData--) | Récupère les données brutes de l'image à partir de l'image source. |
| [getRawParameters](#getRawParameters--) | Obtient les paramètres bruts de l'image |
| [getWidth](#getWidth--) | Obtient la largeur de l'image. |
| [isImage](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | Renvoie true si le primitive est une image. |
| [isImageMask](#isImageMask--) | Obtient un indicateur indiquant si l'image doit être traitée comme un masque d'image (voir 8.9.6, "Masked Images"). Si cet indicateur est true, la valeur de BitsPerComponent doit être 1 et Mask et ColorSpace ne doivent pas être spécifiés ; les zones non masquées doivent être peintes en utilisant la couleur de tracé actuelle. Valeur par défaut : false. Valeur : True si l'image est un masque d'image. |
| [isTheSameObject](#isTheSameObject-com.aspose.pdf.XImage-) | Renvoie true si les deux images font référence au même objet. |
| [rename](#rename-java.lang.String-) | Renomme l'image et remplace toutes les références à l'image par le nouveau nom |
| [replace](#replace-java.io.InputStream-) | Remplace l'image dans le flux spécifié dans {@code image}. * |
| [save](#save-java.io.OutputStream-) | Enregistre les données de l'image dans le flux en tant qu'image JPEG. |
| [save](#save-java.io.OutputStream-float-float-) | Enregistre l'image dans le flux avec le format demandé. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Enregistre l'image dans le flux avec le format demandé. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Enregistre l'image dans le flux avec le format demandé. |
| [save](#save-java.io.OutputStream-int-) | Enregistre l'image dans le flux avec le format demandé et la résolution spécifiée. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-) | Enregistre l'image dans le flux avec le format demandé. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | Enregistre les données de l'image dans le flux en tant qu'image JPEG avec la résolution spécifiée. |
| [setName](#setName-java.lang.String-) | Définit le nom de l'image. Veuillez noter que si vous modifiez le nom de l'image qui possède des références dans le contenu des pages, le document peut devenir incorrect. Veuillez utiliser la méthode XImage.Rename dans ce cas. |
| [toStream](#toStream--) | Renvoie le flux d'image original. |
| [toString](#toString--) | Renvoie une représentation sous forme de chaîne des propriétés de l'objet XImage. |
| [trySetAlternativeText](#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-) | Définit le texte alternatif pour un XImage sur la page. |

### XImage {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
pour usage interne uniquement

### addStencilMask {#addStencilMask-java.io.InputStream-}
Ajoute un masque pochoir à l'XImage.

### containsTransparency {#containsTransparency--}
```
public boolean containsTransparency()
```

Si l'image contient de la transparence alors renvoie true ; sinon false.

**Returns:**
valeur booléenne

### delete {#delete--}
```
public void delete()
```

Supprime l'image de la collection parent.

### detectColorType {#detectColorType-java.awt.image.BufferedImage-}
Renvoie le type de couleur de l'image.

### getAlternativeText {#getAlternativeText-com.aspose.pdf.Page-}
Renvoie une liste de chaînes avec le texte alternatif pour un XImage.

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Renvoie le type de couleur de l'image.

**Returns:**
La valeur du type de couleur.

### getEngineImg {#getEngineImg--}
```
public com.aspose.pdf.engine.data.IPdfDataStream getEngineImg()
```

Objet IPdfImage qui décrit l'image. Usage interne uniquement

**Returns:**
IPdfDataStream

### getFilterType {#getFilterType--}
```
public final ImageFilterType getFilterType()
```

Obtient le type de filtre d'image.

**Returns:**
Élément ImageFilterType

### getGrayscaled {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```

Obtient la version en niveaux de gris de l'image.

**Returns:**
BufferedImage

### getHeight {#getHeight--}
```
public int getHeight()
```

Obtient la hauteur de l'image.

**Returns:**
valeur int

### getImage {#getImage--}
```
public com.aspose.ms.System.Drawing.Bitmap getImage()
```

Pour usage interne uniquement

**Returns:**
Image

### getMetadata {#getMetadata--}
```
public final Metadata getMetadata()
```

Métadonnées de l'image.

**Returns:**
Instance Metadata

### getName {#getName--}
```
public String getName()
```

Obtient le nom de l'image. Veuillez noter que si vous changez le nom de l'image qui possède des références dans le contenu des pages, le document peut devenir incorrect. Veuillez utiliser la méthode XImage.Rename dans ce cas.

**Returns:**
Chaîne

### getNameInCollection {#getNameInCollection--}
```
public String getNameInCollection()
```

Renvoie le nom de l'image dans sa collection.

**Returns:**
Clé d'image (nom).

### getRawBytes {#getRawBytes--}
```
public byte[] getRawBytes()
```

Renvoie les octets bruts de l'image sans décodage.

**Returns:**
tableau d'octets

### getRawImageData {#getRawImageData--}
```
public final byte[] getRawImageData()
```

Récupère les données brutes de l'image à partir de l'image source.

**Returns:**
Un {@link byte[]} contenant les données d'image originales.

### getRawParameters {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```

Obtient les paramètres bruts de l'image

**Returns:**
instance RawParameters

### getWidth {#getWidth--}
```
public int getWidth()
```

Obtient la largeur de l'image.

**Returns:**
valeur int

### isImage {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
Renvoie true si le primitive est une image.

### isImageMask {#isImageMask--}
```
public final boolean isImageMask()
```

Obtient un indicateur indiquant si l'image doit être traitée comme un masque d'image (voir 8.9.6, "Masked Images"). Si cet indicateur est true, la valeur de BitsPerComponent doit être 1 et Mask et ColorSpace ne doivent pas être spécifiés ; les zones non masquées doivent être peintes en utilisant la couleur de tracé actuelle. Valeur par défaut : false. Valeur : True si l'image est un masque d'image.

**Returns:**
valeur booléenne

### isTheSameObject {#isTheSameObject-com.aspose.pdf.XImage-}
Renvoie true si les deux images font référence au même objet.

### rename {#rename-java.lang.String-}
Renomme l'image et remplace toutes les références à l'image par le nouveau nom

### replace {#replace-java.io.InputStream-}
Remplace l'image dans le flux spécifié dans {@code image}. *

### save {#save-java.io.OutputStream-}
Enregistre les données de l'image dans le flux en tant qu'image JPEG.

### save {#save-java.io.OutputStream-float-float-}
Enregistre l'image dans le flux avec le format demandé.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Enregistre l'image dans le flux avec le format demandé.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Enregistre l'image dans le flux avec le format demandé.

### save {#save-java.io.OutputStream-int-}
Enregistre l'image dans le flux avec le format demandé et la résolution spécifiée.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-}
Enregistre l'image dans le flux avec le format demandé.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}


### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
Enregistre les données de l'image dans le flux en tant qu'image JPEG avec la résolution spécifiée.

### setName {#setName-java.lang.String-}
Définit le nom de l'image. Veuillez noter que si vous modifiez le nom de l'image qui possède des références dans le contenu des pages, le document peut devenir incorrect. Veuillez utiliser la méthode XImage.Rename dans ce cas.

### toStream {#toStream--}
```
public InputStream toStream()
```

Renvoie le flux d'image original.

**Returns:**
Le flux d'image original.

### toString {#toString--}
```
public String toString()
```

Renvoie une représentation sous forme de chaîne des propriétés de l'objet XImage.

**Returns:**
instance String

### trySetAlternativeText {#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-}
Définit le texte alternatif pour un XImage sur la page.
