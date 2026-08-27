---
title: "OptimizationOptions"
linktitle: "OptimizationOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe che descrive l'algoritmo di ottimizzazione del documento. Un'istanza di questa classe può essere usata come parametro del metodo OptimizeResources()."
type: docs
weight: 40
url: /it/java/com.aspose.pdf.optimization/optimizationoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.OptimizationOptions

```
public class OptimizationOptions extends Object
```

Classe che descrive l'algoritmo di ottimizzazione del documento. Un'istanza di questa classe può essere usata come parametro del metodo OptimizeResources().

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OptimizationOptions](#OptimizationOptions--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [all](#all--) | Crea una strategia di ottimizzazione con tutte le opzioni attivate. Si prega di notare che vengono attivate solo le opzioni che non modificano alcuna funzionalità del documento. Ad esempio, la compressione delle immagini e la rimozione dell'incorporamento dei font non saranno abilitati (e possono essere incorporati manualmente). |
| [getCompressAllContentStreams](#getCompressAllContentStreams--) | Se impostato a {@link}, tutti i flussi di contenuto della pagina non compressi saranno compressi usando il filtro FlateDecode durante {@code Document#OptimizeResources()}. Il valore predefinito è {@link} per preservare la compatibilità retroattiva. |
| [getImageCompressionOptions](#getImageCompressionOptions--) | Insieme di opzioni che descrivono se le immagini nel documento saranno compresse e i parametri della compressione. |
| [getImageEncoding](#getImageEncoding--) | Codifica immagine da utilizzare. |
| [getImageQuality](#getImageQuality--) | Specifica il livello di compressione dell'immagine quando viene usata la flag CompressIamges. |
| [getMaxResoultion](#getMaxResoultion--) | Specifica la risoluzione massima delle immagini. Se un'immagine ha una risoluzione più alta, verrà ridimensionata. |
| [isAllowReusePageContent](#isAllowReusePageContent--) | Se vero, i contenuti della pagina saranno riutilizzati quando il documento viene ottimizzato per pagine uguali. |
| [isCompressImages](#isCompressImages--) | Se questa opzione è impostata su true le immagini verranno compresse nel documento. Il livello di compressione è specificato con la proprietà ImageQuality. |
| [isCompressObjects](#isCompressObjects--) | Se questa opzione è impostata su {@code }, gli oggetti Pdf verranno inseriti in Objest Streams e compressi per ridurre le dimensioni del file pdf. |
| [isLinkDuplicateStreams](#isLinkDuplicateStreams--) | Se questa opzione è impostata su true, i flussi di risorse verranno analizzati. Se vengono trovati flussi duplicati (cioè se il contenuto del flusso è uguale), tali flussi verranno memorizzati come un unico oggetto. Questo consente di ridurre le dimensioni del documento in alcuni casi (ad esempio, quando lo stesso documento è stato concatenato più volte). |
| [isRemovePrivateInfo](#isRemovePrivateInfo--) | Rimuovi le informazioni private (informazioni sulla pagina). |
| [isRemoveUnusedObjects](#isRemoveUnusedObjects--) | Se questa opzione è impostata su true, tutti gli oggetti del documento verranno controllati e gli oggetti inutilizzati (cioè oggetti che non hanno alcun riferimento) vengono rimossi dal documento. |
| [isRemoveUnusedStreams](#isRemoveUnusedStreams--) | Se questa opzione è impostata su true, ogni risorsa viene verificata per l'utilizzo. Se una risorsa non viene mai usata, viene rimossa. Ciò può ridurre le dimensioni del documento, ad esempio quando le pagine sono state estratte dal documento. |
| [isResizeImages](#isResizeImages--) | Se questa opzione è impostata su true e CompressImages è true, le immagini verranno ridimensionate se la risoluzione dell'immagine è maggiore del parametro MaxResolution specificato. |
| [isSubsetFonts](#isSubsetFonts--) | I caratteri verranno convertiti in sottoinsiemi se impostati su true. |
| [isUnembedFonts](#isUnembedFonts--) | Imposta i caratteri non incorporati se impostato su true. |
| [setAllowReusePageContent](#setAllowReusePageContent-boolean-) | Se vero, i contenuti della pagina saranno riutilizzati quando il documento viene ottimizzato per pagine uguali. |
| [setCompressAllContentStreams](#setCompressAllContentStreams-boolean-) | Se impostato a {@link}, tutti i flussi di contenuto della pagina non compressi saranno compressi usando il filtro FlateDecode durante {@code Document#OptimizeResources()}. Il valore predefinito è {@link} per preservare la compatibilità retroattiva. |
| [setCompressImages](#setCompressImages-boolean-) | Se questa opzione è impostata su true le immagini verranno compresse nel documento. Il livello di compressione è specificato con la proprietà ImageQuality. |
| [setCompressObjects](#setCompressObjects-boolean-) | Se questa opzione è impostata su {@code }, gli oggetti Pdf verranno inseriti in Objest Streams e compressi per ridurre le dimensioni del file pdf. |
| [setImageCompressionOptions](#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-) | Insieme di opzioni che descrivono se le immagini nel documento saranno compresse e i parametri della compressione. |
| [setImageEncoding](#setImageEncoding-int-) | Codifica immagine da utilizzare. |
| [setImageQuality](#setImageQuality-int-) | Specifica il livello di compressione dell'immagine quando viene usata la flag CompressIamges. |
| [setLinkDuplicateStreams](#setLinkDuplicateStreams-boolean-) | Se questa opzione è impostata su true, i flussi di risorse verranno analizzati. Se vengono trovati flussi duplicati (cioè se il contenuto del flusso è uguale), tali flussi verranno memorizzati come un unico oggetto. Questo consente di ridurre le dimensioni del documento in alcuni casi (ad esempio, quando lo stesso documento è stato concatenato più volte). |
| [setMaxResoultion](#setMaxResoultion-int-) | Specifica la risoluzione massima delle immagini. Se un'immagine ha una risoluzione più alta, verrà ridimensionata. |
| [setRemovePrivateInfo](#setRemovePrivateInfo-boolean-) | Rimuovi le informazioni private (informazioni sulla pagina). |
| [setRemoveUnusedObjects](#setRemoveUnusedObjects-boolean-) | Se questa opzione è impostata su true, tutti gli oggetti del documento verranno controllati e gli oggetti inutilizzati (cioè oggetti che non hanno alcun riferimento) vengono rimossi dal documento. |
| [setRemoveUnusedStreams](#setRemoveUnusedStreams-boolean-) | Se questa opzione è impostata su true, ogni risorsa viene verificata per l'utilizzo. Se una risorsa non viene mai usata, viene rimossa. Ciò può ridurre le dimensioni del documento, ad esempio quando le pagine sono state estratte dal documento. |
| [setResizeImages](#setResizeImages-boolean-) | Se questa opzione è impostata su true e CompressImages è true, le immagini verranno ridimensionate se la risoluzione dell'immagine è maggiore del parametro MaxResolution specificato. |
| [setSubsetFonts](#setSubsetFonts-boolean-) | I caratteri verranno convertiti in sottoinsiemi se impostati su true. |
| [setUnembedFonts](#setUnembedFonts-boolean-) | Imposta i caratteri non incorporati se impostato su true. |

### OptimizationOptions {#OptimizationOptions--}
```
public OptimizationOptions()
```



### all {#all--}
```
public static OptimizationOptions all()
```

Crea una strategia di ottimizzazione con tutte le opzioni attivate. Si prega di notare che vengono attivate solo le opzioni che non modificano alcuna funzionalità del documento. Ad esempio, la compressione delle immagini e la rimozione dell'incorporamento dei font non saranno abilitati (e possono essere incorporati manualmente).

**Returns:**
Oggetto OptimizationOptions.

### getCompressAllContentStreams {#getCompressAllContentStreams--}
```
public final boolean getCompressAllContentStreams()
```

Se impostato a {@link}, tutti i flussi di contenuto della pagina non compressi saranno compressi usando il filtro FlateDecode durante {@code Document#OptimizeResources()}. Il valore predefinito è {@link} per preservare la compatibilità retroattiva.

**Returns:**
valore booleano

### getImageCompressionOptions {#getImageCompressionOptions--}
```
public final ImageCompressionOptions getImageCompressionOptions()
```

Insieme di opzioni che descrivono se le immagini nel documento saranno compresse e i parametri della compressione.

**Returns:**
Istanza ImageCompressionOptions

### getImageEncoding {#getImageEncoding--}
```
public final int getImageEncoding()
```

Codifica immagine da utilizzare.

**Returns:**
Elemento ImageEncoding

### getImageQuality {#getImageQuality--}
```
@Deprecated public final int getImageQuality()
```

Specifica il livello di compressione dell'immagine quando viene usata la flag CompressIamges.

**Returns:**
valore int @deprecated Si prega di utilizzare ImageCompressionOptions.ImageQuality invece.

### getMaxResoultion {#getMaxResoultion--}
```
public final int getMaxResoultion()
```

Specifica la risoluzione massima delle immagini. Se un'immagine ha una risoluzione più alta, verrà ridimensionata.

**Returns:**
valore int

### isAllowReusePageContent {#isAllowReusePageContent--}
```
public final boolean isAllowReusePageContent()
```

Se vero, i contenuti della pagina saranno riutilizzati quando il documento viene ottimizzato per pagine uguali.

**Returns:**
valore booleano

### isCompressImages {#isCompressImages--}
```
@Deprecated public final boolean isCompressImages()
```

Se questa opzione è impostata su true le immagini verranno compresse nel documento. Il livello di compressione è specificato con la proprietà ImageQuality.

**Returns:**
valore boolean @deprecated Si prega di utilizzare ImageCompressionOptions.CompressImages invece.

### isCompressObjects {#isCompressObjects--}
```
public final boolean isCompressObjects()
```

Se questa opzione è impostata su {@code }, gli oggetti Pdf verranno inseriti in Objest Streams e compressi per ridurre le dimensioni del file pdf.

**Returns:**
valore booleano

### isLinkDuplicateStreams {#isLinkDuplicateStreams--}
```
public final boolean isLinkDuplicateStreams()
```

Se questa opzione è impostata su true, i flussi di risorse verranno analizzati. Se vengono trovati flussi duplicati (cioè se il contenuto del flusso è uguale), tali flussi verranno memorizzati come un unico oggetto. Questo consente di ridurre le dimensioni del documento in alcuni casi (ad esempio, quando lo stesso documento è stato concatenato più volte).

**Returns:**
valore booleano

### isRemovePrivateInfo {#isRemovePrivateInfo--}
```
public final boolean isRemovePrivateInfo()
```

Rimuovi le informazioni private (informazioni sulla pagina).

**Returns:**
valore booleano

### isRemoveUnusedObjects {#isRemoveUnusedObjects--}
```
public final boolean isRemoveUnusedObjects()
```

Se questa opzione è impostata su true, tutti gli oggetti del documento verranno controllati e gli oggetti inutilizzati (cioè oggetti che non hanno alcun riferimento) vengono rimossi dal documento.

**Returns:**
valore booleano

### isRemoveUnusedStreams {#isRemoveUnusedStreams--}
```
public final boolean isRemoveUnusedStreams()
```

Se questa opzione è impostata su true, ogni risorsa viene verificata per l'utilizzo. Se una risorsa non viene mai usata, viene rimossa. Ciò può ridurre le dimensioni del documento, ad esempio quando le pagine sono state estratte dal documento.

**Returns:**
valore booleano

### isResizeImages {#isResizeImages--}
```
@Deprecated public final boolean isResizeImages()
```

Se questa opzione è impostata su true e CompressImages è true, le immagini verranno ridimensionate se la risoluzione dell'immagine è maggiore del parametro MaxResolution specificato.

**Returns:**
valore boolean @deprecated Si prega di utilizzare ImageCompressionOptions.ResizeImages invece.

### isSubsetFonts {#isSubsetFonts--}
```
public final boolean isSubsetFonts()
```

I caratteri verranno convertiti in sottoinsiemi se impostati su true.

**Returns:**
valore booleano

### isUnembedFonts {#isUnembedFonts--}
```
public final boolean isUnembedFonts()
```

Imposta i caratteri non incorporati se impostato su true.

**Returns:**
valore booleano

### setAllowReusePageContent {#setAllowReusePageContent-boolean-}
```
public final void setAllowReusePageContent(boolean value)
```

Se vero, i contenuti della pagina saranno riutilizzati quando il documento viene ottimizzato per pagine uguali.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setCompressAllContentStreams {#setCompressAllContentStreams-boolean-}
```
public final void setCompressAllContentStreams(boolean value)
```

Se impostato a {@link}, tutti i flussi di contenuto della pagina non compressi saranno compressi usando il filtro FlateDecode durante {@code Document#OptimizeResources()}. Il valore predefinito è {@link} per preservare la compatibilità retroattiva.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setCompressImages {#setCompressImages-boolean-}
```
@Deprecated public final void setCompressImages(boolean value)
```

Se questa opzione è impostata su true le immagini verranno compresse nel documento. Il livello di compressione è specificato con la proprietà ImageQuality.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore boolean @deprecated Si prega di utilizzare ImageCompressionOptions.CompressImages invece. |

### setCompressObjects {#setCompressObjects-boolean-}
```
public final void setCompressObjects(boolean value)
```

Se questa opzione è impostata su {@code }, gli oggetti Pdf verranno inseriti in Objest Streams e compressi per ridurre le dimensioni del file pdf.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setImageCompressionOptions {#setImageCompressionOptions-com.aspose.pdf.optimization.ImageCompressionOptions-}
Insieme di opzioni che descrivono se le immagini nel documento saranno compresse e i parametri della compressione.

### setImageEncoding {#setImageEncoding-int-}
```
public final void setImageEncoding(int value)
```

Codifica immagine da utilizzare.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento ImageEncoding |

### setImageQuality {#setImageQuality-int-}
```
@Deprecated public final void setImageQuality(int value)
```

Specifica il livello di compressione dell'immagine quando viene usata la flag CompressIamges.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int @deprecated Si prega di utilizzare ImageCompressionOptions.ImageQuality invece. |

### setLinkDuplicateStreams {#setLinkDuplicateStreams-boolean-}
```
public final void setLinkDuplicateStreams(boolean value)
```

Se questa opzione è impostata su true, i flussi di risorse verranno analizzati. Se vengono trovati flussi duplicati (cioè se il contenuto del flusso è uguale), tali flussi verranno memorizzati come un unico oggetto. Questo consente di ridurre le dimensioni del documento in alcuni casi (ad esempio, quando lo stesso documento è stato concatenato più volte).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setMaxResoultion {#setMaxResoultion-int-}
```
public final void setMaxResoultion(int value)
```

Specifica la risoluzione massima delle immagini. Se un'immagine ha una risoluzione più alta, verrà ridimensionata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setRemovePrivateInfo {#setRemovePrivateInfo-boolean-}
```
public final void setRemovePrivateInfo(boolean value)
```

Rimuovi le informazioni private (informazioni sulla pagina).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRemoveUnusedObjects {#setRemoveUnusedObjects-boolean-}
```
public final void setRemoveUnusedObjects(boolean value)
```

Se questa opzione è impostata su true, tutti gli oggetti del documento verranno controllati e gli oggetti inutilizzati (cioè oggetti che non hanno alcun riferimento) vengono rimossi dal documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRemoveUnusedStreams {#setRemoveUnusedStreams-boolean-}
```
public final void setRemoveUnusedStreams(boolean value)
```

Se questa opzione è impostata su true, ogni risorsa viene verificata per l'utilizzo. Se una risorsa non viene mai usata, viene rimossa. Ciò può ridurre le dimensioni del documento, ad esempio quando le pagine sono state estratte dal documento.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setResizeImages {#setResizeImages-boolean-}
```
@Deprecated public final void setResizeImages(boolean value)
```

Se questa opzione è impostata su true e CompressImages è true, le immagini verranno ridimensionate se la risoluzione dell'immagine è maggiore del parametro MaxResolution specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore boolean @deprecated Si prega di utilizzare ImageCompressionOptions.ResizeImages invece. |

### setSubsetFonts {#setSubsetFonts-boolean-}
```
public final void setSubsetFonts(boolean value)
```

I caratteri verranno convertiti in sottoinsiemi se impostati su true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setUnembedFonts {#setUnembedFonts-boolean-}
```
public final void setUnembedFonts(boolean value)
```

Imposta i caratteri non incorporati se impostato su true.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
