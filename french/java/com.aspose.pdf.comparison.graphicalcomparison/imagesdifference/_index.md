---
title: "ImagesDifference"
linktitle: "ImagesDifference"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente la classe de résultat de la comparaison de deux pages PDF."
type: docs
weight: 20
url: /fr/java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

Représente la classe de résultat de la comparaison de deux pages PDF.

## Méthodes

| Méthode | Description |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Convertit le tableau de différences en une image bitmap en utilisant les couleurs spécifiées. |
| [dispose](#dispose--) | Effectue toutes les opérations de nettoyage nécessaires avant que l'objet ne soit détruit. |
| [getDestinationImage](#getDestinationImage--) | Renvoie un nouveau bitmap représentant l'image de destination en appliquant le tableau de différences à l'image source. |
| [getDifference](#getDifference--) | Obtient le tableau de différences. Ce tableau est similaire au tableau de données d'image original obtenu à la suite de la méthode LockBits. |
| [getHeight](#getHeight--) | La hauteur de la différence. |
| [getSourceImage](#getSourceImage--) | Obtient l'image de la première page comparée. L'image a un format de pixel de 24 bpp. |
| [getStride](#getStride--) | Le pas des données d'image de différence. |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Convertit le tableau de différences en une image bitmap en utilisant les couleurs spécifiées.

### dispose {#dispose--}
```
public final void dispose()
```

Effectue toutes les opérations de nettoyage nécessaires avant que l'objet ne soit détruit.

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

Renvoie un nouveau bitmap représentant l'image de destination en appliquant le tableau de différences à l'image source.

**Returns:**
Une image de destination.

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

Obtient le tableau de différences. Ce tableau est similaire au tableau de données d'image original obtenu à la suite de la méthode LockBits.

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

La hauteur de la différence.

**Returns:**
valeur int

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

Obtient l'image de la première page comparée. L'image a un format de pixel de 24 bpp.

**Returns:**
BufferedImage instance

### getStride {#getStride--}
```
public final int getStride()
```

Le pas des données d'image de différence.

**Returns:**
valeur int
