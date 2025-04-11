---
title: Class TeXLoadOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.TeXLoadOptions. Representa opções para carregar/importar arquivo TeX em documento PDF
type: docs
weight: 10370
url: /pt/net/aspose.pdf/texloadoptions/
---
## Classe TeXLoadOptions

Representa opções para carregar/importar arquivo TeX em documento PDF.

```csharp
public class TeXLoadOptions : LoadOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TeXLoadOptions](texloadoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [DateTime](../../aspose.pdf/texloadoptions/datetime/) { get; set; } | Obtém/define um certo valor para primitivas de data/hora como ano, mês, dia e hora. |
| [DisableFontLicenseVerifications](../../aspose.pdf/loadoptions/disablefontlicenseverifications/) { get; set; } | Obtém ou define uma flag para desativar quaisquer restrições de licença para todas as fontes ao carregar o arquivo. Quando `true`, permite executar operações com fontes que são proibidas por uma licença dessa fonte, por exemplo, permite incorporar uma fonte em um documento PDF mesmo que as regras de licença desativem a incorporação para essa fonte. Por padrão `false`. |
| [InputDirectory](../../aspose.pdf/texloadoptions/inputdirectory/) { get; set; } | Obtém/define o diretório de entrada TeX. |
| [JobName](../../aspose.pdf/texloadoptions/jobname/) { get; set; } | Obtém/define o nome do trabalho. |
| [LoadFormat](../../aspose.pdf/loadoptions/loadformat/) { get; } | Representa o formato de arquivo que [`LoadOptions`](../loadoptions/) descreve. |
| [NoLigatures](../../aspose.pdf/texloadoptions/noligatures/) { get; set; } | Obtém/define uma flag que cancela ligaduras em todas as fontes. |
| [OutputDirectory](../../aspose.pdf/texloadoptions/outputdirectory/) { get; set; } | Obtém/define o diretório de saída TeX. |
| [RasterizeFormulas](../../aspose.pdf/texloadoptions/rasterizeformulas/) { get; set; } | Obtém/define uma flag que permite rasterizar fórmulas matemáticas. |
| [Repeat](../../aspose.pdf/texloadoptions/repeat/) { get; set; } | Obtém/define a flag que indica se é necessário executar o trabalho TeX duas vezes no caso, por exemplo, de haver referências nos arquivos TeX de entrada. Em geral, esse comportamento é útil quando o mecanismo coleta alguns dados ao longo do processo de composição e os armazena em um arquivo auxiliar, tudo na primeira execução. E na segunda execução, o mecanismo de alguma forma usa esses dados. |
| [RequiredInputDirectory](../../aspose.pdf/texloadoptions/requiredinputdirectory/) { get; set; } | Obtém/define o diretório de entrada requerido pelo TeX. A entrada requerida são os arquivos que estão de alguma forma incluídos no arquivo .tex principal, por exemplo, pacotes para os quais não há suporte embutido. |
| [ShowTerminalOutput](../../aspose.pdf/texloadoptions/showterminaloutput/) { get; set; } | Obtém/define a flag que indica se deve mostrar a saída do terminal no console. |
| [SubsetFonts](../../aspose.pdf/texloadoptions/subsetfonts/) { get; set; } | Obtém/define a flag que indica se deve subdefinir fontes no arquivo de saída ou não. |
| [WarningHandler](../../aspose.pdf/loadoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de carregamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de carregamento deve cessar. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetLoadResult](../../aspose.pdf/texloadoptions/getloadresult/)() | Obtém o resultado do carregamento e compilação do TeX - tudo correu bem ou houve comentários/erros. |

## Exemplos

O seguinte exemplo mostra como converter um arquivo TeX em um arquivo PDF

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = @"YOUR_DATA_DIRECTORY";

	// The path to your TeX File.
	string texFile = Path.Combine(dataDir, "TeX-to-PDF.tex");

	// The path to output PDF File.
	string pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf");

	// Initialize TeXLoadOptions	
	TeXLoadOptions texLoadOptions = new TeXLoadOptions();
		
	using (Document pdfDocument = new Document(texFile, texLoadOptions))
	{
	 
		// Save PDF file
		pdfDocument.Save(pdfFile);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your TeX File.
    Dim texFile = Path.Combine(dataDir, "TeX-to-PDF.tex")

    ' The path to output PDF File.
    Dim pdfFile = Path.Combine(dataDir, "Tex-to-PDF.pdf")
 
    ' Initialize TeXLoadOptions
    Dim texLoadOptions As TeXLoadOptions = New TeXLoadOptions()
 
    Using pdfDocument As Document = New Document(texFile, texLoadOptions)
 
        ' Save PDF file
        pdfDocument.Save(pdfFile)
    End Using
```

### Veja Também

* classe [LoadOptions](../loadoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)