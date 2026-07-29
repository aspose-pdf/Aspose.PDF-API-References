---
title: "BmpDevice"
linktitle: "BmpDevice"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf au format bmp."
type: docs
weight: 10
url: /fr/java/com.aspose.pdf.devices/bmpdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.BmpDevice

```
public final class BmpDevice extends ImageDevice
```

Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf au format bmp.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [BmpDevice](#BmpDevice--) | Initialise une nouvelle instance de la classe {@code BmpDevice} avec la résolution par défaut. |
| [BmpDevice](#BmpDevice-int-int-) | Initialise une nouvelle instance de la classe {@code BmpDevice} avec les dimensions d'image fournies, résolution par défaut (=150). |
| [BmpDevice](#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code BmpDevice} avec la résolution par défaut. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-) | Initialise une nouvelle instance de la classe {@code BmpDevice} avec la résolution par défaut. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code BmpDevice} avec la résolution par défaut. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code BmpDevice} avec la résolution par défaut. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | rend la page sur le graphique |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convertit la page en bmp et l'enregistre dans le flux de sortie. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | À usage interne uniquement ! |

### BmpDevice {#BmpDevice--}
```
public BmpDevice()
```

Initialise une nouvelle instance de la classe {@code BmpDevice} avec la résolution par défaut.

### BmpDevice {#BmpDevice-int-int-}
```
public BmpDevice(int width, int height)
```

Initialise une nouvelle instance de la classe {@code BmpDevice} avec les dimensions d'image fournies, résolution par défaut (=150).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Largeur de sortie de l'image. |
| hauteur |  | Hauteur de sortie de l'image. |

### BmpDevice {#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code BmpDevice} avec la résolution par défaut.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-}
Initialise une nouvelle instance de la classe {@code BmpDevice} avec la résolution par défaut.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code BmpDevice} avec la résolution par défaut.

### BmpDevice {#BmpDevice-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code BmpDevice} avec la résolution par défaut.

### process {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
rend la page sur le graphique

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Convertit la page en bmp et l'enregistre dans le flux de sortie.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
À usage interne uniquement !
