---
title: OptimizedMemoryStream.Read
second_title: Aspose.PDF for .NET API Reference
description: OptimizedMemoryStream-Methode. Wenn in einer abgeleiteten Klasse überschrieben, liest eine Folge von Bytes aus dem aktuellen Stream und verschiebt die Position innerhalb des Streams um die Anzahl der gelesenen Bytes.
type: docs
weight: 100
url: /de/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read-Methode

Wenn in einer abgeleiteten Klasse überschrieben, liest eine Folge von Bytes aus dem aktuellen Stream und verschiebt die Position innerhalb des Streams um die Anzahl der gelesenen Bytes.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| buffer | Byte[] | Ein Array von Bytes. Wenn diese Methode zurückkehrt, enthält der Puffer das angegebene Byte-Array mit den Werten |
| offset | Int32 | Der nullbasierte Byte-Offset, an dem mit dem Speichern der aus dem aktuellen Stream gelesenen Daten begonnen werden soll. |
| count | Int32 | Die maximale Anzahl von Bytes, die aus dem aktuellen Stream gelesen werden sollen. |

### Rückgabewert

Die Gesamtzahl der in den Puffer gelesenen Bytes. Dies kann weniger sein als die angeforderte Anzahl von Bytes, wenn nicht so viele Bytes derzeit verfügbar sind, oder null (0), wenn das Ende des Streams erreicht wurde.

### Siehe auch

* Klasse [OptimizedMemoryStream](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)