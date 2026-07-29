---
title: "UnsignedContentAbsorber.Result"
linktitle: "UnsignedContentAbsorber.Result"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Incapsula il risultato di un'operazione che tenta di estrarre contenuto non firmato da un documento PDF. Questa classe fornisce informazioni sul successo dell'operazione, dettagli di."
type: docs
weight: 40
url: /it/java/com.aspose.pdf.security/unsignedcontentabsorber.result/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.security.UnsignedContentAbsorber.Result

```
public static final class UnsignedContentAbsorber.Result extends Object
```

Incapsula il risultato di un'operazione che tenta di estrarre contenuti non firmati da un documento PDF. Questa classe fornisce informazioni sul successo dell'operazione, dettagli del contenuto non firmato, un messaggio che descrive il risultato e lo stato di copertura delle firme del documento.

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [getCoverage](#getCoverage--) | Ottiene un valore che indica la misura in cui il documento è coperto da firme digitali valide. |
| [getMessage](#getMessage--) | Ottiene un messaggio che descrive il risultato dell'operazione. |
| [getSuccess](#getSuccess--) | Ottiene un valore che indica se l'operazione di recupero del contenuto non firmato dal documento è stata eseguita con successo. |
| [getUnsignedContent](#getUnsignedContent--) | Ottiene un contenuto non firmato. |

### getCoverage {#getCoverage--}
```
public final int getCoverage()
```

Ottiene un valore che indica la misura in cui il documento è coperto da firme digitali valide.

**Returns:**
un valore che indica la misura in cui il documento è coperto da firme digitali valide.

### getMessage {#getMessage--}
```
public final String getMessage()
```

Ottiene un messaggio che descrive il risultato dell'operazione.

**Returns:**
un messaggio che descrive il risultato dell'operazione.

### getSuccess {#getSuccess--}
```
public final boolean getSuccess()
```

Ottiene un valore che indica se l'operazione di recupero del contenuto non firmato dal documento è stata eseguita con successo.

**Returns:**
un valore che indica se l'operazione di recupero del contenuto non firmato dal documento è stata eseguita con successo.

### getUnsignedContent {#getUnsignedContent--}
```
public final UnsignedContentAbsorber.UnsignedContent getUnsignedContent()
```

Ottiene un contenuto non firmato.

**Returns:**
un contenuto non firmato.
