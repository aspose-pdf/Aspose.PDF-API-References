---
title: Class GifDevice
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Devices.GifDevice. Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en gif
type: docs
weight: 3600
url: /es/net/aspose.pdf.devices/gifdevice/
---
## Clase GifDevice

Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en gif.

```csharp
public sealed class GifDevice : ImageDevice
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [GifDevice](gifdevice/#constructor)() | Inicializa una nueva instancia de la clase `GifDevice` con resolución predeterminada. |
| [GifDevice](gifdevice/#constructor_2)(PageSize) | Inicializa una nueva instancia de la clase `GifDevice` con el tamaño de página proporcionado, resolución predeterminada (=150). |
| [GifDevice](gifdevice/#constructor_1)(Resolution) | Inicializa una nueva instancia de la clase `GifDevice`. Resolución para el archivo de imagen resultante, ver clase [`Resolution`](../resolution/). |
| [GifDevice](gifdevice/#constructor_4)(int, int) | Inicializa una nueva instancia de la clase `GifDevice` con las dimensiones de imagen proporcionadas, resolución predeterminada (=150). |
| [GifDevice](gifdevice/#constructor_3)(PageSize, Resolution) | Inicializa una nueva instancia de la clase `GifDevice` con el tamaño de página y la resolución proporcionados. |
| [GifDevice](gifdevice/#constructor_5)(int, int, Resolution) | Inicializa una nueva instancia de la clase `GifDevice` con las dimensiones de imagen y la resolución proporcionadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtiene o establece el tipo de coordenada de la página (cajas Media/Crop). El valor CropBox se utiliza por defecto. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtiene o establece el modo de presentación del formulario. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtiene la altura de salida de la imagen. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtiene o establece las opciones de renderizado. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtiene la resolución de la imagen. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtiene el ancho de salida de la imagen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Process](../../aspose.pdf.devices/gifdevice/process/#process)(Page, Stream) | Convierte la página en gif y la guarda en el flujo de salida. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguna operación en la página dada y guarda los resultados en el archivo. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo PDF a imágenes GIF.

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

### Véase También

* clase [ImageDevice](../imagedevice/)
* espacio de nombres [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* ensamblaje [Aspose.PDF](../../)