---
title: Class DocumentDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.DocumentDevice klass. Abstrakt klass för alla enheter som används för att bearbeta hela pdf-dokumentet
type: docs
weight: 3570
url: /sv/net/aspose.pdf.devices/documentdevice/
---
## DocumentDevice klass

Abstrakt klass för alla enheter som används för att bearbeta hela pdf-dokumentet.

```csharp
public abstract class DocumentDevice : PageDevice
```

## Metoder

| Namn | Beskrivning |
| --- | --- |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_2)(Document, Stream) | Bearbetar hela dokumentet och sparar resultat i ström. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_3)(Document, string) | Bearbetar hela dokumentet och sparar resultat i fil. |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Utför någon operation på den angivna sidan, t.ex. konverterar sidan till grafisk bild. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Utför någon operation på den angivna sidan och sparar resultat i fil. |
| abstract [Process](../../aspose.pdf.devices/documentdevice/process/#process)(Document, int, int, Stream) | Varje enhet representerar någon operation på dokumentet, t.ex. vi kan konvertera pdf-dokument till ett annat format. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_1)(Document, int, int, string) | Bearbetar vissa sidor av dokumentet och sparar resultat i fil. |

### Se Även

* klass [PageDevice](../pagedevice/)
* namnrymd [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* sammansättning [Aspose.PDF](../../)