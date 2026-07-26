---
title: "PngDevice"
linktitle: "PngDevice"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf in png."
type: docs
weight: 160
url: /it/java/com.aspose.pdf.devices/pngdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.PngDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.PngDevice

```
public final class PngDevice extends ImageDevice
```

Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf in png.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [PngDevice](#PngDevice--) | Inizializza una nuova istanza della classe {@code PngDevice} con risoluzione predefinita. |
| [PngDevice](#PngDevice-int-int-) | Inizializza una nuova istanza della classe {@code PngDevice} con le dimensioni dell'immagine fornite, risoluzione predefinita (=150). |
| [PngDevice](#PngDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code PngDevice} con risoluzione predefinita. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-) | Inizializza una nuova istanza della classe {@code PngDevice} con risoluzione predefinita. |
| [PngDevice](#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code PngDevice} con risoluzione predefinita. |
| [PngDevice](#PngDevice-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code PngDevice} con risoluzione predefinita. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [isTransparentBackground](#isTransparentBackground--) | Ottiene o imposta se l'immagine ha uno sfondo trasparente. |
| [process](#process-com.aspose.pdf.Page-java.io.OutputStream-) | Converte la pagina in png e la salva nello stream di output. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Converte la pagina in png e la salva nello stream di output. |
| [processToBufferedImage](#processToBufferedImage-com.aspose.pdf.Page-) | Converte la pagina in BufferedImage. |
| [processToBufferedImageBinarized](#processToBufferedImageBinarized-com.aspose.pdf.Page-double-) | Converte la pagina in BufferedImage con binarizzazione Bradley. |
| [setTransparentBackground](#setTransparentBackground-boolean-) | Ottiene o imposta se l'immagine ha uno sfondo trasparente. |

### PngDevice {#PngDevice--}
```
public PngDevice()
```

Inizializza una nuova istanza della classe {@code PngDevice} con risoluzione predefinita.

### PngDevice {#PngDevice-int-int-}
```
public PngDevice(int width, int height)
```

Inizializza una nuova istanza della classe {@code PngDevice} con le dimensioni dell'immagine fornite, risoluzione predefinita (=150).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Larghezza dell'output dell'immagine. |
| altezza |  | Altezza dell'output dell'immagine. |

### PngDevice {#PngDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code PngDevice} con risoluzione predefinita.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-}
Inizializza una nuova istanza della classe {@code PngDevice} con risoluzione predefinita.

### PngDevice {#PngDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code PngDevice} con risoluzione predefinita.

### PngDevice {#PngDevice-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code PngDevice} con risoluzione predefinita.

### isTransparentBackground {#isTransparentBackground--}
```
public final boolean isTransparentBackground()
```

Ottiene o imposta se l'immagine ha uno sfondo trasparente.

**Returns:**
valore booleano

### process {#process-com.aspose.pdf.Page-java.io.OutputStream-}
Converte la pagina in png e la salva nello stream di output.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Converte la pagina in png e la salva nello stream di output.

### processToBufferedImage {#processToBufferedImage-com.aspose.pdf.Page-}
Converte la pagina in BufferedImage.

### processToBufferedImageBinarized {#processToBufferedImageBinarized-com.aspose.pdf.Page-double-}
Converte la pagina in BufferedImage con binarizzazione Bradley.

### setTransparentBackground {#setTransparentBackground-boolean-}
```
public final void setTransparentBackground(boolean value)
```

Ottiene o imposta se l'immagine ha uno sfondo trasparente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
