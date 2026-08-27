---
title: "ImagesDifference"
linktitle: "ImagesDifference"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta la classe risultato del confronto di due pagine PDF."
type: docs
weight: 20
url: /it/java/com.aspose.pdf.comparison.graphicalcomparison/imagesdifference/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.comparison.graphicalcomparison.ImagesDifference

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public final class ImagesDifference extends Object implements com.aspose.ms.System.IDisposable
```

Rappresenta la classe risultato del confronto di due pagine PDF.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [differenceToImage](#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-) | Converte l'array delle differenze in un'immagine bitmap utilizzando i colori specificati. |
| [dispose](#dispose--) | Esegue le operazioni di pulizia necessarie prima che l'oggetto venga distrutto. |
| [getDestinationImage](#getDestinationImage--) | Restituisce un nuovo bitmap che rappresenta l'immagine di destinazione applicando l'array delle differenze all'immagine sorgente. |
| [getDifference](#getDifference--) | Ottiene l'array delle differenze. Questo array è simile all'array dei dati dell'immagine originale ottenuto come risultato del metodo LockBits. |
| [getHeight](#getHeight--) | L'altezza della differenza. |
| [getSourceImage](#getSourceImage--) | Ottiene l'immagine della prima pagina confrontata. L'immagine ha un formato pixel di 24 bpp. |
| [getStride](#getStride--) | Il passo (stride) dei dati immagine della differenza. |

### differenceToImage {#differenceToImage-com.aspose.pdf.Color-com.aspose.pdf.Color-}
Converte l'array delle differenze in un'immagine bitmap utilizzando i colori specificati.

### dispose {#dispose--}
```
public final void dispose()
```

Esegue le operazioni di pulizia necessarie prima che l'oggetto venga distrutto.

### getDestinationImage {#getDestinationImage--}
```
public final BufferedImage getDestinationImage()
```

Restituisce un nuovo bitmap che rappresenta l'immagine di destinazione applicando l'array delle differenze all'immagine sorgente.

**Returns:**
Un'immagine di destinazione.

### getDifference {#getDifference--}
```
public final int[] getDifference()
```

Ottiene l'array delle differenze. Questo array è simile all'array dei dati dell'immagine originale ottenuto come risultato del metodo LockBits.

**Returns:**
int[] array

### getHeight {#getHeight--}
```
public final int getHeight()
```

L'altezza della differenza.

**Returns:**
valore int

### getSourceImage {#getSourceImage--}
```
public final BufferedImage getSourceImage()
```

Ottiene l'immagine della prima pagina confrontata. L'immagine ha un formato pixel di 24 bpp.

**Returns:**
BufferedImage instance

### getStride {#getStride--}
```
public final int getStride()
```

Il passo (stride) dei dati immagine della differenza.

**Returns:**
valore int
