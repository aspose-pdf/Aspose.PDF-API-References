---
title: "ThumbnailDevice"
linktitle: "ThumbnailDevice"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un dispositivo immagine che salva le pagine del documento pdf in un'immagine Thumbnail."
type: docs
weight: 200
url: /it/java/com.aspose.pdf.devices/thumbnaildevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.ImageDevice com.aspose.pdf.devices.ThumbnailDevice, com.aspose.pdf.devices.ImageDevice, com.aspose.pdf.devices.ThumbnailDevice

```
public final class ThumbnailDevice extends ImageDevice
```

Rappresenta un dispositivo immagine che salva le pagine del documento pdf in un'immagine Thumbnail.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ThumbnailDevice](#ThumbnailDevice--) | Inizializza una nuova istanza della classe {@link ThumbnailDevice} con la dimensione predefinita dell'immagine miniatura (200x200 pixel). |
| [ThumbnailDevice](#ThumbnailDevice-int-int-) | Inizializza una nuova istanza della classe {@link ThumbnailDevice}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [processInternal](#processInternal-com.aspose.pdf.Page-java.io.OutputStream-) | Converte la pagina in un'immagine miniatura png e la salva nello stream di output. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Esegue qualche operazione sulla pagina fornita, ad es. |

### ThumbnailDevice {#ThumbnailDevice--}
```
public ThumbnailDevice()
```

Inizializza una nuova istanza della classe {@link ThumbnailDevice} con la dimensione predefinita dell'immagine miniatura (200x200 pixel).

### ThumbnailDevice {#ThumbnailDevice-int-int-}
```
public ThumbnailDevice(int width, int height)
```

Inizializza una nuova istanza della classe {@link ThumbnailDevice}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Larghezza di output dell'immagine miniatura. |
| altezza |  | Altezza di output dell'immagine miniatura. |

### processInternal {#processInternal-com.aspose.pdf.Page-java.io.OutputStream-}
Converte la pagina in un'immagine miniatura png e la salva nello stream di output.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Esegue qualche operazione sulla pagina fornita, ad es.
