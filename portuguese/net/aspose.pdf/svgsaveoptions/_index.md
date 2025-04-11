---
title: Class SvgSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.SvgSaveOptions. Opções de salvamento para exportação para o formato SVG
type: docs
weight: 10230
url: /pt/net/aspose.pdf/svgsaveoptions/
---
## Classe SvgSaveOptions

Opções de salvamento para exportação para o formato SVG

```csharp
public class SvgSaveOptions : UnifiedSaveOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [SvgSaveOptions](svgsaveoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtém ou define um valor booleano que indica se os glifos da fonte serão armazenados em cache enquanto prepara as páginas aps. Melhora o desempenho da conversão de PDF para outros formatos, mas aumenta o consumo de memória. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtém ou define um valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo ativa a funcionalidade para extrair imagem ou texto de documentos PDF com subcamada OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de salvamento dos dados. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de salvamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de salvamento deve cessar. |

## Campos

| Nome | Descrição |
| --- | --- |
| [CompressOutputToZipArchive](../../aspose.pdf/svgsaveoptions/compressoutputtoziparchive/) | Especifica se a saída será criada como um único arquivo zip. Consulte o comentário sobre as opções 'TreatTargetFileNameAsDirectory' para ver as regras de nomenclatura dos arquivos svg das páginas para documentos de origem multipágina, que também se aplicam ao conjunto compactado de arquivos de saída. |
| [CustomStrategyOfEmbeddedImagesSaving](../../aspose.pdf/svgsaveoptions/customstrategyofembeddedimagessaving/) | Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão para o manuseio personalizado dos arquivos de imagens externas referenciadas criadas (como BMP ou JPEG incorporados) incorporadas no SVG salvo. Essa estratégia deve processar recursos e retornar uma string que representa o URI desejável do recurso salvo no SVG gerado. Se o processamento para este ou aquele arquivo, por algum motivo, deve ser feito pelo código do conversor, e não no código personalizado, defina no código personalizado a flag 'CustomProcessingCancelled' da variável do parâmetro 'imageSavingInfo'. Isso sinaliza ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser feitas no próprio conversor, como se não houvesse nenhum código personalizado externo. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Processar páginas em várias threads. |
| [ScaleToPixels](../../aspose.pdf/svgsaveoptions/scaletopixels/) | Especifica se deve escalar o documento de saída de pontos tipográficos para pixels. |
| [TreatTargetFileNameAsDirectory](../../aspose.pdf/svgsaveoptions/treattargetfilenameasdirectory/) | Esta opção define se será criada uma diretório de destino (se ainda não estiver presente) com o mesmo nome que o arquivo de saída solicitado, em vez do próprio arquivo de saída solicitado. Assim, esse diretório conterá todas as imagens SVG de saída das páginas (como descrito abaixo). Se não, os arquivos de saída das páginas, além do primeiro, serão criados exatamente no diretório solicitado como o arquivo de saída principal, mas conterão no nome do arquivo o sufixo _[2...n], que é definido pelo número da página, por exemplo, se você definir o arquivo de saída "C:\AsposeTests\output.svg" e a saída contiver vários arquivos svg de páginas, então os arquivos das páginas também serão criados no diretório "C:\AsposeTests\" e terão os nomes 'output.svg', 'output_2.svg', 'output_3.svg', etc. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo de azulejos iguais colocadas uma ao lado da outra. Nesse caso, os renderizadores dos formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram limites visíveis entre partes das imagens de fundo, pois suas técnicas de suavização de bordas de imagem (anti-aliasing) são diferentes do Acrobat Reader. Se parecer que o documento exportado contém tais limites visíveis entre partes das mesmas imagens de fundo, tente usar esta configuração para se livrar desse efeito indesejado. ATENÇÃO! Esta otimização de qualidade geralmente desacelera significativamente a conversão, portanto, use esta opção apenas quando realmente necessário. |

## Exemplos

O exemplo a seguir mostra como converter um arquivo PDF para um arquivo SVG

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf");

	// The path to output SVG File.
	var svgFile= Path.Combine(dataDir, "PDF-to-SVG.svg");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize SvgSaveOptions	
		SvgSaveOptions saveOptions = new SvgSaveOptions();
		
		// Save SVG file
		pdfDocument.Save(svgFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-SVG.pdf")

    ' The path to output SVG File.
    Dim svgFile = Path.Combine(dataDir, "PDF-to-SVG.svg")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize SvgSaveOptions
        Dim saveOptions As SvgSaveOptions = New SvgSaveOptions()
 
        ' Save SVG file
        pdfDocument.Save(svgFile, saveOptions)
    End Using
```

### Veja Também

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)