---
title: "Marca"
linktitle: "Marca"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che rappresenta un timbro."
type: docs
weight: 700
url: /it/java/com.aspose.pdf.facades/stamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Stamp

```
public final class Stamp extends Object
```

Classe che rappresenta un timbro.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [Stamp](#Stamp--) | Costruttore per l'oggetto Stamp. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [bindImage](#bindImage-java.io.InputStream-) | Imposta l'immagine che sarà usata come timbro. |
| [bindImage](#bindImage-java.lang.String-) | <p> Imposta l'immagine come timbro. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new Stamp(); stamp.bindImage(\"image.jpg\"); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindLogo](#bindLogo-com.aspose.pdf.facades.FormattedText-) | Imposta il testo come timbro. |
| [bindPdf](#bindPdf-java.io.InputStream-int-) | <p> Imposta il file PDF e il numero di pagina che verrà usato come timbro. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream(\"stamp.pdf\"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindPdf](#bindPdf-java.lang.String-int-) | <p> Imposta il file PDF e il numero di pagina che verrà usato come timbro. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf(\"stamp.pdf\", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |
| [bindTextState](#bindTextState-com.aspose.pdf.TextState-) | Imposta lo stato del testo del timbro. |
| [close](#close--) | Chiude questa istanza. |
| [getBlendingSpace](#getBlendingSpace--) | Ottiene un valore BlendingColorSpace che definisce uno spazio colore utilizzato per eseguire operazioni di trasparenza e fusione sulla pagina. |
| [getOpacity](#getOpacity--) | Ottiene l'opacità del timbro. |
| [getPageNumber](#getPageNumber--) | Ottiene il numero di pagina. |
| [getPages](#getPages--) | Ottiene un array con i numeri delle pagine che saranno interessate dal timbro. |
| [getQuality](#getQuality--) | Ottiene la qualità del timbro immagine in percentuale. Valori consentiti 0..100%. |
| [getRotation](#getRotation--) | Ottiene la rotazione del timbro in gradi. |
| [getStampId](#getStampId--) | Ottiene l'identificatore del timbro. |
| [isBackground](#isBackground--) | Ottiene lo stato di sfondo. Se vero, il timbro verrà posizionato come sfondo della pagina timbrata. Per impostazione predefinita è impostato su false. |
| [setBackground](#setBackground-boolean-) | Imposta lo stato di sfondo. Se vero, il timbro verrà posizionato come sfondo della pagina timbrata. Per impostazione predefinita è impostato su false. |
| [setBlendingSpace](#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-) | Imposta un valore BlendingColorSpace che definisce uno spazio colore utilizzato per eseguire operazioni di trasparenza e fusione sulla pagina. |
| [setImageSize](#setImageSize-float-float-) | Imposta le dimensioni del timbro immagine. L'immagine verrà scalata in base ai valori specificati. |
| [setOpacity](#setOpacity-float-) | Imposta l'opacità del timbro. |
| [setOrigin](#setOrigin-float-float-) | Imposta la posizione sulla pagina dove verrà posizionato il timbro. |
| [setPageNumber](#setPageNumber-int-) | Imposta il numero di pagina. |
| [setPages](#setPages-int:A-) | <p> Imposta un array con i numeri delle pagine che saranno interessate dal timbro. Se Pages = null, tutte le pagine del documento sono interessate. </p> |
| [setQuality](#setQuality-int-) | Imposta la qualità del timbro immagine in percentuale. Valori consentiti 0..100%. |
| [setRotation](#setRotation-float-) | <p> Ottiene o imposta la rotazione del timbro in gradi. </p> |
| [setStampId](#setStampId-int-) | Imposta l'identificatore del timbro. |

### Stamp {#Stamp--}
```
public Stamp()
```

Costruttore per l'oggetto Stamp.

### bindImage {#bindImage-java.io.InputStream-}
Imposta l'immagine che sarà usata come timbro.

### bindImage {#bindImage-java.lang.String-}
<p> Imposta l'immagine come timbro. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new Stamp(); stamp.bindImage(\"image.jpg\"); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindLogo {#bindLogo-com.aspose.pdf.facades.FormattedText-}
Imposta il testo come timbro.

### bindPdf {#bindPdf-java.io.InputStream-int-}
<p> Imposta il file PDF e il numero di pagina che verrà usato come timbro. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new Stamp(); //First page will be used as stamp. InputStream stream = new FileInputStream(\"stamp.pdf\"); stamp.bindPdf(stream, 1); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindPdf {#bindPdf-java.lang.String-int-}
<p> Imposta il file PDF e il numero di pagina che verrà usato come timbro. </p> <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp(\"input.pdf\", \"output.pdf\"); Stamp stamp = new Stamp(); //First page will be used as stamp. stamp.bindPdf(\"stamp.pdf\", 1); stamp.isBackground (true); fileStamp.addStamp(stamp); fileStamp.close(); </pre>

### bindTextState {#bindTextState-com.aspose.pdf.TextState-}
Imposta lo stato del testo del timbro.

### close {#close--}
```
public void close()
```

Chiude questa istanza.

### getBlendingSpace {#getBlendingSpace--}
```
public BlendingColorSpace getBlendingSpace()
```

Ottiene un valore BlendingColorSpace che definisce uno spazio colore utilizzato per eseguire operazioni di trasparenza e fusione sulla pagina.

**Returns:**
valore int @see BlendingColorSpace

### getOpacity {#getOpacity--}
```
public float getOpacity()
```

Ottiene l'opacità del timbro.

**Returns:**
valore float

### getPageNumber {#getPageNumber--}
```
public int getPageNumber()
```

Ottiene il numero di pagina.

**Returns:**
valore int

### getPages {#getPages--}
```
public int[] getPages()
```

Ottiene un array con i numeri delle pagine che saranno interessate dal timbro.

**Returns:**
array di int

### getQuality {#getQuality--}
```
public int getQuality()
```

Ottiene la qualità del timbro immagine in percentuale. Valori consentiti 0..100%.

**Returns:**
valore int

### getRotation {#getRotation--}
```
public float getRotation()
```

Ottiene la rotazione del timbro in gradi.

**Returns:**
valore float

### getStampId {#getStampId--}
```
public int getStampId()
```

Ottiene l'identificatore del timbro.

**Returns:**
valore int

### isBackground {#isBackground--}
```
public boolean isBackground()
```

Ottiene lo stato di sfondo. Se vero, il timbro verrà posizionato come sfondo della pagina timbrata. Per impostazione predefinita è impostato su false.

**Returns:**
valore booleano

### setBackground {#setBackground-boolean-}
```
public void setBackground(boolean value)
```

Imposta lo stato di sfondo. Se vero, il timbro verrà posizionato come sfondo della pagina timbrata. Per impostazione predefinita è impostato su false.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setBlendingSpace {#setBlendingSpace-com.aspose.pdf.facades.BlendingColorSpace-}
Imposta un valore BlendingColorSpace che definisce uno spazio colore utilizzato per eseguire operazioni di trasparenza e fusione sulla pagina.

### setImageSize {#setImageSize-float-float-}
```
public void setImageSize(float width, float height)
```

Imposta le dimensioni del timbro immagine. L'immagine verrà scalata in base ai valori specificati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| larghezza |  | Larghezza immagine. |
| altezza |  | Altezza dell'immagine. |

### setOpacity {#setOpacity-float-}
```
public void setOpacity(float value)
```

Imposta l'opacità del timbro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore float |

### setOrigin {#setOrigin-float-float-}
```
public void setOrigin(float originX, float originY)
```

Imposta la posizione sulla pagina dove verrà posizionato il timbro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| originX |  | Coordinata X del timbro. |
| originY |  | Coordinata Y del timbro. |

### setPageNumber {#setPageNumber-int-}
```
public void setPageNumber(int value)
```

Imposta il numero di pagina.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setPages {#setPages-int:A-}
```
public void setPages(int[] value)
```

<p> Imposta un array con i numeri delle pagine che saranno interessate dal timbro. Se Pages = null, tutte le pagine del documento sono interessate. </p>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Array di int <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new com.aspose.pdf.facades.Stamp(); stamp.bindLogo(new FormattedText(text)); //put stamp only on 1st, 4th and 6th page. stamp.setPages(new int[] { 1, 4, 6 }); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Imposta la qualità del timbro immagine in percentuale. Valori consentiti 0..100%.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setRotation {#setRotation-float-}
```
public void setRotation(float value)
```

<p> Ottiene o imposta la rotazione del timbro in gradi. </p>

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Valore float <hr> <pre> PdfFileStamp fileStamp = new PdfFileStamp("input.pdf", "output.pdf"); Stamp stamp = new Stamp(); stamp.bindLogo(new FormattedText("STAMP")); stamp.setRotation(90); fileStamp.addStamp(stamp); fileStamp.close(); </pre> |

### setStampId {#setStampId-int-}
```
public void setStampId(int value)
```

Imposta l'identificatore del timbro.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |
