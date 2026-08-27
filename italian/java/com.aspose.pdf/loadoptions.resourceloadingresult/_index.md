---
title: "LoadOptions.ResourceLoadingResult"
linktitle: "LoadOptions.ResourceLoadingResult"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Risultato del caricamento personalizzato della risorsa"
type: docs
weight: 2820
url: /it/java/com.aspose.pdf/loadoptions.resourceloadingresult/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.LoadOptions.ResourceLoadingResult

```
public static class LoadOptions.ResourceLoadingResult extends Object
```

Risultato del caricamento personalizzato della risorsa

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [ResourceLoadingResult](#ResourceLoadingResult-byte:A-) | Crea un'istanza del risultato di caricamento |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getData](#getData--) | Dati binari caricati con un loader personalizzato - devono essere impostati dopo il caricamento |
| [getEncodingIfKnown](#getEncodingIfKnown--) | A volte la codifica della risorsa è nota dopo o durante il caricamento. In tal caso il codice personalizzato può fornire al convertitore tale informazione tramite questo parametro. È possibile lasciare null in questo parametro se la codifica è sconosciuta o non è rilevante. |
| [getExceptionOfLoadingIfAny](#getExceptionOfLoadingIfAny--) | A volte è impossibile caricare la risorsa richiesta per qualche motivo. L'indisponibilità della risorsa spesso non porta a un arresto delle conversioni e il documento risultante può comunque essere creato (ma forse con una qualità leggermente inferiore, senza immagini, ecc.). Se si verifica un'eccezione durante il caricamento, basta catturarla e inserirla in questo parametro - a volte tale informazione è utile al convertitore per il rendering del risultato. |
| [getMIMETypeIfKnown](#getMIMETypeIfKnown--) | A volte la conoscenza del tipo MIME della risorsa caricata è utile per il convertitore. È possibile fornire il tipo MIME (se noto dopo il caricamento) in questo parametro. Si prega di lasciare il parametro impostato a null quando il tipo MIME è sconosciuto o non è necessario fornire. |
| [isLoadingCancelled](#isLoadingCancelled--) | A volte, per alcuni motivi, il caricamento non dovrebbe avvenire tramite codice personalizzato. In tal caso impostare questo flag su True. In tal caso il convertitore proverà a utilizzare il loader di risorse predefinito interno per ottenere quel risultato (come si comporta nella situazione in cui non è fornita una strategia personalizzata). |
| [setEncodingIfKnown](#setEncodingIfKnown-java.nio.charset.Charset-) | A volte la codifica della risorsa è nota dopo o durante il caricamento. In tal caso il codice personalizzato può fornire al convertitore tale informazione tramite questo parametro. È possibile lasciare null in questo parametro se la codifica è sconosciuta o non è rilevante. |
| [setExceptionOfLoadingIfAny](#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-) | A volte è impossibile caricare la risorsa richiesta per qualche motivo. |
| [setLoadingCancelled](#setLoadingCancelled-boolean-) | A volte, per alcuni motivi, il caricamento non dovrebbe avvenire tramite codice personalizzato. In tal caso impostare questo flag su True. In tal caso il convertitore proverà a utilizzare il loader di risorse predefinito interno per ottenere quel risultato (come si comporta nella situazione in cui non è fornita una strategia personalizzata). |
| [setMIMETypeIfKnown](#setMIMETypeIfKnown-java.lang.String-) | A volte la conoscenza del tipo MIME della risorsa caricata è utile per il convertitore. È possibile fornire il tipo MIME (se noto dopo il caricamento) in questo parametro. Si prega di lasciare il parametro impostato a null quando il tipo MIME è sconosciuto o non è necessario fornire. |

### ResourceLoadingResult {#ResourceLoadingResult-byte:A-}
```
public ResourceLoadingResult(byte[] data)
```

Crea un'istanza del risultato di caricamento

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| dati |  | Il risultato del caricamento personalizzato deve essere sempre fornito, può essere un array di lunghezza zero se è impossibile ottenere alcun risultato. |

### getData {#getData--}
```
public byte[] getData()
```

Dati binari caricati con un loader personalizzato - devono essere impostati dopo il caricamento

**Returns:**
array di valori byte

### getEncodingIfKnown {#getEncodingIfKnown--}
```
public Charset getEncodingIfKnown()
```

A volte la codifica della risorsa è nota dopo o durante il caricamento. In tal caso il codice personalizzato può fornire al convertitore tale informazione tramite questo parametro. È possibile lasciare null in questo parametro se la codifica è sconosciuta o non è rilevante.

**Returns:**
Istanza di Charset

### getExceptionOfLoadingIfAny {#getExceptionOfLoadingIfAny--}
```
public com.aspose.ms.System.Exception getExceptionOfLoadingIfAny()
```

A volte è impossibile caricare la risorsa richiesta per qualche motivo. L'indisponibilità della risorsa spesso non porta a un arresto delle conversioni e il documento risultante può comunque essere creato (ma forse con una qualità leggermente inferiore, senza immagini, ecc.). Se si verifica un'eccezione durante il caricamento, basta catturarla e inserirla in questo parametro - a volte tale informazione è utile al convertitore per il rendering del risultato.

**Returns:**
Eccezione

### getMIMETypeIfKnown {#getMIMETypeIfKnown--}
```
public String getMIMETypeIfKnown()
```

A volte la conoscenza del tipo MIME della risorsa caricata è utile per il convertitore. È possibile fornire il tipo MIME (se noto dopo il caricamento) in questo parametro. Si prega di lasciare il parametro impostato a null quando il tipo MIME è sconosciuto o non è necessario fornire.

**Returns:**
valore String

### isLoadingCancelled {#isLoadingCancelled--}
```
public boolean isLoadingCancelled()
```

A volte, per alcuni motivi, il caricamento non dovrebbe avvenire tramite codice personalizzato. In tal caso impostare questo flag su True. In tal caso il convertitore proverà a utilizzare il loader di risorse predefinito interno per ottenere quel risultato (come si comporta nella situazione in cui non è fornita una strategia personalizzata).

**Returns:**
valore booleano

### setEncodingIfKnown {#setEncodingIfKnown-java.nio.charset.Charset-}
A volte la codifica della risorsa è nota dopo o durante il caricamento. In tal caso il codice personalizzato può fornire al convertitore tale informazione tramite questo parametro. È possibile lasciare null in questo parametro se la codifica è sconosciuta o non è rilevante.

### setExceptionOfLoadingIfAny {#setExceptionOfLoadingIfAny-com.aspose.ms.System.Exception-}
A volte è impossibile caricare la risorsa richiesta per qualche motivo.

### setLoadingCancelled {#setLoadingCancelled-boolean-}
```
public void setLoadingCancelled(boolean loadingCancelled)
```

A volte, per alcuni motivi, il caricamento non dovrebbe avvenire tramite codice personalizzato. In tal caso impostare questo flag su True. In tal caso il convertitore proverà a utilizzare il loader di risorse predefinito interno per ottenere quel risultato (come si comporta nella situazione in cui non è fornita una strategia personalizzata).

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| loadingCancelled |  | valore booleano |

### setMIMETypeIfKnown {#setMIMETypeIfKnown-java.lang.String-}
A volte la conoscenza del tipo MIME della risorsa caricata è utile per il convertitore. È possibile fornire il tipo MIME (se noto dopo il caricamento) in questo parametro. Si prega di lasciare il parametro impostato a null quando il tipo MIME è sconosciuto o non è necessario fornire.
