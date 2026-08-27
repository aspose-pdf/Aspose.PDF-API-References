---
title: "Класс TiffDevice"
second_title: "Справочник API Aspose.PDF для .NET"
description: "Aspose.Pdf.Devices.TiffDevice class. Этот класс помогает сохранять PDF‑документ постранично в одно TIFF‑изображение"
type: docs
weight: 3820
url: /ru/net/aspose.pdf.devices/tiffdevice/
---
## TiffDevice class

Этот класс помогает сохранять страницы pdf‑документа по одной в одно tiff‑изображение.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Конструкторы

| Имя | Описание |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | Инициализирует новый экземпляр класса `TiffDevice` с настройками по умолчанию. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | Инициализирует новый экземпляр класса `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | Инициализирует новый экземпляр класса `TiffDevice`. |

## Свойства

| Имя | Описание |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Получает или задает режим отображения формы. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Получает высоту выходного изображения. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Получает разрешение изображения. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | Получает настройки для отображения PDF в TIFF‑изображение. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Получает ширину выходного изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Выполняет бинаризацию Брэдли для входного потока. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Обрабатывает весь документ и сохраняет результаты в поток. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Обрабатывает весь документ и сохраняет результаты в файл. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторую операцию на указанной странице и сохраняет результаты в файл. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Преобразует определённые страницы документа в TIFF и сохраняет их в выходном потоке. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Обрабатывает определённые страницы документа и сохраняет результаты в файл. |

## Примеры

В следующем примере показано, как преобразовать PDF‑файл в изображения TIFF.

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
		
		// Создать объект TiffSettings
		TiffSettings tiffSettings = new TiffSettings
		{
			Compression = CompressionType.None,
			Depth = ColorDepth.Default,
			Shape = ShapeType.Landscape,
			SkipBlankPages = false
		};

		// Создать устройство TIFF
		TiffDevice tiffDevice = new TiffDevice(resolution, tiffSettings);

		// Преобразовать PDF‑документ в изображение TIFF
		tiffDevice.Process(pdfDocument, dataDir + "AllPagesToTIFF_out.tif");
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
		
		' Create TiffSettings object
		Dim tiffSettings As TiffSettings = New TiffSettings With {
		  .Compression = CompressionType.None,
			.Depth = ColorDepth.[Default],
			.Shape = ShapeType.Landscape,
			.SkipBlankPages = False
		}

		' Create TIFF device
		Dim tiffDevice As TiffDevice = New TiffDevice(resolution, tiffSettings)

		' Convert a PDF document to TIFF image
		tiffDevice.Process(pdfDocument, dataDir & "AllPagesToTIFF_out.tif")

	End Using
```

### См. также

* class [DocumentDevice](../documentdevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)


