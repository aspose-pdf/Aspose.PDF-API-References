---
title: OptimizedMemoryStream
second_title: Aspose.PDF för .NET API Referens
description: Definierar en MemoryStream som kan innehålla mer standardkapacitet
type: docs
weight: 5750
url: /sv/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream class

Definierar en MemoryStream som kan innehålla mer standardkapacitet

```csharp
public class OptimizedMemoryStream : Stream
```

## Konstruktörer

| namn | Beskrivning |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream#constructor)() | Initierar en ny instans av[`OptimizedMemoryStream`](../optimizedmemorystream) class. |
| [OptimizedMemoryStream](optimizedmemorystream#constructor_1)(byte[]) | Initierar en ny instans av[`OptimizedMemoryStream`](../optimizedmemorystream) klass baserad på den angivna byte-arrayen. |
| [OptimizedMemoryStream](optimizedmemorystream#constructor_2)(int) | Initierar en ny instans av[`OptimizedMemoryStream`](../optimizedmemorystream) class. |
| [OptimizedMemoryStream](optimizedmemorystream#constructor_3)(int, byte[]) | Initierar en ny instans av[`OptimizedMemoryStream`](../optimizedmemorystream) klass baserad på den angivna byte-arrayen. |

## Egenskaper

| namn | Beskrivning |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize) { get; set; } | Hämtar eller ställer in storleken på de underliggande buffertarna. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread) { get; } | När den åsidosätts i en härledd klass, får ett värde som indikerar om den aktuella strömmen stöder läsning. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek) { get; } | När den åsidosätts i en härledd klass, får ett värde som indikerar om den aktuella strömmen stöder sökning. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite) { get; } | När den åsidosätts i en härledd klass, får ett värde som indikerar om den aktuella strömmen stöder skrivning. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose) { get; set; } | Hämtar eller ställer in ett värde som anger om de underliggande buffertarna ska frigöras vid avyttring. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length) { get; } | När den åsidosätts i en härledd klass, får strömmens längd i byte. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position) { get; set; } | När den åsidosätts i en härledd klass, hämtar eller ställer in positionen inom den aktuella strömmen. |

## Metoder

| namn | Beskrivning |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush)() | Funktionen åsidosatt. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read)(byte[], int, int) | När den åsidosätts i en härledd klass, läser en sekvens av byte från den aktuella strömmen och flyttar fram positionen i strömmen med antalet lästa byte. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte)() | Läser en byte från strömmen och flyttar fram positionen i strömmen med en byte, eller returnerar -1 om i slutet av strömmen. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek)(long, SeekOrigin) | När den åsidosätts i en härledd klass, anger positionen inom den aktuella strömmen. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength)(long) | När den åsidosätts i en härledd klass, anger längden på den aktuella strömmen. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray)() | Konverterar den aktuella strömmen till en byte-array. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write)(byte[], int, int) | När den åsidosätts i en härledd klass, skriver en sekvens av byte till den aktuella strömmen och flyttar fram den aktuella positionen inom denna ström med antalet skrivna byte. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte)(byte) | Skriver en byte till den aktuella positionen i strömmen och flyttar fram positionen i strömmen med en byte. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto)(Stream) | Skriver till den angivna strömmen. |

## Fält

| namn | Beskrivning |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize) | Standardvärde för buffertstorlek i byte. |

### Se även

* namnutrymme [Aspose.Pdf](../../aspose.pdf)
* hopsättning [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
