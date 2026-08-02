---
title: "Класс JpegDevice"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Devices.JpegDevice. Представляет устройство изображения, которое помогает сохранять страницы PDF‑документа в jpeg"
type: docs
weight: 3740
url: /ru/net/aspose.pdf.devices/jpegdevice/
---
## JpegDevice class

Представляет устройство изображения, которое помогает сохранять страницы pdf‑документа в jpeg.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | Инициализирует новый экземпляр класса `JpegDevice` с разрешением по умолчанию и максимальным качеством. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | Инициализирует новый экземпляр класса `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | Инициализирует новый экземпляр класса `JpegDevice` с указанным размером страницы, разрешением по умолчанию (=150) и максимальным качеством. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | Инициализирует новый экземпляр класса `JpegDevice`. Разрешение результирующего файла изображения, см. класс [`Resolution`](../resolution/). |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | Инициализирует новый экземпляр класса `JpegDevice` с указанными размерами изображения, разрешением по умолчанию (=150) и максимальным качеством. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | Инициализирует новый экземпляр класса `JpegDevice` с указанным размером страницы, разрешением и максимальным качеством. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | Инициализирует новый экземпляр класса `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | Инициализирует новый экземпляр класса `JpegDevice` с указанными размерами изображения, разрешением и максимальным качеством. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | Инициализирует новый экземпляр класса `JpegDevice` с указанным размером страницы, разрешением и качеством. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | Инициализирует новый экземпляр класса `JpegDevice` с указанными размерами изображения, разрешением и качеством. |

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
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | Преобразует страницу в jpeg и сохраняет её в выходном потоке. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторую операцию на указанной странице и сохраняет результаты в файл. |

## Примеры

Следующий пример показывает, как преобразовать файл PDF в изображения JPEG.

```csharp
[C#]
	// Путь к вашему каталогу PDF
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// Имя файла PDF
	string pdfFile = @"YOUR_PDF_FILE";

	// Инициализировать экземпляр класса Document
	using (Document pdfDocument = new Document(Path.Combine(dataDir, pdfFile)))
	{
		// Создать объект Resolution 	
		Resolution resolution = new Resolution(300);

		// Инициализировать JpegDevice	
		JpegDevice jpegDevice = new JpegDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream jpegStream =
			new FileStream($"{dataDir}image{pageCount}_out.jpeg",
			FileMode.Create))
			{
				// Преобразовать конкретную страницу и сохранить изображение в поток
				jpegDevice.Process(pdfDocument.Pages[pageCount], jpegStream);

				// Закрыть поток
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

### См. также

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


