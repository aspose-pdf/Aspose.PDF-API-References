---
title: ImageDevice
second_title: Aspose.PDF per .NET API Reference
description: Una classe astratta per dispositivi immagine.
type: docs
weight: 1710
url: /it/net/aspose.pdf.devices/imagedevice/
---
## ImageDevice class

Una classe astratta per dispositivi immagine.

```csharp
public abstract class ImageDevice : PageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ImageDevice](imagedevice#constructor)() | Inizializzatore astratto per[`ImageDevice`](../imagedevice) discendenti, imposta la risoluzione su 150x150. |
| [ImageDevice](imagedevice#constructor_2)(PageSize) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe con le dimensioni dell'immagine fornite e la risoluzione predefinita (=150). |
| [ImageDevice](imagedevice#constructor_1)(Resolution) | Inizializzatore astratto per[`ImageDevice`](../imagedevice) discendenti.  Risoluzione per il file immagine del risultato, vedere[`Resolution`](./resolution) classe. |
| [ImageDevice](imagedevice#constructor_4)(int, int) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe con le dimensioni dell'immagine fornite e la risoluzione predefinita (=150). |
| [ImageDevice](imagedevice#constructor_3)(PageSize, Resolution) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe con dimensioni e risoluzione dell'immagine fornite. |
| [ImageDevice](imagedevice#constructor_5)(int, int, Resolution) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe con dimensioni e risoluzione dell'immagine fornite. |

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
| abstract [Process](../../aspose.pdf.devices/pagedevice/process)(Page, Stream) | Esegue alcune operazioni sulla pagina data, ad esempio converte la pagina in un'immagine grafica. |
| [Process](../../aspose.pdf.devices/pagedevice/process)(Page, string) | Esegue alcune operazioni sulla pagina data e salva i risultati nel file. |

### Guarda anche

* class [PageDevice](../pagedevice)
* spazio dei nomi [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
