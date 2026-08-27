---
title: "Classe ImageDevice"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Aspose.Pdf.Devices.ImageDevice class. Una classe astratta per dispositivi immagine."
type: docs
weight: 3730
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
| [ImageDevice](imagedevice/#constructor)() | Inizializzatore astratto per i discendenti di `ImageDevice`, imposta la risoluzione a 150x150. |
| [ImageDevice](imagedevice/#constructor_2)(PageSize) | Inizializza una nuova istanza della classe [`JpegDevice`](../jpegdevice/) con le dimensioni dell'immagine fornite e la risoluzione predefinita (=150). |
| [ImageDevice](imagedevice/#constructor_1)(Resolution) | Inizializzatore astratto per i discendenti di `ImageDevice`. Risoluzione per il file immagine risultante, vedere la classe [`Resolution`](./resolution/). |
| [ImageDevice](imagedevice/#constructor_4)(int, int) | Inizializza una nuova istanza della classe [`JpegDevice`](../jpegdevice/) con le dimensioni dell'immagine fornite e la risoluzione predefinita (=150). |
| [ImageDevice](imagedevice/#constructor_3)(PageSize, Resolution) | Inizializza una nuova istanza della classe [`JpegDevice`](../jpegdevice/) con le dimensioni dell'immagine fornite e la risoluzione. |
| [ImageDevice](imagedevice/#constructor_5)(int, int, Resolution) | Inizializza una nuova istanza della classe [`JpegDevice`](../jpegdevice/) con le dimensioni dell'immagine fornite e la risoluzione. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Ottiene o imposta il tipo di coordinate della pagina (scatole Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Ottiene o imposta la modalità di presentazione del modulo. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Ottiene l'altezza dell'output dell'immagine. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Ottiene o imposta le opzioni di rendering. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Ottiene la risoluzione dell'immagine. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Ottiene la larghezza dell'output dell'immagine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Converte la pagina in Bitmap. |
| abstract [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, Stream) | Esegue qualche operazione sulla pagina fornita, ad es. converte la pagina in un'immagine grafica. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Esegue alcune operazioni sulla pagina fornita e salva i risultati nel file. |

### Vedi anche

* class [PageDevice](../pagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


