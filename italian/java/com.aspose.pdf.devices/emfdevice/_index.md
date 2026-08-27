---
title: "EmfDevice"
linktitle: "EmfDevice"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf in emf."
type: docs
weight: 70
url: /it/java/com.aspose.pdf.devices/emfdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.EmfDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.EmfDevice

```
public final class EmfDevice extends ImageDevice
```

Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf in emf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [EmfDevice](#EmfDevice--) | Inizializza una nuova istanza della classe {@code EmfDevice} con la risoluzione predefinita dell'immagine raster scritta in emf. |
| [EmfDevice](#EmfDevice-int-int-) | Inizializza una nuova istanza della classe {@code EmfDevice} con le dimensioni dell'immagine fornite e la risoluzione predefinita per l'immagine raster scritta in emf (=150) |
| [EmfDevice](#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code EmfDevice} con la risoluzione predefinita dell'immagine raster scritta in emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-) | Inizializza una nuova istanza della classe {@code EmfDevice} con la risoluzione predefinita dell'immagine raster scritta in emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code EmfDevice} con la risoluzione predefinita dell'immagine raster scritta in emf. |
| [EmfDevice](#EmfDevice-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code EmfDevice} con la risoluzione predefinita dell'immagine raster scritta in emf. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converte la pagina in emf e la salva nel flusso di output. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converte la pagina in emf e la salva nel flusso di output. |

### EmfDevice {#EmfDevice--}
```
public EmfDevice()
```

Inizializza una nuova istanza della classe {@code EmfDevice} con la risoluzione predefinita dell'immagine raster scritta in emf.

### EmfDevice {#EmfDevice-int-int-}
```
public EmfDevice(int width, int height)
```

Inizializza una nuova istanza della classe {@code EmfDevice} con le dimensioni dell'immagine fornite e la risoluzione predefinita per l'immagine raster scritta in emf (=150)

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Larghezza dell'output dell'immagine. |
| altezza |  | Altezza dell'output dell'immagine. |

### EmfDevice {#EmfDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code EmfDevice} con la risoluzione predefinita dell'immagine raster scritta in emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-}
Inizializza una nuova istanza della classe {@code EmfDevice} con la risoluzione predefinita dell'immagine raster scritta in emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code EmfDevice} con la risoluzione predefinita dell'immagine raster scritta in emf.

### EmfDevice {#EmfDevice-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code EmfDevice} con la risoluzione predefinita dell'immagine raster scritta in emf.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converte la pagina in emf e la salva nel flusso di output.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Converte la pagina in emf e la salva nel flusso di output.
