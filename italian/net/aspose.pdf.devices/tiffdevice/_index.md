---
title: Class TiffDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.TiffDevice. Questa classe aiuta a salvare il documento pdf pagina per pagina in un'unica immagine tiff
type: docs
weight: 3700
url: /it/net/aspose.pdf.devices/tiffdevice/
---
## Classe TiffDevice

Questa classe aiuta a salvare il documento pdf pagina per pagina in un'unica immagine tiff.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Costruttori

| Nome | Descrizione |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | Inizializza una nuova istanza della classe `TiffDevice` con impostazioni predefinite. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | Inizializza una nuova istanza della classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | Inizializza una nuova istanza della classe `TiffDevice`. |

## Proprietà

| Nome | Descrizione |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Ottiene o imposta la modalità di presentazione del modulo. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Ottiene l'altezza dell'immagine di output. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | Ottiene o imposta le opzioni di rendering. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Ottiene la risoluzione dell'immagine. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | Ottiene le impostazioni per mappare il pdf in un'immagine tiff. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Ottiene la larghezza dell'immagine di output. |

## Metodi

| Nome | Descrizione |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Esegue la binarizzazione di Bradley per lo stream di input. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Elabora l'intero documento e salva i risultati nello stream. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Elabora l'intero documento e salva i risultati nel file. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Esegue alcune operazioni sulla pagina data e salva i risultati nel file. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Converte determinate pagine del documento in tiff e le salva nello stream di output. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Elabora determinate pagine del documento e salva i risultati nel file. |

## Esempi

Il seguente esempio mostra come convertire un file PDF in immagini TIFF.

```csharp
[C#]
	// The path to your PDF Directory
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The file name of the PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// Initialize instance of Document class
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Create Resolution object 	
		Resolution resolution = new Resolution(300);
		
		// Create TiffSettings object
		TiffSettings tiffSettings = new TiffSettings
		{
			Compression = CompressionType.None,
			Depth = ColorDepth.Default,
			Shape = ShapeType.Landscape,
			SkipBlankPages = false
		};

		// Create TIFF device
		TiffDevice tiffDevice = new TiffDevice(resolution, tiffSettings);

		// Convert a PDF document to TIFF image
		tiffDevice.Process(pdfDocument, dataDir + "AllPagesToTIFF_out.tif");
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
		
		' Create TiffSettings object
		Dim tiffSettings As TiffSettings = New TiffSettings With {
		  .Compression = CompressionType.None,
			.Depth = ColorDepth.[Default],
			.Shape = ShapeType.Landscape,
			.SkipBlankPages = False
		}

		' Create TIFF device
		Dim tiffDevice As TiffDevice = New TiffDevice(resolution, tiffSettings)

		' Convert a PDF document to TIFF image
		tiffDevice.Process(pdfDocument, dataDir & "AllPagesToTIFF_out.tif")

	End Using
```

### Vedi Anche

* classe [DocumentDevice](../documentdevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)