---
title: "TiffDevice"
linktitle: "TiffDevice"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Questa classe aiuta a salvare le pagine del documento pdf una per una in un'unica immagine tiff."
type: docs
weight: 210
url: /it/java/com.aspose.pdf.devices/tiffdevice/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.devices.Device com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.Device, com.aspose.pdf.devices.PageDevice com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.PageDevice, com.aspose.pdf.devices.DocumentDevice com.aspose.pdf.devices.TiffDevice, com.aspose.pdf.devices.DocumentDevice, com.aspose.pdf.devices.TiffDevice

```
public final class TiffDevice extends DocumentDevice
```

Questa classe aiuta a salvare le pagine del documento pdf una per una in un'unica immagine tiff.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [TiffDevice](#TiffDevice--) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-int-int-) | Inizializza una nuova istanza della classe {@code TiffDevice}. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |
| [TiffDevice](#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [binarizeBradley](#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-) | Esegue la binarizzazione Bradley per lo stream di input. |
| [getCropRectangle](#getCropRectangle--) | Ottieni il rettangolo che definisce l'area che sarà convertita in un'immagine. Il valore predefinito è null, nel qual caso l'intera immagine viene convertita in una pagina |
| [getFormPresentationMode](#getFormPresentationMode--) | Ottiene la modalità di presentazione del modulo. |
| [getHeight](#getHeight--) | Ottiene l'altezza dell'output dell'immagine. |
| [getRenderingOptions](#getRenderingOptions--) | Ottiene le opzioni di rendering. |
| [getResolution](#getResolution--) | Ottiene la risoluzione dell'immagine. |
| [getSettings](#getSettings--) | Ottiene le impostazioni per la mappatura del PDF in immagine TIFF. |
| [getWidth](#getWidth--) | Ottiene la larghezza dell'output dell'immagine. |
| [process](#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-) | Converte alcune pagine del documento in TIFF e le salva nello stream di output. |
| [processInternal](#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-) | Converte alcune pagine del documento in TIFF e le salva nello stream di output. |
| [processInternal](#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-) | Esegue qualche operazione sulla pagina fornita, ad es. |
| [setCropRectangle](#setCropRectangle-com.aspose.pdf.Rectangle-) | Imposta il rettangolo che definisce l'area che sarà convertita in un'immagine. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Ottiene la modalità di presentazione del modulo. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Imposta le opzioni di rendering. |

### TiffDevice {#TiffDevice--}
```
public TiffDevice()
```

Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-int-int-}
```
public TiffDevice(int width, int height)
```

Inizializza una nuova istanza della classe {@code TiffDevice}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Larghezza dell'output dell'immagine. |
| altezza |  | Altezza dell'output dell'immagine. |

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.Resolution-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### TiffDevice {#TiffDevice-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Inizializza una nuova istanza della classe {@code TiffDevice} con le impostazioni predefinite.

### binarizeBradley {#binarizeBradley-java.io.InputStream-java.io.OutputStream-double-}
Esegue la binarizzazione Bradley per lo stream di input.

### getCropRectangle {#getCropRectangle--}
```
public Rectangle getCropRectangle()
```

Ottieni il rettangolo che definisce l'area che sarà convertita in un'immagine. Il valore predefinito è null, nel qual caso l'intera immagine viene convertita in una pagina

**Returns:**
oggetto Rectangle

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Ottiene la modalità di presentazione del modulo.

**Returns:**
Valore FormPresentationMode @see FormPresentationMode

### getHeight {#getHeight--}
```
public int getHeight()
```

Ottiene l'altezza dell'output dell'immagine.

**Returns:**
valore int

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Ottiene le opzioni di rendering.

**Returns:**
opzioni di rendering.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Ottiene la risoluzione dell'immagine.

**Returns:**
Elemento Resolution

### getSettings {#getSettings--}
```
public TiffSettings getSettings()
```

Ottiene le impostazioni per la mappatura del PDF in immagine TIFF.

**Returns:**
Elemento TiffSettings

### getWidth {#getWidth--}
```
public int getWidth()
```

Ottiene la larghezza dell'output dell'immagine.

**Returns:**
valore int

### process {#process-com.aspose.pdf.IDocument-int-int-java.io.OutputStream-}
Converte alcune pagine del documento in TIFF e le salva nello stream di output.

### processInternal {#processInternal-com.aspose.pdf.IDocument-int-int-com.aspose.ms.System.IO.Stream-}
Converte alcune pagine del documento in TIFF e le salva nello stream di output.

### processInternal {#processInternal-com.aspose.pdf.Page-com.aspose.ms.System.IO.Stream-}
Esegue qualche operazione sulla pagina fornita, ad es.

### setCropRectangle {#setCropRectangle-com.aspose.pdf.Rectangle-}
Imposta il rettangolo che definisce l'area che sarà convertita in un'immagine.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Ottiene la modalità di presentazione del modulo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int @see FormPresentationMode |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Imposta le opzioni di rendering.
