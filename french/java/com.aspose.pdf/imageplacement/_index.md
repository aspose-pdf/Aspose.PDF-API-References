---
title: "ImagePlacement"
linktitle: "ImagePlacement"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "<p> Représente les caractéristiques d'une image placée sur une page de document Pdf. </p> <hr> <pre> L'exemple montre comment trouver des images sur la première page du document PDF et obtenir les images."
type: docs
weight: 2330
url: /fr/java/com.aspose.pdf/imageplacement/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ImagePlacement

```
public final class ImagePlacement extends Object
```

<p> Représente les caractéristiques d'une image placée sur une page de document Pdf. </p> <hr> <pre> L'exemple montre comment trouver des images sur la première page du document PDF et obtenir les images sous forme de bitmaps avec des dimensions visibles. // Ouvrir le document Document doc = new Document("D:\\Tests\\input.pdf"); // Créer l'objet ImagePlacementAbsorber pour effectuer la recherche de placement d'image ImagePlacementAbsorber abs = new ImagePlacementAbsorber(); // Accepter l'absorbeur pour la première page doc.getPages().get_Item(1).accept(abs); // Récupérer les images avec des dimensions visibles for (ImagePlacement imagePlacement : {@code (Iterable<ImagePlacement>)}abs.getImagePlacements()) { BufferedImage scaledImage; ByteArrayOutputStream imageStream = new ByteArrayOutputStream()) // Récupérer l'image depuis les ressources imagePlacement.getImage().save(imageStream, ImageFormatInternal.Png); BufferedImage resourceImage = (BufferedImage) ImageIO.read(imageStream); // Créer un nouveau bitmap avec les dimensions réelles scaledImage = new BufferedImage(resourceImage, (int)imagePlacement.getRectangle().getWidth(), (int)imagePlacement.getRectangle().getHeight()); } </pre> <hr> <p> Lorsqu'une image est placée sur une page, elle peut avoir des dimensions différentes des dimensions physiques définies dans {@code Resources}. L'objet {@code ImagePlacement} est destiné à fournir de telles informations comme les dimensions, la résolution et ainsi de suite. </p>

## Méthodes

| Méthode | Description |
| --- | --- |
| [getCompositingParameters](#getCompositingParameters--) | Obtient les paramètres de composition de l'état graphique actif pour l'image placée sur la page. |
| [getImage](#getImage--) | Obtient l'objet de ressource XImage associé. |
| [getMatrix](#getMatrix--) | Matrice de transformation actuelle pour cette image. |
| [getOperator](#getOperator--) | Opérateur utilisé pour afficher l'image. |
| [getPage](#getPage--) | Obtient la page contenant l'image. |
| [getRectangle](#getRectangle--) | Obtient le rectangle de l'image. |
| [getResolution](#getResolution--) | Obtient la résolution de l'image. |
| [getRotation](#getRotation--) | Obtient l'angle de rotation de l'image. |
| [hide](#hide--) | Supprimer l'image de la page. |
| [replace](#replace-java.io.InputStream-) | Remplacer l'image dans la collection par une autre image. |
| [save](#save-java.io.OutputStream-) | Enregistre l'image avec les transformations correspondantes : mise à l'échelle, rotation et résolution. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Enregistre l'image avec les transformations correspondantes : mise à l'échelle, rotation et résolution. |

### getCompositingParameters {#getCompositingParameters--}
```
public CompositingParameters getCompositingParameters()
```

Obtient les paramètres de composition de l'état graphique actif pour l'image placée sur la page.

**Returns:**
Objet CompositingParameters

### getImage {#getImage--}
```
public XImage getImage()
```

Obtient l'objet de ressource XImage associé.

**Returns:**
objet XImage

### getMatrix {#getMatrix--}
```
public Matrix getMatrix()
```

Matrice de transformation actuelle pour cette image.

**Returns:**
Objet Matrix

### getOperator {#getOperator--}
```
public final Operator getOperator()
```

Opérateur utilisé pour afficher l'image.

**Returns:**
Instance d'opérateur

### getPage {#getPage--}
```
public Page getPage()
```

Obtient la page contenant l'image.

**Returns:**
objet Page

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Obtient le rectangle de l'image.

**Returns:**
objet Rectangle

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Obtient la résolution de l'image.

**Returns:**
Objet Resolution

### getRotation {#getRotation--}
```
public float getRotation()
```

Obtient l'angle de rotation de l'image.

**Returns:**
valeur int

### hide {#hide--}
```
public final void hide()
```

Supprimer l'image de la page.

### replace {#replace-java.io.InputStream-}
Remplacer l'image dans la collection par une autre image.

### save {#save-java.io.OutputStream-}
Enregistre l'image avec les transformations correspondantes : mise à l'échelle, rotation et résolution.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Enregistre l'image avec les transformations correspondantes : mise à l'échelle, rotation et résolution.
