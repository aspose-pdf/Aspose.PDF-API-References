---
title: Class DocumentDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.DocumentDevice-Klasse. Abstrakte Klasse für alle Geräte, die verwendet werden, um das gesamte PDF-Dokument zu verarbeiten
type: docs
weight: 3570
url: /de/net/aspose.pdf.devices/documentdevice/
---
## DocumentDevice-Klasse

Abstrakte Klasse für alle Geräte, die verwendet werden, um das gesamte PDF-Dokument zu verarbeiten.

```csharp
public abstract class DocumentDevice : PageDevice
```

## Methoden

| Name | Beschreibung |
| --- | --- |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_2)(Document, Stream) | Verarbeitet das gesamte Dokument und speichert die Ergebnisse im Stream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_3)(Document, string) | Verarbeitet das gesamte Dokument und speichert die Ergebnisse in einer Datei. |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Führt eine Operation auf der gegebenen Seite aus, z.B. konvertiert die Seite in ein grafisches Bild. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Führt eine Operation auf der gegebenen Seite aus und speichert die Ergebnisse in der Datei. |
| abstract [Process](../../aspose.pdf.devices/documentdevice/process/#process)(Document, int, int, Stream) | Jedes Gerät stellt eine Operation auf dem Dokument dar, z.B. können wir ein PDF-Dokument in ein anderes Format konvertieren. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_1)(Document, int, int, string) | Verarbeitet bestimmte Seiten des Dokuments und speichert die Ergebnisse in einer Datei. |

### Siehe auch

* Klasse [PageDevice](../pagedevice/)
* Namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* Assembly [Aspose.PDF](../../)