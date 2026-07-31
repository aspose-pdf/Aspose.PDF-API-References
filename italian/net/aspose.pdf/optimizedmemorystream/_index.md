---
title: "Classe OptimizedMemoryStream"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.OptimizedMemoryStream. Definisce un MemoryStream che può contenere una capacità maggiore."
type: docs
weight: 8130
url: /it/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class

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
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | Quando sovrascritto in una classe derivata, ottiene un valore che indica se lo stream corrente supporta la lettura. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | Quando sovrascritto in una classe derivata, ottiene un valore che indica se lo stream corrente supporta la ricerca. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | Quando sovrascritto in una classe derivata, ottiene un valore che indica se lo stream corrente supporta la scrittura. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Ottiene o imposta un valore che indica se liberare i buffer sottostanti al momento del dispose. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | Quando sovrascritto in una classe derivata, ottiene la lunghezza in byte dello stream. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | Quando sovrascritto in una classe derivata, ottiene o imposta la posizione all'interno dello stream corrente. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | La funzione è stata sovrascritta. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | Quando sovrascritto in una classe derivata, legge una sequenza di byte dallo stream corrente e avanza la posizione nello stream del numero di byte letti. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Legge un byte dallo stream e avanza la posizione nello stream di un byte, oppure restituisce -1 se è alla fine dello stream. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | Quando sovrascritto in una classe derivata, imposta la posizione all'interno dello stream corrente. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | Quando sovrascritto in una classe derivata, imposta la lunghezza dello stream corrente. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Converte lo stream corrente in un array di byte. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | Quando sovrascritto in una classe derivata, scrive una sequenza di byte nello stream corrente e avanza la posizione corrente all'interno di questo stream del numero di byte scritti. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Scrive un byte nella posizione corrente dello stream e avanza la posizione all'interno dello stream di un byte. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Scrive nello stream specificato. |

## Campi

| Nome | Descrizione |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Valore predefinito della dimensione del buffer in byte. |

### Vedi anche

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


