---
title: Class TiffDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.TiffDevice. Esta classe ajuda a salvar o documento pdf página por página em uma única imagem tiff
type: docs
weight: 3700
url: /pt/net/aspose.pdf.devices/tiffdevice/
---
## Classe TiffDevice

Esta classe ajuda a salvar o documento pdf página por página em uma única imagem tiff.

```csharp
public sealed class TiffDevice : DocumentDevice
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TiffDevice](tiffdevice/#constructor)() | Inicializa uma nova instância da classe `TiffDevice` com configurações padrão. |
| [TiffDevice](tiffdevice/#constructor_6)(PageSize) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_1)(Resolution) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_4)(TiffSettings) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_12)(int, int) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_7)(PageSize, Resolution) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_10)(PageSize, TiffSettings) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_2)(Resolution, TiffSettings) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_5)(TiffSettings, IIndexBitmapConverter) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_13)(int, int, Resolution) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_16)(int, int, TiffSettings) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_8)(PageSize, Resolution, TiffSettings) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_11)(PageSize, TiffSettings, IIndexBitmapConverter) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_3)(Resolution, TiffSettings, IIndexBitmapConverter) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_14)(int, int, Resolution, TiffSettings) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_17)(int, int, TiffSettings, IIndexBitmapConverter) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_9)(PageSize, Resolution, TiffSettings, IIndexBitmapConverter) | Inicializa uma nova instância da classe `TiffDevice`. |
| [TiffDevice](tiffdevice/#constructor_15)(int, int, Resolution, TiffSettings, IIndexBitmapConverter) | Inicializa uma nova instância da classe `TiffDevice`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [FormPresentationMode](../../aspose.pdf.devices/tiffdevice/formpresentationmode/) { get; set; } | Obtém ou define o modo de apresentação de formulário. |
| [Height](../../aspose.pdf.devices/tiffdevice/height/) { get; } | Obtém a altura da imagem de saída. |
| [RenderingOptions](../../aspose.pdf.devices/tiffdevice/renderingoptions/) { get; set; } | Obtém ou define as opções de renderização. |
| [Resolution](../../aspose.pdf.devices/tiffdevice/resolution/) { get; } | Obtém a resolução da imagem. |
| [Settings](../../aspose.pdf.devices/tiffdevice/settings/) { get; } | Obtém as configurações para mapear pdf em imagem tiff. |
| [Width](../../aspose.pdf.devices/tiffdevice/width/) { get; } | Obtém a largura da imagem de saída. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [BinarizeBradley](../../aspose.pdf.devices/tiffdevice/binarizebradley/)(Stream, Stream, double) | Realiza a binarização de Bradley para o fluxo de entrada. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, Stream) | Processa o documento inteiro e salva os resultados no fluxo. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, string) | Processa o documento inteiro e salva os resultados em um arquivo. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process_4)(Page, Stream) |  |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguma operação na página dada e salva os resultados no arquivo. |
| override [Process](../../aspose.pdf.devices/tiffdevice/process/#process)(Document, int, int, Stream) | Converte certas páginas do documento em tiff e as salva no fluxo de saída. |
| [Process](../../aspose.pdf.devices/documentdevice/process/)(Document, int, int, string) | Processa certas páginas do documento e salva os resultados em um arquivo. |

## Exemplos

O seguinte exemplo mostra como converter um arquivo PDF em Imagens TIFF.

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

### Veja Também

* classe [DocumentDevice](../documentdevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)