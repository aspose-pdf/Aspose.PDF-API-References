---
title: "EmfDevice"
linktitle: "EmfDevice"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format emf."
type: docs
weight: 70
url: /fr/java/com.aspose.pdf.devices/emfdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.EmfDevice

```
public final class EmfDevice extends ImageDevice
```

Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format emf.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [EmfDevice](#EmfDevice--) | Initialise une nouvelle instance de la classe {@code EmfDevice} avec la résolution par défaut de l'image raster écrite en emf. |
| [EmfDevice](#EmfDevice-int-int-) | Initialise une nouvelle instance de la classe {@code EmfDevice} avec les dimensions d'image fournies, et la résolution par défaut pour l'image raster écrite en emf (=150). |
| [EmfDevice](#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code EmfDevice} avec la résolution par défaut de l'image raster écrite en emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-) | Initialise une nouvelle instance de la classe {@code EmfDevice} avec la résolution par défaut de l'image raster écrite en emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code EmfDevice} avec la résolution par défaut de l'image raster écrite en emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@code EmfDevice} avec la résolution par défaut de l'image raster écrite en emf. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convertit la page en emf et l'enregistre dans le flux de sortie. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Convertit la page en emf et l'enregistre dans le flux de sortie. |

### EmfDevice {#EmfDevice--}
```
public EmfDevice()
```

Initialise une nouvelle instance de la classe {@code EmfDevice} avec la résolution par défaut de l'image raster écrite en emf.

### EmfDevice {#EmfDevice-int-int-}
```
public EmfDevice(int width, int height)
```

Initialise une nouvelle instance de la classe {@code EmfDevice} avec les dimensions d'image fournies, et la résolution par défaut pour l'image raster écrite en emf (=150).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Largeur de sortie de l'image. |
| hauteur |  | Hauteur de sortie de l'image. |

### EmfDevice {#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code EmfDevice} avec la résolution par défaut de l'image raster écrite en emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-}
Initialise une nouvelle instance de la classe {@code EmfDevice} avec la résolution par défaut de l'image raster écrite en emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code EmfDevice} avec la résolution par défaut de l'image raster écrite en emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@code EmfDevice} avec la résolution par défaut de l'image raster écrite en emf.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Convertit la page en emf et l'enregistre dans le flux de sortie.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Convertit la page en emf et l'enregistre dans le flux de sortie.
