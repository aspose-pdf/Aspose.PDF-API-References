---
title: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
linktitle: "HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Se la proprietà SplitToPages di HtmlSaveOptions è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione da PDF a HTML. Questa classe rappresenta un insieme di."
type: docs
weight: 2100
url: /it/java/com.aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingInfo

```
public static class HtmlSaveOptions.HtmlPageMarkupSavingInfo extends Object
```

Se la proprietà SplitToPages di HtmlSaveOptions è impostata, allora vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione da PDF a HTML. Questa classe rappresenta un insieme di dati relativi al salvataggio personalizzato del markup di una pagina HTML durante la conversione da PDF a HTML.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getContentStream](#getContentStream--) | Impostato dal convertitore. Rappresenta l'HTML salvato come stream. |
| [getHtmlHostPageNumber](#getHtmlHostPageNumber--) | Impostato dal convertitore. Se la proprietà SplitToPages è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione. Questa proprietà contiene l'ordine del file HTML salvato. La proprietà può essere usata nella logica del codice personalizzato per decidere come elaborare o dove salvare la pagina HTML e, se la suddivisione in pagine è disattivata, questo valore contiene sempre '1' poiché in tal caso viene generata una sola grande pagina HTML per l'intero documento sorgente. |
| [getPdfHostPageNumber](#getPdfHostPageNumber--) | Impostato dal convertitore. Se la proprietà SplitToPages è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione. Questa proprietà indica al codice personalizzato da quale pagina del PDF originale è stato creato il markup HTML salvato. Se il numero di pagina originale per qualche motivo è sconosciuto o SplitToPages=false, questa proprietà contiene sempre '0', segnalando che il convertitore non può fornire il numero di pagina originale del PDF per il file di markup HTML fornito. |
| [getSupposedFileName](#getSupposedFileName--) | Impostato dal convertitore. Nome file previsto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare il contenuto. |
| [isCustomProcessingCancelled](#isCustomProcessingCancelled--) | Deve essere impostato nel codice personalizzato quando necessario. Questa flag deve essere impostata a "true" nel codice personalizzato se, per qualche motivo, il markup HTML fornito deve essere elaborato non dal codice personalizzato ma dal codice del convertitore stesso, nel modo standard per il convertitore. Quindi, impostare questa flag nel codice personalizzato significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo autonomamente. |
| [setContentStream](#setContentStream-java.io.InputStream-) | Impostato dal convertitore. Rappresenta l'HTML salvato come stream. |
| [setCustomProcessingCancelled](#setCustomProcessingCancelled-boolean-) | Deve essere impostato nel codice personalizzato quando necessario. Questa flag deve essere impostata a "true" nel codice personalizzato se, per qualche motivo, il markup HTML fornito deve essere elaborato non dal codice personalizzato ma dal codice del convertitore stesso, nel modo standard per il convertitore. Quindi, impostare questa flag nel codice personalizzato significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo autonomamente. |
| [setHtmlHostPageNumber](#setHtmlHostPageNumber-int-) | Impostato dal convertitore. Se la proprietà SplitToPages è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione. Questa proprietà contiene l'ordine del file HTML salvato. La proprietà può essere usata nella logica del codice personalizzato per decidere come elaborare o dove salvare la pagina HTML e, se la suddivisione in pagine è disattivata, questo valore contiene sempre '1' poiché in tal caso viene generata una sola grande pagina HTML per l'intero documento sorgente. |
| [setPdfHostPageNumber](#setPdfHostPageNumber-int-) | Impostato dal convertitore. Se la proprietà SplitToPages è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione. Questa proprietà indica al codice personalizzato da quale pagina del PDF originale è stato creato il markup HTML salvato. Se il numero di pagina originale per qualche motivo è sconosciuto o SplitToPages=false, questa proprietà contiene sempre '0', segnalando che il convertitore non può fornire il numero di pagina originale del PDF per il file di markup HTML fornito. |
| [setSupposedFileName](#setSupposedFileName-java.lang.String-) | Impostato dal convertitore. Nome file previsto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare il contenuto. |

### getContentStream {#getContentStream--}
```
public InputStream getContentStream()
```

Impostato dal convertitore. Rappresenta l'HTML salvato come stream.

**Returns:**
Istanza di InputStream

### getHtmlHostPageNumber {#getHtmlHostPageNumber--}
```
public int getHtmlHostPageNumber()
```

Impostato dal convertitore. Se la proprietà SplitToPages è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione. Questa proprietà contiene l'ordine del file HTML salvato. La proprietà può essere usata nella logica del codice personalizzato per decidere come elaborare o dove salvare la pagina HTML e, se la suddivisione in pagine è disattivata, questo valore contiene sempre '1' poiché in tal caso viene generata una sola grande pagina HTML per l'intero documento sorgente.

**Returns:**
valore int

### getPdfHostPageNumber {#getPdfHostPageNumber--}
```
public int getPdfHostPageNumber()
```

Impostato dal convertitore. Se la proprietà SplitToPages è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione. Questa proprietà indica al codice personalizzato da quale pagina del PDF originale è stato creato il markup HTML salvato. Se il numero di pagina originale per qualche motivo è sconosciuto o SplitToPages=false, questa proprietà contiene sempre '0', segnalando che il convertitore non può fornire il numero di pagina originale del PDF per il file di markup HTML fornito.

**Returns:**
valore int

### getSupposedFileName {#getSupposedFileName--}
```
public String getSupposedFileName()
```

Impostato dal convertitore. Nome file previsto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare il contenuto.

**Returns:**
valore String

### isCustomProcessingCancelled {#isCustomProcessingCancelled--}
```
public boolean isCustomProcessingCancelled()
```

Deve essere impostato nel codice personalizzato quando necessario. Questa flag deve essere impostata a "true" nel codice personalizzato se, per qualche motivo, il markup HTML fornito deve essere elaborato non dal codice personalizzato ma dal codice del convertitore stesso, nel modo standard per il convertitore. Quindi, impostare questa flag nel codice personalizzato significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo autonomamente.

**Returns:**
valore booleano

### setContentStream {#setContentStream-java.io.InputStream-}
Impostato dal convertitore. Rappresenta l'HTML salvato come stream.

### setCustomProcessingCancelled {#setCustomProcessingCancelled-boolean-}
```
public void setCustomProcessingCancelled(boolean customProcessingCancelled)
```

Deve essere impostato nel codice personalizzato quando necessario. Questa flag deve essere impostata a "true" nel codice personalizzato se, per qualche motivo, il markup HTML fornito deve essere elaborato non dal codice personalizzato ma dal codice del convertitore stesso, nel modo standard per il convertitore. Quindi, impostare questa flag nel codice personalizzato significa che il codice personalizzato non ha elaborato il file di riferimento e il convertitore deve gestirlo autonomamente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| customProcessingCancelled |  | valore booleano |

### setHtmlHostPageNumber {#setHtmlHostPageNumber-int-}
```
public void setHtmlHostPageNumber(int htmlHostPageNumber)
```

Impostato dal convertitore. Se la proprietà SplitToPages è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione. Questa proprietà contiene l'ordine del file HTML salvato. La proprietà può essere usata nella logica del codice personalizzato per decidere come elaborare o dove salvare la pagina HTML e, se la suddivisione in pagine è disattivata, questo valore contiene sempre '1' poiché in tal caso viene generata una sola grande pagina HTML per l'intero documento sorgente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| htmlHostPageNumber |  | valore int |

### setPdfHostPageNumber {#setPdfHostPageNumber-int-}
```
public void setPdfHostPageNumber(int pdfHostPageNumber)
```

Impostato dal convertitore. Se la proprietà SplitToPages è impostata, vengono creati diversi file HTML (un file HTML per pagina convertita) durante la conversione. Questa proprietà indica al codice personalizzato da quale pagina del PDF originale è stato creato il markup HTML salvato. Se il numero di pagina originale per qualche motivo è sconosciuto o SplitToPages=false, questa proprietà contiene sempre '0', segnalando che il convertitore non può fornire il numero di pagina originale del PDF per il file di markup HTML fornito.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| pdfHostPageNumber |  | valore int |

### setSupposedFileName {#setSupposedFileName-java.lang.String-}
Impostato dal convertitore. Nome file previsto che passa dal convertitore al codice del metodo personalizzato. Può essere usato nel codice personalizzato per decidere come elaborare o dove salvare il contenuto.
