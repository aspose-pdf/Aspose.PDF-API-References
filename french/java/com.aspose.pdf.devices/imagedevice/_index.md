---
title: "ImageDevice"
linktitle: "ImageDevice"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Une classe abstraite pour les dispositifs d'image."
type: docs
weight: 110
url: /fr/java/com.aspose.pdf.devices/imagedevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice

```
public abstract class ImageDevice extends PageDevice
```

Une classe abstraite pour les dispositifs d'image.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ImageDevice](#ImageDevice--) | Initialiseur abstrait pour les descendants {@code ImageDevice}, définit la résolution à 150x150. |
| [ImageDevice](#ImageDevice-int-int-) | Initialise une nouvelle instance de la classe {@code JpegDevice} avec les dimensions d'image fournies et la résolution par défaut (=150). |
| [ImageDevice](#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialiseur abstrait pour les descendants {@code ImageDevice}, définit la résolution à 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-) | Initialiseur abstrait pour les descendants {@code ImageDevice}, définit la résolution à 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialiseur abstrait pour les descendants {@code ImageDevice}, définit la résolution à 150x150. |
| [ImageDevice](#ImageDevice-com.aspose.pdf.devices.Resolution-) | Initialiseur abstrait pour les descendants {@code ImageDevice}, définit la résolution à 150x150. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [getBitmap](#getBitmap-com.aspose.pdf.Page-) | Convertit la page en {@link java.awt.image.BufferedImage}. |
| [getCoordinateType](#getCoordinateType--) | Obtient le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [getCropRectangle](#getCropRectangle--) | Obtient le rectangle qui définit la zone à convertir en image. La valeur par défaut est null, auquel cas toute la page est convertie en image. |
| [getFormPresentationMode](#getFormPresentationMode--) | Obtient le mode de présentation du formulaire. |
| [getHeight](#getHeight--) | Obtient la hauteur de sortie de l'image. |
| [getRenderingOptions](#getRenderingOptions--) | Obtient les options de rendu. |
| [getResolution](#getResolution--) | Obtient la résolution de l'image. |
| [getWidth](#getWidth--) | Obtient la largeur de sortie de l'image. |
| [isShadingPerformanceHigh](#isShadingPerformanceHigh--) | Indique si la performance des processus d’ombrage est élevée. Par défaut, c’est vrai. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Définit le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Définit le rectangle qui détermine la zone à convertir en image. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Définit le mode de présentation du formulaire. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Définit les options de rendu. |
| [setShadingPerformanceHigh](#setShadingPerformanceHigh-boolean-) | Définit si la performance des processus d’ombrage est élevée ou non. |

### ImageDevice {#ImageDevice--}
```
public ImageDevice()
```

Initialiseur abstrait pour les descendants {@code ImageDevice}, définit la résolution à 150x150.

### ImageDevice {#ImageDevice-int-int-}
```
public ImageDevice(int width, int height)
```

Initialise une nouvelle instance de la classe {@code JpegDevice} avec les dimensions d'image fournies et la résolution par défaut (=150).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Largeur de sortie de l'image. |
| hauteur |  | Hauteur de sortie de l'image. |

### ImageDevice {#ImageDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialiseur abstrait pour les descendants {@code ImageDevice}, définit la résolution à 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-}
Initialiseur abstrait pour les descendants {@code ImageDevice}, définit la résolution à 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialiseur abstrait pour les descendants {@code ImageDevice}, définit la résolution à 150x150.

### ImageDevice {#ImageDevice-com.aspose.pdf.devices.Resolution-}
Initialiseur abstrait pour les descendants {@code ImageDevice}, définit la résolution à 150x150.

### getBitmap {#getBitmap-com.aspose.pdf.Page-}
Convertit la page en {@link java.awt.image.BufferedImage}.

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Obtient le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut.

**Returns:**
PageCoordinateType élément @see PageCoordinateType

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Obtient le rectangle qui définit la zone à convertir en image. La valeur par défaut est null, auquel cas toute la page est convertie en image.

**Returns:**
objet Rectangle

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Obtient le mode de présentation du formulaire.

**Returns:**
FormPresentationMode élément @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

Obtient la hauteur de sortie de l'image.

**Returns:**
valeur int

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Obtient les options de rendu.

**Returns:**
RenderingOptions élément

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Obtient la résolution de l'image.

**Returns:**
Élément de résolution

### getWidth {#getWidth--}
```
public int getWidth()
```

Obtient la largeur de sortie de l'image.

**Returns:**
valeur int

### isShadingPerformanceHigh {#isShadingPerformanceHigh--}
```
public static boolean isShadingPerformanceHigh()
```

Indique si la performance des processus d’ombrage est élevée. Par défaut, c’est vrai.

**Returns:**
valeur booléenne

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Définit le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Définit le rectangle qui détermine la zone à convertir en image.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Définit le mode de présentation du formulaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | FormPresentationMode élément @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Définit les options de rendu.

### setShadingPerformanceHigh {#setShadingPerformanceHigh-boolean-}
```
public static void setShadingPerformanceHigh(boolean value)
```

Définit si la performance des processus d’ombrage est élevée ou non.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
