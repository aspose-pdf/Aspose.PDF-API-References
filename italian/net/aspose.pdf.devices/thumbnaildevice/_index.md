---
title: Class ThumbnailDevice
second_title: Aspose.PDF for .NET API Reference
description: Aspose.Pdf.Devices.Dispositivo di Miniatura. Rappresenta il dispositivo immagine che salva le pagine del documento PDF in immagine miniatura.
type: docs
weight: 3690
url: /it/net/aspose.pdf.devices/thumbnaildevice/
---
## Classe ThumbnailDevice

Rappresenta un dispositivo immagine che salva le pagine del documento pdf in un'immagine in miniatura.

```csharp
public sealed class ThumbnailDevice : ImageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [ThumbnailDevice](thumbnaildevice/#constructor)() | Inizializza una nuova istanza della classe `ThumbnailDevice` con dimensioni predefinite dell'immagine in miniatura (200x200 pixel). |
| [ThumbnailDevice](thumbnaildevice/#constructor_1)(int, int) | Inizializza una nuova istanza della classe `ThumbnailDevice`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Ottiene o imposta il tipo di coordinate della pagina (Media/Crop boxes). Il valore CropBox è utilizzato per impostazione predefinita. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Ottiene o imposta la modalità di presentazione del modulo. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Ottiene l'altezza dell'immagine di output. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Ottiene o imposta le opzioni di rendering. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Ottiene la risoluzione dell'immagine. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Ottiene la larghezza dell'immagine di output. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Process](../../aspose.pdf.devices/thumbnaildevice/process/#process)(Page, Stream) | Converte la pagina in un'immagine in miniatura png e la salva nello stream di output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Esegue alcune operazioni sulla pagina data e salva i risultati nel file. |

### Vedi Anche

* classe [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)