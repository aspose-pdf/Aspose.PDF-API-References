---
title: Class TiffDevice
second_title: Aspose.PDF for .NET API Reference
description: Класс Aspose.Pdf.Devices.TiffDevice. Этот класс помогает сохранить страницы pdf документа в одно изображение tiff.
type: docs
weight: 3700
url: /ru/net/aspose.pdf.devices/tiffdevice/
---
## Класс TiffDevice

Этот класс помогает сохранить страницы pdf документа в одно изображение tiff.

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
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Получает или задает режим представления формы. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Получает высоту выходного изображения. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | Получает или задает параметры рендеринга. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Получает разрешение изображения. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | Получает настройки для отображения pdf в изображение tiff. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Получает ширину выходного изображения. |

## Методы

| Имя | Описание |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Выполняет бинаризацию Бредли для входного потока. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Обрабатывает весь документ и сохраняет результаты в поток. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Обрабатывает весь документ и сохраняет результаты в файл. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Выполняет некоторые операции на данной странице и сохраняет результаты в файл. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Преобразует определенные страницы документа в tiff и сохраняет их в выходном потоке. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Обрабатывает определенные страницы документа и сохраняет результаты в файл. |

## Примеры

Следующий пример показывает, как преобразовать PDF файл в TIFF изображения.

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
		
		// Create TiffSettings object
		TiffSettings tiffSettings = new TiffSettings
		{
			Compression = CompressionType.None,
			Depth = ColorDepth.Default,
			Shape = ShapeType.Landscape,
			SkipBlankPages = false
		};

		// Create TIFF device
		TiffDevice tiffDevice = new TiffDevice(resolution, tiffSettings);

		// Convert a PDF document to TIFF image
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

* класс [DocumentDevice](../documentdevice/)
* пространство имен [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* сборка [Aspose.PDF](../../)