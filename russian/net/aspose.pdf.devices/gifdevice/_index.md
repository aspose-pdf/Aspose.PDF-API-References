---
title: Class GifDevice
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Devices.GifDevice. Представляет устройство изображения, которое помогает сохранять страницы pdf-документа в gif
type: docs
weight: 3600
url: /ru/net/aspose.pdf.devices/gifdevice/
---
## GifDevice class

Представляет устройство изображения, которое помогает сохранять страницы pdf-документа в gif.

```csharp
public sealed class GifDevice : ImageDevice
```

## Constructors

| Name | Description |
| --- | --- |
| [GifDevice](gifdevice/#constructor)() | Инициализирует новый экземпляр класса `GifDevice` с разрешением по умолчанию. |
| [GifDevice](gifdevice/#constructor_2)(PageSize) | Инициализирует новый экземпляр класса `GifDevice` с заданным размером страницы, разрешение по умолчанию (=150). |
| [GifDevice](gifdevice/#constructor_1)(Resolution) | Инициализирует новый экземпляр класса `GifDevice`. Разрешение для результирующего файла изображения, см. класс [`Resolution`](../resolution/). |
| [GifDevice](gifdevice/#constructor_4)(int, int) | Инициализирует новый экземпляр класса `GifDevice` с заданными размерами изображения, разрешение по умолчанию (=150). |
| [GifDevice](gifdevice/#constructor_3)(PageSize, Resolution) | Инициализирует новый экземпляр класса `GifDevice` с заданным размером страницы и разрешением. |
| [GifDevice](gifdevice/#constructor_5)(int, int, Resolution) | Инициализирует новый экземпляр класса `GifDevice` с заданными размерами изображения и разрешением. |

## Properties

| Name | Description |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Получает или задает тип координат страницы (Media/Crop boxes). Значение CropBox используется по умолчанию. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Получает или задает режим представления формы. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Получает высоту выходного изображения. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Получает разрешение изображения. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Получает ширину выходного изображения. |

## Methods

| Name | Description |
| --- | --- |
| override [Process](../../aspose.pdf.devices/gifdevice/process/#process)(Page, Stream) | Преобразует страницу в gif и сохраняет ее в выходном потоке. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторые операции на заданной странице и сохраняет результаты в файл. |

## Examples

Следующий пример показывает, как преобразовать PDF файл в GIF изображения.

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

### See Also

* класс [ImageDevice](../imagedevice/)
* пространство имен [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../)