---
title: "ThumbnailDevice"
linktitle: "ThumbnailDevice"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un dispositif d'image qui enregistre les pages de documents PDF sous forme d'image miniature."
type: docs
weight: 200
url: /fr/java/com.aspose.pdf.devices/thumbnaildevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.ThumbnailDevice

```
public final class ThumbnailDevice extends ImageDevice
```

Représente un dispositif d'image qui enregistre les pages de documents PDF sous forme d'image miniature.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [ThumbnailDevice](#ThumbnailDevice--) | Initialise une nouvelle instance de la classe {@link ThumbnailDevice} avec la taille par défaut de l'image miniature (200 x 200 pixels). |
| [ThumbnailDevice](#ThumbnailDevice-int-int-) | Initialise une nouvelle instance de la classe {@link ThumbnailDevice}. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [processInternal](#processInternal-com.aspose.pdf.Page-java.io.OutputStream-) | Convertit la page en image miniature png et l'enregistre dans le flux de sortie. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Effectue une opération sur la page donnée, par ex. |

### ThumbnailDevice {#ThumbnailDevice--}
```
public ThumbnailDevice()
```

Initialise une nouvelle instance de la classe {@link ThumbnailDevice} avec la taille par défaut de l'image miniature (200 x 200 pixels).

### ThumbnailDevice {#ThumbnailDevice-int-int-}
```
public ThumbnailDevice(int width, int height)
```

Initialise une nouvelle instance de la classe {@link ThumbnailDevice}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Largeur de sortie de l'image miniature. |
| hauteur |  | Hauteur de sortie de l'image miniature. |

### processInternal {#processInternal-com.aspose.pdf.Page-java.io.OutputStream-}
Convertit la page en image miniature png et l'enregistre dans le flux de sortie.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Effectue une opération sur la page donnée, par ex.
