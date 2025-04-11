---
title: Class OptimizedMemoryStream
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.OptimizedMemoryStream-Klasse. Definiert einen MemoryStream, der mehr Standardkapazität enthalten kann
type: docs
weight: 7990
url: /de/net/aspose.pdf/optimizedmemorystream/
---
## OptimizedMemoryStream-Klasse

Definiert einen MemoryStream, der mehr Standardkapazität enthalten kann

```csharp
public class OptimizedMemoryStream : Stream
```

## Konstruktoren

| Name | Beschreibung |
| --- | --- |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor)() | Initialisiert eine neue Instanz der `OptimizedMemoryStream`-Klasse. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_1)(byte[]) | Initialisiert eine neue Instanz der `OptimizedMemoryStream`-Klasse basierend auf dem angegebenen Byte-Array. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_2)(int) | Initialisiert eine neue Instanz der `OptimizedMemoryStream`-Klasse. |
| [OptimizedMemoryStream](optimizedmemorystream/#constructor_3)(int, byte[]) | Initialisiert eine neue Instanz der `OptimizedMemoryStream`-Klasse basierend auf dem angegebenen Byte-Array. |

## Eigenschaften

| Name | Beschreibung |
| --- | --- |
| [BufferSize](../../aspose.pdf/optimizedmemorystream/buffersize/) { get; set; } | Ruft die Größe der zugrunde liegenden Puffer ab oder legt sie fest. |
| override [CanRead](../../aspose.pdf/optimizedmemorystream/canread/) { get; } | Wenn in einer abgeleiteten Klasse überschrieben, ruft einen Wert ab, der angibt, ob der aktuelle Stream das Lesen unterstützt. |
| override [CanSeek](../../aspose.pdf/optimizedmemorystream/canseek/) { get; } | Wenn in einer abgeleiteten Klasse überschrieben, ruft einen Wert ab, der angibt, ob der aktuelle Stream das Suchen unterstützt. |
| override [CanWrite](../../aspose.pdf/optimizedmemorystream/canwrite/) { get; } | Wenn in einer abgeleiteten Klasse überschrieben, ruft einen Wert ab, der angibt, ob der aktuelle Stream das Schreiben unterstützt. |
| [FreeOnDispose](../../aspose.pdf/optimizedmemorystream/freeondispose/) { get; set; } | Ruft einen Wert ab oder legt ihn fest, der angibt, ob die zugrunde liegenden Puffer beim Entsorgen freigegeben werden sollen. |
| override [Length](../../aspose.pdf/optimizedmemorystream/length/) { get; } | Wenn in einer abgeleiteten Klasse überschrieben, ruft die Länge in Bytes des Streams ab. |
| override [Position](../../aspose.pdf/optimizedmemorystream/position/) { get; set; } | Wenn in einer abgeleiteten Klasse überschrieben, ruft die Position innerhalb des aktuellen Streams ab oder legt sie fest. |

## Methoden

| Name | Beschreibung |
| --- | --- |
| override [Flush](../../aspose.pdf/optimizedmemorystream/flush/)() | Die Funktion überschrieben. |
| override [Read](../../aspose.pdf/optimizedmemorystream/read/#read)(byte[], int, int) | Wenn in einer abgeleiteten Klasse überschrieben, liest eine Folge von Bytes aus dem aktuellen Stream und verschiebt die Position innerhalb des Streams um die Anzahl der gelesenen Bytes. |
| override [ReadByte](../../aspose.pdf/optimizedmemorystream/readbyte/)() | Liest ein Byte aus dem Stream und verschiebt die Position innerhalb des Streams um ein Byte oder gibt -1 zurück, wenn das Ende des Streams erreicht ist. |
| override [Seek](../../aspose.pdf/optimizedmemorystream/seek/)(long, SeekOrigin) | Wenn in einer abgeleiteten Klasse überschrieben, legt die Position innerhalb des aktuellen Streams fest. |
| override [SetLength](../../aspose.pdf/optimizedmemorystream/setlength/)(long) | Wenn in einer abgeleiteten Klasse überschrieben, legt die Länge des aktuellen Streams fest. |
| [ToArray](../../aspose.pdf/optimizedmemorystream/toarray/)() | Konvertiert den aktuellen Stream in ein Byte-Array. |
| override [Write](../../aspose.pdf/optimizedmemorystream/write/#write)(byte[], int, int) | Wenn in einer abgeleiteten Klasse überschrieben, schreibt eine Folge von Bytes in den aktuellen Stream und verschiebt die aktuelle Position innerhalb dieses Streams um die Anzahl der geschriebenen Bytes. |
| override [WriteByte](../../aspose.pdf/optimizedmemorystream/writebyte/)(byte) | Schreibt ein Byte an die aktuelle Position im Stream und verschiebt die Position innerhalb des Streams um ein Byte. |
| [WriteTo](../../aspose.pdf/optimizedmemorystream/writeto/)(Stream) | Schreibt in den angegebenen Stream. |

## Felder

| Name | Beschreibung |
| --- | --- |
| const [DefaultBufferSize](../../aspose.pdf/optimizedmemorystream/defaultbuffersize/) | Standardwert für die Puffergröße in Bytes. |

### Siehe auch

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)