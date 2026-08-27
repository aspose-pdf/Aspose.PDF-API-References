---
title: "Класс BmpDevice"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Devices.BmpDevice class. Представляет устройство изображения, которое помогает сохранять страницы PDF‑документа в bmp"
type: docs
weight: 3640
url: /ru/net/aspose.pdf.devices/bmpdevice/
---
## BmpDevice class

Представляет устройство изображения, которое помогает сохранять страницы pdf‑документа в bmp.

```csharp
public sealed class BmpDevice : ImageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [BmpDevice](bmpdevice/#constructor)() | Инициализирует новый экземпляр класса `BmpDevice` с разрешением по умолчанию. |
| [BmpDevice](bmpdevice/#constructor_2)(PageSize) | Инициализирует новый экземпляр класса `BmpDevice` с указанным размером страницы, разрешением по умолчанию (=150). |
| [BmpDevice](bmpdevice/#constructor_1)(Resolution) | Инициализирует новый экземпляр класса `BmpDevice`.  Разрешение результирующего файла изображения, см. класс [`Resolution`](../resolution/). |
| [BmpDevice](bmpdevice/#constructor_4)(int, int) | Инициализирует новый экземпляр класса `BmpDevice` с указанными размерами изображения, разрешением по умолчанию (=150). |
| [BmpDevice](bmpdevice/#constructor_3)(PageSize, Resolution) | Инициализирует новый экземпляр класса `BmpDevice` с указанным размером страницы и разрешением. |
| [BmpDevice](bmpdevice/#constructor_5)(int, int, Resolution) | Инициализирует новый экземпляр класса `BmpDevice` с указанными размерами изображения и разрешением. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Получает или задает тип координат страницы (Media/Crop boxes). Значение CropBox используется по умолчанию. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Получает или задает режим отображения формы. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Получает высоту выходного изображения. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Получает разрешение изображения. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Получает ширину выходного изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Преобразует page в Bitmap. |
| override [Process](../../aspose.pdf.devices/bmpdevice/process/#process)(Page, Stream) | Преобразует страницу в bmp и сохраняет её в выходном потоке. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторую операцию на указанной странице и сохраняет результаты в файл. |

## Примеры

Следующий пример показывает, как преобразовать PDF‑файл в BMP‑изображения.

```csharp
[C#]
	// Путь к вашему каталогу PDF
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Имя файла PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// инициализировать экземпляр класса Document
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Создать объект Resolution 	
		Resolution resolution = new Resolution(300);

		// инициализировать BmpDevice	
		BmpDevice bmpDevice = new BmpDevice(resolution);

		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream bmpStream =
			new FileStream($"{dataDir}image{pageCount}_out.bmp",
			FileMode.Create))
			{
				// Преобразовать конкретную страницу и сохранить изображение в поток
				bmpDevice.Process(pdfDocument.Pages[pageCount], bmpStream);

				// Закрыть поток
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

### См. также

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


