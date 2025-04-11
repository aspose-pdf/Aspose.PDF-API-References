---
title: Class DocumentDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.DocumentDevice. Classe astratta per tutti i dispositivi utilizzati per elaborare l'intero documento pdf
type: docs
weight: 3570
url: /it/net/aspose.pdf.devices/documentdevice/
---
## Classe DocumentDevice

Classe astratta per tutti i dispositivi utilizzati per elaborare l'intero documento pdf.

```csharp
public abstract class DocumentDevice : PageDevice
```

## Metodi

| Nome | Descrizione |
| --- | --- |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_2)(Document, Stream) | Elabora l'intero documento e salva i risultati nello stream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_3)(Document, string) | Elabora l'intero documento e salva i risultati nel file. |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Esegue alcune operazioni sulla pagina fornita, ad esempio converte la pagina in un'immagine grafica. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Esegue alcune operazioni sulla pagina fornita e salva i risultati nel file. |
| abstract [Process](../../aspose.pdf.devices/documentdevice/process/#process)(Document, int, int, Stream) | Ogni dispositivo rappresenta un'operazione sul documento, ad esempio possiamo convertire un documento pdf in un altro formato. |
| [Process](../../aspose.pdf.devices/documentdevice/process/#process_1)(Document, int, int, string) | Elabora determinate pagine del documento e salva i risultati nel file. |

### Vedi Anche

* classe [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)