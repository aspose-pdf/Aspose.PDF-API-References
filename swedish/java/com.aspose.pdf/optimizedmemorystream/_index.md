---
title: "OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "Aspose.PDF för Java API-referens"
description: "Definierar en MemoryStream som kan innehålla större standardkapacitet"
type: docs
weight: 3220
url: /sv/java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream com.aspose.pdf.OptimizedMemoryStream, com.aspose.ms.System.IO.Stream, com.aspose.pdf.OptimizedMemoryStream

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class OptimizedMemoryStream extends com.aspose.ms.System.IO.Stream
```

Definierar en MemoryStream som kan innehålla större standardkapacitet

## Fält

| Fält | Beskrivning |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | Standardbuffertstorlek i byte. |

## Konstruktörer

| Konstruktör | Beskrivning |
| --- | --- |
| [OptimizedMemoryStream](#OptimizedMemoryStream--) | Initierar en ny instans av klassen {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-byte:A-) | Initierar en ny instans av klassen {@link OptimizedMemoryStream} baserat på den angivna byte‑arrayen. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-) | Initierar en ny instans av klassen {@link OptimizedMemoryStream}. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-byte:A-) | Initierar en ny instans av klassen {@link OptimizedMemoryStream} baserat på den angivna byte‑arrayen. |

## Metoder

| Metod | Beskrivning |
| --- | --- |
| [canRead](#canRead--) | När den åsidosätts i en avledd klass, hämtar ett värde som indikerar om den aktuella strömmen stöder läsning. |
| [canSeek](#canSeek--) | När den åsidosätts i en avledd klass, hämtar ett värde som indikerar om den aktuella strömmen stöder sökning. |
| [canWrite](#canWrite--) | När den åsidosätts i en avledd klass, hämtar ett värde som indikerar om den aktuella strömmen stöder skrivning. |
| [flush](#flush--) | Funktionen åsidosattes. |
| [getBufferSize](#getBufferSize--) | Hämtar eller anger storleken på de underliggande buffertarna. Värde: Buffertarnas storlek. |
| [getFreeOnDispose](#getFreeOnDispose--) | Hämtar eller anger ett värde som indikerar om de underliggande buffertarna ska frigöras vid avyttring. |
| [getLength](#getLength--) | När den åsidosätts i en avledd klass, hämtar längden i byte för strömmen. |
| [getPosition](#getPosition--) | När den åsidosätts i en avledd klass, hämtar eller anger positionen i den aktuella strömmen. |
| [read](#read-byte:A-int-int-) | När den åsidosätts i en avledd klass, läser en sekvens av byte från den aktuella strömmen och flyttar positionen i strömmen framåt med antalet lästa byte. |
| [readByte](#readByte--) | Läser en byte från strömmen och flyttar positionen i strömmen framåt med en byte, eller returnerar -1 om slutet av strömmen har nåtts. |
| [seek](#seek-long-int-) | När den åsidosätts i en avledd klass, anger positionen i den aktuella strömmen. |
| [seek](#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-) | När den åsidosätts i en avledd klass, anger positionen i den aktuella strömmen. |
| [setBufferSize](#setBufferSize-int-) | Hämtar eller anger storleken på de underliggande buffertarna. Värde: Buffertarnas storlek. |
| [setFreeOnDispose](#setFreeOnDispose-boolean-) | Hämtar eller anger ett värde som indikerar om de underliggande buffertarna ska frigöras vid avyttring. |
| [setLength](#setLength-long-) | När den åsidosätts i en avledd klass, anger längden på den aktuella strömmen. |
| [setPosition](#setPosition-long-) | När den åsidosätts i en avledd klass, hämtar eller anger positionen i den aktuella strömmen. Den aktuella positionen i strömmen. Värde: |
| [toArray](#toArray--) | Konverterar den aktuella strömmen till en bytearray. |
| [write](#write-byte:A-int-int-) | När den åsidosätts i en avledd klass, skriver en sekvens av byte till den aktuella strömmen och flyttar den aktuella positionen i denna ström framåt med antalet skrivna byte. |
| [writeByte](#writeByte-byte-) | Skriver en byte till den aktuella positionen i strömmen och flyttar positionen i strömmen framåt med en byte. |
| [writeTo](#writeTo-com.aspose.ms.System.IO.Stream-) | Skriver till den angivna strömmen. |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```

Standardbuffertstorlek i byte.

### OptimizedMemoryStream {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```

Initierar en ny instans av klassen {@link OptimizedMemoryStream}.

### OptimizedMemoryStream {#OptimizedMemoryStream-byte:A-}
```
public OptimizedMemoryStream(byte[] buffer)
```

Initierar en ny instans av klassen {@link OptimizedMemoryStream} baserat på den angivna byte‑arrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffert |  | Arrayen av osignerade byte som ska användas för att skapa den aktuella strömmen. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```

Initierar en ny instans av klassen {@link OptimizedMemoryStream}.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bufferSize |  | Storlek på de underliggande buffertarna. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-byte:A-}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```

Initierar en ny instans av klassen {@link OptimizedMemoryStream} baserat på den angivna byte‑arrayen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| bufferSize |  | Storlek på de underliggande buffertarna. |
| buffert |  | Arrayen av osignerade byte som ska användas för att skapa den aktuella strömmen. |

