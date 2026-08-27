---
title: "PngDevice"
linktitle: "PngDevice"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format png."
type: docs
weight: 160
url: /fr/java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PngDevice

```
public final class PngDevice extends ImageDevice
```

Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format png.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [PngDevice](#PngDevice--) | Initialise une nouvelle instance de la classe {@code PngDevice} avec la résolution par défaut. |
| [PngDevice](#PngDevice-int-int-) | Initialise une nouvelle instance de la classe {@code PngDevice} avec les dimensions d'image fournies, résolution par défaut (=150). |
| [PngDevice](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code PngDevice} avec la résolution par défaut. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-) | Initialise une nouvelle instance de la classe {@code PngDevice} avec la résolution par défaut. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code PngDevice} avec la résolution par défaut. |
| [PngDevice](#PngDevice-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code PngDevice} avec la résolution par défaut. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [isTransparentBackground](#isTransparentBackground--) | Obtient ou définit si l'image possède un arrière-plan transparent. |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convertit la page en png et l'enregistre dans le flux de sortie. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Convertit la page en png et l'enregistre dans le flux de sortie. |
| [processToBufferedImage](#processToBufferedImage-com.aspose.pdf.Page-) | Convertit la page en BufferedImage. |
| [processToBufferedImageBinarized](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | Convertit la page en BufferedImage avec binarisation Bradley. |
| [setTransparentBackground](#setTransparentBackground-boolean-) | Obtient ou définit si l'image possède un arrière-plan transparent. |

### PngDevice {#PngDevice--}
```
public PngDevice()
```

Initialise une nouvelle instance de la classe {@code PngDevice} avec la résolution par défaut.

### PngDevice {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```

Initialise une nouvelle instance de la classe {@code PngDevice} avec les dimensions d'image fournies, résolution par défaut (=150).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Largeur de sortie de l'image. |
| hauteur |  | Hauteur de sortie de l'image. |

### PngDevice {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code PngDevice} avec la résolution par défaut.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-}
Initialise une nouvelle instance de la classe {@code PngDevice} avec la résolution par défaut.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code PngDevice} avec la résolution par défaut.

### PngDevice {#PngDevice-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code PngDevice} avec la résolution par défaut.

### isTransparentBackground {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```

Obtient ou définit si l'image possède un arrière-plan transparent.

**Returns:**
valeur booléenne

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Convertit la page en png et l'enregistre dans le flux de sortie.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Convertit la page en png et l'enregistre dans le flux de sortie.

### processToBufferedImage {#processToBufferedImage-com.aspose.pdf.Page-}
Convertit la page en BufferedImage.

### processToBufferedImageBinarized {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
Convertit la page en BufferedImage avec binarisation Bradley.

### setTransparentBackground {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```

Obtient ou définit si l'image possède un arrière-plan transparent.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| valeur |  | valeur booléenne |
