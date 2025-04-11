---
title: Class BmpDevice
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Devices.BmpDevice. Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en bmp
type: docs
weight: 3520
url: /es/net/aspose.pdf.devices/bmpdevice/
---
## Clase BmpDevice

Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en bmp.

```csharp
public sealed class BmpDevice : ImageDevice
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | Inicializa una nueva instancia de la clase `BmpDevice` con resolución predeterminada. |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | Inicializa una nueva instancia de la clase `BmpDevice` con el tamaño de página proporcionado, resolución predeterminada (=150). |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | Inicializa una nueva instancia de la clase `BmpDevice`. Resolución para el archivo de imagen resultante, ver clase [`Resolution`](../resolution/). |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | Inicializa una nueva instancia de la clase `BmpDevice` con las dimensiones de imagen proporcionadas, resolución predeterminada (=150). |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | Inicializa una nueva instancia de la clase `BmpDevice` con el tamaño de página y la resolución proporcionados. |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | Inicializa una nueva instancia de la clase `BmpDevice` con las dimensiones de imagen y la resolución proporcionadas. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtiene o establece el tipo de coordenada de la página (Media/Crop boxes). El valor CropBox se utiliza por defecto. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtiene o establece el modo de presentación del formulario. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtiene la altura de salida de la imagen. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtiene o establece las opciones de renderizado. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtiene la resolución de la imagen. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtiene el ancho de salida de la imagen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | Convierte la página en bmp y la guarda en el flujo de salida. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguna operación en la página dada y guarda los resultados en el archivo. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo PDF a imágenes BMP.

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

### Véase también

* clase [ImageDevice](../imagedevice/)
* espacio de nombres [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* ensamblado [Aspose.PDF](../../)