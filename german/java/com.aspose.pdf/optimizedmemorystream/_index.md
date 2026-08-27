---
title: "OptimizedMemoryStream"
linktitle: "OptimizedMemoryStream"
second_title: "Aspose.PDF für Java API-Referenz"
description: "Definiert einen MemoryStream, der eine höhere Standardkapazität enthalten kann."
type: docs
weight: 3220
url: /de/java/com.aspose.pdf/optimizedmemorystream/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.IO.Stream com.aspose.pdf.OptimizedMemoryStream, com.aspose.ms.System.IO.Stream, com.aspose.pdf.OptimizedMemoryStream

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable

```
public class OptimizedMemoryStream extends com.aspose.ms.System.IO.Stream
```

Definiert einen MemoryStream, der eine höhere Standardkapazität enthalten kann.

## Felder

| Feld | Beschreibung |
| --- | --- |
| [DefaultBufferSize](#DefaultBufferSize) | Standardwert für die Puffergröße in Bytes. |

## Konstruktoren

| Konstruktor | Beschreibung |
| --- | --- |
| [OptimizedMemoryStream](#OptimizedMemoryStream--) | Initialisiert eine neue Instanz der {@link OptimizedMemoryStream} Klasse. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-byte:A-) | Initialisiert eine neue Instanz der {@link OptimizedMemoryStream} Klasse basierend auf dem angegebenen Byte-Array. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-) | Initialisiert eine neue Instanz der {@link OptimizedMemoryStream} Klasse. |
| [OptimizedMemoryStream](#OptimizedMemoryStream-int-byte:A-) | Initialisiert eine neue Instanz der {@link OptimizedMemoryStream} Klasse basierend auf dem angegebenen Byte-Array. |

## Methoden

| Methode | Beschreibung |
| --- | --- |
| [canRead](#canRead--) | Wird in einer abgeleiteten Klasse überschrieben, liefert einen Wert, der angibt, ob der aktuelle Stream das Lesen unterstützt. |
| [canSeek](#canSeek--) | Wird in einer abgeleiteten Klasse überschrieben, liefert einen Wert, der angibt, ob der aktuelle Stream das Suchen unterstützt. |
| [canWrite](#canWrite--) | Wird in einer abgeleiteten Klasse überschrieben, liefert einen Wert, der angibt, ob der aktuelle Stream das Schreiben unterstützt. |
| [flush](#flush--) | Die Funktion wurde überschrieben. |
| [getBufferSize](#getBufferSize--) | Liefert oder setzt die Größe der zugrunde liegenden Puffer. Wert: Die Puffergröße. |
| [getFreeOnDispose](#getFreeOnDispose--) | Liefert oder setzt einen Wert, der angibt, ob die zugrunde liegenden Puffer beim Entladen freigegeben werden sollen. |
| [getLength](#getLength--) | Wird in einer abgeleiteten Klasse überschrieben, liefert die Länge des Streams in Bytes. |
| [getPosition](#getPosition--) | Wird in einer abgeleiteten Klasse überschrieben, liefert oder setzt die Position im aktuellen Stream. |
| [read](#read-byte:A-int-int-) | Wird in einer abgeleiteten Klasse überschrieben, liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die gelesene Anzahl von Bytes. |
| [readByte](#readByte--) | Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist. |
| [seek](#seek-long-int-) | Wird in einer abgeleiteten Klasse überschrieben, setzt die Position im aktuellen Stream. |
| [seek](#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-) | Wird in einer abgeleiteten Klasse überschrieben, setzt die Position im aktuellen Stream. |
| [setBufferSize](#setBufferSize-int-) | Liefert oder setzt die Größe der zugrunde liegenden Puffer. Wert: Die Puffergröße. |
| [setFreeOnDispose](#setFreeOnDispose-boolean-) | Liefert oder setzt einen Wert, der angibt, ob die zugrunde liegenden Puffer beim Entladen freigegeben werden sollen. |
| [setLength](#setLength-long-) | Wird in einer abgeleiteten Klasse überschrieben, setzt die Länge des aktuellen Streams. |
| [setPosition](#setPosition-long-) | Wird in einer abgeleiteten Klasse überschrieben, liefert oder setzt die Position im aktuellen Stream. Die aktuelle Position im Stream. Wert: |
| [toArray](#toArray--) | Konvertiert den aktuellen Stream in ein Byte-Array. |
| [write](#write-byte:A-int-int-) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt es eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |
| [writeByte](#writeByte-byte-) | Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position im Stream um ein Byte. |
| [writeTo](#writeTo-com.aspose.ms.System.IO.Stream-) | Schreibt in den angegebenen Stream. |

### DefaultBufferSize {#DefaultBufferSize}
```
public static final int DefaultBufferSize
```

Standardwert für die Puffergröße in Bytes.

### OptimizedMemoryStream {#OptimizedMemoryStream--}
```
public OptimizedMemoryStream()
```

Initialisiert eine neue Instanz der {@link OptimizedMemoryStream} Klasse.

### OptimizedMemoryStream {#OptimizedMemoryStream-byte:A-}
```
public OptimizedMemoryStream(byte[] buffer)
```

Initialisiert eine neue Instanz der {@link OptimizedMemoryStream} Klasse basierend auf dem angegebenen Byte-Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer |  | Das Array aus vorzeichenlosen Bytes, aus dem der aktuelle Stream erstellt wird. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-}
```
public OptimizedMemoryStream(int bufferSize)
```

Initialisiert eine neue Instanz der {@link OptimizedMemoryStream} Klasse.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffergröße |  | Größe der zugrunde liegenden Puffer. |

### OptimizedMemoryStream {#OptimizedMemoryStream-int-byte:A-}
```
public OptimizedMemoryStream(int bufferSize, byte[] buffer)
```

Initialisiert eine neue Instanz der {@link OptimizedMemoryStream} Klasse basierend auf dem angegebenen Byte-Array.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffergröße |  | Größe der zugrunde liegenden Puffer. |
| Puffer |  | Das Array aus vorzeichenlosen Bytes, aus dem der aktuelle Stream erstellt wird. |

### canRead {#canRead--}
```
public boolean canRead()
```

Wird in einer abgeleiteten Klasse überschrieben, liefert einen Wert, der angibt, ob der aktuelle Stream das Lesen unterstützt.

**Returns:**
true, wenn der Stream das Lesen unterstützt; andernfalls false. Wert:

### canSeek {#canSeek--}
```
public boolean canSeek()
```

Wird in einer abgeleiteten Klasse überschrieben, liefert einen Wert, der angibt, ob der aktuelle Stream das Suchen unterstützt.

**Returns:**
true, wenn der Stream das Suchen unterstützt; andernfalls false. Wert:

### canWrite {#canWrite--}
```
public boolean canWrite()
```

Wird in einer abgeleiteten Klasse überschrieben, liefert einen Wert, der angibt, ob der aktuelle Stream das Schreiben unterstützt.

**Returns:**
true, wenn der Stream das Schreiben unterstützt; andernfalls false. Wert:

### flush {#flush--}
```
public void flush()
```

Die Funktion wurde überschrieben.

### getBufferSize {#getBufferSize--}
```
public final int getBufferSize()
```

Liefert oder setzt die Größe der zugrunde liegenden Puffer. Wert: Die Puffergröße.

**Returns:**
int-Wert

### getFreeOnDispose {#getFreeOnDispose--}
```
public final boolean getFreeOnDispose()
```

Liefert oder setzt einen Wert, der angibt, ob die zugrunde liegenden Puffer beim Entladen freigegeben werden sollen.

**Returns:**
boolescher Wert

### getLength {#getLength--}
```
public long getLength()
```

Wird in einer abgeleiteten Klasse überschrieben, liefert die Länge des Streams in Bytes.

**Returns:**
Ein long-Wert, der die Länge des Streams in Bytes darstellt. Wert:

### getPosition {#getPosition--}
```
public long getPosition()
```

Wird in einer abgeleiteten Klasse überschrieben, liefert oder setzt die Position im aktuellen Stream.

**Returns:**
Die aktuelle Position innerhalb des Streams. Wert:

### read {#read-byte:A-int-int-}
```
public int read(byte[] buffer, int offset, int count)
```

Wird in einer abgeleiteten Klasse überschrieben, liest eine Sequenz von Bytes aus dem aktuellen Stream und verschiebt die Position im Stream um die gelesene Anzahl von Bytes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer |  | Ein Array von Bytes. Wenn diese Methode zurückkehrt, enthält der Puffer das angegebene Byte-Array mit den Werten |
| Versatz |  | Der nullbasierte Byte-Versatz, an dem das Lesen der Daten aus dem aktuellen Stream gespeichert werden soll. |
| Anzahl |  | Die maximale Anzahl von Bytes, die aus dem aktuellen Stream gelesen werden sollen. |

**Returns:**
Die Gesamtzahl der in den Puffer gelesenen Bytes. Diese kann kleiner sein als die angeforderte Anzahl von Bytes, wenn nicht so viele Bytes verfügbar sind, oder null (0), wenn das Ende des Streams erreicht wurde.

### readByte {#readByte--}
```
public int readByte()
```

Liest ein Byte aus dem Stream und verschiebt die Position im Stream um ein Byte, oder gibt -1 zurück, wenn das Ende des Streams erreicht ist.

**Returns:**
Byte oder -1, wenn das Ende des Streams erreicht ist.

### seek {#seek-long-int-}
```
public long seek(long offset, int origin)
```

Wird in einer abgeleiteten Klasse überschrieben, setzt die Position im aktuellen Stream.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Versatz |  | Ein Byte-Versatz relativ zum {@code origin}-Parameter. |
| Ursprung |  | Ein Wert vom Typ {@link SeekOrigin}, der den Bezugspunkt angibt, der zur Ermittlung der neuen Position verwendet wird. |

**Returns:**
Die neue Position innerhalb des aktuellen Streams.

### seek {#seek-long-com.aspose.pdf.OptimizedMemoryStream.SeekOrigin-}
Wird in einer abgeleiteten Klasse überschrieben, setzt die Position im aktuellen Stream.

### setBufferSize {#setBufferSize-int-}
```
public final void setBufferSize(int value)
```

Liefert oder setzt die Größe der zugrunde liegenden Puffer. Wert: Die Puffergröße.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | int-Wert |

### setFreeOnDispose {#setFreeOnDispose-boolean-}
```
public final void setFreeOnDispose(boolean value)
```

Liefert oder setzt einen Wert, der angibt, ob die zugrunde liegenden Puffer beim Entladen freigegeben werden sollen.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | boolescher Wert |

### setLength {#setLength-long-}
```
public void setLength(long value)
```

Wird in einer abgeleiteten Klasse überschrieben, setzt die Länge des aktuellen Streams.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Die gewünschte Länge des aktuellen Streams in Bytes. |

### setPosition {#setPosition-long-}
```
public void setPosition(long value)
```

Wird in einer abgeleiteten Klasse überschrieben, liefert oder setzt die Position im aktuellen Stream. Die aktuelle Position im Stream. Wert:

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  |  |

### toArray {#toArray--}
```
public final byte[] toArray()
```

Konvertiert den aktuellen Stream in ein Byte-Array.

**Returns:**
Ein Array von Bytes

### write {#write-byte:A-int-int-}
```
public void write(byte[] buffer, int offset, int count)
```

Wenn in einer abgeleiteten Klasse überschrieben, schreibt es eine Sequenz von Bytes in den aktuellen Stream und verschiebt die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Puffer |  | Ein Array von Bytes. Diese Methode kopiert {@code count} Bytes von {@code buffer} in den aktuellen Stream. |
| Versatz |  | Der nullbasierte Byte-Offset im {@code buffer}, an dem das Kopieren von Bytes in den aktuellen Stream beginnen soll. |
| Anzahl |  | Die Anzahl der Bytes, die in den aktuellen Stream geschrieben werden sollen. |

### writeByte {#writeByte-byte-}
```
public void writeByte(byte value)
```

Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position im Stream um ein Byte.

**Parameters:**
| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| Wert |  | Das Byte, das in den Stream geschrieben werden soll. |

### writeTo {#writeTo-com.aspose.ms.System.IO.Stream-}
Schreibt in den angegebenen Stream.
