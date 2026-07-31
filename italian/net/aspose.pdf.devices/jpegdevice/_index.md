---
title: "Classe JpegDevice"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Classe Aspose.Pdf.Devices.JpegDevice. Rappresenta un dispositivo immagine che aiuta a salvare le pagine di documenti pdf in jpeg"
type: docs
weight: 3740
url: /it/net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice class

Rappresenta un dispositivo immagine che consente di salvare le pagine del documento pdf in jpeg.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | Inizializza una nuova istanza della classe `JpegDevice` con risoluzione predefinita e qualità massima. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | Inizializza una nuova istanza della classe `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | Inizializza una nuova istanza della classe `JpegDevice` con dimensione della pagina fornita, risoluzione predefinita (=150) e qualità massima. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | Inizializza una nuova istanza della classe `JpegDevice`. Risoluzione per il file immagine risultante, vedere la classe [`Resolution`](../resolution/). |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | Inizializza una nuova istanza della classe `JpegDevice` con dimensioni dell'immagine fornite, risoluzione predefinita (=150) e qualità massima. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | Inizializza una nuova istanza della classe `JpegDevice` con dimensione della pagina fornita, risoluzione e qualità massima. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | Inizializza una nuova istanza della classe `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | Inizializza una nuova istanza della classe `JpegDevice` con dimensioni dell'immagine fornite, risoluzione e qualità massima. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | Inizializza una nuova istanza della classe `JpegDevice` con dimensione della pagina fornita, risoluzione e qualità. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | Inizializza una nuova istanza della classe `JpegDevice` con dimensioni dell'immagine fornite, risoluzione e qualità. |

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
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | Converte la pagina in jpeg e la salva nello stream di output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Esegue alcune operazioni sulla pagina fornita e salva i risultati nel file. |

## Esempi

Il seguente esempio mostra come convertire un file PDF in immagini JPEG.

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

		// Inizializza JpegDevice\t
		JpegDevice jpegDevice = new JpegDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream jpegStream =
			new FileStream($"{dataDir}image{pageCount}_out.jpeg",
			FileMode.Create))
			{
				// Converti una pagina specifica e salva l'immagine nello stream.
				jpegDevice.Process(pdfDocument.Pages[pageCount], jpegStream);

				// Chiudi lo stream
				jpegStream.Close();
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
		
		' Initialize JpegDevice
		Dim jpegDevice As JpegDevice = New JpegDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using jpegStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.jpeg", FileMode.Create)
				
				' Convert a particular page and save the image to stream
				jpegDevice.Process(pdfDocument.Pages(pageCount), jpegStream)

				' Close stream
				jpegStream.Close()
			End Using
		Next
    End Using
```

### Vedi anche

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


