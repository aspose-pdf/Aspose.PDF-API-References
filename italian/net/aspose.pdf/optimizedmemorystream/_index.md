---
title: Class OptimizedMemoryStream
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.OptimizedMemoryStream. Definisce un MemoryStream che può contenere una capacità più standard
type: docs
weight: 7990
url: /it/net/aspose.pdf/optimizedmemorystream/
---
## Classe OptimizedMemoryStream

Definisce un MemoryStream che può contenere una capacità più standard

```csharp
public class OptimizedMemoryStream : Stream
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | Inizializza una nuova istanza della classe `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | Inizializza una nuova istanza della classe `OptimizedMemoryStream` basata sull'array di byte specificato. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | Inizializza una nuova istanza della classe `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | Inizializza una nuova istanza della classe `OptimizedMemoryStream` basata sull'array di byte specificato. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | Ottiene o imposta la dimensione dei buffer sottostanti. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | Quando sovrascritto in una classe derivata, ottiene un valore che indica se il flusso corrente supporta la lettura. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | Quando sovrascritto in una classe derivata, ottiene un valore che indica se il flusso corrente supporta la ricerca. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | Quando sovrascritto in una classe derivata, ottiene un valore che indica se il flusso corrente supporta la scrittura. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Ottiene o imposta un valore che indica se liberare i buffer sottostanti al momento della disposizione. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | Quando sovrascritto in una classe derivata, ottiene la lunghezza in byte del flusso. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | Quando sovrascritto in una classe derivata, ottiene o imposta la posizione all'interno del flusso corrente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | La funzione sovrascritta. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | Quando sovrascritto in una classe derivata, legge una sequenza di byte dal flusso corrente e avanza la posizione all'interno del flusso in base al numero di byte letti. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Legge un byte dal flusso e avanza la posizione all'interno del flusso di un byte, oppure restituisce -1 se si trova alla fine del flusso. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | Quando sovrascritto in una classe derivata, imposta la posizione all'interno del flusso corrente. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | Quando sovrascritto in una classe derivata, imposta la lunghezza del flusso corrente. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Converte il flusso corrente in un array di byte. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | Quando sovrascritto in una classe derivata, scrive una sequenza di byte nel flusso corrente e avanza la posizione corrente all'interno di questo flusso in base al numero di byte scritti. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Scrive un byte nella posizione corrente del flusso e avanza la posizione all'interno del flusso di un byte. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Scrive nel flusso specificato. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Valore predefinito della dimensione del buffer in byte. |

### Vedi Anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)