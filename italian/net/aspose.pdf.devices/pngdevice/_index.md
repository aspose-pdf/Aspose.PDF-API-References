---
title: "Classe PngDevice"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Devices.PngDevice. Rappresenta un dispositivo immagine che aiuta a salvare le pagine di documenti pdf in png"
type: docs
weight: 3770
url: /it/net/aspose.pdf.devices/pngdevice/
---
## PngDevice class

Rappresenta un dispositivo immagine che consente di salvare le pagine del documento pdf in png.

```csharp
public sealed class PngDevice : ImageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | Inizializza una nuova istanza della classe `PngDevice` con risoluzione predefinita. |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | Inizializza una nuova istanza della classe `PngDevice` con dimensione della pagina fornita, risoluzione predefinita (=150). |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | Inizializza una nuova istanza della classe `PngDevice`. Risoluzione per il file immagine risultante, vedere la classe [`Resolution`](../resolution/). |
| [PngDevice](pngdevice/#constructor_4)(int, int) | Inizializza una nuova istanza della classe `PngDevice` con dimensioni dell'immagine fornite, risoluzione predefinita (=150). |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | Inizializza una nuova istanza della classe `PngDevice` con dimensione della pagina e risoluzione fornite. |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | Inizializza una nuova istanza della classe `PngDevice` con dimensioni dell'immagine e risoluzione fornite. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Ottiene o imposta il tipo di coordinate della pagina (scatole Media/Crop). Il valore CropBox è usato per impostazione predefinita. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Ottiene o imposta la modalità di presentazione del modulo. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Ottiene l'altezza dell'output dell'immagine. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Ottiene o imposta le opzioni di rendering. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Ottiene la risoluzione dell'immagine. |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | Ottiene o imposta se l'immagine ha uno sfondo trasparente. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Ottiene la larghezza dell'output dell'immagine. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Converte la pagina in Bitmap. |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | Converte la pagina in png e la salva nello stream di output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Esegue alcune operazioni sulla pagina fornita e salva i risultati nel file. |

## Esempi

Il seguente esempio mostra come convertire un file PDF in immagini PNG.

```csharp
[C#]
	// Il percorso alla tua directory PDF
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Il nome file del PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// Inizializza un'istanza della classe Document
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Crea un oggetto Resolution 	
		Resolution resolution = new Resolution(300);

		// Inizializza PngDevice	
		PngDevice pngDevice = new PngDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream pngStream =
			new FileStream($"{dataDir}image{pageCount}_out.png",
			FileMode.Create))
			{
				// Converti una pagina specifica e salva l'immagine nello stream.
				pngDevice.Process(pdfDocument.Pages[pageCount], pngStream);

				// Chiudi lo stream
				pngStream.Close();
			}
		}
	}
```

```csharp
[VB.NET]

    ' The path to your PDF Directory
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"
	
    ' The file name of the PDF
    Dim pdfFile As String = "YOUR_PDF_FILE"
 
    ' Initialize instance of Document class
	Using pdfDocument As Document = New Document(Path.Combine(dataDir, pdfFile))
		' Create Resolution object  
		Dim resolution As Resolution = New Resolution(300)
		' initialize PngDevice  

		Dim pngDevice As PngDevice = New PngDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using pngStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.png", FileMode.Create)
				' Convert a particular page and save the image to stream
				pngDevice.Process(pdfDocument.Pages(pageCount), pngStream)

				' Close stream
				pngStream.Close()
			End Using
		Next
	End Using
```

### Vedi anche

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


