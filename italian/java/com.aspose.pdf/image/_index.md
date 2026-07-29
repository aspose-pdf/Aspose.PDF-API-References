---
title: "Image"
linktitle: "Image"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un'immagine."
type: docs
weight: 2280
url: /it/java/com.aspose.pdf/image/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.BaseParagraph com.aspose.pdf.Image, com.aspose.pdf.BaseParagraph, com.aspose.pdf.Image

**All Implemented Interfaces:**
com.aspose.ms.System.ICloneable

```
public final class Image extends BaseParagraph
```

Rappresenta un'immagine.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Image](#Image--) | costruttore predefinito |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [convertToJpeg](#convertToJpeg-java.io.InputStream-) | Prova a convertire un'immagine bmp/png/gif/tiff in stream in un'immagine con formato JPG. |
| [deepClone](#deepClone--) | Clona l'immagine. |
| [getBitmapInfo](#getBitmapInfo--) | Ottiene o imposta i byte dell'immagine non compressi. |
| [getBitmapSize](#getBitmapSize--) | Ottiene la dimensione bitmap dell'immagine. |
| [getBufferedImage](#getBufferedImage--) | Ottiene l'immagine java awt. |
| [getFile](#getFile--) | Ottiene il file immagine. |
| [getFileType](#getFileType--) | Ottiene il tipo di file immagine. |
| [getFixHeight](#getFixHeight--) | Ottiene l'altezza dell'immagine. |
| [getFixWidth](#getFixWidth--) | Ottiene la larghezza dell'immagine. |
| [getImageScale](#getImageScale--) | Ottiene la scala dell'immagine. |
| [getImageStream](#getImageStream--) | Ottiene lo stream dell'immagine. |
| [getMimeType](#getMimeType-com.aspose.ms.System.Drawing.Image-) | Restituisce il tipo mime per l'immagine. |
| [getTitle](#getTitle--) | Ottiene un valore stringa che indica il titolo dell'immagine. |
| [isApplyResolution](#isApplyResolution--) | Ottiene o imposta un valore booleano che indica se l'immagine utilizza la risoluzione durante la generazione |
| [isBlackWhite](#isBlackWhite--) | Ottiene un valore booleano che indica se l'immagine è forzata a essere in bianco e nero. Se viene utilizzata un'immagine TIFF del subformat CCITT, questa proprietà deve essere impostata su true. |
| [isBlackWhiteForGrayScale](#isBlackWhiteForGrayScale--) | Prova a rilevare e utilizzare la codifica 1bpp per le immagini in scala di grigi Valore predefinito == FALSE |
| [setApplyResolution](#setApplyResolution-boolean-) | Ottiene o imposta un valore booleano che indica se l'immagine utilizza la risoluzione durante la generazione |
| [setBitmapInfo](#setBitmapInfo-com.aspose.pdf.BitmapInfo-) | Ottiene o imposta i byte dell'immagine non compressi. |
| [setBlackWhite](#setBlackWhite-boolean-) | Imposta un valore booleano che indica se l'immagine è forzata a essere in bianco e nero. Se viene utilizzata un'immagine TIFF del subformat CCITT, questa proprietà deve essere impostata su true. |
| [setBlackWhiteForGrayScale](#setBlackWhiteForGrayScale-boolean-) | Prova a rilevare e utilizzare la codifica 1bpp per le immagini in scala di grigi. Valore predefinito == FALSE |
| [setBufferedImage](#setBufferedImage-java.awt.image.BufferedImage-) | Imposta l'immagine java awt. |
| [setFile](#setFile-java.lang.String-) | Imposta il file immagine. |
| [setFileType](#setFileType-com.aspose.pdf.ImageFileType-) | Imposta il tipo di file immagine. |
| [setFixHeight](#setFixHeight-double-) | Imposta l'altezza dell'immagine. |
| [setFixWidth](#setFixWidth-double-) | Imposta la larghezza dell'immagine. |
| [setImageScale](#setImageScale-double-) | Imposta la scala dell'immagine. |
| [setImageStream](#setImageStream-java.io.InputStream-) | Imposta lo stream dell'immagine. |
| [setTitle](#setTitle-com.aspose.pdf.TextFragment-) | Imposta un valore stringa che indica il titolo dell'immagine. |

### Image {#Image--}
```
public Image()
```

costruttore predefinito

### convertToJpeg {#convertToJpeg-java.io.InputStream-}
Prova a convertire un'immagine bmp/png/gif/tiff in stream in un'immagine con formato JPG.

### deepClone {#deepClone--}
```
public Object deepClone()
```

Clona l'immagine.

**Returns:**
L'oggetto clonato

### getBitmapInfo {#getBitmapInfo--}
```
public final BitmapInfo getBitmapInfo()
```

Ottiene o imposta i byte dell'immagine non compressi.

**Returns:**
Istanza BitmapInfo

### getBitmapSize {#getBitmapSize--}
```
public final Rectangle getBitmapSize()
```

Ottiene la dimensione bitmap dell'immagine.

**Returns:**
Istanza Rectangle

### getBufferedImage {#getBufferedImage--}
```
public BufferedImage getBufferedImage()
```

Ottiene l'immagine java awt.

**Returns:**
Oggetto BufferedImage

### getFile {#getFile--}
```
public String getFile()
```

Ottiene il file immagine.

**Returns:**
valore String

### getFileType {#getFileType--}
```
public ImageFileType getFileType()
```

Ottiene il tipo di file immagine.

**Returns:**
valore int @see ImageFileType

### getFixHeight {#getFixHeight--}
```
public double getFixHeight()
```

Ottiene l'altezza dell'immagine.

**Returns:**
valore double

### getFixWidth {#getFixWidth--}
```
public double getFixWidth()
```

Ottiene la larghezza dell'immagine.

**Returns:**
valore double

### getImageScale {#getImageScale--}
```
public double getImageScale()
```

Ottiene la scala dell'immagine.

**Returns:**
valore double

### getImageStream {#getImageStream--}
```
public InputStream getImageStream()
```

Ottiene lo stream dell'immagine.

**Returns:**
Oggetto InputStream

### getMimeType {#getMimeType-com.aspose.ms.System.Drawing.Image-}
Restituisce il tipo mime per l'immagine.

### getTitle {#getTitle--}
```
public TextFragment getTitle()
```

Ottiene un valore stringa che indica il titolo dell'immagine.

**Returns:**
Valore TextFragment

### isApplyResolution {#isApplyResolution--}
```
public boolean isApplyResolution()
```

Ottiene o imposta un valore booleano che indica se l'immagine utilizza la risoluzione durante la generazione

**Returns:**
valore booleano

### isBlackWhite {#isBlackWhite--}
```
public boolean isBlackWhite()
```

Ottiene un valore booleano che indica se l'immagine è forzata a essere in bianco e nero. Se viene utilizzata un'immagine TIFF del subformat CCITT, questa proprietà deve essere impostata su true.

**Returns:**
valore booleano

### isBlackWhiteForGrayScale {#isBlackWhiteForGrayScale--}
```
public boolean isBlackWhiteForGrayScale()
```

Prova a rilevare e utilizzare la codifica 1bpp per le immagini in scala di grigi Valore predefinito == FALSE

**Returns:**
valore booleano

### setApplyResolution {#setApplyResolution-boolean-}
```
public void setApplyResolution(boolean value)
```

Ottiene o imposta un valore booleano che indica se l'immagine utilizza la risoluzione durante la generazione

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setBitmapInfo {#setBitmapInfo-com.aspose.pdf.BitmapInfo-}
Ottiene o imposta i byte dell'immagine non compressi.

### setBlackWhite {#setBlackWhite-boolean-}
```
public void setBlackWhite(boolean value)
```

Imposta un valore booleano che indica se l'immagine è forzata a essere in bianco e nero. Se viene utilizzata un'immagine TIFF del subformat CCITT, questa proprietà deve essere impostata su true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setBlackWhiteForGrayScale {#setBlackWhiteForGrayScale-boolean-}
```
public void setBlackWhiteForGrayScale(boolean blackWhiteForGrayScale)
```

Prova a rilevare e utilizzare la codifica 1bpp per le immagini in scala di grigi. Valore predefinito == FALSE

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| blackWhiteForGrayScale |  | valore booleano |

### setBufferedImage {#setBufferedImage-java.awt.image.BufferedImage-}
Imposta l'immagine java awt.

### setFile {#setFile-java.lang.String-}
Imposta il file immagine.

### setFileType {#setFileType-com.aspose.pdf.ImageFileType-}
Imposta il tipo di file immagine.

### setFixHeight {#setFixHeight-double-}
```
public void setFixHeight(double value)
```

Imposta l'altezza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setFixWidth {#setFixWidth-double-}
```
public void setFixWidth(double value)
```

Imposta la larghezza dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setImageScale {#setImageScale-double-}
```
public void setImageScale(double value)
```

Imposta la scala dell'immagine.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setImageStream {#setImageStream-java.io.InputStream-}
Imposta lo stream dell'immagine.

### setTitle {#setTitle-com.aspose.pdf.TextFragment-}
Imposta un valore stringa che indica il titolo dell'immagine.
