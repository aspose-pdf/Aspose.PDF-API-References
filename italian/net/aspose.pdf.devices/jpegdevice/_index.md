---
title: JpegDevice
second_title: Aspose.PDF per .NET API Reference
description: Rappresenta un dispositivo di immagine che aiuta a salvare le pagine di documenti pdf in jpeg.
type: docs
weight: 1720
url: /it/net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice class

Rappresenta un dispositivo di immagine che aiuta a salvare le pagine di documenti pdf in jpeg.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [JpegDevice](jpegdevice#constructor)() | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe con risoluzione predefinita e qualità massima. |
| [JpegDevice](jpegdevice#constructor_6)(int) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe. |
| [JpegDevice](jpegdevice#constructor_3)(PageSize) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe con dimensione pagina fornita, risoluzione predefinita (=150) e qualità massima. |
| [JpegDevice](jpegdevice#constructor_1)(Resolution) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe.  Risoluzione per il file immagine del risultato, vedere[`Resolution`](../resolution) classe. |
| [JpegDevice](jpegdevice#constructor_7)(int, int) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe con dimensioni dell'immagine fornite, risoluzione predefinita (=150) e qualità massima. |
| [JpegDevice](jpegdevice#constructor_4)(PageSize, Resolution) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice)classe con dimensione pagina fornita, risoluzione e qualità massima. |
| [JpegDevice](jpegdevice#constructor_2)(Resolution, int) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe. |
| [JpegDevice](jpegdevice#constructor_8)(int, int, Resolution) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe con dimensioni dell'immagine fornite, risoluzione e qualità massima. |
| [JpegDevice](jpegdevice#constructor_5)(PageSize, Resolution, int) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe con dimensione pagina fornita, risoluzione e qualità . |
| [JpegDevice](jpegdevice#constructor_9)(int, int, Resolution, int) | Inizializza una nuova istanza di[`JpegDevice`](../jpegdevice) classe con dimensioni dell'immagine fornite, risoluzione e qualità . |

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
| override [Process](../../aspose.pdf.devices/jpegdevice/process#process)(Page, Stream) | Converte la pagina in jpeg e la salva nel flusso di output. |
| [Process](../../aspose.pdf.devices/pagedevice/process)(Page, string) | Esegue alcune operazioni sulla pagina data e salva i risultati nel file. |

### Guarda anche

* class [ImageDevice](../imagedevice)
* spazio dei nomi [Aspose.Pdf.Devices](../../aspose.pdf.devices)
* assemblea [Aspose.PDF](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
