---
title: "XImage"
linktitle: "XImage"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta l'oggetto immagine X-Object."
type: docs
weight: 5610
url: /it/java/com.aspose.pdf/ximage/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.XImage

```
public final class XImage extends Object
```

Classe che rappresenta l'oggetto immagine X-Object.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [XImage](#XImage-com.aspose.pdf.engine.data.IPdfDataStream-) | solo per uso interno |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [addStencilMask](#addStencilMask-java.io.InputStream-) | Aggiunge una maschera stencil al XImage. |
| [containsTransparency](#containsTransparency--) | Se l'immagine contiene trasparenza restituisce true; altrimenti, false. |
| [delete](#delete--) | Elimina l'immagine dalla collezione genitore. |
| [detectColorType](#detectColorType-java.awt.image.BufferedImage-) | Restituisce il tipo di colore dell'immagine. |
| [getAlternativeText](#getAlternativeText-com.aspose.pdf.Page-) | Restituisce un elenco di stringhe con testo alternativo per un XImage. |
| [getColorType](#getColorType--) | Restituisce il tipo di colore dell'immagine. |
| [getEngineImg](#getEngineImg--) | Oggetto IPdfImage che descrive l'immagine. Solo per uso interno. |
| [getFilterType](#getFilterType--) | Ottiene il tipo di filtro dell'immagine. |
| [getGrayscaled](#getGrayscaled--) | Ottiene la versione in scala di grigi dell'immagine. |
| [getHeight](#getHeight--) | Ottiene l'altezza dell'immagine. |
| [getImage](#getImage--) | Solo per uso interno |
| [getMetadata](#getMetadata--) | Metadati dell'immagine. |
| [getName](#getName--) | Ottiene il nome dell'immagine. Si prega di notare che se si cambia il nome dell'immagine che ha riferimenti nei contenuti della pagina, il documento potrebbe diventare errato. Si prega di utilizzare il metodo XImage.Rename in questo caso. |
| [getNameInCollection](#getNameInCollection--) | Restituisce il nome dell'immagine nella sua collezione. |
| [getRawBytes](#getRawBytes--) | Restituisce i byte grezzi dell'immagine senza decodifica. |
| [getRawImageData](#getRawImageData--) | Recupera i dati grezzi dell'immagine dall'immagine di origine. |
| [getRawParameters](#getRawParameters--) | Ottiene i parametri grezzi dell'immagine |
| [getWidth](#getWidth--) | Ottiene la larghezza dell'immagine. |
| [isImage](#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-) | Restituisce true se la primitiva è un'immagine. |
| [isImageMask](#isImageMask--) | Ottiene un flag che indica se l'immagine deve essere trattata come una maschera di immagine (vedi 8.9.6, "Masked Images"). Se questo flag è true, il valore di BitsPerComponent deve essere 1 e Mask e ColorSpace non devono essere specificati; le aree non mascherate devono essere dipinte usando il colore di riempimento corrente. Valore predefinito: false. Valore: True se l'immagine è una maschera di immagine. |
| [isTheSameObject](#isTheSameObject-com.aspose.pdf.XImage-) | Restituisce true se entrambe le immagini fanno riferimento allo stesso oggetto. |
| [rename](#rename-java.lang.String-) | Rinomina l'immagine e sostituisce tutti i riferimenti all'immagine con il nuovo nome |
| [replace](#replace-java.io.InputStream-) | Sostituisce l'immagine nello stream specificato in {@code image}. * |
| [save](#save-java.io.OutputStream-) | Salva i dati dell'immagine nello stream come immagine JPEG. |
| [save](#save-java.io.OutputStream-float-float-) | Salva l'immagine nello stream con il formato richiesto. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-) | Salva l'immagine nello stream con il formato richiesto. |
| [save](#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Salva l'immagine nello stream con il formato richiesto. |
| [save](#save-java.io.OutputStream-int-) | Salva l'immagine nello stream con il formato richiesto e con la risoluzione specificata. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-) | Salva l'immagine nello stream con il formato richiesto. |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-) |  |
| [saveInternal](#saveInternal-com.aspose.ms.System.IO.Stream-int-) | Salva i dati dell'immagine nello stream come immagine JPEG con risoluzione specificata. |
| [setName](#setName-java.lang.String-) | Imposta il nome dell'immagine. Si prega di notare che se si cambia il nome dell'immagine che ha riferimenti nei contenuti della pagina, il documento potrebbe diventare errato. Si prega di utilizzare il metodo XImage.Rename in questo caso. |
| [toStream](#toStream--) | Restituisce lo stream originale dell'immagine. |
| [toString](#toString--) | Restituisce una rappresentazione stringa delle proprietà dell'oggetto XImage. |
| [trySetAlternativeText](#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-) | Imposta il testo alternativo per un XImage nella pagina. |

### XImage {#XImage-com.aspose.pdf.engine.data.IPdfDataStream-}
solo per uso interno

### addStencilMask {#addStencilMask-java.io.InputStream-}
Aggiunge una maschera stencil al XImage.

### containsTransparency {#containsTransparency--}
```
public boolean containsTransparency()
```

Se l'immagine contiene trasparenza restituisce true; altrimenti, false.

**Returns:**
valore booleano

### delete {#delete--}
```
public void delete()
```

Elimina l'immagine dalla collezione genitore.

### detectColorType {#detectColorType-java.awt.image.BufferedImage-}
Restituisce il tipo di colore dell'immagine.

### getAlternativeText {#getAlternativeText-com.aspose.pdf.Page-}
Restituisce un elenco di stringhe con testo alternativo per un XImage.

### getColorType {#getColorType--}
```
public ColorType getColorType()
```

Restituisce il tipo di colore dell'immagine.

**Returns:**
Il valore del tipo di colore.

### getEngineImg {#getEngineImg--}
```
public com.aspose.pdf.engine.data.IPdfDataStream getEngineImg()
```

Oggetto IPdfImage che descrive l'immagine. Solo per uso interno.

**Returns:**
IPdfDataStream

### getFilterType {#getFilterType--}
```
public final ImageFilterType getFilterType()
```

Ottiene il tipo di filtro dell'immagine.

**Returns:**
Elemento ImageFilterType

### getGrayscaled {#getGrayscaled--}
```
public BufferedImage getGrayscaled()
```

Ottiene la versione in scala di grigi dell'immagine.

**Returns:**
BufferedImage

### getHeight {#getHeight--}
```
public int getHeight()
```

Ottiene l'altezza dell'immagine.

**Returns:**
valore int

### getImage {#getImage--}
```
public com.aspose.ms.System.Drawing.Bitmap getImage()
```

Solo per uso interno

**Returns:**
Image

### getMetadata {#getMetadata--}
```
public final Metadata getMetadata()
```

Metadati dell'immagine.

**Returns:**
Istanza Metadata

### getName {#getName--}
```
public String getName()
```

Ottiene il nome dell'immagine. Si prega di notare che se si cambia il nome dell'immagine che ha riferimenti nei contenuti della pagina, il documento potrebbe diventare errato. Si prega di utilizzare il metodo XImage.Rename in questo caso.

**Returns:**
Stringa

### getNameInCollection {#getNameInCollection--}
```
public String getNameInCollection()
```

Restituisce il nome dell'immagine nella sua collezione.

**Returns:**
Chiave immagine (nome).

### getRawBytes {#getRawBytes--}
```
public byte[] getRawBytes()
```

Restituisce i byte grezzi dell'immagine senza decodifica.

**Returns:**
array di byte

### getRawImageData {#getRawImageData--}
```
public final byte[] getRawImageData()
```

Recupera i dati grezzi dell'immagine dall'immagine di origine.

**Returns:**
Un {@link byte[]} contenente i dati originali dell'immagine.

### getRawParameters {#getRawParameters--}
```
public XImage.RawParameters getRawParameters()
```

Ottiene i parametri grezzi dell'immagine

**Returns:**
Istanza di RawParameters

### getWidth {#getWidth--}
```
public int getWidth()
```

Ottiene la larghezza dell'immagine.

**Returns:**
valore int

### isImage {#isImage-com.aspose.pdf.engine.data.IPdfPrimitive-}
Restituisce true se la primitiva è un'immagine.

### isImageMask {#isImageMask--}
```
public final boolean isImageMask()
```

Ottiene un flag che indica se l'immagine deve essere trattata come una maschera di immagine (vedi 8.9.6, "Masked Images"). Se questo flag è true, il valore di BitsPerComponent deve essere 1 e Mask e ColorSpace non devono essere specificati; le aree non mascherate devono essere dipinte usando il colore di riempimento corrente. Valore predefinito: false. Valore: True se l'immagine è una maschera di immagine.

**Returns:**
valore booleano

### isTheSameObject {#isTheSameObject-com.aspose.pdf.XImage-}
Restituisce true se entrambe le immagini fanno riferimento allo stesso oggetto.

### rename {#rename-java.lang.String-}
Rinomina l'immagine e sostituisce tutti i riferimenti all'immagine con il nuovo nome

### replace {#replace-java.io.InputStream-}
Sostituisce l'immagine nello stream specificato in {@code image}. *

### save {#save-java.io.OutputStream-}
Salva i dati dell'immagine nello stream come immagine JPEG.

### save {#save-java.io.OutputStream-float-float-}
Salva l'immagine nello stream con il formato richiesto.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-}
Salva l'immagine nello stream con il formato richiesto.

### save {#save-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Salva l'immagine nello stream con il formato richiesto.

### save {#save-java.io.OutputStream-int-}
Salva l'immagine nello stream con il formato richiesto e con la risoluzione specificata.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-}
Salva l'immagine nello stream con il formato richiesto.

### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-com.aspose.pdf.ImageType-int-}


### saveInternal {#saveInternal-com.aspose.ms.System.IO.Stream-int-}
Salva i dati dell'immagine nello stream come immagine JPEG con risoluzione specificata.

### setName {#setName-java.lang.String-}
Imposta il nome dell'immagine. Si prega di notare che se si cambia il nome dell'immagine che ha riferimenti nei contenuti della pagina, il documento potrebbe diventare errato. Si prega di utilizzare il metodo XImage.Rename in questo caso.

### toStream {#toStream--}
```
public InputStream toStream()
```

Restituisce lo stream originale dell'immagine.

**Returns:**
Il flusso immagine originale.

### toString {#toString--}
```
public String toString()
```

Restituisce una rappresentazione stringa delle proprietà dell'oggetto XImage.

**Returns:**
Istanza di String

### trySetAlternativeText {#trySetAlternativeText-java.lang.String-com.aspose.pdf.Page-}
Imposta il testo alternativo per un XImage nella pagina.
