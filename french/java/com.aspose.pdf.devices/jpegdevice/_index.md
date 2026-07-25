---
title: "JpegDevice"
linktitle: "JpegDevice"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format jpeg."
type: docs
weight: 130
url: /fr/java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.JpegDevice

```
public final class JpegDevice extends ImageDevice
```

Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format jpeg.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [JpegDevice](#JpegDevice--) | Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale. |
| [JpegDevice](#JpegDevice-int-) | Initialise une nouvelle instance de la classe {@code JpegDevice}. |
| [JpegDevice](#JpegDevice-int-int-) | Initialise une nouvelle instance de la classe {@code JpegDevice} avec les dimensions d'image fournies, la résolution par défaut (=150) et la qualité maximale. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-) | Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convertit la page en jpeg et l'enregistre dans le flux de sortie. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Convertit la page en jpeg et l'enregistre dans le flux de sortie. |

### JpegDevice {#JpegDevice--}
```
public JpegDevice()
```

Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale.

### JpegDevice {#JpegDevice-int-}
```
public JpegDevice(int quality)
```

Initialise une nouvelle instance de la classe {@code JpegDevice}.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| qualité |  | Spécifie le niveau de compression d'une image. La plage de valeurs utiles pour la qualité va de 0 à 100. Plus le nombre spécifié est bas, plus la compression est élevée et donc la qualité de l'image est moindre. Un zéro vous donnera l'image de la plus basse qualité et 100 la plus haute. |

### JpegDevice {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```

Initialise une nouvelle instance de la classe {@code JpegDevice} avec les dimensions d'image fournies, la résolution par défaut (=150) et la qualité maximale.

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Largeur de sortie de l'image. |
| hauteur |  | Hauteur de sortie de l'image. |

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale.

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-}
Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
Initialise une nouvelle instance de la classe {@code JpegDevice} avec la résolution par défaut et la qualité maximale.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Convertit la page en jpeg et l'enregistre dans le flux de sortie.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Convertit la page en jpeg et l'enregistre dans le flux de sortie.
