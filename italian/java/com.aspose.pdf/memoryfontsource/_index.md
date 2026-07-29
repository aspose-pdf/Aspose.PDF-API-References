---
title: "MemoryFontSource"
linktitle: "MemoryFontSource"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Rappresenta una singola origine di file di carattere."
type: docs
weight: 3040
url: /it/java/com.aspose.pdf/memoryfontsource/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.FontSource com.aspose.pdf.MemoryFontSource, com.aspose.pdf.FontSource, com.aspose.pdf.MemoryFontSource

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, Closeable, AutoCloseable

```
public final class MemoryFontSource extends FontSource implements com.aspose.ms.System.IDisposable, Closeable
```

Rappresenta una singola origine di file di carattere.

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [MemoryFontSource](#MemoryFontSource-byte:A-) | Inizializza una nuova istanza della classe {@code MemoryFontSource}. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [close](#close--) | Chiude tutte le risorse utilizzate da questo documento. |
| [dispose](#dispose--) | Rilascia le risorse interne. Questo metodo è obsoleto, usa close() al suo posto. |
| [equals](#equals-java.lang.Object-) | Verifica se gli oggetti di origine del file di carattere sono uguali. |
| [getFontBytes](#getFontBytes--) | Array di byte del file di font. |
| [hashCode](#hashCode--) | Restituisce un valore di hash code per l'oggetto. Questo metodo è supportato per il beneficio delle tabelle hash, come quelle fornite da {@link java.util.HashMap}. <p> Il contratto generale di {@code hashCode} è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo {@code hashCode} deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti {@code equals} sull'oggetto sia modificata. Questo intero non deve rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo {@code equals(Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>necessario</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti produca risultati interi distinti. Tuttavia, lo sviluppatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe {@code Object} restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio di programmazione Java<span style=\"font-size:70%\"><sup>TM</sup></span>.) |

### MemoryFontSource {#MemoryFontSource-byte:A-}
```
public MemoryFontSource(byte[] fontBytes)
```

Inizializza una nuova istanza della classe {@code MemoryFontSource}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| fontBytes |  | Array di byte del file di font. |

### close {#close--}
```
public void close()
```

Chiude tutte le risorse utilizzate da questo documento.

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Rilascia le risorse interne. Questo metodo è obsoleto, usa close() al suo posto.

### equals {#equals-java.lang.Object-}
Verifica se gli oggetti di origine del file di carattere sono uguali.

### getFontBytes {#getFontBytes--}
```
public byte[] getFontBytes()
```

Array di byte del file di font.

**Returns:**
byte[] array

### hashCode {#hashCode--}
```
public int hashCode()
```

Restituisce un valore di hash code per l'oggetto. Questo metodo è supportato per il beneficio delle tabelle hash, come quelle fornite da {@link java.util.HashMap}. <p> Il contratto generale di {@code hashCode} è: <ul> <li>Ogni volta che viene invocato sullo stesso oggetto più di una volta durante l'esecuzione di un'applicazione Java, il metodo {@code hashCode} deve restituire costantemente lo stesso intero, a condizione che nessuna informazione usata nei confronti {@code equals} sull'oggetto sia modificata. Questo intero non deve rimanere coerente da un'esecuzione dell'applicazione a un'altra esecuzione della stessa applicazione. <li>Se due oggetti sono uguali secondo il metodo {@code equals(Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti deve produrre lo stesso risultato intero. <li>Non è <em>necessario</em> che se due oggetti sono diversi secondo il metodo {@link java.lang.Object#equals(java.lang.Object)}, allora chiamare il metodo {@code hashCode} su ciascuno dei due oggetti produca risultati interi distinti. Tuttavia, lo sviluppatore dovrebbe essere consapevole che produrre risultati interi distinti per oggetti diversi può migliorare le prestazioni delle tabelle hash. </ul> <p> Per quanto ragionevolmente praticabile, il metodo hashCode definito dalla classe {@code Object} restituisce interi distinti per oggetti distinti. (Questo è tipicamente implementato convertendo l'indirizzo interno dell'oggetto in un intero, ma questa tecnica di implementazione non è richiesta dal linguaggio di programmazione Java<span style=\"font-size:70%\"><sup>TM</sup></span>.)

**Returns:**
un valore di hash code per questo oggetto. @see java.lang.Object#equals(java.lang.Object) @see java.lang.System#identityHashCode
