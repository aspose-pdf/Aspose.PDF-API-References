---
title: "GifDevice"
linktitle: "GifDevice"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format gif."
type: docs
weight: 90
url: /fr/java/com.aspose.pdf.devices/gifdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.GifDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.GifDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.GifDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.GifDevice

```
public final class GifDevice extends ImageDevice
```

Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format gif.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [GifDevice](#GifDevice--) | Initialise une nouvelle instance de la classe {@code GifDevice} avec la résolution par défaut. |
| [GifDevice](#GifDevice-int-int-) | Initialise une nouvelle instance de la classe {@code GifDevice} avec les dimensions d’image fournies, résolution par défaut (=150). |
| [GifDevice](#GifDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code GifDevice} avec la résolution par défaut. |
| [GifDevice](#GifDevice-com.aspose.pdf.PageSize-) | Initialise une nouvelle instance de la classe {@code GifDevice} avec la résolution par défaut. |
| [GifDevice](#GifDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code GifDevice} avec la résolution par défaut. |
| [GifDevice](#GifDevice-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code GifDevice} avec la résolution par défaut. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convertit la page en gif et l’enregistre dans le flux de sortie. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Convertit la page en gif et l’enregistre dans le flux de sortie. |

### GifDevice {#GifDevice--}
```
public GifDevice()
```

Initialise une nouvelle instance de la classe {@code GifDevice} avec la résolution par défaut.

### GifDevice {#GifDevice-int-int-}
```
public GifDevice(int width, int height)
```

Initialise une nouvelle instance de la classe {@code GifDevice} avec les dimensions d’image fournies, résolution par défaut (=150).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Largeur de sortie de l'image. |
| hauteur |  | Hauteur de sortie de l'image. |

### GifDevice {#GifDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code GifDevice} avec la résolution par défaut.

### GifDevice {#GifDevice-com.aspose.pdf.PageSize-}
Initialise une nouvelle instance de la classe {@code GifDevice} avec la résolution par défaut.

### GifDevice {#GifDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code GifDevice} avec la résolution par défaut.

### GifDevice {#GifDevice-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code GifDevice} avec la résolution par défaut.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Convertit la page en gif et l’enregistre dans le flux de sortie.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Convertit la page en gif et l’enregistre dans le flux de sortie.
