---
title: "Класс PngDevice"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Devices.PngDevice class. Представляет устройство изображения, которое помогает сохранять страницы PDF‑документа в png."
type: docs
weight: 3770
url: /ru/net/aspose.pdf.devices/pngdevice/
---
## PngDevice class

Представляет устройство изображения, которое помогает сохранять страницы pdf‑документа в png.

```csharp
public sealed class PngDevice : ImageDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | Инициализирует новый экземпляр класса `PngDevice` с разрешением по умолчанию. |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | Инициализирует новый экземпляр класса `PngDevice` с указанным размером страницы, разрешением по умолчанию (=150). |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | Инициализирует новый экземпляр класса `PngDevice`.  Разрешение результирующего файла изображения, см. класс [`Resolution`](../resolution/). |
| [PngDevice](pngdevice/#constructor_4)(int, int) | Инициализирует новый экземпляр класса `PngDevice` с указанными размерами изображения, разрешением по умолчанию (=150). |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | Инициализирует новый экземпляр класса `PngDevice` с указанным размером страницы и разрешением. |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | Инициализирует новый экземпляр класса `PngDevice` с указанными размерами изображения и разрешением. |

## Свойства

| Имя | Описание |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Получает или задает тип координат страницы (Media/Crop boxes). Значение CropBox используется по умолчанию. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Получает или задает режим отображения формы. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Получает высоту выходного изображения. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Получает разрешение изображения. |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | Получает или задает, имеет ли изображение прозрачный фон. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Получает ширину выходного изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| [GetBitmap](../../aspose.pdf.devices/imagedevice/getbitmap/)(Page) | Преобразует page в Bitmap. |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | Преобразует страницу в png и сохраняет её в выходном потоке. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторую операцию на указанной странице и сохраняет результаты в файл. |

## Примеры

В следующем примере показано, как преобразовать PDF‑файл в PNG‑изображения.

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

		// Инициализировать PngDevice	
		PngDevice pngDevice = new PngDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream pngStream =
			new FileStream($"{dataDir}image{pageCount}_out.png",
			FileMode.Create))
			{
				// Преобразовать конкретную страницу и сохранить изображение в поток
				pngDevice.Process(pdfDocument.Pages[pageCount], pngStream);

				// Закрыть поток
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

* class [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


