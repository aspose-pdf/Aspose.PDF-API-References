---
title: "Klass OptimizedMemoryStream"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Aspose.Pdf.OptimizedMemoryStream-klass. Definierar en MemoryStream som kan innehålla mer standardkapacitet."
type: docs
weight: 8130
url: /sv/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class

Definierar en MemoryStream som kan innehålla större standardkapacitet.

```csharp
public class OptimizedMemoryStream : Stream
```

## Konstruktörer

| Namn | Beskrivning |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | Initierar en ny instans av klassen `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | Initierar en ny instans av klassen `OptimizedMemoryStream` baserat på den angivna bytearrayen. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | Initierar en ny instans av klassen `OptimizedMemoryStream`. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | Initierar en ny instans av klassen `OptimizedMemoryStream` baserat på den angivna bytearrayen. |

## Egenskaper

| Namn | Beskrivning |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | Hämtar eller anger storleken på de underliggande buffertarna. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | När den åsidosätts i en avledd klass, hämtar ett värde som indikerar om den aktuella strömmen stödjer läsning. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | När den åsidosätts i en avledd klass, hämtar ett värde som indikerar om den aktuella strömmen stödjer sökning. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | När den åsidosätts i en avledd klass, hämtar ett värde som indikerar om den aktuella strömmen stödjer skrivning. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Hämtar eller anger ett värde som indikerar om de underliggande buffertarna ska frigöras vid disponering. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | När den åsidosätts i en avledd klass, hämtar strömmens längd i byte. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | När den åsidosätts i en avledd klass, hämtar eller anger positionen i den aktuella strömmen. |

## Metoder

| Namn | Beskrivning |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | Funktionen är åsidosatt. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | När den åsidosätts i en avledd klass, läser en sekvens av byte från den aktuella strömmen och flyttar positionen i strömmen framåt med antalet lästa byte. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Läser en byte från strömmen och flyttar positionen i strömmen framåt med en byte, eller returnerar -1 om slutet av strömmen har nåtts. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | När den åsidosätts i en avledd klass, anger positionen i den aktuella strömmen. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | När den åsidosätts i en avledd klass, anger längden på den aktuella strömmen. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Konverterar den aktuella strömmen till en bytearray. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | När den åsidosätts i en avledd klass, skriver den en sekvens av byte till den aktuella strömmen och flyttar den aktuella positionen i strömmen framåt med antalet skrivna byte. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Skriver en byte till den aktuella positionen i strömmen och flyttar positionen i strömmen framåt med en byte. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Skriver till den angivna strömmen. |

## Fält

| Namn | Beskrivning |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Standardvärde för buffertstorlek i byte. |

### Se även

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


