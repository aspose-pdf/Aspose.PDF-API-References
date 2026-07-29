---
title: "HtmlLoadOptions"
linktitle: "HtmlLoadOptions"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta le opzioni per il caricamento/importazione di un file html in un documento pdf."
type: docs
weight: 1960
url: /it/java/com.aspose.pdf/htmlloadoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions com.aspose.pdf.HtmlLoadOptions, com.aspose.pdf.LoadOptions, com.aspose.pdf.HtmlLoadOptions

```
public final class HtmlLoadOptions extends LoadOptions
```

Rappresenta le opzioni per il caricamento/importazione di un file html in un documento pdf.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [HtmlLoadOptions](#HtmlLoadOptions--) | Crea le opzioni di caricamento per convertire html in documento pdf con percorso base vuoto. |
| [HtmlLoadOptions](#HtmlLoadOptions-java.lang.String-) | Crea le opzioni di caricamento per convertire html in documento pdf con percorso base vuoto. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getBasePath](#getBasePath--) | Il percorso/base URL per il file html. |
| [getCustomLoaderOfExternalResources](#getCustomLoaderOfExternalResources--) | A volte è necessario evitare l'uso del caricatore interno di risorse esterne (come immagini o CSS) e fornire un metodo personalizzato che ottenga le risorse richieste da qualche parte. Per esempio, durante l'uso di Aspose.PDF nel cloud l'accesso diretto ai file di riferimento è impossibile: in tal caso dovrebbe essere utilizzato del codice cliente inserito in un metodo speciale, e il delegato che fa riferimento a quel metodo dovrebbe essere assegnato a questo attributo. |
| [getHtmlMediaType](#getHtmlMediaType--) | Ottiene o imposta i possibili tipi di media utilizzati durante il rendering. |
| [getInputEncoding](#getInputEncoding--) | Ottiene l'attributo che specifica la codifica utilizzata per questo documento al momento dell'analisi. Se questo attributo è null, la codifica verrà determinata dal set di caratteri del documento. |
| [getPageInfo](#getPageInfo--) | Ottiene le informazioni della pagina del documento |
| [getPageLayoutOption](#getPageLayoutOption--) | Ottiene o imposta l'opzione di layout. |
| [isEmbedFonts](#isEmbedFonts--) | Ottiene o imposta l'incorporamento dei font nel documento risultante |
| [isPriorityCssPageRule](#isPriorityCssPageRule--) | Ottiene o imposta il flag che specifica che le regole @page definite nel css sovrascriveranno i valori definiti in PageInfo. |
| [isRenderToSinglePage](#isRenderToSinglePage--) | Ottiene o imposta il rendering dell'intero documento in una singola pagina |
| [setCustomLoaderOfExternalResources](#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-) | A volte è necessario evitare l'uso del caricatore interno di risorse esterne (come immagini o CSS) e fornire un metodo personalizzato che ottenga le risorse richieste da qualche parte. |
| [setEmbedFonts](#setEmbedFonts-boolean-) | Ottiene o imposta l'incorporamento dei font nel documento risultante |
| [setHtmlMediaType](#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-) | Ottiene o imposta i possibili tipi di media utilizzati durante il rendering. |
| [setInputEncoding](#setInputEncoding-java.lang.String-) | Imposta l'attributo che specifica la codifica utilizzata per questo documento al momento dell'analisi. Se questo attributo è null, la codifica verrà determinata dal set di caratteri del documento. |
| [setPageInfo](#setPageInfo-com.aspose.pdf.PageInfo-) | Imposta le informazioni della pagina del documento |
| [setPageLayoutOption](#setPageLayoutOption-int-) | Ottiene o imposta l'opzione di layout. |
| [setPriorityCssPageRule](#setPriorityCssPageRule-boolean-) | Ottiene o imposta il flag che specifica che le regole @page definite nel css sovrascriveranno i valori definiti in PageInfo. |
| [setRenderToSinglePage](#setRenderToSinglePage-boolean-) | Ottiene o imposta il rendering dell'intero documento in una singola pagina |

### HtmlLoadOptions {#HtmlLoadOptions--}
```
public HtmlLoadOptions()
```

Crea le opzioni di caricamento per convertire html in documento pdf con percorso base vuoto.

### HtmlLoadOptions {#HtmlLoadOptions-java.lang.String-}
Crea le opzioni di caricamento per convertire html in documento pdf con percorso base vuoto.

### getBasePath {#getBasePath--}
```
public String getBasePath()
```

Il percorso/base URL per il file html.

**Returns:**
valore String

### getCustomLoaderOfExternalResources {#getCustomLoaderOfExternalResources--}
```
public LoadOptions.ResourceLoadingStrategy getCustomLoaderOfExternalResources()
```

A volte è necessario evitare l'uso del caricatore interno di risorse esterne (come immagini o CSS) e fornire un metodo personalizzato che ottenga le risorse richieste da qualche parte. Per esempio, durante l'uso di Aspose.PDF nel cloud l'accesso diretto ai file di riferimento è impossibile: in tal caso dovrebbe essere utilizzato del codice cliente inserito in un metodo speciale, e il delegato che fa riferimento a quel metodo dovrebbe essere assegnato a questo attributo.

**Returns:**
Istanza di ResourceLoadingStrategy

### getHtmlMediaType {#getHtmlMediaType--}
```
public HtmlMediaType getHtmlMediaType()
```

Ottiene o imposta i possibili tipi di media utilizzati durante il rendering.

**Returns:**
Elemento HtmlMediaType

### getInputEncoding {#getInputEncoding--}
```
public String getInputEncoding()
```

Ottiene l'attributo che specifica la codifica utilizzata per questo documento al momento dell'analisi. Se questo attributo è null, la codifica verrà determinata dal set di caratteri del documento.

**Returns:**
valore String

### getPageInfo {#getPageInfo--}
```
public PageInfo getPageInfo()
```

Ottiene le informazioni della pagina del documento

**Returns:**
informazioni pagina

### getPageLayoutOption {#getPageLayoutOption--}
```
public final int getPageLayoutOption()
```

Ottiene o imposta l'opzione di layout.

**Returns:**
Elemento HtmlPageLayoutOption @see HtmlPageLayoutOption

### isEmbedFonts {#isEmbedFonts--}
```
public final boolean isEmbedFonts()
```

Ottiene o imposta l'incorporamento dei font nel documento risultante

**Returns:**
valore booleano

### isPriorityCssPageRule {#isPriorityCssPageRule--}
```
public final boolean isPriorityCssPageRule()
```

Ottiene o imposta il flag che specifica che le regole @page definite nel css sovrascriveranno i valori definiti in PageInfo.

**Returns:**
valore booleano

### isRenderToSinglePage {#isRenderToSinglePage--}
```
public final boolean isRenderToSinglePage()
```

Ottiene o imposta il rendering dell'intero documento in una singola pagina

**Returns:**
valore booleano

### setCustomLoaderOfExternalResources {#setCustomLoaderOfExternalResources-com.aspose.pdf.LoadOptions.ResourceLoadingStrategy-}
A volte è necessario evitare l'uso del caricatore interno di risorse esterne (come immagini o CSS) e fornire un metodo personalizzato che ottenga le risorse richieste da qualche parte.

### setEmbedFonts {#setEmbedFonts-boolean-}
```
public final void setEmbedFonts(boolean value)
```

Ottiene o imposta l'incorporamento dei font nel documento risultante

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setHtmlMediaType {#setHtmlMediaType-com.aspose.pdf.HtmlMediaType-}
Ottiene o imposta i possibili tipi di media utilizzati durante il rendering.

### setInputEncoding {#setInputEncoding-java.lang.String-}
Imposta l'attributo che specifica la codifica utilizzata per questo documento al momento dell'analisi. Se questo attributo è null, la codifica verrà determinata dal set di caratteri del documento.

### setPageInfo {#setPageInfo-com.aspose.pdf.PageInfo-}
Imposta le informazioni della pagina del documento

### setPageLayoutOption {#setPageLayoutOption-int-}
```
public final void setPageLayoutOption(int value)
```

Ottiene o imposta l'opzione di layout.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Elemento HtmlPageLayoutOption @see HtmlPageLayoutOption |

### setPriorityCssPageRule {#setPriorityCssPageRule-boolean-}
```
public final void setPriorityCssPageRule(boolean value)
```

Ottiene o imposta il flag che specifica che le regole @page definite nel css sovrascriveranno i valori definiti in PageInfo.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setRenderToSinglePage {#setRenderToSinglePage-boolean-}
```
public final void setRenderToSinglePage(boolean value)
```

Ottiene o imposta il rendering dell'intero documento in una singola pagina

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |
