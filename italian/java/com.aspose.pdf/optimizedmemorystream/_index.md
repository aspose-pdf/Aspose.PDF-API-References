---
title: "OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "Riferimento API Aspose.PDF per Java"
description: "Definisce un MemoryStream che può contenere una capacità più standard"
type: docs
weight: 3220
url: /it/java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream com.aspose.pdf.OptimizedMemoryStream, com.aspose.ms.System.IO.Stream, com.aspose.pdf.OptimizedMemoryStream

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class OptimizedMemoryStream extends com.aspose.ms.System.IO.Stream
```

Definisce un MemoryStream che può contenere una capacità più standard

## Campi

| Campo | Descrizione |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | Valore predefinito della dimensione del buffer in byte. |

## Costruttori

| Costruttore | Descrizione |
| --- | --- |
| [OptimizedMemoryStream](#OptimizedMemoryStream--) | Inizializza una nuova istanza della classe {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-byte:A-) | Inizializza una nuova istanza della classe {@link OptimizedMemoryStream} basata sull'array di byte specificato. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-) | Inizializza una nuova istanza della classe {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-byte:A-) | Inizializza una nuova istanza della classe {@link OptimizedMemoryStream} basata sull'array di byte specificato. |

## Metodi

| Metodo | Descrizione |
| --- | --- |
| [canRead](#canRead--) | Quando sovrascritto in una classe derivata, restituisce un valore che indica se lo stream corrente supporta la lettura. |
| [canSeek](#canSeek--) | Quando sovrascritto in una classe derivata, restituisce un valore che indica se lo stream corrente supporta lo spostamento. |
| [canWrite](#canWrite--) | Quando sovrascritto in una classe derivata, restituisce un valore che indica se lo stream corrente supporta la scrittura. |
| [flush](#flush--) | La funzione è stata sovrascritta. |
| [getBufferSize](#getBufferSize--) | Ottiene o imposta la dimensione dei buffer sottostanti. Valore: la dimensione dei buffer. |
| [getFreeOnDispose](#getFreeOnDispose--) | Ottiene o imposta un valore che indica se liberare i buffer sottostanti al momento della chiusura. |
| [getLength](#getLength--) | Quando sovrascritto in una classe derivata, ottiene la lunghezza in byte del flusso. |
| [getPosition](#getPosition--) | Quando sovrascritto in una classe derivata, ottiene o imposta la posizione all'interno del flusso corrente. |
| [read](#read-byte:A-int-int-) | Quando sovrascritto in una classe derivata, legge una sequenza di byte dal flusso corrente e avanza la posizione nel flusso del numero di byte letti. |
| [readByte](#readByte--) | Legge un byte dal flusso e avanza la posizione nel flusso di un byte, oppure restituisce -1 se si è alla fine del flusso. |
| [seek](#seek-long-int-) | Quando sovrascritto in una classe derivata, imposta la posizione all'interno del flusso corrente. |
| [seek](#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-) | Quando sovrascritto in una classe derivata, imposta la posizione all'interno del flusso corrente. |
| [setBufferSize](#setBufferSize-int-) | Ottiene o imposta la dimensione dei buffer sottostanti. Valore: la dimensione dei buffer. |
| [setFreeOnDispose](#setFreeOnDispose-boolean-) | Ottiene o imposta un valore che indica se liberare i buffer sottostanti al momento della chiusura. |
| [setLength](#setLength-long-) | Quando sovrascritto in una classe derivata, imposta la lunghezza del flusso corrente. |
| [setPosition](#setPosition-long-) | Quando sovrascritto in una classe derivata, ottiene o imposta la posizione all'interno del flusso corrente. La posizione corrente nel flusso. Valore: |
| [toArray](#toArray--) | Converte il flusso corrente in un array di byte. |
| [write](#write-byte:A-int-int-) | Quando sovrascritto in una classe derivata, scrive una sequenza di byte nel flusso corrente e avanza la posizione corrente in questo flusso del numero di byte scritti. |
| [writeByte](#writeByte-byte-) | Scrive un byte nella posizione corrente del flusso e avanza la posizione nel flusso di un byte. |
| [writeTo](#writeTo-com.aspose.ms.System.IO.Stream-) | Scrive nel flusso specificato. |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```

Valore predefinito della dimensione del buffer in byte.

### OptimizedMemoryStream {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```

Inizializza una nuova istanza della classe {@link OptimizedMemoryStream}.

### OptimizedMemoryStream {#OptimizedMemoryStream-byte:A-}
```
public OptimizedMemoryStream(byte[] buffer)
```

Inizializza una nuova istanza della classe {@link OptimizedMemoryStream} basata sull'array di byte specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer |  | L'array di byte senza segno da cui creare il flusso corrente. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```

Inizializza una nuova istanza della classe {@link OptimizedMemoryStream}.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bufferSize |  | Dimensione dei buffer sottostanti. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-byte:A-}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```

Inizializza una nuova istanza della classe {@link OptimizedMemoryStream} basata sull'array di byte specificato.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| bufferSize |  | Dimensione dei buffer sottostanti. |
| buffer |  | L'array di byte senza segno da cui creare il flusso corrente. |

