---
title: "Classe ThumbnailDevice"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Devices.ThumbnailDevice. Rappresenta un dispositivo immagine che salva le pagine di documenti pdf in un'immagine Thumbnail"
type: docs
weight: 3810
url: /it/net/aspose.pdf.devices/thumbnaildevice/
---
## ThumbnailDevice class

Rappresenta un dispositivo immagine che salva le pagine del documento pdf in un'immagine Thumbnail.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Inizializza una nuova istanza della classe `ThumbnailDevice` con dimensione predefinita dell'immagine thumbnail (200x200 pixel). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Inizializza una nuova istanza della classe `ThumbnailDevice`. |

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
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Converte la pagina in un'immagine thumbnail png e la salva nello stream di output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Esegue alcune operazioni sulla pagina fornita e salva i risultati nel file. |

### Vedi anche

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


