---
title: Class PclLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PclLoadOptions. Representa opções para carregar/importar arquivo PCL em documento PDF
type: docs
weight: 8300
url: /pt/net/aspose.pdf/pclloadoptions/
---
## Classe PclLoadOptions

Representa opções para carregar (importar) arquivo PCL em documento PDF.

```csharp
public sealed class PclLoadOptions : LoadOptions, IPipelineOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PclLoadOptions](pclloadoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BatchSize](../../aspose.pdf/pclloadoptions/batchsize/) { get; set; } | Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtém ou define a flag para desabilitar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando `true`, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desabilitem a incorporação para essa fonte. Por padrão `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa o formato de arquivo que [`LoadOptions`](../loadoptions/) descreve. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de carregamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de carregamento deve cessar. |

## Campos

| Nome | Descrição |
| --- | --- |
| [ConversionEngine](../../aspose.pdf/pclloadoptions/conversionengine/) | Define o mecanismo de conversão que será usado para a conversão |
| [Exceptions](../../aspose.pdf/pclloadoptions/exceptions/) | Lista de erros de conversão. |
| [SupressErrors](../../aspose.pdf/pclloadoptions/supresserrors/) | Obtém ou define um valor booleano que indica se os erros de conversão PCL devem ser suprimidos. |

## Exemplos

O seguinte exemplo mostra como converter um arquivo PCL em um arquivo PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your PCL File.
	string pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf");

	// Initialize PclLoadOptions	
	PclLoadOptions pclLoadOptions = new PclLoadOptions();
		
	using (Document pdfDocument = new Document(pclFile, pclLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PCL File.
    Dim pclFile = Path.Combine(dataDir, "PCL-to-PDF.pcl")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PCL-to-PDF.pdf")
 
    ' Initialize PclLoadOptions
    Dim pclLoadOptions As PclLoadOptions = New PclLoadOptions()
 
    Using pdfDocument As Document = New Document(pclFile, pclLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Veja Também

* classe [LoadOptions](../loadoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)