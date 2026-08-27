---
title: "Classe EmfDevice"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "classe Aspose.Pdf.Devices.EmfDevice. Rappresenta un dispositivo immagine che consente di salvare le pagine del documento pdf in emf."
type: docs
weight: 3700
url: /it/net/aspose.pdf.devices/emfdevice/
---
## EmfDevice class

Rappresenta un dispositivo immagine che consente di salvare le pagine del documento pdf in emf.

```csharp
public sealed class EmfDevice : ImageDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [EmfDevice](emfdevice/#constructor)() | Inizializza una nuova istanza della classe `EmfDevice` con la risoluzione predefinita dell'immagine raster scritta in emf. |
| [EmfDevice](emfdevice/#constructor_2)(PageSize) | Inizializza una nuova istanza della classe `EmfDevice` con la dimensione della pagina fornita e la risoluzione predefinita per l'immagine raster scritta in emf (=150). |
| [EmfDevice](emfdevice/#constructor_1)(Resolution) | Inizializza una nuova istanza della classe `EmfDevice`. Risoluzione per l'immagine raster scritta in emf, vedere la classe [`Resolution`](../resolution/). |
| [EmfDevice](emfdevice/#constructor_4)(int, int) | Inizializza una nuova istanza della classe `EmfDevice` con le dimensioni dell'immagine fornite e la risoluzione predefinita per l'immagine raster scritta in emf (=150). |
| [EmfDevice](emfdevice/#constructor_3)(PageSize, Resolution) | Inizializza una nuova istanza della classe [`JpegDevice`](../jpegdevice/) con la dimensione della pagina fornita e la risoluzione per l'immagine raster scritta in emf. |
| [EmfDevice](emfdevice/#constructor_5)(int, int, Resolution) | Inizializza una nuova istanza della classe [`JpegDevice`](../jpegdevice/) con le dimensioni dell'immagine fornite e la risoluzione per l'immagine raster scritta in emf. |

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
| override [Process](../../aspose.pdf.devices/emfdevice/process/#process)(Page, Stream) | Converte la pagina in emf e la salva nello stream di output. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Esegue alcune operazioni sulla pagina fornita e salva i risultati nel file. |

## Esempi

Il seguente esempio mostra come convertire un file PDF in immagini EMF.

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

		// Inizializza EmfDevice 	
		EmfDevice emfDevice = new EmfDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream emfStream =
			new FileStream($"{dataDir}image{pageCount}_out.emf",
			FileMode.Create))
			{
				// Converti una pagina specifica e salva l'immagine nello stream.
				emfDevice.Process(pdfDocument.Pages[pageCount], emfStream);

				// Chiudi lo stream
				emfStream.Close();
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
	
		' Initialize EmfDevice   
		Dim emfDevice As EmfDevice = New EmfDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using emfStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.emf", FileMode.Create)
			
				' Convert a particular page and save the image to stream
				emfDevice.Process(pdfDocument.Pages(pageCount), emfStream)

				' Close stream
				emfStream.Close()
			End Using
		Next
	End Using
```

### Vedi anche

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