### canRead {#canRead--}
```
public boolean canRead()
```

Quando sovrascritto in una classe derivata, restituisce un valore che indica se lo stream corrente supporta la lettura.

**Returns:**
true se il flusso supporta la lettura; altrimenti, false. Valore:

### canSeek {#canSeek--}
```
public boolean canSeek()
```

Quando sovrascritto in una classe derivata, restituisce un valore che indica se lo stream corrente supporta lo spostamento.

**Returns:**
true se il flusso supporta la ricerca; altrimenti, false. Valore:

### canWrite {#canWrite--}
```
public boolean canWrite()
```

Quando sovrascritto in una classe derivata, restituisce un valore che indica se lo stream corrente supporta la scrittura.

**Returns:**
true se il flusso supporta la scrittura; altrimenti, false. Valore:

### flush {#flush--}
```
public void flush()
```

La funzione è stata sovrascritta.

### getBufferSize {#getBufferSize--}
```
public final int getBufferSize()
```

Ottiene o imposta la dimensione dei buffer sottostanti. Valore: la dimensione dei buffer.

**Returns:**
valore int

### getFreeOnDispose {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```

Ottiene o imposta un valore che indica se liberare i buffer sottostanti al momento della chiusura.

**Returns:**
valore booleano

### getLength {#getLength--}
```
public long getLength()
```

Quando sovrascritto in una classe derivata, ottiene la lunghezza in byte del flusso.

**Returns:**
Un valore long che rappresenta la lunghezza del flusso in byte. Valore:

### getPosition {#getPosition--}
```
public long getPosition()
```

Quando sovrascritto in una classe derivata, ottiene o imposta la posizione all'interno del flusso corrente.

**Returns:**
La posizione corrente nel flusso. Valore:

### read {#read-byte:A-int-int-}
```
public int read(byte[] buffer, int offset, int count)
```

Quando sovrascritto in una classe derivata, legge una sequenza di byte dal flusso corrente e avanza la posizione nel flusso del numero di byte letti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer |  | Un array di byte. Quando questo metodo restituisce, il buffer contiene l'array di byte specificato con i valori |
| offset |  | L'offset di byte basato su zero in cui iniziare a memorizzare i dati letti dal flusso corrente. |
| conteggio |  | Il numero massimo di byte da leggere dal flusso corrente. |

**Returns:**
Il numero totale di byte letti nel buffer. Questo può essere inferiore al numero di byte richiesti se tali byte non sono attualmente disponibili, o zero (0) se è stato raggiunto la fine del flusso.

### readByte {#readByte--}
```
public int readByte()
```

Legge un byte dal flusso e avanza la posizione nel flusso di un byte, oppure restituisce -1 se si è alla fine del flusso.

**Returns:**
byte o -1 se si è alla fine del flusso.

### seek {#seek-long-int-}
```
public long seek(long offset, int origin)
```

Quando sovrascritto in una classe derivata, imposta la posizione all'interno del flusso corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| offset |  | Un offset di byte relativo al parametro {@code origin}. |
| origin |  | Un valore di tipo {@link SeekOrigin} che indica il punto di riferimento usato per ottenere la nuova posizione. |

**Returns:**
La nuova posizione all'interno del flusso corrente.

### seek {#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-}
Quando sovrascritto in una classe derivata, imposta la posizione all'interno del flusso corrente.

### setBufferSize {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```

Ottiene o imposta la dimensione dei buffer sottostanti. Valore: la dimensione dei buffer.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore int |

### setFreeOnDispose {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```

Ottiene o imposta un valore che indica se liberare i buffer sottostanti al momento della chiusura.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | valore booleano |

### setLength {#setLength-long-}
```
public void setLength(long value)
```

Quando sovrascritto in una classe derivata, imposta la lunghezza del flusso corrente.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | La lunghezza desiderata del flusso corrente in byte. |

### setPosition {#setPosition-long-}
```
public void setPosition(long value)
```

Quando sovrascritto in una classe derivata, ottiene o imposta la posizione all'interno del flusso corrente. La posizione corrente nel flusso. Valore:

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  |  |

### toArray {#toArray--}
```
public final byte[] toArray()
```

Converte il flusso corrente in un array di byte.

**Returns:**
Un array di byte

### write {#write-byte:A-int-int-}
```
public void write(byte[] buffer, int offset, int count)
```

Quando sovrascritto in una classe derivata, scrive una sequenza di byte nel flusso corrente e avanza la posizione corrente in questo flusso del numero di byte scritti.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| buffer |  | Un array di byte. Questo metodo copia {@code count} byte da {@code buffer} al flusso corrente. |
| offset |  | L'offset di byte basato su zero in {@code buffer} a partire dal quale iniziare a copiare i byte nel flusso corrente. |
| conteggio |  | Il numero di byte da scrivere nel flusso corrente. |

### writeByte {#writeByte-byte-}
```
public void writeByte(byte value)
```

Scrive un byte nella posizione corrente del flusso e avanza la posizione nel flusso di un byte.

**Parameters:**
| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| valore |  | Il byte da scrivere nel flusso. |

### writeTo {#writeTo-com.aspose.ms.System.IO.Stream-}
Scrive nel flusso specificato.
