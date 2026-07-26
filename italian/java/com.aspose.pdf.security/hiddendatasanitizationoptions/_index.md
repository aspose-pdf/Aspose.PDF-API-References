---
title: "HiddenDataSanitizationOptions"
linktitle: "HiddenDataSanitizationOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni di configurazione per la sanificazione dei dati nascosti all'interno di un documento."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.security/hiddendatasanitizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.HiddenDataSanitizationOptions

```
public final class HiddenDataSanitizationOptions extends Object
```

Rappresenta le opzioni di configurazione per la sanificazione dei dati nascosti all'interno di un documento.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HiddenDataSanitizationOptions](#HiddenDataSanitizationOptions--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [all](#all--) | Crea una nuova istanza della classe {@link HiddenDataSanitizationOptions} con tutte le opzioni impostate per la sanitizzazione. Questo include abilitare la rimozione di annotazioni, JavaScript, metadati, allegati, indice di ricerca, informazioni private, l'appiattimento di moduli e livelli, mentre disabilita l'opzione per convertire le pagine in immagini. Configurazioni opzionali come {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) o {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) possono essere modificate manualmente dopo aver ottenuto l'istanza, poiché non sono attive per impostazione predefinita. |
| [getConvertPagesToImages](#getConvertPagesToImages--) | Restituisce l'opzione per convertire le pagine in immagini. Se questa opzione è abilitata, l'opzione ImageCompressionOptions verrà ignorata. L'opzione deve essere abilitata manualmente quando si utilizza il metodo {@code #All()} se è necessaria. La conversione delle pagine in immagini avverrà dopo la pulizia dei principali dati nascosti, controllata da altre opzioni. |
| [getFlattenForms](#getFlattenForms--) | Restituisce un valore che indica se i moduli nel documento devono essere appiattiti durante il processo di sanitizzazione. L'appiattimento dei moduli converte i campi interattivi in contenuto statico, rendendoli non modificabili o compilabili. |
| [getFlattenLayers](#getFlattenLayers--) | Restituisce l'opzione per appiattire i livelli nel documento PDF. Quando è abilitata, tutti i livelli del documento vengono uniti in un unico livello, rimuovendo la loro struttura separata. Questa opzione è utile per sanitizzare i documenti semplificando il loro contenuto e garantendo che nessun dato nascosto risieda nei livelli. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Restituisce l'opzione di conversione delle immagini del documento. L'opzione deve essere abilitata manualmente quando si utilizza il metodo {@code #All()} se è necessaria. |
| [getImageDpi](#getImageDpi--) | Restituisce l'opzione per risolvere le immagini delle pagine durante la conversione. |
| [getRemoveAnnotations](#getRemoveAnnotations--) | Restituisce un valore che indica se rimuovere le annotazioni dal documento. Quando è abilitata, tutte le annotazioni presenti nel documento verranno rimosse durante il processo di sanitizzazione. Verranno applicate le annotazioni di redazione. |
| [getRemoveAttachments](#getRemoveAttachments--) | Restituisce l'opzione per rimuovere tutti i file allegati dal documento. Quando è abilitata, garantisce che tutti gli allegati all'interno del PDF vengano eliminati durante il processo di sanitizzazione. |
| [getRemoveJavaScriptsAndActions](#getRemoveJavaScriptsAndActions--) | Restituisce un valore che indica se JavaScript e le azioni associate devono essere rimosse dal documento. Questa opzione è utile per eliminare potenziali vulnerabilità di sicurezza introdotte dagli script incorporati. |
| [getRemoveMetadata](#getRemoveMetadata--) | Restituisce un'opzione per rimuovere i metadati dal documento. Se impostata su true, i metadati come le proprietà del documento e ulteriori informazioni di metadati incorporati verranno rimossi durante la sanitizzazione. |
| [getRemoveSearchIndexAndPrivateInfo](#getRemoveSearchIndexAndPrivateInfo--) | Restituisce un valore che indica se l'indice di ricerca e le informazioni private devono essere rimosse dal documento. Consente la rimozione di indici di ricerca incorporati e dati privati per migliorare la sicurezza e la privacy del documento. |
| [setConvertPagesToImages](#setConvertPagesToImages-boolean-) | Imposta l'opzione per convertire le pagine in immagini. Se questa opzione è abilitata, l'opzione ImageCompressionOptions verrà ignorata. L'opzione deve essere abilitata manualmente quando si utilizza il metodo {@code #All()} se è necessaria. La conversione delle pagine in immagini avverrà dopo la pulizia dei principali dati nascosti, controllata da altre opzioni. |
| [setFlattenForms](#setFlattenForms-boolean-) | Imposta un valore che indica se i moduli nel documento devono essere appiattiti durante il processo di sanitizzazione. L'appiattimento dei moduli converte i campi interattivi in contenuto statico, rendendoli non modificabili o compilabili. |
| [setFlattenLayers](#setFlattenLayers-boolean-) | Imposta l'opzione per appiattire i livelli nel documento PDF. Quando è abilitata, tutti i livelli del documento vengono uniti in un unico livello, rimuovendo la loro struttura separata. Questa opzione è utile per sanitizzare i documenti semplificando il loro contenuto e garantendo che nessun dato nascosto risieda nei livelli. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Imposta l'opzione di conversione delle immagini del documento. L'opzione deve essere abilitata manualmente quando si utilizza il metodo {@code #All()} se è necessaria. |
| [setImageDpi](#setImageDpi-int-) | Imposta l'opzione per risolvere le immagini delle pagine durante la conversione. |
| [setRemoveAnnotations](#setRemoveAnnotations-boolean-) | Imposta un valore che indica se rimuovere le annotazioni dal documento. Quando è abilitata, tutte le annotazioni presenti nel documento verranno rimosse durante il processo di sanitizzazione. Verranno applicate le annotazioni di redazione. |
| [setRemoveAttachments](#setRemoveAttachments-boolean-) | Imposta l'opzione per rimuovere tutti i file allegati dal documento. Quando abilitata, garantisce che tutti gli allegati all'interno del PDF vengano eliminati durante il processo di sanificazione. |
| [setRemoveJavaScriptsAndActions](#setRemoveJavaScriptsAndActions-boolean-) | Imposta un valore che indica se JavaScript e le azioni associate devono essere rimosse dal documento. Questa opzione è utile per eliminare potenziali vulnerabilità di sicurezza introdotte dagli script incorporati. |
| [setRemoveMetadata](#setRemoveMetadata-boolean-) | Imposta un'opzione per rimuovere i metadati dal documento. Se impostata su true, i metadati come le proprietà del documento e le informazioni aggiuntive di metadati incorporati verranno rimossi durante la sanificazione. |
| [setRemoveSearchIndexAndPrivateInfo](#setRemoveSearchIndexAndPrivateInfo-boolean-) | Imposta un valore che indica se l'indice di ricerca e le informazioni private devono essere rimossi dal documento. Consente la rimozione degli indici di ricerca incorporati e dei dati privati per migliorare la sicurezza e la privacy del documento. |

### HiddenDataSanitizationOptions {#HiddenDataSanitizationOptions--}
```
public HiddenDataSanitizationOptions()
```



### all {#all--}
```
public static HiddenDataSanitizationOptions all()
```

Crea una nuova istanza della classe {@link HiddenDataSanitizationOptions} con tutte le opzioni impostate per la sanitizzazione. Questo include abilitare la rimozione di annotazioni, JavaScript, metadati, allegati, indice di ricerca, informazioni private, l'appiattimento di moduli e livelli, mentre disabilita l'opzione per convertire le pagine in immagini. Configurazioni opzionali come {@code ImageCompressionOptions}({@link #getImageCompressionOptions}/{@link #setImageCompressionOptions}) o {@code ConvertPagesToImages}({@link #getConvertPagesToImages}/{@link #setConvertPagesToImages}) possono essere modificate manualmente dopo aver ottenuto l'istanza, poiché non sono attive per impostazione predefinita.

**Returns:**
Un'istanza {@link HiddenDataSanitizationOptions} con tutte le opzioni di sanificazione preconfigurate.

### getConvertPagesToImages {#getConvertPagesToImages--}
```
public final boolean getConvertPagesToImages()
```

Restituisce l'opzione per convertire le pagine in immagini. Se questa opzione è abilitata, l'opzione ImageCompressionOptions verrà ignorata. L'opzione deve essere abilitata manualmente quando si utilizza il metodo {@code #All()} se è necessaria. La conversione delle pagine in immagini avverrà dopo la pulizia dei principali dati nascosti, controllata da altre opzioni.

**Returns:**
l'opzione per convertire le pagine in immagini.

### getFlattenForms {#getFlattenForms--}
```
public final boolean getFlattenForms()
```

Restituisce un valore che indica se i moduli nel documento devono essere appiattiti durante il processo di sanitizzazione. L'appiattimento dei moduli converte i campi interattivi in contenuto statico, rendendoli non modificabili o compilabili.

**Returns:**
un valore che indica se i moduli nel documento devono essere appiattiti durante il processo di sanificazione.

### getFlattenLayers {#getFlattenLayers--}
```
public final boolean getFlattenLayers()
```

Restituisce l'opzione per appiattire i livelli nel documento PDF. Quando è abilitata, tutti i livelli del documento vengono uniti in un unico livello, rimuovendo la loro struttura separata. Questa opzione è utile per sanitizzare i documenti semplificando il loro contenuto e garantendo che nessun dato nascosto risieda nei livelli.

**Returns:**
l'opzione per appiattire i livelli nel documento PDF.

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Restituisce l'opzione di conversione delle immagini del documento. L'opzione deve essere abilitata manualmente quando si utilizza il metodo {@code #All()} se è necessaria.

**Returns:**
l'opzione di conversione delle immagini del documento.

### getImageDpi {#getImageDpi--}
```
public final int getImageDpi()
```

Restituisce l'opzione per risolvere le immagini delle pagine durante la conversione.

**Returns:**
l'opzione per risolvere le immagini delle pagine durante la conversione.

### getRemoveAnnotations {#getRemoveAnnotations--}
```
public final boolean getRemoveAnnotations()
```

Restituisce un valore che indica se rimuovere le annotazioni dal documento. Quando è abilitata, tutte le annotazioni presenti nel documento verranno rimosse durante il processo di sanitizzazione. Verranno applicate le annotazioni di redazione.

**Returns:**
un valore che indica se rimuovere le annotazioni dal documento.

### getRemoveAttachments {#getRemoveAttachments--}
```
public final boolean getRemoveAttachments()
```

Restituisce l'opzione per rimuovere tutti i file allegati dal documento. Quando è abilitata, garantisce che tutti gli allegati all'interno del PDF vengano eliminati durante il processo di sanitizzazione.

**Returns:**
l'opzione per rimuovere tutti i file allegati dal documento.

### getRemoveJavaScriptsAndActions {#getRemoveJavaScriptsAndActions--}
```
public final boolean getRemoveJavaScriptsAndActions()
```

Restituisce un valore che indica se JavaScript e le azioni associate devono essere rimosse dal documento. Questa opzione è utile per eliminare potenziali vulnerabilità di sicurezza introdotte dagli script incorporati.

**Returns:**
un valore che indica se JavaScript e le azioni associate devono essere rimosse dal documento.

### getRemoveMetadata {#getRemoveMetadata--}
```
public final boolean getRemoveMetadata()
```

Restituisce un'opzione per rimuovere i metadati dal documento. Se impostata su true, i metadati come le proprietà del documento e ulteriori informazioni di metadati incorporati verranno rimossi durante la sanitizzazione.

**Returns:**
un'opzione per rimuovere i metadati dal documento.

### getRemoveSearchIndexAndPrivateInfo {#getRemoveSearchIndexAndPrivateInfo--}
```
public final boolean getRemoveSearchIndexAndPrivateInfo()
```

Restituisce un valore che indica se l'indice di ricerca e le informazioni private devono essere rimosse dal documento. Consente la rimozione di indici di ricerca incorporati e dati privati per migliorare la sicurezza e la privacy del documento.

**Returns:**
un valore che indica se l'indice di ricerca e le informazioni private devono essere rimossi dal documento.

### setConvertPagesToImages {#setConvertPagesToImages-boolean-}
```
public final void setConvertPagesToImages(boolean value)
```

Imposta l'opzione per convertire le pagine in immagini. Se questa opzione è abilitata, l'opzione ImageCompressionOptions verrà ignorata. L'opzione deve essere abilitata manualmente quando si utilizza il metodo {@code #All()} se è necessaria. La conversione delle pagine in immagini avverrà dopo la pulizia dei principali dati nascosti, controllata da altre opzioni.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | l'opzione per convertire le pagine in immagini. |

### setFlattenForms {#setFlattenForms-boolean-}
```
public final void setFlattenForms(boolean value)
```

Imposta un valore che indica se i moduli nel documento devono essere appiattiti durante il processo di sanitizzazione. L'appiattimento dei moduli converte i campi interattivi in contenuto statico, rendendoli non modificabili o compilabili.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | un valore che indica se i moduli nel documento devono essere appiattiti durante il processo di sanificazione. |

### setFlattenLayers {#setFlattenLayers-boolean-}
```
public final void setFlattenLayers(boolean value)
```

Imposta l'opzione per appiattire i livelli nel documento PDF. Quando è abilitata, tutti i livelli del documento vengono uniti in un unico livello, rimuovendo la loro struttura separata. Questa opzione è utile per sanitizzare i documenti semplificando il loro contenuto e garantendo che nessun dato nascosto risieda nei livelli.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | l'opzione per appiattire i livelli nel documento PDF. |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Imposta l'opzione di conversione delle immagini del documento. L'opzione deve essere abilitata manualmente quando si utilizza il metodo {@code #All()} se è necessaria.

### setImageDpi {#setImageDpi-int-}
```
public final void setImageDpi(int value)
```

Imposta l'opzione per risolvere le immagini delle pagine durante la conversione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | l'opzione per risolvere le immagini delle pagine durante la conversione. |

### setRemoveAnnotations {#setRemoveAnnotations-boolean-}
```
public final void setRemoveAnnotations(boolean value)
```

Imposta un valore che indica se rimuovere le annotazioni dal documento. Quando è abilitata, tutte le annotazioni presenti nel documento verranno rimosse durante il processo di sanitizzazione. Verranno applicate le annotazioni di redazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | un valore che indica se rimuovere le annotazioni dal documento. |

### setRemoveAttachments {#setRemoveAttachments-boolean-}
```
public final void setRemoveAttachments(boolean value)
```

Imposta l'opzione per rimuovere tutti i file allegati dal documento. Quando abilitata, garantisce che tutti gli allegati all'interno del PDF vengano eliminati durante il processo di sanificazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | l'opzione per rimuovere tutti i file allegati dal documento. |

### setRemoveJavaScriptsAndActions {#setRemoveJavaScriptsAndActions-boolean-}
```
public final void setRemoveJavaScriptsAndActions(boolean value)
```

Imposta un valore che indica se JavaScript e le azioni associate devono essere rimosse dal documento. Questa opzione è utile per eliminare potenziali vulnerabilità di sicurezza introdotte dagli script incorporati.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | un valore che indica se JavaScript e le azioni associate devono essere rimosse dal documento. |

### setRemoveMetadata {#setRemoveMetadata-boolean-}
```
public final void setRemoveMetadata(boolean value)
```

Imposta un'opzione per rimuovere i metadati dal documento. Se impostata su true, i metadati come le proprietà del documento e le informazioni aggiuntive di metadati incorporati verranno rimossi durante la sanificazione.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | un'opzione per rimuovere i metadati dal documento. |

### setRemoveSearchIndexAndPrivateInfo {#setRemoveSearchIndexAndPrivateInfo-boolean-}
```
public final void setRemoveSearchIndexAndPrivateInfo(boolean value)
```

Imposta un valore che indica se l'indice di ricerca e le informazioni private devono essere rimossi dal documento. Consente la rimozione degli indici di ricerca incorporati e dei dati privati per migliorare la sicurezza e la privacy del documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | un valore che indica se l'indice di ricerca e le informazioni private devono essere rimossi dal documento. |
