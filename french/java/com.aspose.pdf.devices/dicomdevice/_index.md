---
title: "DicomDevice"
linktitle: "DicomDevice"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format Dicom."
type: docs
weight: 50
url: /fr/java/com.aspose.pdf.devices/dicomdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.DicomDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.DicomDevice

```
public final class DicomDevice extends ImageDevice
```

Représente un dispositif d'image qui aide à enregistrer les pages de documents PDF au format Dicom.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DicomDevice](#DicomDevice--) | Initialise une nouvelle instance de la classe {@link DicomDevice} avec la résolution par défaut. |
| [DicomDevice](#DicomDevice-int-int-) | Initialise une nouvelle instance de la classe {@link DicomDevice} avec les dimensions d'image fournies, avec la résolution par défaut (=150). |
| [DicomDevice](#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@link DicomDevice} avec la résolution par défaut. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-) | Initialise une nouvelle instance de la classe {@link DicomDevice} avec la résolution par défaut. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@link DicomDevice} avec la résolution par défaut. |
| [DicomDevice](#DicomDevice-com.aspose.pdf.devices.Resolution-) | Initialise une nouvelle instance de la classe {@link DicomDevice} avec la résolution par défaut. |

## Méthodes

| Méthode | Description |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Convertit la page en Dicom et l'enregistre dans le flux de sortie. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Effectue une opération sur la page donnée, par ex. |

### DicomDevice {#DicomDevice--}
```
public DicomDevice()
```

Initialise une nouvelle instance de la classe {@link DicomDevice} avec la résolution par défaut.

### DicomDevice {#DicomDevice-int-int-}
```
public DicomDevice(int width, int height)
```

Initialise une nouvelle instance de la classe {@link DicomDevice} avec les dimensions d'image fournies, avec la résolution par défaut (=150).

**Parameters:**
| Paramètre | Type | Description |
| --- | --- | --- |
| largeur |  | Largeur de sortie de l'image. |
| hauteur |  | Hauteur de sortie de l'image. |

### DicomDevice {#DicomDevice-int-int-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@link DicomDevice} avec la résolution par défaut.

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-}
Initialise une nouvelle instance de la classe {@link DicomDevice} avec la résolution par défaut.

### DicomDevice {#DicomDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@link DicomDevice} avec la résolution par défaut.

### DicomDevice {#DicomDevice-com.aspose.pdf.devices.Resolution-}
Initialise une nouvelle instance de la classe {@link DicomDevice} avec la résolution par défaut.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Convertit la page en Dicom et l'enregistre dans le flux de sortie.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Effectue une opération sur la page donnée, par ex.
