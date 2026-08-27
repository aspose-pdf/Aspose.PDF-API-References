---
title: "ImageStamp"
linktitle: "ImageStamp"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta un timbro grafico."
type: docs
weight: 2360
url: /it/java/com.aspose.pdf/imagestamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.ImageStamp, com.aspose.pdf.Stamp, com.aspose.pdf.ImageStamp

```
public final class ImageStamp extends Stamp
```

Rappresenta un timbro grafico.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageStamp](#ImageStamp-java.io.InputStream-) | Inizializza una nuova istanza della classe {@code ImageStamp}. |
| [ImageStamp](#ImageStamp-java.lang.String-) | Crea un timbro immagine dall'immagine nel file specificato. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close](#close--) | Chiude questa istanza. |
| [getAlternativeText](#getAlternativeText--) | Restituisce il testo alternativo per il timbro immagine. |
| [getHeight](#getHeight--) | Restituisce l'altezza dell'immagine. Impostare questa immagine consente di scalare l'immagine verticalmente. |
| [getImage](#getImage--) | Restituisce lo stream dell'immagine usato per il timbro. |
| [getQuality](#getQuality--) | Restituisce la qualità del timbro immagine in percentuale. I valori validi sono 0..100%. |
| [getWidth](#getWidth--) | Restituisce la larghezza dell'immagine. Impostare questa proprietà consente di scalare l'immagine orizzontalmente. |
| [getXIndent](#getXIndent--) | Restituisce e imposta la coordinata orizzontale del timbro, a partire da sinistra. |
| [getYIndent](#getYIndent--) | Restituisce e imposta la coordinata verticale del timbro, a partire dal basso. |
| [put](#put-com.aspose.pdf.Page-) | Aggiunge un timbro grafico nella pagina. |
| [setAlternativeText](#setAlternativeText-java.lang.String-) | Imposta il testo alternativo per il timbro immagine. |
| [setHeight](#setHeight-double-) | Imposta l'altezza dell'immagine. Impostare questa immagine consente di scalare l'immagine verticalmente. |
| [setQuality](#setQuality-int-) | Imposta la qualità del timbro immagine in percentuale. I valori validi sono 0..100%. |
| [setWidth](#setWidth-double-) | Imposta la larghezza dell'immagine. Impostare questa proprietà consente di scalare l'immagine orizzontalmente. |
| [setXIndent](#setXIndent-double-) | Restituisce e imposta la coordinata orizzontale del timbro, a partire da sinistra. |
| [setYIndent](#setYIndent-double-) | Restituisce e imposta la coordinata verticale del timbro, a partire dal basso. |

### ImageStamp {#ImageStamp-java.io.InputStream-}
Inizializza una nuova istanza della classe {@code ImageStamp}.

### ImageStamp {#ImageStamp-java.lang.String-}
Crea un timbro immagine dall'immagine nel file specificato.

### close {#close--}
```
public void close()
```

Chiude questa istanza.

### getAlternativeText {#getAlternativeText--}
```
public final String getAlternativeText()
```

Restituisce il testo alternativo per il timbro immagine.

**Returns:**
valore String

### getHeight {#getHeight--}
```
public double getHeight()
```

Restituisce l'altezza dell'immagine. Impostare questa immagine consente di scalare l'immagine verticalmente.

**Returns:**
valore double

### getImage {#getImage--}
```
public InputStream getImage()
```

Restituisce lo stream dell'immagine usato per il timbro.

**Returns:**
Oggetto InputStream

### getQuality {#getQuality--}
```
public int getQuality()
```

Restituisce la qualità del timbro immagine in percentuale. I valori validi sono 0..100%.

**Returns:**
valore int

### getWidth {#getWidth--}
```
public double getWidth()
```

Restituisce la larghezza dell'immagine. Impostare questa proprietà consente di scalare l'immagine orizzontalmente.

**Returns:**
valore double

### getXIndent {#getXIndent--}
```
public double getXIndent()
```

Restituisce e imposta la coordinata orizzontale del timbro, a partire da sinistra.

**Returns:**
valore double

### getYIndent {#getYIndent--}
```
public double getYIndent()
```

Restituisce e imposta la coordinata verticale del timbro, a partire dal basso.

**Returns:**
valore double

### put {#put-com.aspose.pdf.Page-}
Aggiunge un timbro grafico nella pagina.

### setAlternativeText {#setAlternativeText-java.lang.String-}
Imposta il testo alternativo per il timbro immagine.

### setHeight {#setHeight-double-}
```
public void setHeight(double value)
```

Imposta l'altezza dell'immagine. Impostare questa immagine consente di scalare l'immagine verticalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setQuality {#setQuality-int-}
```
public void setQuality(int value)
```

Imposta la qualità del timbro immagine in percentuale. I valori validi sono 0..100%.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setWidth {#setWidth-double-}
```
public void setWidth(double value)
```

Imposta la larghezza dell'immagine. Impostare questa proprietà consente di scalare l'immagine orizzontalmente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setXIndent {#setXIndent-double-}
```
public void setXIndent(double value)
```

Restituisce e imposta la coordinata orizzontale del timbro, a partire da sinistra.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |

### setYIndent {#setYIndent-double-}
```
public void setYIndent(double value)
```

Restituisce e imposta la coordinata verticale del timbro, a partire dal basso.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore double |
