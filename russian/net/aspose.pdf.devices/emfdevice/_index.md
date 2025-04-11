---
title: Class EmfDevice
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Devices.EmfDevice. Представляет устройство изображения, которое помогает сохранять страницы pdf-документа в emf
type: docs
weight: 3580
url: /ru/net/aspose.pdf.devices/emfdevice/
---
## Класс EmfDevice

Представляет устройство изображения, которое помогает сохранять страницы pdf-документа в emf.

```csharp
public sealed class EmfDevice : ImageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [EmfDevice](emfdevice/#constructor)() | Инициализирует новый экземпляр класса `EmfDevice` с разрешением по умолчанию для растрового изображения, записанного в emf. |
| [EmfDevice](emfdevice/#constructor_2)(PageSize) | Инициализирует новый экземпляр класса `EmfDevice` с заданным размером страницы и разрешением по умолчанию для растрового изображения, записанного в emf (=150) |
| [EmfDevice](emfdevice/#constructor_1)(Resolution) | Инициализирует новый экземпляр класса `EmfDevice`. Разрешение для растрового изображения, записанного в emf, см. класс [`Resolution`](../resolution/). |
| [EmfDevice](emfdevice/#constructor_4)(int, int) | Инициализирует новый экземпляр класса `EmfDevice` с заданными размерами изображения и разрешением по умолчанию для растрового изображения, записанного в emf (=150) |
| [EmfDevice](emfdevice/#constructor_3)(PageSize, Resolution) | Инициализирует новый экземпляр класса [`JpegDevice`](../jpegdevice/) с заданным размером страницы и разрешением для растрового изображения, записанного в emf. |
| [EmfDevice](emfdevice/#constructor_5)(int, int, Resolution) | Инициализирует новый экземпляр класса [`JpegDevice`](../jpegdevice/) с заданными размерами изображения и разрешением для растрового изображения, записанного в emf. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Получает или задает тип координат страницы (Media/Crop boxes). Значение CropBox используется по умолчанию. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Получает или задает режим представления формы. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Получает высоту выходного изображения. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Получает разрешение изображения. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Получает ширину выходного изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| override [Process](../../aspose.pdf.devices/emfdevice/process/#process)(Page, Stream) | Преобразует страницу в emf и сохраняет ее в выходном потоке. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторые операции на заданной странице и сохраняет результаты в файл. |

## Примеры

Следующий пример показывает, как преобразовать PDF-файл в изображения EMF.

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

### См. также

* класс [ImageDevice](../imagedevice/)
* пространство имен [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../)