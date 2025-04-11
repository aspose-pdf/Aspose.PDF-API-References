---
title: Class JpegDevice
second_title: Aspose.PDF for .NET API Reference
description: Clase Aspose.Pdf.Devices.JpegDevice. Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en jpeg
type: docs
weight: 3620
url: /es/net/aspose.pdf.devices/jpegdevice/
---
## Clase JpegDevice

Representa un dispositivo de imagen que ayuda a guardar las páginas del documento pdf en jpeg.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Constructores

| Nombre | Descripción |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | Inicializa una nueva instancia de la clase `JpegDevice` con resolución predeterminada y calidad máxima. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | Inicializa una nueva instancia de la clase `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | Inicializa una nueva instancia de la clase `JpegDevice` con el tamaño de página proporcionado, resolución predeterminada (=150) y calidad máxima. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | Inicializa una nueva instancia de la clase `JpegDevice`. Resolución para el archivo de imagen resultante, ver clase [`Resolution`](../resolution/). |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | Inicializa una nueva instancia de la clase `JpegDevice` con las dimensiones de imagen proporcionadas, resolución predeterminada (=150) y calidad máxima. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | Inicializa una nueva instancia de la clase `JpegDevice` con el tamaño de página, resolución y calidad proporcionados. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | Inicializa una nueva instancia de la clase `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | Inicializa una nueva instancia de la clase `JpegDevice` con las dimensiones de imagen proporcionadas, resolución y calidad máxima. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | Inicializa una nueva instancia de la clase `JpegDevice` con el tamaño de página, resolución y calidad proporcionados. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | Inicializa una nueva instancia de la clase `JpegDevice` con las dimensiones de imagen proporcionadas, resolución y calidad. |

## Propiedades

| Nombre | Descripción |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtiene o establece el tipo de coordenadas de la página (cajas Media/Crop). El valor CropBox se utiliza por defecto. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtiene o establece el modo de presentación del formulario. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtiene la altura de salida de la imagen. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtiene o establece las opciones de renderizado. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtiene la resolución de la imagen. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtiene el ancho de salida de la imagen. |

## Métodos

| Nombre | Descripción |
| --- | --- |
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | Convierte la página en jpeg y la guarda en el flujo de salida. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguna operación en la página dada y guarda los resultados en el archivo. |

## Ejemplos

El siguiente ejemplo muestra cómo convertir un archivo PDF a imágenes JPEG.

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

		// Initialize JpegDevice	
		JpegDevice jpegDevice = new JpegDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream jpegStream =
			new FileStream($"{dataDir}image{pageCount}_out.jpeg",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				jpegDevice.Process(pdfDocument.Pages[pageCount], jpegStream);

				// Close stream
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

### Véase También

* clase [ImageDevice](../imagedevice/)
* espacio de nombres [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* ensamblaje [Aspose.PDF](../../)