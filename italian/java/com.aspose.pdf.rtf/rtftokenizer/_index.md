---
title: "RtfTokenizer"
linktitle: "RtfTokenizer"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Classe progettata per estrarre contenuti RTF in streaming come insieme di token."
type: docs
weight: 40
url: /it/java/com.aspose.pdf.rtf/rtftokenizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.rtf.RtfTokenizer

```
public class RtfTokenizer extends Object
```

Classe progettata per estrarre contenuti RTF in streaming come insieme di token.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.Stream-) |  |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.TextReader-) |  |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [readNextToken](#readNextToken--) | Legge lo stream di input e restituisce il token successivo. |
| [skip](#skip-int-) | Consuma e scarta il numero specificato di caratteri dallo stream di input. |

### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.Stream-}


### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.TextReader-}


### readNextToken {#readNextToken--}
```
public final RtfToken readNextToken()
```

Legge lo stream di input e restituisce il token successivo.

### skip {#skip-int-}
```
public final void skip(int count)
```

Consuma e scarta il numero specificato di caratteri dallo stream di input.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| conteggio |  | Il numero di caratteri da saltare. |
