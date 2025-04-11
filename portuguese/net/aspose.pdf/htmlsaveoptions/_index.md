---
title: Class HtmlSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.HtmlSaveOptions. Opções de salvamento para exportação para o formato Html
type: docs
weight: 5560
url: /pt/net/aspose.pdf/htmlsaveoptions/
---
## Classe HtmlSaveOptions

Opções de salvamento para exportação para o formato Html

```csharp
public class HtmlSaveOptions : UnifiedSaveOptions, IPageSetOptions, IPipelineOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [HtmlSaveOptions](htmlsaveoptions/#constructor)() | Inicializa uma nova instância da classe `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_3)(bool) | Inicializa uma nova instância da classe `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_1)(HtmlDocumentType) | Inicializa uma nova instância da classe `HtmlSaveOptions`. |
| [HtmlSaveOptions](htmlsaveoptions/#constructor_2)(HtmlDocumentType, bool) | Inicializa uma nova instância da classe `HtmlSaveOptions`. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [BatchSize](../../aspose.pdf/htmlsaveoptions/batchsize/) { get; set; } | Define o tamanho do lote se a conversão em lotes for aplicável ao par de formatos de origem e destino. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtém ou define um valor booleano que indica se os glifos da fonte serão armazenados em cache ao preparar páginas aps. Melhora o desempenho da conversão de pdf para outros formatos, mas aumenta o consumo de memória. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtém ou define um valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| [CompressSvgGraphicsIfAny](../../aspose.pdf/htmlsaveoptions/compresssvggraphicsifany/) { get; set; } | Obtém ou define a flag que indica se gráficos SVG encontrados (se houver) serão comprimidos (zipados) no formato SVGZ durante o salvamento. |
| [ConvertMarkedContentToLayers](../../aspose.pdf/htmlsaveoptions/convertmarkedcontenttolayers/) { get; set; } | Se o atributo ConvertMarkedContentToLayers estiver definido como verdadeiro, todos os elementos dentro de um conteúdo marcado PDF (camada) serão colocados em um div HTML com o atributo "data-pdflayer" especificando um nome de camada. Este nome de camada será extraído das propriedades opcionais do conteúdo marcado PDF. Se este atributo for falso (por padrão), nenhuma camada será criada a partir do conteúdo marcado PDF. |
| [DefaultFontName](../../aspose.pdf/htmlsaveoptions/defaultfontname/) { get; set; } | Especifica o nome de uma fonte instalada que é usada para substituir qualquer fonte do documento que não esteja incorporada e não esteja instalada no sistema. Se nulo, a fonte de substituição padrão é usada. |
| [DocumentType](../../aspose.pdf/htmlsaveoptions/documenttype/) { get; set; } | Obtém ou define o [`HtmlDocumentType`](../htmldocumenttype/). |
| [ExplicitListOfSavedPages](../../aspose.pdf/htmlsaveoptions/explicitlistofsavedpages/) { get; set; } | Com esta propriedade, você pode definir explicitamente quais páginas do documento devem ser convertidas. As páginas nesta lista devem ter números baseados em 1. Ou seja, números válidos de páginas devem ser retirados do intervalo (1...[NumberOfPagesInConvertedDocument]) A ordem de aparecimento das páginas nesta lista não afeta sua ordem na(s) página(s) HTML resultante(s) - nas páginas resultantes, todas sempre estarão na ordem em que estão presentes no PDF de origem. Se esta lista for nula (como é por padrão), todas as páginas serão convertidas. Se qualquer número de página desta lista estiver fora do intervalo das páginas presentes (1-[amountOfPagesInDocument]), uma exceção será lançada. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo ativa a funcionalidade para extrair imagem ou texto para documentos PDF com subcamada OCR. |
| [FixedLayout](../../aspose.pdf/htmlsaveoptions/fixedlayout/) { get; set; } | Obtém ou define um valor que indica se o HTML é criado como layout fixo. |
| [FlowLayoutParagraphFullWidth](../../aspose.pdf/htmlsaveoptions/flowlayoutparagraphfullwidth/) { get; set; } | Este atributo especifica texto de parágrafo de largura total para o modo de fluxo, FixedLayout = falso. |
| [FontSources](../../aspose.pdf/htmlsaveoptions/fontsources/) { get; } | Fontes de fontes pré-salvas. |
| [IgnoredTextFontSize](../../aspose.pdf/htmlsaveoptions/ignoredtextfontsize/) { get; set; } | Texto com o tamanho especificado ou menor será ignorado durante a conversão. Não removemos esse texto, apenas o ignoramos e não o transferimos para o arquivo de saída. |
| [IgnoreResourceFontErrors](../../aspose.pdf/htmlsaveoptions/ignoreresourcefonterrors/) { get; set; } | Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados. verdadeiro - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que se referem a recursos incorretos serão ignorados durante o processamento. falso por padrão. |
| [ImageResolution](../../aspose.pdf/htmlsaveoptions/imageresolution/) { get; set; } | Obtém ou define a resolução para renderização de imagem. |
| [MinimalLineWidth](../../aspose.pdf/htmlsaveoptions/minimallinewidth/) { get; set; } | Este atributo define a largura mínima da linha do caminho gráfico. Se a espessura da linha for menor que 1px, o Adobe Acrobat arredonda para este valor. Portanto, este atributo pode ser usado para emular esse comportamento para navegadores HTML. |
| [PreventGlyphsGrouping](../../aspose.pdf/htmlsaveoptions/preventglyphsgrouping/) { get; set; } | Este atributo ativa o modo em que os glifos de texto não serão agrupados em palavras e strings. Este modo permite manter a máxima precisão durante o posicionamento dos glifos na página e pode ser usado para converter documentos com notas musicais ou glifos que devem ser colocados separadamente uns dos outros. Este parâmetro será aplicado ao documento apenas quando o valor do atributo FixedLayout for verdadeiro. |
| [RenderTextAsImage](../../aspose.pdf/htmlsaveoptions/rendertextasimage/) { get; set; } | Se o atributo RenderTextAsImage estiver definido como verdadeiro, o texto da fonte se torna uma imagem em HTML. Pode ser útil para tornar o texto não selecionável ou quando o texto HTML não é renderizado corretamente. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de salvamento de dados. |
| [SaveFullFont](../../aspose.pdf/htmlsaveoptions/savefullfont/) { get; set; } | Indica que a fonte completa será salva, suporta apenas fontes True Type. Por padrão, SaveFullFont = falso e o conversor salva o subconjunto da fonte inicial necessário para exibir o texto do documento. |
| [SimpleTextboxModeGrouping](../../aspose.pdf/htmlsaveoptions/simpletextboxmodegrouping/) { get; set; } | Este atributo especifica um agrupamento sequencial de glifos e palavras em strings. Por exemplo, tags e palavras têm ordens diferentes no HTML convertido e você deseja que elas coincidam. Este parâmetro será aplicado ao documento apenas quando o valor do atributo FixedLayout for verdadeiro. |
| [SplitCssIntoPages](../../aspose.pdf/htmlsaveoptions/splitcssintopages/) { get; set; } | Quando o modo multipágina é selecionado (ou seja, 'SplitIntoPages' é 'verdadeiro'), este atributo define se deve ser criado um arquivo CSS separado para cada página HTML resultante. Por padrão, este atributo é falso, portanto, será criado um grande CSS comum para todas as páginas criadas. O tamanho total de todos os CSS gerados neste modo (um CSS por página) geralmente é muito maior do que o tamanho de um grande arquivo CSS, porque, no primeiro caso, as classes CSS são duplicadas em vários arquivos CSS para cada página. Portanto, esta configuração deve ser usada apenas quando você estiver interessado no processamento futuro de cada página HTML de forma independente, e, portanto, o tamanho do CSS de cada página separadamente é a questão mais crítica. |
| [SplitIntoPages](../../aspose.pdf/htmlsaveoptions/splitintopages/) { get; set; } | Obtém ou define a flag que indica se cada página do documento de origem será convertida em seu próprio documento HTML de destino, ou seja, se o HTML resultante será dividido em várias páginas HTML. |
| [Title](../../aspose.pdf/htmlsaveoptions/title/) { get; set; } | Obtém ou define o título da página HTML. |
| [TryMergeFragments](../../aspose.pdf/htmlsaveoptions/trymergefragments/) { get; set; } | A flag para combinar fragmentos de imagem em uma única imagem. |
| [UseZOrder](../../aspose.pdf/htmlsaveoptions/usezorder/) { get; set; } | Se o atributo UseZOrder estiver definido como verdadeiro, gráficos e texto são adicionados ao documento HTML resultante de acordo com a ordem Z no documento PDF original. Se este atributo for falso, todos os gráficos são colocados como uma única camada, o que pode causar alguns efeitos indesejados para objetos sobrepostos. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de salvamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de salvamento deve cessar. |

## Campos

| Nome | Descrição |
| --- | --- |
| [AntialiasingProcessing](../../aspose.pdf/htmlsaveoptions/antialiasingprocessing/) | Este parâmetro define as medidas de antialiasing necessárias durante a conversão de imagens de fundo compostas de PDF para HTML. |
| [CssClassNamesPrefix](../../aspose.pdf/htmlsaveoptions/cssclassnamesprefix/) | Quando o conversor PDFtoHTML gera os CSSs resultantes, os nomes das classes CSS (algo como ".stl_01 {}" ... ".stl_NN {}") são gerados e usados no CSS resultante. Esta propriedade permite definir forçosamente o prefixo do nome da classe. Por exemplo, se você quiser que todos os nomes de classe comecem com 'my_prefix_' (ou seja, sejam algo como 'my_prefix_1' ... 'my_prefix_NNN'), basta atribuir 'my_prefix_' a esta propriedade antes da conversão. Se esta propriedade permanecer inalterada (ou seja, nula), o conversor gerará os nomes das classes por conta própria (será algo como ".stl_01 {}" ... ".stl_NN {}"). |
| [CustomCssSavingStrategy](../../aspose.pdf/htmlsaveoptions/customcsssavingstrategy/) | Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão de PDF para HTML para o manuseio do salvamento dos CSSs relacionados ao documento HTML criado como um todo ou às suas páginas (se várias páginas HTML forem geradas). Se você quiser manipular o arquivo CSS de alguma maneira específica, basta criar o método relevante e atribuir o delegado criado a esta propriedade. |
| [CustomHtmlSavingStrategy](../../aspose.pdf/htmlsaveoptions/customhtmlsavingstrategy/) | O resultado da conversão pode conter uma ou várias páginas HTML. Você pode atribuir a esta propriedade um delegado criado a partir de um método personalizado que implementa o processamento de uma página HTML (para ser preciso - HTML de marcação, sem arquivos vinculados externos, se houver) que foi criada durante a conversão. Nesse caso, o processamento (como salvar o HTML da página em um stream ou disco) pode ser feito nesse código personalizado. Nesse caso, todas as ações necessárias para salvar a página HTML devem ser realizadas no código do método fornecido, pois o salvamento do resultado no código do conversor não será utilizado. Se o processamento para este ou aquele caso, por algum motivo, deve ser feito pelo código do conversor em si, e não no código personalizado, defina no código personalizado a flag 'CustomProcessingCancelled' da variável do parâmetro 'htmlSavingInfo': isso sinalizará ao conversor que todos os passos necessários para o processamento desse recurso devem ser feitos no próprio conversor da mesma forma que se não houvesse nenhum código externo personalizado para processamento. |
| [CustomProgressHandler](../../aspose.pdf/htmlsaveoptions/customprogresshandler/) | Este manipulador pode ser usado para lidar com eventos de progresso da conversão, por exemplo, pode ser usado para mostrar uma barra de progresso ou mensagens sobre a quantidade atual de páginas processadas, um exemplo do código do manipulador que mostra o progresso no console é: |
| [CustomResourceSavingStrategy](../../aspose.pdf/htmlsaveoptions/customresourcesavingstrategy/) | Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão para o manuseio personalizado dos arquivos de recurso referenciados criados (como imagens e fontes) relacionados aos nós do HTML salvo. Essa estratégia deve processar recursos e retornar uma string que representa a URL desejável do recurso salvo no HTML gerado. |
| [CustomStrategyOfCssUrlCreation](../../aspose.pdf/htmlsaveoptions/customstrategyofcssurlcreation/) | Este campo pode conter um método personalizado que retorna a URL (ou modelo de URL, se a geração multipágina estiver ativada - veja detalhes abaixo) do CSS em questão, como deve ser colocado no HTML resultante gerado. Por exemplo, se você quiser que o conversor coloque uma URL específica em vez do nome do arquivo CSS padrão no CSS gerado, basta criar e colocar neste campo um método que gera a URL desejável. Se a flag 'SplitCssIntoPages' estiver definida, então esta estratégia personalizada (se houver) deve retornar não a URL exata do CSS, mas sim uma string de modelo que (após a substituição do espaço reservado pelo número da página com a função string.Format() dentro do conversor) pode ser resolvida na URL do CSS daquela página. Exemplos de string de retorno esperada nesse caso são: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&amp;CssPage={0}') |
| [ExcludeFontNameList](../../aspose.pdf/htmlsaveoptions/excludefontnamelist/) | Lista de nomes de fontes incorporadas no PDF que não serão incorporadas no HTML. |
| [FontEncodingStrategy](../../aspose.pdf/htmlsaveoptions/fontencodingstrategy/) | Define uma regra de codificação especial para ajustar a decodificação do PDF para o documento atual. |
| [FontSavingMode](../../aspose.pdf/htmlsaveoptions/fontsavingmode/) | Define o modo de salvamento de fontes que será usado durante o salvamento do PDF para o formato desejado. |
| [HtmlMarkupGenerationMode](../../aspose.pdf/htmlsaveoptions/htmlmarkupgenerationmode/) | Às vezes, requisitos específicos para a geração de marcação HTML estão presentes. Este parâmetro define os modos de preparação de HTML que podem ser usados durante a conversão de PDF para HTML para atender a esses requisitos específicos. |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Processar páginas em várias threads. |
| [LettersPositioningMethod](../../aspose.pdf/htmlsaveoptions/letterspositioningmethod/) | Define o modo de posicionamento das letras nas palavras no HTML resultante. |
| [PageBorderIfAny](../../aspose.pdf/htmlsaveoptions/pageborderifany/) | Este atributo representa um conjunto de configurações usadas para desenhar bordas (se houver) no documento HTML resultante ao redor da área que representa a página PDF de origem. Em essência, diz respeito à exibição das bordas do papel da página, não à borda da página referenciada na própria página PDF. |
| [PageMarginIfAny](../../aspose.pdf/htmlsaveoptions/pagemarginifany/) | Este atributo representa um conjunto de margens extras da página (se houver) no documento HTML resultante ao redor da área que representa a página PDF de origem. |
| [PagesFlowTypeDependsOnViewersScreenSize](../../aspose.pdf/htmlsaveoptions/pagesflowtypedependsonviewersscreensize/) | Se o atributo 'SplitOnPages=false', então todo o HTML representando todas as páginas PDF de entrada será colocado em um grande arquivo HTML resultante. Esta flag define se o HTML resultante será gerado de tal forma que o fluxo das áreas que representam as páginas PDF no HTML resultante dependerá da resolução da tela do visualizador. Suponha que a largura da tela do lado do visualizador seja grande o suficiente para colocar 2 ou mais páginas uma ao lado da outra na direção horizontal. Se esta flag estiver definida como verdadeira, então essa oportunidade será utilizada (quantas páginas forem mostradas na direção horizontal uma ao lado da outra, o próximo grupo horizontal de páginas será mostrado abaixo do primeiro). Caso contrário, as páginas fluirão da seguinte forma: a próxima página sempre vai abaixo da anterior. |
| [PartsEmbeddingMode](../../aspose.pdf/htmlsaveoptions/partsembeddingmode/) | Define se arquivos referenciados (HTML, fontes, imagens, CSS) serão incorporados no arquivo HTML principal ou serão gerados como entidades binárias separadas. |
| [RasterImagesSavingMode](../../aspose.pdf/htmlsaveoptions/rasterimagessavingmode/) | PDFs convertidos podem conter imagens raster. Este parâmetro define como elas devem ser tratadas durante a conversão de PDF para HTML. |
| [RemoveEmptyAreasOnTopAndBottom](../../aspose.pdf/htmlsaveoptions/removeemptyareasontopandbottom/) | Define se as áreas vazias superiores e inferiores sem conteúdo (se houver) serão removidas no HTML criado. |
| [SaveShadowedTextsAsTransparentTexts](../../aspose.pdf/htmlsaveoptions/saveshadowedtextsastransparenttexts/) | PDFs podem conter textos que são sombreado por outros elementos (por exemplo, por imagens), mas podem ser selecionados para a área de transferência no Acrobat Reader (geralmente isso acontece quando o documento contém imagens e textos OCR extraídos dele). Esta configuração informa ao conversor se precisamos salvar esses textos como textos transparentes selecionáveis no HTML resultante para imitar o comportamento do Acrobat Reader (caso contrário, esses textos geralmente são salvos como ocultos, não disponíveis para cópia para a área de transferência). |
| [SaveTransparentTexts](../../aspose.pdf/htmlsaveoptions/savetransparenttexts/) | PDFs podem conter textos transparentes que podem ser selecionados para a área de transferência (geralmente isso acontece quando o documento contém imagens e textos OCR extraídos dele). Esta configuração informa ao conversor se precisamos salvar esses textos como textos transparentes selecionáveis no HTML resultante. |
| [SpecialFolderForAllImages](../../aspose.pdf/htmlsaveoptions/specialfolderforallimages/) | Obtém ou define o caminho para o diretório onde devem ser salvas todas as imagens se forem encontradas durante o salvamento do documento como HTML. Se o parâmetro estiver vazio ou nulo, os arquivos de imagem (se houver) serão salvos junto com outros arquivos vinculados ao HTML. Não afeta nada se a propriedade CustomImageSavingStrategy foi usada com sucesso para processar o arquivo de imagem relevante. |
| [SpecialFolderForSvgImages](../../aspose.pdf/htmlsaveoptions/specialfolderforsvgimages/) | Obtém ou define o caminho para o diretório onde devem ser salvas apenas imagens SVG se forem encontradas durante o salvamento do documento como HTML. Se o parâmetro estiver vazio ou nulo, os arquivos SVG (se houver) serão salvos junto com outros arquivos de imagem (perto do arquivo de saída) ou em uma pasta especial para imagens (se especificada na opção SpecialImagesFolderIfAny). Não afeta nada se a propriedade CustomImageSavingStrategy foi usada com sucesso para processar o arquivo de imagem relevante. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo de azulejos iguais colocadas uma ao lado da outra. Nesse caso, os renderizadores dos formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram bordas visíveis entre partes das imagens de fundo, pois suas técnicas de suavização de bordas de imagem (antialiasing) são diferentes do Acrobat Reader. Se parecer que o documento exportado contém essas bordas visíveis entre partes das mesmas imagens de fundo, tente usar esta configuração para se livrar desse efeito indesejado. ATENÇÃO! Esta otimização de qualidade geralmente desacelera significativamente a conversão, portanto, use esta opção apenas quando realmente necessário. |
| [TrySaveTextUnderliningAndStrikeoutingInCss](../../aspose.pdf/htmlsaveoptions/trysavetextunderliningandstrikeoutingincss/) | O PDF em si não contém marcadores de sublinhado para textos. Isso é emulado com uma linha situada sob o texto. Esta opção permite que o conversor tente adivinhar que esta ou aquela linha é um sublinhado de texto e coloque essa informação no CSS em vez de desenhar o sublinhado graficamente. |

## Exemplos

O seguinte exemplo mostra como converter um arquivo PDF para um arquivo HTML

```csharp
[C#]
	// The path to the documents directory.
	string dataDir = "YOUR_DATA_DIRECTORY";

	// The path to your PDF File.
	var pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf");

	// The path to output HTML File.
	var htmlFile= Path.Combine(dataDir, "PDF-to-HTML.html");
		
	using (Document pdfDocument = new Document(pdfFile))
	{
		// Initialize HtmlSaveOptions 	
		HtmlSaveOptions saveOptions = new HtmlSaveOptions();
		
		// Save HTML file
		pdfDocument.Save(htmlFile, saveOptions);
	}
```

```csharp
[VB.NET]

    ' The path to the documents directory.
    Dim dataDir As String = "YOUR_DATA_DIRECTORY"

    ' The path to your PDF File.
    Dim pdfFile = Path.Combine(dataDir, "PDF-to-HTML.pdf")

    ' The path to output HTML File.
    Dim htmlFile = Path.Combine(dataDir, "PDF-to-HTML.html")
 
    Using pdfDocument As Document = New Document(pdfFile)
        ' Initialize HtmlSaveOptions    
        Dim saveOptions As HtmlSaveOptions = New HtmlSaveOptions()
 
        ' Save HTML file
        pdfDocument.Save(htmlFile, saveOptions)
    End Using
```

### Veja Também

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* interface [IPageSetOptions](../ipagesetoptions/)
* interface [IPipelineOptions](../ipipelineoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)