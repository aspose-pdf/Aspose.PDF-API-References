---
title: Class GifDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.GifDevice. Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf en gif
type: docs
weight: 3600
url: /fr/net/aspose.pdf.devices/gifdevice/
---
## Classe GifDevice

Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf en gif.

```csharp
public sealed class GifDevice : ImageDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [GifDevice](gifdevice/#constructor)() | Initialise une nouvelle instance de la classe `GifDevice` avec une résolution par défaut. |
| [GifDevice](gifdevice/#constructor_2)(PageSize) | Initialise une nouvelle instance de la classe `GifDevice` avec la taille de page fournie, résolution par défaut (=150). |
| [GifDevice](gifdevice/#constructor_1)(Resolution) | Initialise une nouvelle instance de la classe `GifDevice`. Résolution pour le fichier image résultant, voir la classe [`Resolution`](../resolution/). |
| [GifDevice](gifdevice/#constructor_4)(int, int) | Initialise une nouvelle instance de la classe `GifDevice` avec les dimensions d'image fournies, résolution par défaut (=150). |
| [GifDevice](gifdevice/#constructor_3)(PageSize, Resolution) | Initialise une nouvelle instance de la classe `GifDevice` avec la taille de page et la résolution fournies. |
| [GifDevice](gifdevice/#constructor_5)(int, int, Resolution) | Initialise une nouvelle instance de la classe `GifDevice` avec les dimensions d'image et la résolution fournies. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtient ou définit le type de coordonnées de la page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtient ou définit le mode de présentation du formulaire. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtient la hauteur de sortie de l'image. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtient ou définit les options de rendu. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtient la résolution de l'image. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtient la largeur de sortie de l'image. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/gifdevice/process/#process)(Page, Stream) | Convertit la page en gif et l'enregistre dans le flux de sortie. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en images GIF.

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

		// Initialize GifDevice	
		GifDevice gifDevice = new GifDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream gifStream =
			new FileStream($"{dataDir}image{pageCount}_out.gif",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				gifDevice.Process(pdfDocument.Pages[pageCount], gifStream);

				// Close stream
				gifStream.Close();
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
	
		' Initialize GifDevice  
		Dim gifDevice As GifDevice = New GifDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using gifStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.gif", FileMode.Create)
		   
				' Convert a particular page and save the image to stream
				gifDevice.Process(pdfDocument.Pages(pageCount), gifStream)

				' Close stream
				gifStream.Close()
			End Using
		Next
	End Using
```

### Voir aussi

* classe [ImageDevice](../imagedevice/)
* espace de noms [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)