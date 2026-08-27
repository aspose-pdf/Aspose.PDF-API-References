---
title: "Classe BmpDevice"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Devices.BmpDevice. Rappresenta un dispositivo immagine che aiuta a salvare le pagine di documenti pdf in bmp"
type: docs
weight: 3640
url: /it/net/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class

Rappresenta un dispositivo immagine che consente di salvare le pagine del documento pdf in bmp.

```csharp
public sealed class BmpDevice : ImageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | Inizializza una nuova istanza della classe `BmpDevice` con risoluzione predefinita. |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | Inizializza una nuova istanza della classe `BmpDevice` con dimensione della pagina fornita, risoluzione predefinita (=150). |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | Inizializza una nuova istanza della classe `BmpDevice`. Risoluzione per il file immagine risultante, vedere la classe [`Resolution`](../resolution/). |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | Inizializza una nuova istanza della classe `BmpDevice` con dimensioni dell'immagine fornite, risoluzione predefinita (=150). |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | Inizializza una nuova istanza della classe `BmpDevice` con dimensione della pagina e risoluzione fornite. |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | Inizializza una nuova istanza della classe `BmpDevice` con dimensioni dell'immagine e risoluzione fornite. |

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
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | Converte la pagina in bmp e la salva nello stream di output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Esegue alcune operazioni sulla pagina fornita e salva i risultati nel file. |

## Esempi

Il seguente esempio mostra come convertire un file PDF in immagini BMP.

```csharp
[C#]
	// Il percorso alla tua directory PDF
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Il nome file del PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// inizializza un'istanza della classe Document
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Crea un oggetto Resolution 	
		Resolution resolution = new Resolution(300);

		// inizializza BmpDevice	
		BmpDevice bmpDevice = new BmpDevice(resolution);

		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream bmpStream =
			new FileStream($"{dataDir}image{pageCount}_out.bmp",
			FileMode.Create))
			{
				// Converti una pagina specifica e salva l'immagine nello stream.
				bmpDevice.Process(pdfDocument.Pages[pageCount], bmpStream);

				// Chiudi lo stream
				bmpStream.Close();
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
		
		' Initialize BmpDevice  
		Dim bmpDevice As BmpDevice = New BmpDevice(resolution)
		
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using bmpStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.bmp", FileMode.Create)
				
				' Convert a particular page and save the image to stream
				bmpDevice.Process(pdfDocument.Pages(pageCount), bmpStream)

				' Close stream
				bmpStream.Close()
			End Using
		Next
	End Using
```

### Vedi anche

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


