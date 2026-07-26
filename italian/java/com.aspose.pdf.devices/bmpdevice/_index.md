---
title: "BmpDevice"
linktitle: "BmpDevice"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un dispositivo immagine che aiuta a salvare le pagine di un documento PDF in BMP."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.devices/bmpdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.BmpDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.BmpDevice

```
public final class BmpDevice extends ImageDevice
```

Rappresenta un dispositivo immagine che aiuta a salvare le pagine di un documento PDF in BMP.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [BmpDevice](#BmpDevice--) | Inizializza una nuova istanza della classe {@code BmpDevice} con risoluzione predefinita. |
| [BmpDevice](#BmpDevice-int-int-) | Inizializza una nuova istanza della classe {@code BmpDevice} con le dimensioni dell'immagine fornite, risoluzione predefinita (=150). |
| [BmpDevice](#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code BmpDevice} con risoluzione predefinita. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-) | Inizializza una nuova istanza della classe {@code BmpDevice} con risoluzione predefinita. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code BmpDevice} con risoluzione predefinita. |
| [BmpDevice](#BmpDevice-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code BmpDevice} con risoluzione predefinita. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-) | renderizza la pagina sul dispositivo grafico. |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converte la pagina in bmp e la salva nello stream di output. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Solo per uso interno! |

### BmpDevice {#BmpDevice--}
```
public BmpDevice()
```

Inizializza una nuova istanza della classe {@code BmpDevice} con risoluzione predefinita.

### BmpDevice {#BmpDevice-int-int-}
```
public BmpDevice(int width, int height)
```

Inizializza una nuova istanza della classe {@code BmpDevice} con le dimensioni dell'immagine fornite, risoluzione predefinita (=150).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Larghezza dell'output dell'immagine. |
| altezza |  | Altezza dell'output dell'immagine. |

### BmpDevice {#BmpDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code BmpDevice} con risoluzione predefinita.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-}
Inizializza una nuova istanza della classe {@code BmpDevice} con risoluzione predefinita.

### BmpDevice {#BmpDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code BmpDevice} con risoluzione predefinita.

### BmpDevice {#BmpDevice-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code BmpDevice} con risoluzione predefinita.

### process {#process-com.aspose.pdf.Page-com.aspose.ms.System.Drawing.Graphics-}
renderizza la pagina sul dispositivo grafico.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converte la pagina in bmp e la salva nello stream di output.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Solo per uso interno!
