---
title: Class PngDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.PngDevice. Representa um dispositivo de imagem que ajuda a salvar páginas de documentos pdf em png
type: docs
weight: 3650
url: /pt/net/aspose.pdf.devices/pngdevice/
---
## Classe PngDevice

Representa um dispositivo de imagem que ajuda a salvar páginas de documentos pdf em png.

```csharp
public sealed class PngDevice : ImageDevice
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PngDevice](pngdevice/#constructor)() | Inicializa uma nova instância da classe `PngDevice` com resolução padrão. |
| [PngDevice](pngdevice/#constructor_2)(PageSize) | Inicializa uma nova instância da classe `PngDevice` com o tamanho de página fornecido, resolução padrão (=150). |
| [PngDevice](pngdevice/#constructor_1)(Resolution) | Inicializa uma nova instância da classe `PngDevice`. Resolução para o arquivo de imagem resultante, veja a classe [`Resolution`](../resolution/). |
| [PngDevice](pngdevice/#constructor_4)(int, int) | Inicializa uma nova instância da classe `PngDevice` com as dimensões da imagem fornecidas, resolução padrão (=150). |
| [PngDevice](pngdevice/#constructor_3)(PageSize, Resolution) | Inicializa uma nova instância da classe `PngDevice` com o tamanho de página e a resolução fornecidos. |
| [PngDevice](pngdevice/#constructor_5)(int, int, Resolution) | Inicializa uma nova instância da classe `PngDevice` com as dimensões da imagem e a resolução fornecidas. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtém ou define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtém ou define o modo de apresentação do formulário. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtém a altura da saída da imagem. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtém ou define as opções de renderização. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtém a resolução da imagem. |
| [TransparentBackground](../../aspose.pdf.devices/pngdevice/transparentbackground/) { get; set; } | Obtém ou define se a imagem tem fundo transparente. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtém a largura da saída da imagem. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Process](../../aspose.pdf.devices/pngdevice/process/#process)(Page, Stream) | Converte a página em png e a salva no fluxo de saída. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguma operação na página dada e salva os resultados no arquivo. |

## Exemplos

O exemplo a seguir mostra como converter um arquivo PDF em imagens PNG.

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

### Veja Também

* classe [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)