---
title: Class HtmlLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlLoadOptions. Representa opções para carregar/importar arquivo html em documento pdf
type: docs
weight: 5530
url: /pt/net/aspose.pdf/htmlloadoptions/
---
## Classe HtmlLoadOptions

Representa opções para carregar/importar arquivo html em documento pdf.

```csharp
public sealed class HtmlLoadOptions : LoadOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [HtmlLoadOptions](htmlloadoptions/#constructor)() | Cria opções de carregamento para converter html em documento pdf com caminho base vazio. |
| [HtmlLoadOptions](htmlloadoptions/#constructor_1)(string) | Cria opções de carregamento para converter html em documento pdf com caminho base definido. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BasePath](../../aspose.pdf/htmlloadoptions/basepath/) { get; } | O caminho/url base para o arquivo html. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtém ou define a flag para desabilitar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando `true`, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desabilitem a incorporação para essa fonte. Por padrão `false`. |
| [HtmlMediaType](../../aspose.pdf/htmlloadoptions/htmlmediatype/) { get; set; } | Obtém ou define os tipos de mídia possíveis usados durante a renderização. |
| [InputEncoding](../../aspose.pdf/htmlloadoptions/inputencoding/) { get; set; } | Obtém ou define o atributo que especifica a codificação usada para este documento no momento da análise. Se este atributo for nulo, a codificação será determinada a partir do atributo de conjunto de caracteres do documento. |
| [IsEmbedFonts](../../aspose.pdf/htmlloadoptions/isembedfonts/) { get; set; } | Obtém ou define a incorporação de fontes no documento resultante |
| [IsPriorityCssPageRule](../../aspose.pdf/htmlloadoptions/isprioritycsspagerule/) { get; set; } | Obtém ou define a flag que especifica que as regras @page definidas em css substituirão os valores definidos em PageInfo. |
| [IsRenderToSinglePage](../../aspose.pdf/htmlloadoptions/isrendertosinglepage/) { get; set; } | Obtém ou define a renderização de todo o documento em uma única página |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa o formato de arquivo que [`LoadOptions`](../loadoptions/) descreve. |
| [PageInfo](../../aspose.pdf/htmlloadoptions/pageinfo/) { get; set; } | Obtém ou define as informações da página do documento |
| [PageLayoutOption](../../aspose.pdf/htmlloadoptions/pagelayoutoption/) { get; set; } | Obtém ou define a opção de layout. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de carregamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de carregamento deve cessar. |

## Campos

| Nome | Descrição |
| --- | --- |
| [CustomLoaderOfExternalResources](../../aspose.pdf/htmlloadoptions/customloaderofexternalresources/) | Às vezes, é necessário evitar o uso do carregador interno de recursos externos (como imagens ou CSS) e fornecer um método personalizado que obterá os recursos solicitados de algum lugar. Por exemplo, durante o uso do Aspose.PDF na nuvem, o acesso direto a arquivos referenciados é impossível: nesse caso, algum código personalizado colocado em um método especial deve ser usado, e um delegado que se refere a esse método deve ser atribuído a este atributo. |
| [ExternalResourcesCredentials](../../aspose.pdf/htmlloadoptions/externalresourcescredentials/) | Se o carregamento de dados externos referenciados no HTML requer credenciais, você pode colocá-las neste parâmetro - elas serão usadas durante o carregamento de recursos externos |

## Exemplos

O seguinte exemplo mostra como converter um arquivo HTML em um arquivo PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your HTML File.
	string htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf");

	// Initialize HtmlLoadOptions	
	HtmlLoadOptions htmlLoadOptions = new HtmlLoadOptions();
		
	using (Document pdfDocument = new Document(htmlFile, htmlLoadOptions))
	{ 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your HTML File.
    Dim htmlFile = Path.Combine(dataDir, "HTML-to-PDF.html")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "HTML-to-PDF.pdf")
 
    ' Initialize HtmlLoadOptions    
    Dim htmlLoadOptions As HtmlLoadOptions = New HtmlLoadOptions()
 
    Using pdfDocument As Document = New Document(htmlFile, htmlLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Veja Também

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)