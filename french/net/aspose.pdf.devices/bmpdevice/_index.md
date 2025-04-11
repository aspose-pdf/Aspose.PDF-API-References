---
title: Class BmpDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.BmpDevice. Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf en bmp
type: docs
weight: 3520
url: /fr/net/aspose.pdf.devices/bmpdevice/
---
## Classe BmpDevice

Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf en bmp.

```csharp
public sealed class BmpDevice : ImageDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | Initialise une nouvelle instance de la classe `BmpDevice` avec une résolution par défaut. |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | Initialise une nouvelle instance de la classe `BmpDevice` avec la taille de page fournie, résolution par défaut (=150). |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | Initialise une nouvelle instance de la classe `BmpDevice`. Résolution pour le fichier image résultant, voir la classe [`Resolution`](../resolution/). |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | Initialise une nouvelle instance de la classe `BmpDevice` avec les dimensions d'image fournies, résolution par défaut (=150). |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | Initialise une nouvelle instance de la classe `BmpDevice` avec la taille de page et la résolution fournies. |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | Initialise une nouvelle instance de la classe `BmpDevice` avec les dimensions d'image et la résolution fournies. |

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
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | Convertit la page en bmp et l'enregistre dans le flux de sortie. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en images BMP.

```csharp
[C#]
	// The path to your PDF Directory
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The file name of the PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// initialize instance of Document class
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Create Resolution object 	
		Resolution resolution = new Resolution(300);

		// initialize BmpDevice	
		BmpDevice bmpDevice = new BmpDevice(resolution);

		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream bmpStream =
			new FileStream($"{dataDir}image{pageCount}_out.bmp",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				bmpDevice.Process(pdfDocument.Pages[pageCount], bmpStream);

				// Close stream
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

### Voir aussi

* classe [ImageDevice](../imagedevice/)
* espace de noms [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)