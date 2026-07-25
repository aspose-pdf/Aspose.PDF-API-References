---
title: "DocumentDevice"
linktitle: "DocumentDevice"
second_title: "Référence de l'API Aspose.PDF pour Java"
description: "Classe abstraite pour tous les dispositifs utilisés pour traiter l'intégralité du document PDF."
type: docs
weight: 60
url: /fr/java/com.aspose.pdf.devices/documentdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice

```
public abstract class DocumentDevice extends PageDevice
```

Classe abstraite pour tous les dispositifs utilisés pour traiter l'intégralité du document PDF.

## Constructeurs

| Constructeur | Description |
| --- | --- |
| [DocumentDevice](#DocumentDevice--) |  |

## Méthodes

| Méthode | Description |
| --- | --- |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Chaque appareil représente une opération sur le document, par exemple nous pouvons convertir le document pdf en un autre format. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.lang.String-) | Traite certaines pages du document et enregistre les résultats dans un fichier. |
| [process](#process-com.aspose.pdf.IDocument-java.io.OutputStream-) | Traite l'intégralité du document et enregistre les résultats dans un flux. |
| [process](#process-com.aspose.pdf.IDocument-java.lang.String-) | Traite l'intégralité du document et enregistre les résultats dans un fichier. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Chaque appareil représente une opération sur le document, par exemple. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-) | Traite l'intégralité du document et enregistre les résultats dans un flux. |

### DocumentDevice {#DocumentDevice--}
```
public DocumentDevice()
```



### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Chaque appareil représente une opération sur le document, par exemple nous pouvons convertir le document pdf en un autre format.

### process {#process-com.aspose.pdf.IDocument-int-int-java.lang.String-}
Traite certaines pages du document et enregistre les résultats dans un fichier.

### process {#process-com.aspose.pdf.IDocument-java.io.OutputStream-}
Traite l'intégralité du document et enregistre les résultats dans un flux.

### process {#process-com.aspose.pdf.IDocument-java.lang.String-}
Traite l'intégralité du document et enregistre les résultats dans un fichier.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Chaque appareil représente une opération sur le document, par exemple.

### processInternal {#processInternal-com.aspose.pdf.IDocument-com.aspose.ms.System.IO.Stream-}
Traite l'intégralité du document et enregistre les résultats dans un flux.
