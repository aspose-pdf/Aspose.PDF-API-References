---
title: Class GifDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.GifDevice. Representa um dispositivo de imagem que ajuda a salvar páginas de documentos PDF em gif
type: docs
weight: 3600
url: /pt/net/aspose.pdf.devices/gifdevice/
---
## Classe GifDevice

Representa um dispositivo de imagem que ajuda a salvar páginas de documentos PDF em gif.

```csharp
public sealed class GifDevice : ImageDevice
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [GifDevice](gifdevice/#constructor)() | Inicializa uma nova instância da classe `GifDevice` com resolução padrão. |
| [GifDevice](gifdevice/#constructor_2)(PageSize) | Inicializa uma nova instância da classe `GifDevice` com o tamanho de página fornecido, resolução padrão (=150). |
| [GifDevice](gifdevice/#constructor_1)(Resolution) | Inicializa uma nova instância da classe `GifDevice`. Resolução para o arquivo de imagem resultante, veja a classe [`Resolution`](../resolution/). |
| [GifDevice](gifdevice/#constructor_4)(int, int) | Inicializa uma nova instância da classe `GifDevice` com as dimensões da imagem fornecidas, resolução padrão (=150). |
| [GifDevice](gifdevice/#constructor_3)(PageSize, Resolution) | Inicializa uma nova instância da classe `GifDevice` com o tamanho de página e resolução fornecidos. |
| [GifDevice](gifdevice/#constructor_5)(int, int, Resolution) | Inicializa uma nova instância da classe `GifDevice` com as dimensões da imagem e resolução fornecidas. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CoordinateType](../../aspose.pdf.devices/imagedevice/coordinatetype/) { get; set; } | Obtém ou define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| [FormPresentationMode](../../aspose.pdf.devices/imagedevice/formpresentationmode/) { get; set; } | Obtém ou define o modo de apresentação do formulário. |
| [Height](../../aspose.pdf.devices/imagedevice/height/) { get; } | Obtém a altura da saída da imagem. |
| [RenderingOptions](../../aspose.pdf.devices/imagedevice/renderingoptions/) { get; set; } | Obtém ou define as opções de renderização. |
| [Resolution](../../aspose.pdf.devices/imagedevice/resolution/) { get; } | Obtém a resolução da imagem. |
| [Width](../../aspose.pdf.devices/imagedevice/width/) { get; } | Obtém a largura da saída da imagem. |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [Process](../../aspose.pdf.devices/gifdevice/process/#process)(Page, Stream) | Converte a página em gif e a salva no fluxo de saída. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguma operação na página dada e salva os resultados no arquivo. |

## Exemplos

O seguinte exemplo mostra como converter um arquivo PDF em Imagens GIF.

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

		// Initialize GifDevice	
		GifDevice gifDevice = new GifDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream gifStream =
			new FileStream($"{dataDir}image{pageCount}_out.gif",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				gifDevice.Process(pdfDocument.Pages[pageCount], gifStream);

				// Close stream
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

### Veja Também

* classe [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)