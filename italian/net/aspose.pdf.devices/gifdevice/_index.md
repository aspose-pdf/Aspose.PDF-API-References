---
title: GifDevice
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta un dispositivo di immagine che aiuta a salvare le pagine del documento pdf in gif.
type: docs
weight: 1700
url: /it/net/aspose.pdf.devices/gifdevice/
---
## GifDevice class

Rappresenta un dispositivo di immagine che aiuta a salvare le pagine del documento pdf in gif.

```csharp
public sealed class GifDevice : ImageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [GifDevice](gifdevice#constructor)() | Inizializza una nuova istanza di[`GifDevice`](../gifdevice) classe con risoluzione predefinita. |
| [GifDevice](gifdevice#constructor_2)(PageSize) | Inizializza una nuova istanza di[`GifDevice`](../gifdevice) classe con dimensione pagina fornita, risoluzione predefinita (=150). |
| [GifDevice](gifdevice#constructor_1)(Resolution) | Inizializza una nuova istanza di[`GifDevice`](../gifdevice) classe.  Risoluzione per il file immagine del risultato, vedere[`Resolution`](../resolution) classe. |
| [GifDevice](gifdevice#constructor_4)(int, int) | Inizializza una nuova istanza di[`GifDevice`](../gifdevice) classe con le dimensioni dell'immagine fornite, risoluzione predefinita (=150). |
| [GifDevice](gifdevice#constructor_3)(PageSize, Resolution) | Inizializza una nuova istanza di[`GifDevice`](../gifdevice)classe con dimensione pagina fornita e risoluzione . |
| [GifDevice](gifdevice#constructor_5)(int, int, Resolution) | Inizializza una nuova istanza di[`GifDevice`](../gifdevice) classe con le dimensioni dell'immagine fornite e la risoluzione . |

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
| override [Process](../../aspose.pdf.devices/gifdevice/process#process)(Page, Stream) | Converte la pagina in gif e la salva nel flusso di output. |
| [Process](../../aspose.pdf.devices/pagedevice/process)(Page, string) | Esegue alcune operazioni sulla pagina data e salva i risultati nel file. |

### Guarda anche

* class [ImageDevice](../imagedevice)
* spazio dei nomi [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
