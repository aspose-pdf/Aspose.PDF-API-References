---
title: Class JpegDevice
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Devices.JpegDevice. Representa um dispositivo de imagem que ajuda a salvar páginas de documentos PDF em jpeg
type: docs
weight: 3620
url: /pt/net/aspose.pdf.devices/jpegdevice/
---
## Classe JpegDevice

Representa um dispositivo de imagem que ajuda a salvar páginas de documentos PDF em jpeg.

```csharp
public sealed class JpegDevice : ImageDevice
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [JpegDevice](jpegdevice/#constructor)() | Inicializa uma nova instância da classe `JpegDevice` com resolução padrão e qualidade máxima. |
| [JpegDevice](jpegdevice/#constructor_6)(int) | Inicializa uma nova instância da classe `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_3)(PageSize) | Inicializa uma nova instância da classe `JpegDevice` com o tamanho de página fornecido, resolução padrão (=150) e qualidade máxima. |
| [JpegDevice](jpegdevice/#constructor_1)(Resolution) | Inicializa uma nova instância da classe `JpegDevice`. Resolução para o arquivo de imagem resultante, veja a classe [`Resolution`](../resolution/). |
| [JpegDevice](jpegdevice/#constructor_7)(int, int) | Inicializa uma nova instância da classe `JpegDevice` com as dimensões da imagem fornecidas, resolução padrão (=150) e qualidade máxima. |
| [JpegDevice](jpegdevice/#constructor_4)(PageSize, Resolution) | Inicializa uma nova instância da classe `JpegDevice` com o tamanho de página fornecido, resolução e qualidade máxima. |
| [JpegDevice](jpegdevice/#constructor_2)(Resolution, int) | Inicializa uma nova instância da classe `JpegDevice`. |
| [JpegDevice](jpegdevice/#constructor_8)(int, int, Resolution) | Inicializa uma nova instância da classe `JpegDevice` com as dimensões da imagem fornecidas, resolução e qualidade máxima. |
| [JpegDevice](jpegdevice/#constructor_5)(PageSize, Resolution, int) | Inicializa uma nova instância da classe `JpegDevice` com o tamanho de página fornecido, resolução e qualidade. |
| [JpegDevice](jpegdevice/#constructor_9)(int, int, Resolution, int) | Inicializa uma nova instância da classe `JpegDevice` com as dimensões da imagem fornecidas, resolução e qualidade. |

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
| override [Process](../../aspose.pdf.devices/jpegdevice/process/#process)(Page, Stream) | Converte a página em jpeg e a salva no fluxo de saída. |
| [Process](../../aspose.pdf.devices/pagedevice/process/)(Page, string) | Realiza alguma operação na página dada e salva os resultados no arquivo. |

## Exemplos

O exemplo a seguir mostra como converter um arquivo PDF em imagens JPEG.

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

		// Initialize JpegDevice	
		JpegDevice jpegDevice = new JpegDevice(resolution);
		for (int pageCount = 1; pageCount <= pdfDocument.Pages.Count; pageCount++)
		{
			using (FileStream jpegStream =
			new FileStream($"{dataDir}image{pageCount}_out.jpeg",
			FileMode.Create))
			{
				// Convert a particular page and save the image to stream
				jpegDevice.Process(pdfDocument.Pages[pageCount], jpegStream);

				// Close stream
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

### Veja Também

* classe [ImageDevice](../imagedevice/)
* namespace [Aspose.Pdf.Devices](../../aspose.pdf.devices/)
* assembly [Aspose.PDF](../../)