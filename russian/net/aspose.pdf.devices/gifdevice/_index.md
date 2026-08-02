---
title: "Класс GifDevice"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Класс Aspose.Pdf.Devices.GifDevice. Представляет графическое устройство, которое помогает сохранять страницы PDF‑документа в gif"
type: docs
weight: 3720
url: /ru/net/aspose.pdf.devices/gifdevice/
---
## GifDevice class

Представляет устройство изображения, которое помогает сохранять страницы pdf‑документа в gif.

```csharp
public sealed class GifDevice : ImageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [GifDevice](gifdevice/#constructor)() | Инициализирует новый экземпляр класса `GifDevice` с разрешением по умолчанию. |
| [GifDevice](gifdevice/#constructor_2)(PageSize) | Инициализирует новый экземпляр класса `GifDevice` с указанным размером страницы, разрешением по умолчанию (=150). |
| [GifDevice](gifdevice/#constructor_1)(Resolution) | Инициализирует новый экземпляр класса `GifDevice`. Разрешение для результирующего файла изображения, см. класс [`Resolution`](../resolution/). |
| [GifDevice](gifdevice/#constructor_4)(int, int) | Инициализирует новый экземпляр класса `GifDevice` с указанными размерами изображения, разрешением по умолчанию (=150). |
| [GifDevice](gifdevice/#constructor_3)(PageSize, Resolution) | Инициализирует новый экземпляр класса `GifDevice` с указанным размером страницы и разрешением. |
| [GifDevice](gifdevice/#constructor_5)(int, int, Resolution) | Инициализирует новый экземпляр класса `GifDevice` с указанными размерами изображения и разрешением. |

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
| override [Process](../../aspose.pdf.devices/gifdevice/process/#process)(Page, Stream) | Преобразует страницу в gif и сохраняет её в выходной поток. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторую операцию на указанной странице и сохраняет результаты в файл. |

## Примеры

Следующий пример показывает, как преобразовать файл PDF в изображения GIF.

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

		// Инициализировать GifDevice	
		GifDevice gifDevice = new GifDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream gifStream =
			new FileStream($"{dataDir}image{pageCount}_out.gif",
			FileMode.Create))
			{
				// Преобразовать конкретную страницу и сохранить изображение в поток
				gifDevice.Process(pdfDocument.Pages[pageCount], gifStream);

				// Закрыть поток
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

### См. также

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


