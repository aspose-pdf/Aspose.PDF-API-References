---
title: BmpDevice
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta un dispositivo di immagine che aiuta a salvare le pagine di documenti pdf in bmp.
type: docs
weight: 1630
url: /it/net/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class

Rappresenta un dispositivo di immagine che aiuta a salvare le pagine di documenti pdf in bmp.

```csharp
public sealed class BmpDevice : ImageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BmpDevice](bmpdevice#constructor)() | Inizializza una nuova istanza di[`BmpDevice`](../bmpdevice) classe con risoluzione predefinita. |
| [BmpDevice](bmpdevice#constructor_2)(PageSize) | Inizializza una nuova istanza di[`BmpDevice`](../bmpdevice) classe con dimensione pagina fornita, risoluzione predefinita (=150). |
| [BmpDevice](bmpdevice#constructor_1)(Resolution) | Inizializza una nuova istanza di[`BmpDevice`](../bmpdevice) classe.  Risoluzione per il file immagine del risultato, vedere[`Resolution`](../resolution) classe. |
| [BmpDevice](bmpdevice#constructor_4)(int, int) | Inizializza una nuova istanza di[`BmpDevice`](../bmpdevice) classe con le dimensioni dell'immagine fornite, risoluzione predefinita (=150). |
| [BmpDevice](bmpdevice#constructor_3)(PageSize, Resolution) | Inizializza una nuova istanza di[`BmpDevice`](../bmpdevice)classe con dimensione pagina fornita e risoluzione . |
| [BmpDevice](bmpdevice#constructor_5)(int, int, Resolution) | Inizializza una nuova istanza di[`BmpDevice`](../bmpdevice) classe con le dimensioni dell'immagine fornite e la risoluzione . |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype) { get; set; } | Ottiene o imposta il tipo di coordinate della pagina (caselle Media/Ritaglia). Il valore CropBox viene utilizzato per impostazione predefinita. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode) { get; set; } | Ottiene o imposta la modalità di presentazione del modulo. |
| [Height](../../aspose.pdf.devices/imagedevice/height) { get; } | Ottiene l'altezza di output dell'immagine. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions) { get; set; } | Ottiene o imposta le opzioni di rendering. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution) { get; } | Ottiene la risoluzione dell'immagine. |
| [Width](../../aspose.pdf.devices/imagedevice/width) { get; } | Ottiene la larghezza di output dell'immagine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Process](../../aspose.pdf.devices/bmpdevice/process#process)(Page, Stream) | Converte la pagina in bmp e la salva nel flusso di output. |
| [Process](../../aspose.pdf.devices/pagedevice/process)(Page, string) | Esegue alcune operazioni sulla pagina data e salva i risultati nel file. |

### Guarda anche

* class [ImageDevice](../imagedevice)
* spazio dei nomi [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->