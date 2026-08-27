---
title: "Classe JpegDevice"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Classe Aspose.Pdf.Devices.JpegDevice. Représente un dispositif d'image qui aide à enregistrer les pages de documents pdf au format jpeg"
type: docs
weight: 3740
url: /fr/net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice class

Représente un dispositif d'image qui permet d'enregistrer les pages du document PDF au format JPEG.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Constructeurs

| Nom | Description |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | Initialise une nouvelle instance de la classe `JpegDevice` avec la résolution par défaut et la qualité maximale. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | Initialise une nouvelle instance de la classe `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | Initialise une nouvelle instance de la classe `JpegDevice` avec la taille de page fournie, la résolution par défaut (=150) et la qualité maximale. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | Initialise une nouvelle instance de la classe `JpegDevice`. Résolution du fichier image résultant, voir la classe [`Resolution`](../resolution/). |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | Initialise une nouvelle instance de la classe `JpegDevice` avec les dimensions d'image fournies, la résolution par défaut (=150) et la qualité maximale. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | Initialise une nouvelle instance de la classe `JpegDevice` avec la taille de page fournie, la résolution et la qualité maximale. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | Initialise une nouvelle instance de la classe `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | Initialise une nouvelle instance de la classe `JpegDevice` avec les dimensions d'image fournies, la résolution et la qualité maximale. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | Initialise une nouvelle instance de la classe `JpegDevice` avec la taille de page fournie, la résolution et la qualité. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | Initialise une nouvelle instance de la classe `JpegDevice` avec les dimensions d'image fournies, la résolution et la qualité. |

## Propriétés

| Nom | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtient ou définit le type de coordonnées de page (boîtes Media/Crop). La valeur CropBox est utilisée par défaut. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtient ou définit le mode de présentation du formulaire. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtient la hauteur de sortie de l'image. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtient ou définit les options de rendu. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtient la résolution de l'image. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtient la largeur de sortie de l'image. |

## Méthodes

| Nom | Description |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Convertit la page en Bitmap. |
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | Convertit la page en jpeg et l'enregistre dans le flux de sortie. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Effectue une opération sur la page donnée et enregistre les résultats dans le fichier. |

## Exemples

L'exemple suivant montre comment convertir un fichier PDF en images JPEG.

```csharp
[C#]
	// Le chemin vers votre répertoire PDF
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Le nom du fichier PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// Initialiser une instance de la classe Document
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Créer un objet Resolution \t
		Resolution resolution = new Resolution(300);

		// Initialiser JpegDevice	
		JpegDevice jpegDevice = new JpegDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream jpegStream =
			new FileStream($"{dataDir}image{pageCount}_out.jpeg",
			FileMode.Create))
			{
				// Convertir une page particulière et enregistrer l'image dans le flux
				jpegDevice.Process(pdfDocument.Pages[pageCount], jpegStream);

				// Fermer le flux
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

### Voir aussi

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


