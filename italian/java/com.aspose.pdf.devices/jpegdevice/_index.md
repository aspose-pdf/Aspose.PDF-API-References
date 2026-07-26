---
title: "JpegDevice"
linktitle: "JpegDevice"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf in jpeg."
type: docs
weight: 130
url: /it/java/com.aspose.pdf.devices/jpegdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.JpegDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.JpegDevice

```
public final class JpegDevice extends ImageDevice
```

Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf in jpeg.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [JpegDevice](#JpegDevice--) | Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima. |
| [JpegDevice](#JpegDevice-int-) | Inizializza una nuova istanza della classe {@code JpegDevice}. |
| [JpegDevice](#JpegDevice-int-int-) | Inizializza una nuova istanza della classe {@code JpegDevice} con le dimensioni dell'immagine fornite, risoluzione predefinita (=150) e qualità massima. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima. |
| [JpegDevice](#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-) | Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-) | Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-) | Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima. |
| [JpegDevice](#JpegDevice-com.aspose.pdf.devices.Resolution-int-) | Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converte la pagina in jpeg e la salva nello stream di output. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converte la pagina in jpeg e la salva nello stream di output. |

### JpegDevice {#JpegDevice--}
```
public JpegDevice()
```

Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima.

### JpegDevice {#JpegDevice-int-}
```
public JpegDevice(int quality)
```

Inizializza una nuova istanza della classe {@code JpegDevice}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| qualità |  | Specifica il livello di compressione per un'immagine. L'intervallo di valori utili per la qualità è da 0 a 100. Più basso è il numero specificato, maggiore è la compressione e quindi più bassa è la qualità dell'immagine. Zero fornisce l'immagine di qualità più bassa e 100 la più alta. |

### JpegDevice {#JpegDevice-int-int-}
```
public JpegDevice(int width, int height)
```

Inizializza una nuova istanza della classe {@code JpegDevice} con le dimensioni dell'immagine fornite, risoluzione predefinita (=150) e qualità massima.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Larghezza dell'output dell'immagine. |
| altezza |  | Altezza dell'output dell'immagine. |

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima.

### JpegDevice {#JpegDevice-int-int-com.aspose.pdf.devices.Resolution-int-}
Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-}
Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima.

### JpegDevice {#JpegDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-int-}
Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima.

### JpegDevice {#JpegDevice-com.aspose.pdf.devices.Resolution-int-}
Inizializza una nuova istanza della classe {@code JpegDevice} con risoluzione predefinita e qualità massima.

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converte la pagina in jpeg e la salva nello stream di output.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Converte la pagina in jpeg e la salva nello stream di output.
