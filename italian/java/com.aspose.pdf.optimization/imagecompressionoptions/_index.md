---
title: "ImageCompressionOptions"
linktitle: "ImageCompressionOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "La classe contiene un insieme di opzioni per la compressione delle immagini."
type: docs
weight: 10
url: /it/java/com.aspose.pdf.optimization/imagecompressionoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.optimization.ImageCompressionOptions

```
public class ImageCompressionOptions extends Object
```

La classe contiene un insieme di opzioni per la compressione delle immagini.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ImageCompressionOptions](#ImageCompressionOptions--) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getEncoding](#getEncoding--) | Ottiene o imposta la codifica utilizzata per memorizzare le immagini. |
| [getImageQuality](#getImageQuality--) | Specifica il livello di compressione dell'immagine quando viene utilizzata la flag CompressImages. |
| [getMaxResolution](#getMaxResolution--) | Specifica la risoluzione massima delle immagini. Se l'immagine ha una risoluzione più alta, verrà ridimensionata. |
| [getResizeImages](#getResizeImages--) | Se questa flag è impostata su true e CompressImages è true, le immagini verranno ridimensionate se la risoluzione dell'immagine è superiore al parametro MaxResolution specificato. |
| [getVersion](#getVersion--) | Versione dell'algoritmo di compressione. I valori possibili sono: 1. compressione standard, 2. fast (compressione migliorata che è più veloce della standard ma potrebbe non essere applicabile a tutte le immagini), 3. mixed (la compressione standard viene applicata alle immagini che non possono essere compresse dall'algoritmo più veloce; questo può fornire la migliore compressione ma è più lento rispetto all'algoritmo \"fast\". La versione \"Fast\" non è applicabile al ridimensionamento delle immagini (verrà utilizzato il metodo standard). Il valore predefinito è \"Standard\"). |
| [isCompressImages](#isCompressImages--) | Se questa flag è impostata su true, le immagini verranno compresse nel documento. Il livello di compressione è specificato con la proprietà ImageQuality. |
| [setCompressImages](#setCompressImages-boolean-) | Se questa flag è impostata su true, le immagini verranno compresse nel documento. Il livello di compressione è specificato con la proprietà ImageQuality. |
| [setEncoding](#setEncoding-int-) | Ottiene o imposta la codifica utilizzata per memorizzare le immagini. |
| [setImageQuality](#setImageQuality-int-) | Specifica il livello di compressione dell'immagine quando viene utilizzata la flag CompressImages. |
| [setMaxResolution](#setMaxResolution-int-) | Specifica la risoluzione massima delle immagini. Se l'immagine ha una risoluzione più alta, verrà ridimensionata. |
| [setResizeImages](#setResizeImages-boolean-) | Se questa flag è impostata su true e CompressImages è true, le immagini verranno ridimensionate se la risoluzione dell'immagine è superiore al parametro MaxResolution specificato. |
| [setVersion](#setVersion-int-) | Versione dell'algoritmo di compressione. I valori possibili sono: 1. compressione standard, 2. fast (compressione migliorata che è più veloce della standard ma potrebbe non essere applicabile a tutte le immagini), 3. mixed (la compressione standard viene applicata alle immagini che non possono essere compresse dall'algoritmo più veloce; questo può fornire la migliore compressione ma è più lento rispetto all'algoritmo \"fast\". La versione \"Fast\" non è applicabile al ridimensionamento delle immagini (verrà utilizzato il metodo standard). Il valore predefinito è \"Standard\"). |

### ImageCompressionOptions {#ImageCompressionOptions--}
```
public ImageCompressionOptions()
```



### getEncoding {#getEncoding--}
```
public final int getEncoding()
```

Ottiene o imposta la codifica utilizzata per memorizzare le immagini.

**Returns:**
Elemento ImageEncoding

### getImageQuality {#getImageQuality--}
```
public final int getImageQuality()
```

Specifica il livello di compressione dell'immagine quando viene utilizzata la flag CompressImages.

**Returns:**
valore int

### getMaxResolution {#getMaxResolution--}
```
public final int getMaxResolution()
```

Specifica la risoluzione massima delle immagini. Se l'immagine ha una risoluzione più alta, verrà ridimensionata.

**Returns:**
valore int

### getResizeImages {#getResizeImages--}
```
public final boolean getResizeImages()
```

Se questa flag è impostata su true e CompressImages è true, le immagini verranno ridimensionate se la risoluzione dell'immagine è superiore al parametro MaxResolution specificato.

**Returns:**
valore booleano

### getVersion {#getVersion--}
```
public final int getVersion()
```

Versione dell'algoritmo di compressione. I valori possibili sono: 1. compressione standard, 2. fast (compressione migliorata che è più veloce della standard ma potrebbe non essere applicabile a tutte le immagini), 3. mixed (la compressione standard viene applicata alle immagini che non possono essere compresse dall'algoritmo più veloce; questo può fornire la migliore compressione ma è più lento rispetto all'algoritmo \"fast\". La versione \"Fast\" non è applicabile al ridimensionamento delle immagini (verrà utilizzato il metodo standard). Il valore predefinito è \"Standard\").

**Returns:**
valore int

### isCompressImages {#isCompressImages--}
```
public final boolean isCompressImages()
```

Se questa flag è impostata su true, le immagini verranno compresse nel documento. Il livello di compressione è specificato con la proprietà ImageQuality.

**Returns:**
valore booleano

### setCompressImages {#setCompressImages-boolean-}
```
public final void setCompressImages(boolean value)
```

Se questa flag è impostata su true, le immagini verranno compresse nel documento. Il livello di compressione è specificato con la proprietà ImageQuality.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setEncoding {#setEncoding-int-}
```
public final void setEncoding(int value)
```

Ottiene o imposta la codifica utilizzata per memorizzare le immagini.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento ImageEncoding |

### setImageQuality {#setImageQuality-int-}
```
public final void setImageQuality(int value)
```

Specifica il livello di compressione dell'immagine quando viene utilizzata la flag CompressImages.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setMaxResolution {#setMaxResolution-int-}
```
public final void setMaxResolution(int value)
```

Specifica la risoluzione massima delle immagini. Se l'immagine ha una risoluzione più alta, verrà ridimensionata.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setResizeImages {#setResizeImages-boolean-}
```
public final void setResizeImages(boolean value)
```

Se questa flag è impostata su true e CompressImages è true, le immagini verranno ridimensionate se la risoluzione dell'immagine è superiore al parametro MaxResolution specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setVersion {#setVersion-int-}
```
public final void setVersion(int value)
```

Versione dell'algoritmo di compressione. I valori possibili sono: 1. compressione standard, 2. fast (compressione migliorata che è più veloce della standard ma potrebbe non essere applicabile a tutte le immagini), 3. mixed (la compressione standard viene applicata alle immagini che non possono essere compresse dall'algoritmo più veloce; questo può fornire la migliore compressione ma è più lento rispetto all'algoritmo \"fast\". La versione \"Fast\" non è applicabile al ridimensionamento delle immagini (verrà utilizzato il metodo standard). Il valore predefinito è \"Standard\").

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |
