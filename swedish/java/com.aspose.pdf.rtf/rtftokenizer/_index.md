---
title: "RtfTokenizer"
linktitle: "RtfTokenizer"
second_title: "Aspose.PDF för Java API-referens"
description: "Klass utformad för att extrahera strömmat RTF‑innehåll som en uppsättning token."
type: docs
weight: 40
url: /sv/java/com.aspose.pdf.rtf/rtftokenizer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.rtf.RtfTokenizer

```
public class RtfTokenizer extends Object
```

Klass utformad för att extrahera strömmat RTF‑innehåll som en uppsättning token.

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.Stream-) |  |
| [RtfTokenizer](#RtfTokenizer-com.aspose.ms.System.IO.TextReader-) |  |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [readNextToken](#readNextToken--) | Läser indata‑strömmen och returnerar nästa token. |
| [skip](#skip-int-) | Konsumerar och förkastar det angivna antalet tecken från indata‑strömmen. |

### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.Stream-}


### RtfTokenizer {#RtfTokenizer-com.aspose.ms.System.IO.TextReader-}


### readNextToken {#readNextToken--}
```
public final RtfToken readNextToken()
```

Läser indata‑strömmen och returnerar nästa token.

### skip {#skip-int-}
```
public final void skip(int count)
```

Konsumerar och förkastar det angivna antalet tecken från indata‑strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| antal |  | Antalet tecken att hoppa över. |
