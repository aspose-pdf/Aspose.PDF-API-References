---
title: "TiffDevice"
linktitle: "TiffDevice"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Cette classe aide à enregistrer les pages d'un document PDF une par une dans une seule image TIFF."
type: docs
weight: 210
url: /fr/java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.TiffDevice

```
public final class TiffDevice extends DocumentDevice
```

Cette classe aide à enregistrer les pages d'un document PDF une par une dans une seule image TIFF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [TiffDevice](#TiffDevice--) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-int-int-) | Initialise une nouvelle instance de la classe {@code TiffDevice}. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [binarizeBradley](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | Effectue la binarisation Bradley pour le flux d'entrée. |
| [getCropRectangle](#getCropRectangle--) | Obtient le rectangle qui définit la zone à convertir en image. La valeur par défaut est null, auquel cas l'image entière est convertie en page. |
| [getFormPresentationMode](#getFormPresentationMode--) | Obtient le mode de présentation du formulaire. |
| [getHeight](#getHeight--) | Obtient la hauteur de sortie de l'image. |
| [getRenderingOptions](#getRenderingOptions--) | Obtient les options de rendu. |
| [getResolution](#getResolution--) | Obtient la résolution de l'image. |
| [getSettings](#getSettings--) | Obtient les paramètres pour le mappage du PDF en image TIFF. |
| [getWidth](#getWidth--) | Obtient la largeur de sortie de l'image. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Convertit certaines pages du document en TIFF et les enregistre dans le flux de sortie. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Convertit certaines pages du document en TIFF et les enregistre dans le flux de sortie. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Effectue une opération sur la page donnée, par ex. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Définit le rectangle qui détermine la zone à convertir en image. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Obtient le mode de présentation du formulaire. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Définit les options de rendu. |

### TiffDevice {#TiffDevice--}
```
public TiffDevice()
```

Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```

Initialise une nouvelle instance de la classe {@code TiffDevice}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Largeur de sortie de l'image. |
| hauteur |  | Hauteur de sortie de l'image. |

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Initialise une nouvelle instance de la classe {@code TiffDevice} avec les paramètres par défaut.

### binarizeBradley {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
Effectue la binarisation Bradley pour le flux d'entrée.

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Obtient le rectangle qui définit la zone à convertir en image. La valeur par défaut est null, auquel cas l'image entière est convertie en page.

**Returns:**
objet Rectangle

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Obtient le mode de présentation du formulaire.

**Returns:**
Valeur FormPresentationMode @see FormPresentationMode

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
options de rendu.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Obtient la résolution de l'image.

**Returns:**
Élément de résolution

### getSettings {#getSettings--}
```
public TiffSettings getSettings()
```

Obtient les paramètres pour le mappage du PDF en image TIFF.

**Returns:**
Élément TiffSettings

### getWidth {#getWidth--}
```
public int getWidth()
```

Obtient la largeur de sortie de l'image.

**Returns:**
valeur int

### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Convertit certaines pages du document en TIFF et les enregistre dans le flux de sortie.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Convertit certaines pages du document en TIFF et les enregistre dans le flux de sortie.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Effectue une opération sur la page donnée, par ex.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Définit le rectangle qui détermine la zone à convertir en image.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Obtient le mode de présentation du formulaire.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur int @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Définit les options de rendu.
