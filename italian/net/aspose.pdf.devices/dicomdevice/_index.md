---
title: Class DicomDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.DicomDevice. Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf nel formato Dicom
type: docs
weight: 3560
url: /it/net/aspose.pdf.devices/dicomdevice/
---
## Classe DicomDevice

Rappresenta un dispositivo immagine che aiuta a salvare le pagine del documento pdf nel formato Dicom.

```csharp
public sealed class DicomDevice : ImageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [DicomDevice](dicomdevice/#constructor)() | Inizializza una nuova istanza della classe `DicomDevice` con risoluzione predefinita. |
| [DicomDevice](dicomdevice/#constructor_2)(PageSize) | Inizializza una nuova istanza della classe `DicomDevice` con la dimensione della pagina fornita, con risoluzione predefinita (=150). |
| [DicomDevice](dicomdevice/#constructor_1)(Resolution) | Inizializza una nuova istanza della classe `DicomDevice`. Risoluzione per il file immagine risultante, vedere la classe [`Resolution`](../resolution/). |
| [DicomDevice](dicomdevice/#constructor_4)(int, int) | Inizializza una nuova istanza della classe `DicomDevice` con le dimensioni dell'immagine fornite, con risoluzione predefinita (=150). |
| [DicomDevice](dicomdevice/#constructor_3)(PageSize, Resolution) | Inizializza una nuova istanza della classe `DicomDevice` con la dimensione della pagina e la risoluzione fornite. |
| [DicomDevice](dicomdevice/#constructor_5)(int, int, Resolution) | Inizializza una nuova istanza della classe `DicomDevice` con le dimensioni dell'immagine e la risoluzione fornite. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Ottiene o imposta il tipo di coordinate della pagina (Media/Crop boxes). Il valore CropBox è utilizzato per impostazione predefinita. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Ottiene o imposta la modalità di presentazione del modulo. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Ottiene l'altezza dell'output dell'immagine. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Ottiene o imposta le opzioni di rendering. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Ottiene la risoluzione dell'immagine. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Ottiene la larghezza dell'output dell'immagine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| override [Process](../../aspose.pdf.devices/dicomdevice/process/#process)(Page, Stream) | Converte la pagina in Dicom e la salva nello stream di output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Esegue alcune operazioni sulla pagina fornita e salva i risultati nel file. |

### Vedi Anche

* classe [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)