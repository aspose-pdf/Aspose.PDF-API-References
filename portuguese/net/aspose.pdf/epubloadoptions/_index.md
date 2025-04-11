---
title: Class EpubLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.EpubLoadOptions. Contém opções para carregar/importar arquivo EPUB em documento pdf
type: docs
weight: 4050
url: /pt/net/aspose.pdf/epubloadoptions/
---
## Classe EpubLoadOptions

Contém opções para carregar/importar arquivo EPUB em documento pdf.

```csharp
public sealed class EpubLoadOptions : LoadOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [EpubLoadOptions](epubloadoptions/#constructor)() | Cria opções de carregamento padrão para converter arquivo EPUB em documento pdf. Tamanho padrão da página pdf - A4 300dpi 2480 X 3508. |
| [EpubLoadOptions](epubloadoptions/#constructor_1)(SizeF) | Cria opções de carregamento com tamanho de página especificado. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CustomCss](../../aspose.pdf/epubloadoptions/customcss/) { get; set; } | Obtém ou define o Css personalizado a ser aplicado ao abrir o documento Epub. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtém ou define a flag para desativar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando `true`, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desativem a incorporação para essa fonte. Por padrão `false`. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa o formato do arquivo que [`LoadOptions`](../loadoptions/) descreve. |
| [Margin](../../aspose.pdf/epubloadoptions/margin/) { get; set; } | Obtém referência ao objeto que representa as informações de margem. |
| [PageSize](../../aspose.pdf/epubloadoptions/pagesize/) { get; } | Obtém ou define o tamanho da página de saída para importação. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de carregamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de carregamento deve cessar. |

## Campos

| Nome | Descrição |
| --- | --- |
| [MarginsAreaUsageMode](../../aspose.pdf/epubloadoptions/marginsareausagemode/) | Representa o modo de uso da área de margens - define o tratamento das instruções (se houver) do CSS do documento importado relacionadas ao uso de margens. |
| [PageSizeAdjustmentMode](../../aspose.pdf/epubloadoptions/pagesizeadjustmentmode/) | ATENÇÃO! O recurso foi implementado, mas ainda não foi colocado na API pública desde que um problema bloqueador na camada OSHARED foi revelado para o documento de exemplo. Representa o modo de uso do tamanho da página durante a conversão. Formatos (como HTML, EPUB etc), geralmente têm design flutuante, portanto, permite ajustar o tamanho da página necessário. Mas às vezes o conteúdo tem posições ou tamanhos horizontais especificados que não permitem colocar o conteúdo no tamanho de página necessário. Nesse caso, podemos definir o que deve ser feito nesse caso (ou seja, quando o tamanho do conteúdo não se ajusta ao tamanho de página inicial necessário do documento PDF resultante). |

## Exemplos

O seguinte exemplo mostra como converter um arquivo EPUB em um arquivo PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your EPUB File.
	string epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf");

	// Initialize EpubLoadOptions 	
	EpubLoadOptions epubLoadOptions = new EpubLoadOptions();
		
	using (Document pdfDocument = new Document(epubFile, epubLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your EPUB File.
    Dim epubFile = Path.Combine(dataDir, "EPUB-to-PDF.epub")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "EPUB-to-PDF.pdf")
 
    ' Initialize EpubLoadOptions    
    Dim epubLoadOptions As EpubLoadOptions = New EpubLoadOptions()
 
    Using pdfDocument As Document = New Document(epubFile, epubLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Veja Também

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)