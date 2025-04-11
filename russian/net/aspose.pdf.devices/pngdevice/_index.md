---
title: Class PngDevice
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Devices.PngDevice. Представляет устройство изображения, которое помогает сохранять страницы pdf-документа в формате png
type: docs
weight: 3650
url: /ru/net/aspose.pdf.devices/pngdevice/
---
## Класс PngDevice

Представляет устройство изображения, которое помогает сохранять страницы pdf-документа в формате png.

```csharp
public sealed class PngDevice : ImageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | Инициализирует новый экземпляр класса `PngDevice` с разрешением по умолчанию. |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | Инициализирует новый экземпляр класса `PngDevice` с заданным размером страницы, разрешение по умолчанию (=150). |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | Инициализирует новый экземпляр класса `PngDevice`. Разрешение для результирующего файла изображения, см. класс [`Resolution`](../resolution/). |
| [PngDevice](pngdevice/#constructor_4)(int, int) | Инициализирует новый экземпляр класса `PngDevice` с заданными размерами изображения, разрешение по умолчанию (=150). |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | Инициализирует новый экземпляр класса `PngDevice` с заданным размером страницы и разрешением. |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | Инициализирует новый экземпляр класса `PngDevice` с заданными размерами изображения и разрешением. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Получает или задает тип координат страницы (Media/Crop boxes). Значение CropBox используется по умолчанию. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Получает или задает режим представления формы. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Получает высоту выходного изображения. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Получает разрешение изображения. |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | Получает или задает, имеет ли изображение прозрачный фон. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Получает ширину выходного изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | Преобразует страницу в png и сохраняет ее в выходном потоке. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторые операции на заданной странице и сохраняет результаты в файл. |

## Примеры

Следующий пример показывает, как преобразовать PDF файл в изображения PNG.

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

		// Initialize PngDevice	
		PngDevice pngDevice = new PngDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream pngStream =
			new FileStream($"{dataDir}image{pageCount}_out.png",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				pngDevice.Process(pdfDocument.Pages[pageCount], pngStream);

				// Close stream
				pngStream.Close();
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
		' initialize PngDevice  

		Dim pngDevice As PngDevice = New PngDevice(resolution)
		For pageCount As Integer = 1 To pdfDocument.Pages.Count
			Using pngStream As FileStream = New FileStream($"{dataDir}image{pageCount}_out.png", FileMode.Create)
				' Convert a particular page and save the image to stream
				pngDevice.Process(pdfDocument.Pages(pageCount), pngStream)

				' Close stream
				pngStream.Close()
			End Using
		Next
	End Using
```

### См. также

* класс [ImageDevice](../imagedevice/)
* пространство имен [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../)