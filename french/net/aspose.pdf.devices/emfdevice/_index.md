---
title: Class EmfDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.EmfDevice. Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf en emf
type: docs
weight: 3580
url: /fr/net/aspose.pdf.devices/emfdevice/
---
## Classe EmfDevice

Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf en emf.

```csharp
public sealed class EmfDevice : ImageDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [EmfDevice](emfdevice/#constructor)() | Initialise une nouvelle instance de la classe `EmfDevice` avec une résolution par défaut de l'image raster écrite en emf. |
| [EmfDevice](emfdevice/#constructor_2)(PageSize) | Initialise une nouvelle instance de la classe `EmfDevice` avec la taille de page fournie et une résolution par défaut pour l'image raster écrite en emf (=150) |
| [EmfDevice](emfdevice/#constructor_1)(Resolution) | Initialise une nouvelle instance de la classe `EmfDevice`. Résolution pour l'image raster écrite en emf, voir la classe [`Resolution`](../resolution/). |
| [EmfDevice](emfdevice/#constructor_4)(int, int) | Initialise une nouvelle instance de la classe `EmfDevice` avec les dimensions d'image fournies et une résolution par défaut pour l'image raster écrite en emf (=150) |
| [EmfDevice](emfdevice/#constructor_3)(PageSize, Resolution) | Initialise une nouvelle instance de la classe [`JpegDevice`](../jpegdevice/) avec la taille de page fournie et la résolution pour l'image raster écrite en emf. |
| [EmfDevice](emfdevice/#constructor_5)(int, int, Resolution) | Initialise une nouvelle instance de la classe [`JpegDevice`](../jpegdevice/) avec les dimensions d'image fournies et la résolution pour l'image raster écrite en emf. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtient ou définit le type de coordonnées de page (Media/Crop boxes). La valeur CropBox est utilisée par défaut. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtient ou définit le mode de présentation du formulaire. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtient la hauteur de sortie de l'image. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtient ou définit les options de rendu. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtient la résolution de l'image. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtient la largeur de sortie de l'image. |

## Méthodes

| Nom | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/emfdevice/process/#process)(Page, Stream) | Convertit la page en emf et l'enregistre dans le flux de sortie. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en images EMF.

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

		// Initialize EmfDevice 	
		EmfDevice emfDevice = new EmfDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream emfStream =
			new FileStream($"{dataDir}image{pageCount}_out.emf",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				emfDevice.Process(pdfDocument.Pages[pageCount], emfStream);

				// Close stream
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

### Voir aussi

* classe [ImageDevice](../imagedevice/)
* espace de noms [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)