### canRead {#canRead--}
```
public boolean canRead()
```

När den åsidosätts i en avledd klass, hämtar ett värde som indikerar om den aktuella strömmen stöder läsning.

**Returns:**
Sant om strömmen stöder läsning; annars falskt. Värde:

### canSeek {#canSeek--}
```
public boolean canSeek()
```

När den åsidosätts i en avledd klass, hämtar ett värde som indikerar om den aktuella strömmen stöder sökning.

**Returns:**
Sant om strömmen stöder sökning; annars falskt. Värde:

### canWrite {#canWrite--}
```
public boolean canWrite()
```

När den åsidosätts i en avledd klass, hämtar ett värde som indikerar om den aktuella strömmen stöder skrivning.

**Returns:**
Sant om strömmen stöder skrivning; annars falskt. Värde:

### flush {#flush--}
```
public void flush()
```

Funktionen åsidosattes.

### getBufferSize {#getBufferSize--}
```
public final int getBufferSize()
```

Hämtar eller anger storleken på de underliggande buffertarna. Värde: Buffertarnas storlek.

**Returns:**
int‑värde

### getFreeOnDispose {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```

Hämtar eller anger ett värde som indikerar om de underliggande buffertarna ska frigöras vid avyttring.

**Returns:**
booleskt värde

### getLength {#getLength--}
```
public long getLength()
```

När den åsidosätts i en avledd klass, hämtar längden i byte för strömmen.

**Returns:**
Ett långt värde som representerar strömmens längd i byte. Värde:

### getPosition {#getPosition--}
```
public long getPosition()
```

När den åsidosätts i en avledd klass, hämtar eller anger positionen i den aktuella strömmen.

**Returns:**
Den aktuella positionen i strömmen. Värde:

### read {#read-byte:A-int-int-}
```
public int read(byte[] buffer, int offset, int count)
```

När den åsidosätts i en avledd klass, läser en sekvens av byte från den aktuella strömmen och flyttar positionen i strömmen framåt med antalet lästa byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffert |  | En bytearray. När den här metoden återvänder innehåller bufferten den angivna bytearrayen med värdena |
| offset |  | Den nollbaserade byteoffseten vid vilken lagring av data läst från den aktuella strömmen ska påbörjas. |
| antal |  | Det maximala antalet byte som ska läsas från den aktuella strömmen. |

**Returns:**
Det totala antalet byte som lästs in i bufferten. Detta kan vara mindre än det begärda antalet byte om så många byte för närvarande inte är tillgängliga, eller noll (0) om slutet av strömmen har nåtts.

### readByte {#readByte--}
```
public int readByte()
```

Läser en byte från strömmen och flyttar positionen i strömmen framåt med en byte, eller returnerar -1 om slutet av strömmen har nåtts.

**Returns:**
byte eller -1 om slutet av strömmen har nåtts.

### seek {#seek-long-int-}
```
public long seek(long offset, int origin)
```

När den åsidosätts i en avledd klass, anger positionen i den aktuella strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| offset |  | En byteoffset relativt parametern {@code origin}. |
| origin |  | Ett värde av typen {@link SeekOrigin} som indikerar referenspunkten som används för att erhålla den nya positionen. |

**Returns:**
Den nya positionen i den aktuella strömmen.

### seek {#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-}
När den åsidosätts i en avledd klass, anger positionen i den aktuella strömmen.

### setBufferSize {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```

Hämtar eller anger storleken på de underliggande buffertarna. Värde: Buffertarnas storlek.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | int‑värde |

### setFreeOnDispose {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```

Hämtar eller anger ett värde som indikerar om de underliggande buffertarna ska frigöras vid avyttring.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | booleskt värde |

### setLength {#setLength-long-}
```
public void setLength(long value)
```

När den åsidosätts i en avledd klass, anger längden på den aktuella strömmen.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Den önskade längden på den aktuella strömmen i byte. |

### setPosition {#setPosition-long-}
```
public void setPosition(long value)
```

När den åsidosätts i en avledd klass, hämtar eller anger positionen i den aktuella strömmen. Den aktuella positionen i strömmen. Värde:

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  |  |

### toArray {#toArray--}
```
public final byte[] toArray()
```

Konverterar den aktuella strömmen till en bytearray.

**Returns:**
En bytearray

### write {#write-byte:A-int-int-}
```
public void write(byte[] buffer, int offset, int count)
```

När den åsidosätts i en avledd klass, skriver en sekvens av byte till den aktuella strömmen och flyttar den aktuella positionen i denna ström framåt med antalet skrivna byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| buffert |  | En bytearray. Denna metod kopierar {@code count} byte från {@code buffer} till den aktuella strömmen. |
| offset |  | Den nollbaserade byteoffseten i {@code buffer} vid vilken kopieringen av byte till den aktuella strömmen ska påbörjas. |
| antal |  | Antalet byte som ska skrivas till den aktuella strömmen. |

### writeByte {#writeByte-byte-}
```
public void writeByte(byte value)
```

Skriver en byte till den aktuella positionen i strömmen och flyttar positionen i strömmen framåt med en byte.

**Parameters:**
| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| värde |  | Byte som ska skrivas till strömmen. |

### writeTo {#writeTo-com.aspose.ms.System.IO.Stream-}
Skriver till den angivna strömmen.
