---
title: "HtmlSaveOptions"
linktitle: "HtmlSaveOptions"
second_title: "Referência da API Aspose.PDF para Java"
description: "Opções de salvamento para exportação para o formato HTML"
type: docs
weight: 1990
url: /pt/java/com.aspose.pdf/htmlsaveoptions/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.SaveOptions com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.SaveOptions, com.aspose.pdf.UnifiedSaveOptions com.aspose.pdf.HtmlSaveOptions, com.aspose.pdf.UnifiedSaveOptions, com.aspose.pdf.HtmlSaveOptions

**All Implemented Interfaces:**
IPageSetOptions, IPipelineOptions

```
public class HtmlSaveOptions extends UnifiedSaveOptions implements IPageSetOptions , IPipelineOptions
```

Opções de salvamento para exportação para o formato HTML

## Construtores

| Construtor | Descrição |
| --- | --- |
| [HtmlSaveOptions](#HtmlSaveOptions--) | Inicializa uma nova instância da classe HtmlSaveOptions. |
| [HtmlSaveOptions](#HtmlSaveOptions-boolean-) | Inicializa uma nova instância da classe {@code HtmlSaveOptions}. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-) | Inicializa uma nova instância da classe HtmlSaveOptions. |
| [HtmlSaveOptions](#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-) | Inicializa uma nova instância da classe HtmlSaveOptions. |

## Métodos

| Método | Descrição |
| --- | --- |
| [getAdditionalMarginWidthInPoints](#getAdditionalMarginWidthInPoints--) | Se o atributo 'SplitOnPages=false' for usado, então todo o HTML que representa todas as páginas PDF de entrada não será dividido em páginas HTML diferentes, mas será colocado em um único arquivo HTML grande de resultado. Contudo, cada página PDF de origem será representada com sua própria área retangular no HTML (se necessário, essas áreas podem ser contornadas para mostrar as bordas do papel da página com o atributo especial 'PageBorderIfAny'). Este parâmetro define a largura da margem que será forçadamente deixada ao redor dessas áreas HTML de saída que representam as páginas do documento PDF de origem. Em essência, define o intervalo garantido entre as representações HTML das páginas \"paper\" do PDF nesse modo de conversão. |
| [getAntialiasingProcessing](#getAntialiasingProcessing--) | Este parâmetro define as medidas de antisserrilhamento necessárias durante a conversão de imagens de fundo compostas de PDF para HTML. |
| [getBatchSize](#getBatchSize--) | Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino. |
| [getCssClassNamesPrefix](#getCssClassNamesPrefix--) | Quando o conversor PDFtoHTML gera os CSS resultantes, os nomes de classes CSS (algo como \".stl_01 {}\" ... \".stl_NN {}\") são gerados e usados no CSS resultante. Esta propriedade permite definir forçadamente um prefixo para o nome da classe. Por exemplo, se você quiser que todos os nomes de classe comecem com 'my_prefix_' (ou seja, algo como 'my_prefix_1' ... 'my_prefix_NNN'), basta atribuir 'my_prefix_' a esta propriedade antes da conversão. Se esta propriedade permanecer inalterada (ou seja, null será mantido como valor), o conversor gerará os nomes de classe por conta própria (será algo como \".stl_01 {}\" ... \".stl_NN {}\"). |
| [getCustomCssSavingStrategy](#getCustomCssSavingStrategy--) | Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão de PDF para HTML para o tratamento da gravação dos CSS relacionados ao documento HTML criado como um todo ou às suas páginas (se várias páginas HTML forem geradas). Se você quiser manipular o arquivo CSS de maneira específica, basta criar o método relevante e atribuir o delegate criado a partir dele a esta propriedade. |
| [getCustomHtmlSavingStrategy](#getCustomHtmlSavingStrategy--) | Resultado da conversão pode conter uma ou várias páginas HTML. Você pode atribuir a esta propriedade um delegate criado a partir de um método personalizado que implementa o processamento de uma página HTML (para ser preciso – markup-HTML, sem arquivos vinculados externos, se houver) que foi criada durante a conversão. Nesse caso, o processamento (como salvar o HTML da página em stream ou disco) pode ser feito nesse código personalizado. Nesse caso, todas as ações necessárias para salvar a página HTML devem ser realizadas no código do método fornecido, porque a gravação do resultado no código do conversor não será utilizada. Se o processamento para este ou aquele caso, por algum motivo, precisar ser feito pelo próprio código do conversor, e não no código personalizado, por favor defina no código personalizado a flag 'CustomProcessingCancelled' da variável do parâmetro 'htmlSavingInfo': isso sinalizará ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser realizadas pelo conversor, da mesma forma como se não houvesse nenhum código personalizado externo para o processamento. |
| [getCustomProgressHandler](#getCustomProgressHandler--) | <p> Este manipulador pode ser usado para tratar eventos de progresso da conversão, por exemplo, pode ser usado para exibir uma barra de progresso ou mensagens sobre a quantidade atual de páginas processadas; exemplo de código do manipulador que mostra o progresso no console: </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre> |
| [getCustomResourceSavingStrategy](#getCustomResourceSavingStrategy--) | Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão para o tratamento personalizado dos arquivos de recursos referenciados criados (como imagens e fontes) relacionados aos nós do HTML salvo. Essa estratégia deve processar os recursos e retornar uma string que represente a URL desejada do recurso salvo no HTML gerado. |
| [getCustomStrategyOfCssUrlCreation](#getCustomStrategyOfCssUrlCreation--) | Este campo pode conter um método personalizado que retorna a URL (ou modelo de URL se a geração multipágina estiver ativada – veja detalhes abaixo) do CSS de assunto, como ele deve ser inserido no HTML resultante gerado. Por exemplo, se você quiser que o conversor coloque uma URL específica em vez do nome padrão do arquivo CSS no CSS gerado, então basta criar e atribuir a esta propriedade um método que gera a URL desejada. Se a flag 'SplitCssIntoPages' estiver definida, então essa estratégia personalizada (se houver) deve retornar não a URL exata do CSS, mas sim uma string modelo que (após a substituição do placeholder pelo número da página usando a função String.Format() dentro do conversor) possa ser resolvida para a URL do CSS dessa página. Exemplos de strings de retorno esperadas nesse caso são: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' ) |
| [getDefaultFontName](#getDefaultFontName--) | Especifica o nome de uma fonte instalada que é usada para substituir qualquer fonte do documento que não esteja incorporada e não esteja instalada no sistema. Se for nulo, a fonte de substituição padrão será usada. |
| [getDocumentType](#getDocumentType--) | Obtém o {@code HtmlDocumentTypeInternal}. |
| [getExcludeFontNameList](#getExcludeFontNameList--) | Lista de nomes de fontes incorporadas em PDF que não serão incorporadas em HTML. |
| [getExplicitListOfSavedPages](#getExplicitListOfSavedPages--) | Com esta propriedade, você pode definir explicitamente quais páginas do documento devem ser convertidas. As páginas nesta lista devem ter números baseados em 1. Ou seja, os números válidos de páginas devem ser obtidos do intervalo (1...[NumberOfPagesInConvertedDocument]). A ordem de aparição das páginas nesta lista não afeta a ordem nas páginas HTML resultantes – nas páginas resultantes, elas sempre aparecerão na ordem em que estão presentes no PDF de origem. Se esta lista for nula (como é o padrão), todas as páginas serão convertidas. Se algum número de página desta lista estiver fora do intervalo das páginas presentes (1-[amountOfPagesInDocument]), será lançada uma exceção. |
| [getFlowLayoutParagraphFullWidth](#getFlowLayoutParagraphFullWidth--) | Este atributo especifica texto de parágrafo em largura total para o modo Fluxo, FixedLayout = false |
| [getFontEncodingStrategy](#getFontEncodingStrategy--) | Define regra especial de codificação para ajustar a decodificação de PDF para o documento atual |
| [getFontSavingMode](#getFontSavingMode--) | Define o modo de salvamento de fontes que será usado ao salvar o PDF no formato desejado |
| [getFontSources](#getFontSources--) | <p> Fontes de fontes pré-salvas. </p> |
| [getHtmlMarkupGenerationMode](#getHtmlMarkupGenerationMode--) | Às vezes, requisitos específicos para a geração de marcação HTML estão presentes. Este parâmetro define modos de preparação de HTML que podem ser usados durante a conversão de PDF para HTML para atender a esses requisitos específicos. |
| [getImageResolution](#getImageResolution--) | Obtém ou define a resolução para renderização de imagens. |
| [getLettersPositioningMethod](#getLettersPositioningMethod--) | Define o modo de posicionamento de letras em palavras no HTML resultante |
| [getMinimalLineWidth](#getMinimalLineWidth--) | Este atributo define a largura mínima da linha de caminho gráfico. Se a espessura da linha for menor que 1 px, o Adobe Acrobat arredonda para esse valor. Portanto, este atributo pode ser usado para emular esse comportamento em navegadores HTML. |
| [getPageBorderIfAny](#getPageBorderIfAny--) | Este atributo representa um conjunto de configurações usadas para desenhar bordas (se houver) no documento HTML resultante ao redor da área que representa a página PDF de origem. Essencialmente, trata da exibição das bordas do papel da página, não da borda da página referenciada no próprio PDF. |
| [getPageMarginIfAny](#getPageMarginIfAny--) | Este atributo representa um conjunto de margens de página extras (se houver) no documento HTML resultante ao redor da área que representa a página PDF de origem. |
| [getPartsEmbeddingMode](#getPartsEmbeddingMode--) | Define se os arquivos referenciados (HTML, fontes, imagens, CSS) serão incorporados ao arquivo HTML principal ou serão gerados como entidades binárias separadas |
| [getRasterImagesSavingMode](#getRasterImagesSavingMode--) | Um PDF convertido pode conter imagens raster. Este parâmetro define como elas devem ser tratadas durante a conversão de PDF para HTML |
| [getSpecialFolderForAllImages](#getSpecialFolderForAllImages--) | Obtém ou define o caminho para o diretório onde quaisquer imagens encontradas durante a gravação do documento como HTML devem ser salvas. Se o parâmetro estiver vazio ou nulo, os arquivos de imagem (se houver) serão salvos junto com os demais arquivos vinculados ao HTML. Não afeta nada se a propriedade CustomImageSavingStrategy foi usada com sucesso para processar o arquivo de imagem relevante. |
| [getSpecialFolderForSvgImages](#getSpecialFolderForSvgImages--) | Obtém ou define o caminho para o diretório onde apenas imagens SVG encontradas durante a gravação do documento como HTML devem ser salvas. Se o parâmetro estiver vazio ou nulo, os arquivos SVG (se houver) serão salvos junto com os demais arquivos de imagem (próximos ao arquivo de saída) ou em pasta especial para imagens (se especificada na opção SpecialImagesFolderIfAny). Não afeta nada se a propriedade CustomImageSavingStrategy foi usada com sucesso para processar o arquivo de imagem relevante. |
| [getTitle](#getTitle--) | Obtém ou define o título da página HTML. |
| [isCompressSvgGraphicsIfAny](#isCompressSvgGraphicsIfAny--) | Obtém o indicador que indica se os gráficos SVG encontrados (se houver) serão comprimidos (zipados) no formato SVGZ durante a gravação. Valor: {@code HtmlDocumentType}. |
| [isConvertMarkedContentToLayers](#isConvertMarkedContentToLayers--) | Se o atributo ConvertMarkedContentToLayers estiver definido como true, então todos os elementos dentro de um conteúdo marcado de PDF (camada) serão colocados em uma div HTML com o atributo \"data-pdflayer\" especificando o nome da camada. Esse nome de camada será extraído das propriedades opcionais do conteúdo marcado de PDF. Se este atributo for false (por padrão), nenhuma camada será criada a partir do conteúdo marcado de PDF. |
| [isFixedLayout](#isFixedLayout--) | Obtém um valor que indica se o HTML é criado como layout fixo. |
| [isIgnoreResourceFontErrors](#isIgnoreResourceFontErrors--) | Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados. true - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que referem recursos incorretos serão pulados durante o processamento. false por padrão |
| [isPagesFlowTypeDependsOnViewersScreenSize](#isPagesFlowTypeDependsOnViewersScreenSize--) | Se o atributo 'SplitOnPages=false', então todo o HTML que representa todas as páginas PDF de entrada será colocado em um único grande arquivo HTML de resultado. Esta bandeira define se o HTML de resultado será gerado de modo que o fluxo das áreas que representam as páginas PDF no HTML de resultado dependa da resolução de tela do visualizador. Suponha que a largura da tela no lado do visualizador seja grande o suficiente para colocar 2 ou mais páginas próximas umas das outras na direção horizontal. Se esta bandeira for definida como true, então essa oportunidade será usada (tantas páginas serão mostradas na direção horizontal próximas umas das outras quanto possível, então o próximo grupo horizontal de páginas será exibido abaixo da primeira). Caso contrário, as páginas fluirão da seguinte forma: a página seguinte sempre fica abaixo da anterior. |
| [isPreventGlyphsGrouping](#isPreventGlyphsGrouping--) | Este atributo ativa o modo em que os glifos de texto não serão agrupados em palavras e cadeias. Esse modo permite manter a máxima precisão ao posicionar os glifos na página e pode ser usado para converter documentos com notas musicais ou glifos que devem ser colocados separadamente uns dos outros. Este parâmetro será aplicado ao documento somente quando o valor do atributo FixedLayout for true. |
| [isRemoveEmptyAreasOnTopAndBottom](#isRemoveEmptyAreasOnTopAndBottom--) | Define se no HTML criado serão removidas as áreas vazias superior e inferior sem nenhum conteúdo (se houver). |
| [isRenderTextAsImage](#isRenderTextAsImage--) | Se o atributo RenderTextAsImage for definido como true, o texto da fonte se torna uma imagem no HTML. Pode ser útil para tornar o texto não selecionável ou quando o texto HTML não é renderizado corretamente. |
| [isSaveFullFont](#isSaveFullFont--) | Indica que a fonte completa será salva, suporta apenas fontes True Type. Por padrão, SaveFullFont = false e o conversor salva o subconjunto da fonte inicial necessário para exibir o texto do documento. |
| [isSaveShadowedTextsAsTransparentTexts](#isSaveShadowedTextsAsTransparentTexts--) | Um PDF pode conter textos que são sombreado por outros elementos (por exemplo, por imagens), mas que podem ser selecionados para a área de transferência no Acrobat Reader (geralmente isso ocorre quando o documento contém imagens e textos OCR extraídos dele). Esta configuração indica ao conversor se devemos salvar esses textos como textos transparentes selecionáveis no HTML de resultado para imitar o comportamento do Acrobat Reader (caso contrário, esses textos geralmente são salvos como ocultos, não disponíveis para cópia). |
| [isSaveTransparentTexts](#isSaveTransparentTexts--) | Um PDF pode conter textos transparentes que podem ser selecionados para a área de transferência (geralmente isso ocorre quando o documento contém imagens e textos OCR extraídos dele). Esta configuração indica ao conversor se devemos salvar esses textos como textos transparentes selecionáveis no HTML de resultado. |
| [isSimpleTextboxModeGrouping](#isSimpleTextboxModeGrouping--) | Este atributo especifica um agrupamento sequencial de glifos e palavras em cadeias. Por exemplo, tags e palavras têm ordem diferente no HTML convertido e você deseja que correspondam. Este parâmetro será aplicado ao documento somente quando o valor do atributo FixedLayout for true. |
| [isSplitCssIntoPages](#isSplitCssIntoPages--) | Quando o modo multipágina está selecionado (ou seja, 'SplitIntoPages' está 'true'), este atributo define se deve ser criado um arquivo CSS separado para cada página HTML de resultado. Por padrão, esse atributo é false, portanto será criado um único CSS comum para todas as páginas criadas. O tamanho total de todos os CSSs gerados neste modo (um CSS por página) costuma ser muito maior que o tamanho de um único CSS grande, porque no primeiro caso as classes CSS são duplicadas em vários arquivos CSS para cada página. Assim, essa configuração deve ser usada apenas quando você está interessado no processamento futuro de cada página HTML de forma independente, e portanto o tamanho do CSS de cada página individual é a questão mais crítica. |
| [isSplitIntoPages](#isSplitIntoPages--) | Obtém a bandeira que indica se cada página do documento de origem será convertida em seu próprio documento HTML de destino, ou seja, se o HTML de resultado será dividido em várias páginas HTML. |
| [isTrySaveTextUnderliningAndStrikeoutingInCss](#isTrySaveTextUnderliningAndStrikeoutingInCss--) | O próprio PDF não contém marcadores de sublinhado para textos. Ele os emula com uma linha situada sob o texto. Esta opção permite que o conversor tente adivinhar que esta ou aquela linha é o sublinhado de um texto e coloque essa informação no CSS em vez de desenhar o sublinhado graficamente. |
| [isUseZOrder](#isUseZOrder--) | Se o atributo UseZORder for definido como true, gráficos e texto são adicionados ao documento HTML resultante de acordo com a ordem Z no documento PDF original. Se esse atributo for false, todos os gráficos são colocados em uma única camada, o que pode causar alguns efeitos indesejados em objetos sobrepostos. |
| [setAdditionalMarginWidthInPoints](#setAdditionalMarginWidthInPoints-int-) | Se o atributo 'SplitOnPages=false' for usado, então todo o HTML que representa todas as páginas PDF de entrada não será dividido em páginas HTML diferentes, mas será colocado em um único arquivo HTML grande de resultado. Contudo, cada página PDF de origem será representada com sua própria área retangular no HTML (se necessário, essas áreas podem ser contornadas para mostrar as bordas do papel da página com o atributo especial 'PageBorderIfAny'). Este parâmetro define a largura da margem que será forçadamente deixada ao redor dessas áreas HTML de saída que representam as páginas do documento PDF de origem. Em essência, define o intervalo garantido entre as representações HTML das páginas \"paper\" do PDF nesse modo de conversão. |
| [setAntialiasingProcessing](#setAntialiasingProcessing-int-) | Este parâmetro define as medidas de antisserrilhamento necessárias durante a conversão de imagens de fundo compostas de PDF para HTML. |
| [setBatchSize](#setBatchSize-int-) | Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino. |
| [setCompressSvgGraphicsIfAny](#setCompressSvgGraphicsIfAny-boolean-) | Define a bandeira que indica se os gráficos SVG encontrados (se houver) serão comprimidos (zipados) no formato SVGZ durante a gravação. Valor: O {@code HtmlDocumentType}. |
| [setConvertMarkedContentToLayers](#setConvertMarkedContentToLayers-boolean-) | Se o atributo ConvertMarkedContentToLayers estiver definido como true, então todos os elementos dentro de um conteúdo marcado de PDF (camada) serão colocados em uma div HTML com o atributo \"data-pdflayer\" especificando o nome da camada. Esse nome de camada será extraído das propriedades opcionais do conteúdo marcado de PDF. Se este atributo for false (por padrão), nenhuma camada será criada a partir do conteúdo marcado de PDF. |
| [setCssClassNamesPrefix](#setCssClassNamesPrefix-java.lang.String-) | Quando o conversor PDFtoHTML gera os CSS resultantes, os nomes de classes CSS (algo como \".stl_01 {}\" ... \".stl_NN {}\") são gerados e usados no CSS resultante. Esta propriedade permite definir forçadamente um prefixo para o nome da classe. Por exemplo, se você quiser que todos os nomes de classe comecem com 'my_prefix_' (ou seja, algo como 'my_prefix_1' ... 'my_prefix_NNN'), basta atribuir 'my_prefix_' a esta propriedade antes da conversão. Se esta propriedade permanecer inalterada (ou seja, null será mantido como valor), o conversor gerará os nomes de classe por conta própria (será algo como \".stl_01 {}\" ... \".stl_NN {}\"). |
| [setCustomCssSavingStrategy](#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-) | Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão de PDF para HTML para o tratamento da gravação dos CSS relacionados ao documento HTML criado como um todo ou às suas páginas (se várias páginas HTML forem geradas). Se você quiser manipular o arquivo CSS de maneira específica, basta criar o método relevante e atribuir o delegate criado a partir dele a esta propriedade. |
| [setCustomHtmlSavingStrategy](#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-) | O resultado da conversão pode conter uma ou várias páginas HTML. Você pode atribuir a esta propriedade um delegate criado a partir de um método personalizado que implementa o processamento de uma página HTML (para ser preciso – markup-HTML, sem arquivos externos vinculados, se houver) que foi criada durante a conversão. |
| [setCustomProgressHandler](#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-) | Este manipulador pode ser usado para tratar eventos de progresso da conversão, por exemplo. |
| [setCustomResourceSavingStrategy](#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-) | Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão para tratamento personalizado dos arquivos de recursos referenciados criados (como imagens e fontes) relacionados aos nós do HTML salvo. |
| [setCustomStrategyOfCssUrlCreation](#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-) | Este campo pode conter um método personalizado que retorna a URL (ou modelo de URL se a geração multipágina estiver ativada – veja detalhes abaixo) do CSS de assunto, como deve ser inserido no HTML resultante gerado. |
| [setDefaultFontName](#setDefaultFontName-java.lang.String-) | Especifica o nome de uma fonte instalada que é usada para substituir qualquer fonte do documento que não esteja incorporada e não esteja instalada no sistema. Se for nulo, a fonte de substituição padrão será usada. |
| [setDocumentType](#setDocumentType-com.aspose.pdf.HtmlDocumentType-) | Define o {@code HtmlDocumentType}. |
| [setExcludeFontNameList](#setExcludeFontNameList-java.lang.String:A-) | Lista de nomes de fontes incorporadas em PDF que não serão incorporadas em HTML. |
| [setExplicitListOfSavedPages](#setExplicitListOfSavedPages-int:A-) | Com esta propriedade, você pode definir explicitamente quais páginas do documento devem ser convertidas. As páginas nesta lista devem ter números baseados em 1. Ou seja, os números válidos de páginas devem ser obtidos do intervalo (1...[NumberOfPagesInConvertedDocument]). A ordem de aparição das páginas nesta lista não afeta a ordem nas páginas HTML resultantes – nas páginas resultantes, elas sempre aparecerão na ordem em que estão presentes no PDF de origem. Se esta lista for nula (como é o padrão), todas as páginas serão convertidas. Se algum número de página desta lista estiver fora do intervalo das páginas presentes (1-[amountOfPagesInDocument]), será lançada uma exceção. |
| [setFixedLayout](#setFixedLayout-boolean-) | Define um valor que indica se esse HTML é criado como layout fixo. |
| [setFlowLayoutParagraphFullWidth](#setFlowLayoutParagraphFullWidth-boolean-) | Este atributo especifica texto de parágrafo em largura total para o modo Fluxo, FixedLayout = false |
| [setFontEncodingStrategy](#setFontEncodingStrategy-byte-) | Define regra especial de codificação para ajustar a decodificação de PDF para o documento atual |
| [setFontSavingMode](#setFontSavingMode-int-) | Define o modo de salvamento de fontes que será usado ao salvar o PDF no formato desejado |
| [setHtmlMarkupGenerationMode](#setHtmlMarkupGenerationMode-int-) | Às vezes, requisitos específicos para a geração de marcação HTML estão presentes. Este parâmetro define modos de preparação de HTML que podem ser usados durante a conversão de PDF para HTML para atender a esses requisitos específicos. |
| [setIgnoreResourceFontErrors](#setIgnoreResourceFontErrors-boolean-) | Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados. true - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que referem recursos incorretos serão pulados durante o processamento. false por padrão |
| [setImageResolution](#setImageResolution-int-) | Obtém ou define a resolução para renderização de imagens. |
| [setLettersPositioningMethod](#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-) | Define o modo de posicionamento de letras em palavras no HTML resultante |
| [setMinimalLineWidth](#setMinimalLineWidth-float-) | Este atributo define a largura mínima da linha de caminho gráfico. Se a espessura da linha for menor que 1 px, o Adobe Acrobat arredonda para esse valor. Portanto, este atributo pode ser usado para emular esse comportamento em navegadores HTML. |
| [setPageBorderIfAny](#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-) | Este atributo representa o conjunto de configurações usadas para desenhar borda (se houver) no documento HTML resultante ao redor da área que representa a página PDF de origem. |
| [setPageMarginIfAny](#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-) | Este atributo representa um conjunto de margens de página extras (se houver) no documento HTML resultante ao redor da área que representa a página PDF de origem. |
| [setPagesFlowTypeDependsOnViewersScreenSize](#setPagesFlowTypeDependsOnViewersScreenSize-boolean-) | Se o atributo 'SplitOnPages=false', então todo o HTML que representa todas as páginas PDF de entrada será colocado em um único grande arquivo HTML de resultado. Esta bandeira define se o HTML de resultado será gerado de modo que o fluxo das áreas que representam as páginas PDF no HTML de resultado dependa da resolução de tela do visualizador. Suponha que a largura da tela no lado do visualizador seja grande o suficiente para colocar 2 ou mais páginas próximas umas das outras na direção horizontal. Se esta bandeira for definida como true, então essa oportunidade será usada (tantas páginas serão mostradas na direção horizontal próximas umas das outras quanto possível, então o próximo grupo horizontal de páginas será exibido abaixo da primeira). Caso contrário, as páginas fluirão da seguinte forma: a página seguinte sempre fica abaixo da anterior. |
| [setPartsEmbeddingMode](#setPartsEmbeddingMode-int-) | Define se os arquivos referenciados (HTML, fontes, imagens, CSS) serão incorporados ao arquivo HTML principal ou serão gerados como entidades binárias separadas |
| [setPreventGlyphsGrouping](#setPreventGlyphsGrouping-boolean-) | Este atributo ativa o modo em que os glifos de texto não serão agrupados em palavras e cadeias. Esse modo permite manter a máxima precisão ao posicionar os glifos na página e pode ser usado para converter documentos com notas musicais ou glifos que devem ser colocados separadamente uns dos outros. Este parâmetro será aplicado ao documento somente quando o valor do atributo FixedLayout for true. |
| [setRasterImagesSavingMode](#setRasterImagesSavingMode-int-) | Um PDF convertido pode conter imagens raster. Este parâmetro define como elas devem ser tratadas durante a conversão de PDF para HTML |
| [setRemoveEmptyAreasOnTopAndBottom](#setRemoveEmptyAreasOnTopAndBottom-boolean-) | Define se no HTML criado serão removidas as áreas vazias superior e inferior sem nenhum conteúdo (se houver). |
| [setRenderTextAsImage](#setRenderTextAsImage-boolean-) | Se o atributo RenderTextAsImage for definido como true, o texto da fonte se torna uma imagem no HTML. Pode ser útil para tornar o texto não selecionável ou quando o texto HTML não é renderizado corretamente. |
| [setSaveFullFont](#setSaveFullFont-boolean-) | Indica que a fonte completa será salva, suporta apenas fontes True Type. Por padrão, SaveFullFont = false e o conversor salva o subconjunto da fonte inicial necessário para exibir o texto do documento. |
| [setSaveShadowedTextsAsTransparentTexts](#setSaveShadowedTextsAsTransparentTexts-boolean-) | Um PDF pode conter textos que são sombreado por outros elementos (por exemplo, por imagens), mas que podem ser selecionados para a área de transferência no Acrobat Reader (geralmente isso ocorre quando o documento contém imagens e textos OCR extraídos dele). Esta configuração indica ao conversor se devemos salvar esses textos como textos transparentes selecionáveis no HTML de resultado para imitar o comportamento do Acrobat Reader (caso contrário, esses textos geralmente são salvos como ocultos, não disponíveis para cópia). |
| [setSaveTransparentTexts](#setSaveTransparentTexts-boolean-) | Um PDF pode conter textos transparentes que podem ser selecionados para a área de transferência (geralmente isso ocorre quando o documento contém imagens e textos OCR extraídos dele). Esta configuração indica ao conversor se devemos salvar esses textos como textos transparentes selecionáveis no HTML de resultado. |
| [setSimpleTextboxModeGrouping](#setSimpleTextboxModeGrouping-boolean-) | Este atributo especifica um agrupamento sequencial de glifos e palavras em cadeias. Por exemplo, tags e palavras têm ordem diferente no HTML convertido e você deseja que correspondam. Este parâmetro será aplicado ao documento somente quando o valor do atributo FixedLayout for true. |
| [setSpecialFolderForAllImages](#setSpecialFolderForAllImages-java.lang.String-) | Obtém ou define o caminho para o diretório onde quaisquer imagens encontradas durante a gravação do documento como HTML devem ser salvas. Se o parâmetro estiver vazio ou nulo, os arquivos de imagem (se houver) serão salvos junto com os demais arquivos vinculados ao HTML. Não afeta nada se a propriedade CustomImageSavingStrategy foi usada com sucesso para processar o arquivo de imagem relevante. |
| [setSpecialFolderForSvgImages](#setSpecialFolderForSvgImages-java.lang.String-) | Obtém ou define o caminho para o diretório onde apenas imagens SVG encontradas durante a gravação do documento como HTML devem ser salvas. Se o parâmetro estiver vazio ou nulo, os arquivos SVG (se houver) serão salvos junto com os demais arquivos de imagem (próximos ao arquivo de saída) ou em pasta especial para imagens (se especificada na opção SpecialImagesFolderIfAny). Não afeta nada se a propriedade CustomImageSavingStrategy foi usada com sucesso para processar o arquivo de imagem relevante. |
| [setSplitCssIntoPages](#setSplitCssIntoPages-boolean-) | Quando o modo multipágina está selecionado (ou seja, 'SplitIntoPages' está 'true'), este atributo define se deve ser criado um arquivo CSS separado para cada página HTML de resultado. Por padrão, esse atributo é false, portanto será criado um único CSS comum para todas as páginas criadas. O tamanho total de todos os CSSs gerados neste modo (um CSS por página) costuma ser muito maior que o tamanho de um único CSS grande, porque no primeiro caso as classes CSS são duplicadas em vários arquivos CSS para cada página. Assim, essa configuração deve ser usada apenas quando você está interessado no processamento futuro de cada página HTML de forma independente, e portanto o tamanho do CSS de cada página individual é a questão mais crítica. |
| [setSplitIntoPages](#setSplitIntoPages-boolean-) | Define a bandeira que indica se cada página do documento de origem será convertida em seu próprio documento HTML de destino, ou seja, se o HTML resultante será dividido em várias páginas HTML. |
| [setTitle](#setTitle-java.lang.String-) | Obtém ou define o título da página HTML. |
| [setTrySaveTextUnderliningAndStrikeoutingInCss](#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-) | O próprio PDF não contém marcadores de sublinhado para textos. Ele os emula com uma linha situada sob o texto. Esta opção permite que o conversor tente adivinhar que esta ou aquela linha é o sublinhado de um texto e coloque essa informação no CSS em vez de desenhar o sublinhado graficamente. |
| [setUseZOrder](#setUseZOrder-boolean-) | Se o atributo UseZORder for definido como true, gráficos e texto são adicionados ao documento HTML resultante de acordo com a ordem Z no documento PDF original. Se esse atributo for false, todos os gráficos são colocados em uma única camada, o que pode causar alguns efeitos indesejados em objetos sobrepostos. |

### HtmlSaveOptions {#HtmlSaveOptions--}
```
public HtmlSaveOptions()
```

Inicializa uma nova instância da classe HtmlSaveOptions.

### HtmlSaveOptions {#HtmlSaveOptions-boolean-}
```
public HtmlSaveOptions(boolean fixedLayout)
```

Inicializa uma nova instância da classe {@code HtmlSaveOptions}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| fixedLayout |  | valor booleano |

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-}
Inicializa uma nova instância da classe HtmlSaveOptions.

### HtmlSaveOptions {#HtmlSaveOptions-com.aspose.pdf.HtmlDocumentType-boolean-}
Inicializa uma nova instância da classe HtmlSaveOptions.

### getAdditionalMarginWidthInPoints {#getAdditionalMarginWidthInPoints--}
```
@Deprecated public int getAdditionalMarginWidthInPoints()
```

Se o atributo 'SplitOnPages=false' for usado, então todo o HTML que representa todas as páginas PDF de entrada não será dividido em páginas HTML diferentes, mas será colocado em um único arquivo HTML grande de resultado. Contudo, cada página PDF de origem será representada com sua própria área retangular no HTML (se necessário, essas áreas podem ser contornadas para mostrar as bordas do papel da página com o atributo especial 'PageBorderIfAny'). Este parâmetro define a largura da margem que será forçadamente deixada ao redor dessas áreas HTML de saída que representam as páginas do documento PDF de origem. Em essência, define o intervalo garantido entre as representações HTML das páginas \"paper\" do PDF nesse modo de conversão.

**Returns:**
valor int @deprecated AdditionalMarginWidthInPoints está obsoleto, por favor use PageMarginIfAny em vez disso.

### getAntialiasingProcessing {#getAntialiasingProcessing--}
```
public int getAntialiasingProcessing()
```

Este parâmetro define as medidas de antisserrilhamento necessárias durante a conversão de imagens de fundo compostas de PDF para HTML.

**Returns:**
elemento AntialiasingProcessingType @see AntialiasingProcessingType

### getBatchSize {#getBatchSize--}
```
public final int getBatchSize()
```

Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino.

**Returns:**
valor int

### getCssClassNamesPrefix {#getCssClassNamesPrefix--}
```
public String getCssClassNamesPrefix()
```

Quando o conversor PDFtoHTML gera os CSS resultantes, os nomes de classes CSS (algo como \".stl_01 {}\" ... \".stl_NN {}\") são gerados e usados no CSS resultante. Esta propriedade permite definir forçadamente um prefixo para o nome da classe. Por exemplo, se você quiser que todos os nomes de classe comecem com 'my_prefix_' (ou seja, algo como 'my_prefix_1' ... 'my_prefix_NNN'), basta atribuir 'my_prefix_' a esta propriedade antes da conversão. Se esta propriedade permanecer inalterada (ou seja, null será mantido como valor), o conversor gerará os nomes de classe por conta própria (será algo como \".stl_01 {}\" ... \".stl_NN {}\").

**Returns:**
valor String

### getCustomCssSavingStrategy {#getCustomCssSavingStrategy--}
```
public HtmlSaveOptions.CssSavingStrategy getCustomCssSavingStrategy()
```

Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão de PDF para HTML para o tratamento da gravação dos CSS relacionados ao documento HTML criado como um todo ou às suas páginas (se várias páginas HTML forem geradas). Se você quiser manipular o arquivo CSS de maneira específica, basta criar o método relevante e atribuir o delegate criado a partir dele a esta propriedade.

**Returns:**
instância CssSavingStrategy

### getCustomHtmlSavingStrategy {#getCustomHtmlSavingStrategy--}
```
public HtmlSaveOptions.HtmlPageMarkupSavingStrategy getCustomHtmlSavingStrategy()
```

Resultado da conversão pode conter uma ou várias páginas HTML. Você pode atribuir a esta propriedade um delegate criado a partir de um método personalizado que implementa o processamento de uma página HTML (para ser preciso – markup-HTML, sem arquivos vinculados externos, se houver) que foi criada durante a conversão. Nesse caso, o processamento (como salvar o HTML da página em stream ou disco) pode ser feito nesse código personalizado. Nesse caso, todas as ações necessárias para salvar a página HTML devem ser realizadas no código do método fornecido, porque a gravação do resultado no código do conversor não será utilizada. Se o processamento para este ou aquele caso, por algum motivo, precisar ser feito pelo próprio código do conversor, e não no código personalizado, por favor defina no código personalizado a flag 'CustomProcessingCancelled' da variável do parâmetro 'htmlSavingInfo': isso sinalizará ao conversor que todas as etapas necessárias para o processamento desse recurso devem ser realizadas pelo conversor, da mesma forma como se não houvesse nenhum código personalizado externo para o processamento.

**Returns:**
instância HtmlPageMarkupSavingStrategy

### getCustomProgressHandler {#getCustomProgressHandler--}
```
public UnifiedSaveOptions.ConversionProgressEventHandler getCustomProgressHandler()
```

<p> Este manipulador pode ser usado para tratar eventos de progresso da conversão, por exemplo, pode ser usado para exibir uma barra de progresso ou mensagens sobre a quantidade atual de páginas processadas; exemplo de código do manipulador que mostra o progresso no console: </p> <hr> <pre> public static void ConvertWithShowingProgress() { (new com.aspose.pdf.License()).setLicense("Aspose.Total.lic"); Document doc = new Document("Booklet.pdf"); HtmlSaveOptions saveOptions = new HtmlSaveOptions(); saveOptions.CustomProgressHandler = new com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler() { public void invoke( UnifiedSaveOptions.ProgressEventHandlerInfo eventInfo) { showProgressOnConsole(eventInfo); } }; doc.save("Booklet.doc", saveOptions); } public static void showProgressOnConsole(HtmlSaveOptions.ProgressEventHandlerInfo eventInfo) { switch (eventInfo.EventType) { case HtmlSaveOptions.ProgressEventType.TotalProgress: System.out.println(String.format("%s - Conversion progress : %d % .", (new Date()).toString(), eventInfo.Value)); break; case HtmlSaveOptions.ProgressEventType.SourcePageAnalized: System.out.println(String.format("%s - Source page %d of %d analyzed.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageCreated: System.out.println(String.format("%s - Result page's %d of %d layout created.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; case HtmlSaveOptions.ProgressEventType.ResultPageSaved: System.out.println(String.format("%s - Result page %d of %d exported.", (new Date()).toString(), eventInfo.Value, eventInfo.MaxValue)); break; default: break; } } </pre>

**Returns:**
instância ConversionProgressEventHandler

### getCustomResourceSavingStrategy {#getCustomResourceSavingStrategy--}
```
public HtmlSaveOptions.ResourceSavingStrategy getCustomResourceSavingStrategy()
```

Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão para o tratamento personalizado dos arquivos de recursos referenciados criados (como imagens e fontes) relacionados aos nós do HTML salvo. Essa estratégia deve processar os recursos e retornar uma string que represente a URL desejada do recurso salvo no HTML gerado.

**Returns:**
instância ResourceSavingStrategy

### getCustomStrategyOfCssUrlCreation {#getCustomStrategyOfCssUrlCreation--}
```
public HtmlSaveOptions.CssUrlMakingStrategy getCustomStrategyOfCssUrlCreation()
```

Este campo pode conter um método personalizado que retorna a URL (ou modelo de URL se a geração multipágina estiver ativada – veja detalhes abaixo) do CSS de assunto, como ele deve ser inserido no HTML resultante gerado. Por exemplo, se você quiser que o conversor coloque uma URL específica em vez do nome padrão do arquivo CSS no CSS gerado, então basta criar e atribuir a esta propriedade um método que gera a URL desejada. Se a flag 'SplitCssIntoPages' estiver definida, então essa estratégia personalizada (se houver) deve retornar não a URL exata do CSS, mas sim uma string modelo que (após a substituição do placeholder pelo número da página usando a função String.Format() dentro do conversor) possa ser resolvida para a URL do CSS dessa página. Exemplos de strings de retorno esperadas nesse caso são: 'SomeTargetLocation-page_{0}.css','../PartHandlers/GetCss.aspx?DocumentId=45654&CssPage={0 }' )

**Returns:**
instância CssUrlMakingStrategy

### getDefaultFontName {#getDefaultFontName--}
```
public String getDefaultFontName()
```

Especifica o nome de uma fonte instalada que é usada para substituir qualquer fonte do documento que não esteja incorporada e não esteja instalada no sistema. Se for nulo, a fonte de substituição padrão será usada.

**Returns:**
valor String: nome da fonte

### getDocumentType {#getDocumentType--}
```
public HtmlDocumentType getDocumentType()
```

Obtém o {@code HtmlDocumentTypeInternal}.

**Returns:**
O {@code HtmlDocumentTypeInternal}.

### getExcludeFontNameList {#getExcludeFontNameList--}
```
public String [] getExcludeFontNameList()
```

Lista de nomes de fontes incorporadas em PDF que não serão incorporadas em HTML.

**Returns:**
array de elementos String

### getExplicitListOfSavedPages {#getExplicitListOfSavedPages--}
```
public final int[] getExplicitListOfSavedPages()
```

Com esta propriedade, você pode definir explicitamente quais páginas do documento devem ser convertidas. As páginas nesta lista devem ter números baseados em 1. Ou seja, os números válidos de páginas devem ser obtidos do intervalo (1...[NumberOfPagesInConvertedDocument]). A ordem de aparição das páginas nesta lista não afeta a ordem nas páginas HTML resultantes – nas páginas resultantes, elas sempre aparecerão na ordem em que estão presentes no PDF de origem. Se esta lista for nula (como é o padrão), todas as páginas serão convertidas. Se algum número de página desta lista estiver fora do intervalo das páginas presentes (1-[amountOfPagesInDocument]), será lançada uma exceção.

**Returns:**
array de int

### getFlowLayoutParagraphFullWidth {#getFlowLayoutParagraphFullWidth--}
```
public final boolean getFlowLayoutParagraphFullWidth()
```

Este atributo especifica texto de parágrafo em largura total para o modo Fluxo, FixedLayout = false

**Returns:**
valor booleano

### getFontEncodingStrategy {#getFontEncodingStrategy--}
```
public byte getFontEncodingStrategy()
```

Define regra especial de codificação para ajustar a decodificação de PDF para o documento atual

**Returns:**
elemento FontEncodingRules @see FontEncodingRules

### getFontSavingMode {#getFontSavingMode--}
```
public int getFontSavingMode()
```

Define o modo de salvamento de fontes que será usado ao salvar o PDF no formato desejado

**Returns:**
elemento FontSavingModes @see FontSavingModes

### getFontSources {#getFontSources--}
```
public FontSourceCollection getFontSources()
```

<p> Fontes de fontes pré-salvas. </p>

**Returns:**
FontSourceCollection object <hr> <p> As fontes podem ser salvas preliminarmente para fins de cache e então passadas para o processo de conversão Html. Por exemplo, isso pode ser útil em cenários de divisão de documentos e processamento de páginas de documentos em múltiplas threads com um único conjunto de fontes. </p>

### getHtmlMarkupGenerationMode {#getHtmlMarkupGenerationMode--}
```
public int getHtmlMarkupGenerationMode()
```

Às vezes, requisitos específicos para a geração de marcação HTML estão presentes. Este parâmetro define modos de preparação de HTML que podem ser usados durante a conversão de PDF para HTML para atender a esses requisitos específicos.

**Returns:**
elemento HtmlMarkupGenerationModes @see HtmlMarkupGenerationModes

### getImageResolution {#getImageResolution--}
```
public int getImageResolution()
```

Obtém ou define a resolução para renderização de imagens.

**Returns:**
Valor: Resolução

### getLettersPositioningMethod {#getLettersPositioningMethod--}
```
public LettersPositioningMethods getLettersPositioningMethod()
```

Define o modo de posicionamento de letras em palavras no HTML resultante

**Returns:**
Elemento LettersPositioningMethods @see LettersPositioningMethods

### getMinimalLineWidth {#getMinimalLineWidth--}
```
public float getMinimalLineWidth()
```

Este atributo define a largura mínima da linha de caminho gráfico. Se a espessura da linha for menor que 1 px, o Adobe Acrobat arredonda para esse valor. Portanto, este atributo pode ser usado para emular esse comportamento em navegadores HTML.

**Returns:**
valor float

### getPageBorderIfAny {#getPageBorderIfAny--}
```
public SaveOptions.BorderInfo getPageBorderIfAny()
```

Este atributo representa um conjunto de configurações usadas para desenhar bordas (se houver) no documento HTML resultante ao redor da área que representa a página PDF de origem. Essencialmente, trata da exibição das bordas do papel da página, não da borda da página referenciada no próprio PDF.

**Returns:**
Instância BorderInfo

### getPageMarginIfAny {#getPageMarginIfAny--}
```
public SaveOptions.MarginInfo getPageMarginIfAny()
```

Este atributo representa um conjunto de margens de página extras (se houver) no documento HTML resultante ao redor da área que representa a página PDF de origem.

**Returns:**
Instância MarginInfo

### getPartsEmbeddingMode {#getPartsEmbeddingMode--}
```
public int getPartsEmbeddingMode()
```

Define se os arquivos referenciados (HTML, fontes, imagens, CSS) serão incorporados ao arquivo HTML principal ou serão gerados como entidades binárias separadas

**Returns:**
Elemento PartsEmbeddingModes @see PartsEmbeddingModes

### getRasterImagesSavingMode {#getRasterImagesSavingMode--}
```
public int getRasterImagesSavingMode()
```

Um PDF convertido pode conter imagens raster. Este parâmetro define como elas devem ser tratadas durante a conversão de PDF para HTML

**Returns:**
Elemento RasterImagesSavingModes @see RasterImagesSavingModes

### getSpecialFolderForAllImages {#getSpecialFolderForAllImages--}
```
public String getSpecialFolderForAllImages()
```

Obtém ou define o caminho para o diretório onde quaisquer imagens encontradas durante a gravação do documento como HTML devem ser salvas. Se o parâmetro estiver vazio ou nulo, os arquivos de imagem (se houver) serão salvos junto com os demais arquivos vinculados ao HTML. Não afeta nada se a propriedade CustomImageSavingStrategy foi usada com sucesso para processar o arquivo de imagem relevante.

**Returns:**
valor String

### getSpecialFolderForSvgImages {#getSpecialFolderForSvgImages--}
```
public String getSpecialFolderForSvgImages()
```

Obtém ou define o caminho para o diretório onde apenas imagens SVG encontradas durante a gravação do documento como HTML devem ser salvas. Se o parâmetro estiver vazio ou nulo, os arquivos SVG (se houver) serão salvos junto com os demais arquivos de imagem (próximos ao arquivo de saída) ou em pasta especial para imagens (se especificada na opção SpecialImagesFolderIfAny). Não afeta nada se a propriedade CustomImageSavingStrategy foi usada com sucesso para processar o arquivo de imagem relevante.

**Returns:**
valor String

### getTitle {#getTitle--}
```
public final String getTitle()
```

Obtém ou define o título da página HTML.

**Returns:**
valor String

### isCompressSvgGraphicsIfAny {#isCompressSvgGraphicsIfAny--}
```
public boolean isCompressSvgGraphicsIfAny()
```

Obtém o indicador que indica se os gráficos SVG encontrados (se houver) serão comprimidos (zipados) no formato SVGZ durante a gravação. Valor: {@code HtmlDocumentType}.

**Returns:**
valor booleano

### isConvertMarkedContentToLayers {#isConvertMarkedContentToLayers--}
```
public boolean isConvertMarkedContentToLayers()
```

Se o atributo ConvertMarkedContentToLayers estiver definido como true, então todos os elementos dentro de um conteúdo marcado de PDF (camada) serão colocados em uma div HTML com o atributo \"data-pdflayer\" especificando o nome da camada. Esse nome de camada será extraído das propriedades opcionais do conteúdo marcado de PDF. Se este atributo for false (por padrão), nenhuma camada será criada a partir do conteúdo marcado de PDF.

**Returns:**
valor booleano

### isFixedLayout {#isFixedLayout--}
```
public boolean isFixedLayout()
```

Obtém um valor que indica se o HTML é criado como layout fixo.

**Returns:**
valor: {@code true} se [fixed layout]; caso contrário, {@code false}.

### isIgnoreResourceFontErrors {#isIgnoreResourceFontErrors--}
```
public final boolean isIgnoreResourceFontErrors()
```

Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados. true - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que referem recursos incorretos serão pulados durante o processamento. false por padrão

**Returns:**
valor booleano

### isPagesFlowTypeDependsOnViewersScreenSize {#isPagesFlowTypeDependsOnViewersScreenSize--}
```
public boolean isPagesFlowTypeDependsOnViewersScreenSize()
```

Se o atributo 'SplitOnPages=false', então todo o HTML que representa todas as páginas PDF de entrada será colocado em um único grande arquivo HTML de resultado. Esta bandeira define se o HTML de resultado será gerado de modo que o fluxo das áreas que representam as páginas PDF no HTML de resultado dependa da resolução de tela do visualizador. Suponha que a largura da tela no lado do visualizador seja grande o suficiente para colocar 2 ou mais páginas próximas umas das outras na direção horizontal. Se esta bandeira for definida como true, então essa oportunidade será usada (tantas páginas serão mostradas na direção horizontal próximas umas das outras quanto possível, então o próximo grupo horizontal de páginas será exibido abaixo da primeira). Caso contrário, as páginas fluirão da seguinte forma: a página seguinte sempre fica abaixo da anterior.

**Returns:**
valor booleano

### isPreventGlyphsGrouping {#isPreventGlyphsGrouping--}
```
public boolean isPreventGlyphsGrouping()
```

Este atributo ativa o modo em que os glifos de texto não serão agrupados em palavras e cadeias. Esse modo permite manter a máxima precisão ao posicionar os glifos na página e pode ser usado para converter documentos com notas musicais ou glifos que devem ser colocados separadamente uns dos outros. Este parâmetro será aplicado ao documento somente quando o valor do atributo FixedLayout for true.

**Returns:**
valor booleano

### isRemoveEmptyAreasOnTopAndBottom {#isRemoveEmptyAreasOnTopAndBottom--}
```
public boolean isRemoveEmptyAreasOnTopAndBottom()
```

Define se no HTML criado serão removidas as áreas vazias superior e inferior sem nenhum conteúdo (se houver).

**Returns:**
valor booleano

### isRenderTextAsImage {#isRenderTextAsImage--}
```
public boolean isRenderTextAsImage()
```

Se o atributo RenderTextAsImage for definido como true, o texto da fonte se torna uma imagem no HTML. Pode ser útil para tornar o texto não selecionável ou quando o texto HTML não é renderizado corretamente.

**Returns:**
valor booleano

### isSaveFullFont {#isSaveFullFont--}
```
public boolean isSaveFullFont()
```

Indica que a fonte completa será salva, suporta apenas fontes True Type. Por padrão, SaveFullFont = false e o conversor salva o subconjunto da fonte inicial necessário para exibir o texto do documento.

**Returns:**
valor booleano

### isSaveShadowedTextsAsTransparentTexts {#isSaveShadowedTextsAsTransparentTexts--}
```
public boolean isSaveShadowedTextsAsTransparentTexts()
```

Um PDF pode conter textos que são sombreado por outros elementos (por exemplo, por imagens), mas que podem ser selecionados para a área de transferência no Acrobat Reader (geralmente isso ocorre quando o documento contém imagens e textos OCR extraídos dele). Esta configuração indica ao conversor se devemos salvar esses textos como textos transparentes selecionáveis no HTML de resultado para imitar o comportamento do Acrobat Reader (caso contrário, esses textos geralmente são salvos como ocultos, não disponíveis para cópia).

**Returns:**
valor booleano

### isSaveTransparentTexts {#isSaveTransparentTexts--}
```
public boolean isSaveTransparentTexts()
```

Um PDF pode conter textos transparentes que podem ser selecionados para a área de transferência (geralmente isso ocorre quando o documento contém imagens e textos OCR extraídos dele). Esta configuração indica ao conversor se devemos salvar esses textos como textos transparentes selecionáveis no HTML de resultado.

**Returns:**
valor booleano

### isSimpleTextboxModeGrouping {#isSimpleTextboxModeGrouping--}
```
public final boolean isSimpleTextboxModeGrouping()
```

Este atributo especifica um agrupamento sequencial de glifos e palavras em cadeias. Por exemplo, tags e palavras têm ordem diferente no HTML convertido e você deseja que correspondam. Este parâmetro será aplicado ao documento somente quando o valor do atributo FixedLayout for true.

**Returns:**
valor booleano

### isSplitCssIntoPages {#isSplitCssIntoPages--}
```
public boolean isSplitCssIntoPages()
```

Quando o modo multipágina está selecionado (ou seja, 'SplitIntoPages' está 'true'), este atributo define se deve ser criado um arquivo CSS separado para cada página HTML de resultado. Por padrão, esse atributo é false, portanto será criado um único CSS comum para todas as páginas criadas. O tamanho total de todos os CSSs gerados neste modo (um CSS por página) costuma ser muito maior que o tamanho de um único CSS grande, porque no primeiro caso as classes CSS são duplicadas em vários arquivos CSS para cada página. Assim, essa configuração deve ser usada apenas quando você está interessado no processamento futuro de cada página HTML de forma independente, e portanto o tamanho do CSS de cada página individual é a questão mais crítica.

**Returns:**
valor booleano

### isSplitIntoPages {#isSplitIntoPages--}
```
public boolean isSplitIntoPages()
```

Obtém a bandeira que indica se cada página do documento de origem será convertida em seu próprio documento HTML de destino, ou seja, se o HTML de resultado será dividido em várias páginas HTML.

**Returns:**
valor booleano

### isTrySaveTextUnderliningAndStrikeoutingInCss {#isTrySaveTextUnderliningAndStrikeoutingInCss--}
```
public boolean isTrySaveTextUnderliningAndStrikeoutingInCss()
```

O próprio PDF não contém marcadores de sublinhado para textos. Ele os emula com uma linha situada sob o texto. Esta opção permite que o conversor tente adivinhar que esta ou aquela linha é o sublinhado de um texto e coloque essa informação no CSS em vez de desenhar o sublinhado graficamente.

**Returns:**
valor booleano

### isUseZOrder {#isUseZOrder--}
```
public boolean isUseZOrder()
```

Se o atributo UseZORder for definido como true, gráficos e texto são adicionados ao documento HTML resultante de acordo com a ordem Z no documento PDF original. Se esse atributo for false, todos os gráficos são colocados em uma única camada, o que pode causar alguns efeitos indesejados em objetos sobrepostos.

**Returns:**
valor booleano

### setAdditionalMarginWidthInPoints {#setAdditionalMarginWidthInPoints-int-}
```
@Deprecated public void setAdditionalMarginWidthInPoints(int value)
```

Se o atributo 'SplitOnPages=false' for usado, então todo o HTML que representa todas as páginas PDF de entrada não será dividido em páginas HTML diferentes, mas será colocado em um único arquivo HTML grande de resultado. Contudo, cada página PDF de origem será representada com sua própria área retangular no HTML (se necessário, essas áreas podem ser contornadas para mostrar as bordas do papel da página com o atributo especial 'PageBorderIfAny'). Este parâmetro define a largura da margem que será forçadamente deixada ao redor dessas áreas HTML de saída que representam as páginas do documento PDF de origem. Em essência, define o intervalo garantido entre as representações HTML das páginas \"paper\" do PDF nesse modo de conversão.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor int @deprecated AdditionalMarginWidthInPoints está obsoleto, por favor use PageMarginIfAny em vez disso. |

### setAntialiasingProcessing {#setAntialiasingProcessing-int-}
```
public void setAntialiasingProcessing(int antialiasingProcessing)
```

Este parâmetro define as medidas de antisserrilhamento necessárias durante a conversão de imagens de fundo compostas de PDF para HTML.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| processamentoAntialiasing |  | elemento AntialiasingProcessingType @see AntialiasingProcessingType |

### setBatchSize {#setBatchSize-int-}
```
public final void setBatchSize(int value)
```

Define o tamanho do lote se a conversão em lote for aplicável ao par de formatos de origem e destino.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  |  |

### setCompressSvgGraphicsIfAny {#setCompressSvgGraphicsIfAny-boolean-}
```
public void setCompressSvgGraphicsIfAny(boolean value)
```

Define a bandeira que indica se os gráficos SVG encontrados (se houver) serão comprimidos (zipados) no formato SVGZ durante a gravação. Valor: O {@code HtmlDocumentType}.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setConvertMarkedContentToLayers {#setConvertMarkedContentToLayers-boolean-}
```
public void setConvertMarkedContentToLayers(boolean value)
```

Se o atributo ConvertMarkedContentToLayers estiver definido como true, então todos os elementos dentro de um conteúdo marcado de PDF (camada) serão colocados em uma div HTML com o atributo \"data-pdflayer\" especificando o nome da camada. Esse nome de camada será extraído das propriedades opcionais do conteúdo marcado de PDF. Se este atributo for false (por padrão), nenhuma camada será criada a partir do conteúdo marcado de PDF.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setCssClassNamesPrefix {#setCssClassNamesPrefix-java.lang.String-}
Quando o conversor PDFtoHTML gera os CSS resultantes, os nomes de classes CSS (algo como \".stl_01 {}\" ... \".stl_NN {}\") são gerados e usados no CSS resultante. Esta propriedade permite definir forçadamente um prefixo para o nome da classe. Por exemplo, se você quiser que todos os nomes de classe comecem com 'my_prefix_' (ou seja, algo como 'my_prefix_1' ... 'my_prefix_NNN'), basta atribuir 'my_prefix_' a esta propriedade antes da conversão. Se esta propriedade permanecer inalterada (ou seja, null será mantido como valor), o conversor gerará os nomes de classe por conta própria (será algo como \".stl_01 {}\" ... \".stl_NN {}\").

### setCustomCssSavingStrategy {#setCustomCssSavingStrategy-com.aspose.pdf.HtmlSaveOptions.CssSavingStrategy-}
Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão de PDF para HTML para o tratamento da gravação dos CSS relacionados ao documento HTML criado como um todo ou às suas páginas (se várias páginas HTML forem geradas). Se você quiser manipular o arquivo CSS de maneira específica, basta criar o método relevante e atribuir o delegate criado a partir dele a esta propriedade.

### setCustomHtmlSavingStrategy {#setCustomHtmlSavingStrategy-com.aspose.pdf.HtmlSaveOptions.HtmlPageMarkupSavingStrategy-}
O resultado da conversão pode conter uma ou várias páginas HTML. Você pode atribuir a esta propriedade um delegate criado a partir de um método personalizado que implementa o processamento de uma página HTML (para ser preciso – markup-HTML, sem arquivos externos vinculados, se houver) que foi criada durante a conversão.

### setCustomProgressHandler {#setCustomProgressHandler-com.aspose.pdf.UnifiedSaveOptions.ConversionProgressEventHandler-}
Este manipulador pode ser usado para tratar eventos de progresso da conversão, por exemplo.

### setCustomResourceSavingStrategy {#setCustomResourceSavingStrategy-com.aspose.pdf.HtmlSaveOptions.ResourceSavingStrategy-}
Este campo pode conter a estratégia de salvamento que deve ser usada (se presente) durante a conversão para tratamento personalizado dos arquivos de recursos referenciados criados (como imagens e fontes) relacionados aos nós do HTML salvo.

### setCustomStrategyOfCssUrlCreation {#setCustomStrategyOfCssUrlCreation-com.aspose.pdf.HtmlSaveOptions.CssUrlMakingStrategy-}
Este campo pode conter um método personalizado que retorna a URL (ou modelo de URL se a geração multipágina estiver ativada – veja detalhes abaixo) do CSS de assunto, como deve ser inserido no HTML resultante gerado.

### setDefaultFontName {#setDefaultFontName-java.lang.String-}
Especifica o nome de uma fonte instalada que é usada para substituir qualquer fonte do documento que não esteja incorporada e não esteja instalada no sistema. Se for nulo, a fonte de substituição padrão será usada.

### setDocumentType {#setDocumentType-com.aspose.pdf.HtmlDocumentType-}
Define o {@code HtmlDocumentType}.

### setExcludeFontNameList {#setExcludeFontNameList-java.lang.String:A-}
Lista de nomes de fontes incorporadas em PDF que não serão incorporadas em HTML.

### setExplicitListOfSavedPages {#setExplicitListOfSavedPages-int:A-}
```
public final void setExplicitListOfSavedPages(int[] value)
```

Com esta propriedade, você pode definir explicitamente quais páginas do documento devem ser convertidas. As páginas nesta lista devem ter números baseados em 1. Ou seja, os números válidos de páginas devem ser obtidos do intervalo (1...[NumberOfPagesInConvertedDocument]). A ordem de aparição das páginas nesta lista não afeta a ordem nas páginas HTML resultantes – nas páginas resultantes, elas sempre aparecerão na ordem em que estão presentes no PDF de origem. Se esta lista for nula (como é o padrão), todas as páginas serão convertidas. Se algum número de página desta lista estiver fora do intervalo das páginas presentes (1-[amountOfPagesInDocument]), será lançada uma exceção.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  |  |

### setFixedLayout {#setFixedLayout-boolean-}
```
public void setFixedLayout(boolean value)
```

Define um valor que indica se esse HTML é criado como layout fixo.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | : {@code true} se [fixed layout]; caso contrário, {@code false}. |

### setFlowLayoutParagraphFullWidth {#setFlowLayoutParagraphFullWidth-boolean-}
```
public final void setFlowLayoutParagraphFullWidth(boolean value)
```

Este atributo especifica texto de parágrafo em largura total para o modo Fluxo, FixedLayout = false

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setFontEncodingStrategy {#setFontEncodingStrategy-byte-}
```
public void setFontEncodingStrategy(byte fontEncodingStrategy)
```

Define regra especial de codificação para ajustar a decodificação de PDF para o documento atual

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| estrategiaCodificacaoFonte |  | elemento FontEncodingRules @see FontEncodingRules |

### setFontSavingMode {#setFontSavingMode-int-}
```
public void setFontSavingMode(int fontSavingMode)
```

Define o modo de salvamento de fontes que será usado ao salvar o PDF no formato desejado

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| modoSalvamentoFonte |  | elemento FontSavingModes @see FontSavingModes |

### setHtmlMarkupGenerationMode {#setHtmlMarkupGenerationMode-int-}
```
public void setHtmlMarkupGenerationMode(int htmlMarkupGenerationMode)
```

Às vezes, requisitos específicos para a geração de marcação HTML estão presentes. Este parâmetro define modos de preparação de HTML que podem ser usados durante a conversão de PDF para HTML para atender a esses requisitos específicos.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| modoGeracaoMarkupHtml |  | elemento HtmlMarkupGenerationModes @see HtmlMarkupGenerationModes |

### setIgnoreResourceFontErrors {#setIgnoreResourceFontErrors-boolean-}
```
public final void setIgnoreResourceFontErrors(boolean value)
```

Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados. true - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que referem recursos incorretos serão pulados durante o processamento. false por padrão

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setImageResolution {#setImageResolution-int-}
```
public void setImageResolution(int value)
```

Obtém ou define a resolução para renderização de imagens.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | Valor: Resolução |

### setLettersPositioningMethod {#setLettersPositioningMethod-com.aspose.pdf.LettersPositioningMethods-}
Define o modo de posicionamento de letras em palavras no HTML resultante

### setMinimalLineWidth {#setMinimalLineWidth-float-}
```
public void setMinimalLineWidth(float value)
```

Este atributo define a largura mínima da linha de caminho gráfico. Se a espessura da linha for menor que 1 px, o Adobe Acrobat arredonda para esse valor. Portanto, este atributo pode ser usado para emular esse comportamento em navegadores HTML.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor float |

### setPageBorderIfAny {#setPageBorderIfAny-com.aspose.pdf.SaveOptions.BorderInfo-}
Este atributo representa o conjunto de configurações usadas para desenhar borda (se houver) no documento HTML resultante ao redor da área que representa a página PDF de origem.

### setPageMarginIfAny {#setPageMarginIfAny-com.aspose.pdf.SaveOptions.MarginInfo-}
Este atributo representa um conjunto de margens de página extras (se houver) no documento HTML resultante ao redor da área que representa a página PDF de origem.

### setPagesFlowTypeDependsOnViewersScreenSize {#setPagesFlowTypeDependsOnViewersScreenSize-boolean-}
```
public void setPagesFlowTypeDependsOnViewersScreenSize(boolean pagesFlowTypeDependsOnViewersScreenSize)
```

Se o atributo 'SplitOnPages=false', então todo o HTML que representa todas as páginas PDF de entrada será colocado em um único grande arquivo HTML de resultado. Esta bandeira define se o HTML de resultado será gerado de modo que o fluxo das áreas que representam as páginas PDF no HTML de resultado dependa da resolução de tela do visualizador. Suponha que a largura da tela no lado do visualizador seja grande o suficiente para colocar 2 ou mais páginas próximas umas das outras na direção horizontal. Se esta bandeira for definida como true, então essa oportunidade será usada (tantas páginas serão mostradas na direção horizontal próximas umas das outras quanto possível, então o próximo grupo horizontal de páginas será exibido abaixo da primeira). Caso contrário, as páginas fluirão da seguinte forma: a página seguinte sempre fica abaixo da anterior.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tipoFluxoPaginasDependeTamanhoTelaVisualizador |  | valor booleano |

### setPartsEmbeddingMode {#setPartsEmbeddingMode-int-}
```
public void setPartsEmbeddingMode(int partsEmbeddingMode)
```

Define se os arquivos referenciados (HTML, fontes, imagens, CSS) serão incorporados ao arquivo HTML principal ou serão gerados como entidades binárias separadas

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| modoIncorporacaoPartes |  | Elemento PartsEmbeddingModes @see PartsEmbeddingModes |

### setPreventGlyphsGrouping {#setPreventGlyphsGrouping-boolean-}
```
public void setPreventGlyphsGrouping(boolean value)
```

Este atributo ativa o modo em que os glifos de texto não serão agrupados em palavras e cadeias. Esse modo permite manter a máxima precisão ao posicionar os glifos na página e pode ser usado para converter documentos com notas musicais ou glifos que devem ser colocados separadamente uns dos outros. Este parâmetro será aplicado ao documento somente quando o valor do atributo FixedLayout for true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setRasterImagesSavingMode {#setRasterImagesSavingMode-int-}
```
public void setRasterImagesSavingMode(int rasterImagesSavingMode)
```

Um PDF convertido pode conter imagens raster. Este parâmetro define como elas devem ser tratadas durante a conversão de PDF para HTML

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| modoSalvamentoImagensRaster |  | Elemento RasterImagesSavingModes @see RasterImagesSavingModes |

### setRemoveEmptyAreasOnTopAndBottom {#setRemoveEmptyAreasOnTopAndBottom-boolean-}
```
public void setRemoveEmptyAreasOnTopAndBottom(boolean removeEmptyAreasOnTopAndBottom)
```

Define se no HTML criado serão removidas as áreas vazias superior e inferior sem nenhum conteúdo (se houver).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| removerAreasVaziasEmCimaEBaixo |  | valor booleano |

### setRenderTextAsImage {#setRenderTextAsImage-boolean-}
```
public void setRenderTextAsImage(boolean value)
```

Se o atributo RenderTextAsImage for definido como true, o texto da fonte se torna uma imagem no HTML. Pode ser útil para tornar o texto não selecionável ou quando o texto HTML não é renderizado corretamente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveFullFont {#setSaveFullFont-boolean-}
```
public void setSaveFullFont(boolean value)
```

Indica que a fonte completa será salva, suporta apenas fontes True Type. Por padrão, SaveFullFont = false e o conversor salva o subconjunto da fonte inicial necessário para exibir o texto do documento.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSaveShadowedTextsAsTransparentTexts {#setSaveShadowedTextsAsTransparentTexts-boolean-}
```
public void setSaveShadowedTextsAsTransparentTexts(boolean saveShadowedTextsAsTransparentTexts)
```

Um PDF pode conter textos que são sombreado por outros elementos (por exemplo, por imagens), mas que podem ser selecionados para a área de transferência no Acrobat Reader (geralmente isso ocorre quando o documento contém imagens e textos OCR extraídos dele). Esta configuração indica ao conversor se devemos salvar esses textos como textos transparentes selecionáveis no HTML de resultado para imitar o comportamento do Acrobat Reader (caso contrário, esses textos geralmente são salvos como ocultos, não disponíveis para cópia).

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| salvarTextosSombrasComoTextosTransparentes |  | valor booleano |

### setSaveTransparentTexts {#setSaveTransparentTexts-boolean-}
```
public void setSaveTransparentTexts(boolean saveTransparentTexts)
```

Um PDF pode conter textos transparentes que podem ser selecionados para a área de transferência (geralmente isso ocorre quando o documento contém imagens e textos OCR extraídos dele). Esta configuração indica ao conversor se devemos salvar esses textos como textos transparentes selecionáveis no HTML de resultado.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| salvarTextosTransparentes |  | valor booleano |

### setSimpleTextboxModeGrouping {#setSimpleTextboxModeGrouping-boolean-}
```
public final void setSimpleTextboxModeGrouping(boolean value)
```

Este atributo especifica um agrupamento sequencial de glifos e palavras em cadeias. Por exemplo, tags e palavras têm ordem diferente no HTML convertido e você deseja que correspondam. Este parâmetro será aplicado ao documento somente quando o valor do atributo FixedLayout for true.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSpecialFolderForAllImages {#setSpecialFolderForAllImages-java.lang.String-}
Obtém ou define o caminho para o diretório onde quaisquer imagens encontradas durante a gravação do documento como HTML devem ser salvas. Se o parâmetro estiver vazio ou nulo, os arquivos de imagem (se houver) serão salvos junto com os demais arquivos vinculados ao HTML. Não afeta nada se a propriedade CustomImageSavingStrategy foi usada com sucesso para processar o arquivo de imagem relevante.

### setSpecialFolderForSvgImages {#setSpecialFolderForSvgImages-java.lang.String-}
Obtém ou define o caminho para o diretório onde apenas imagens SVG encontradas durante a gravação do documento como HTML devem ser salvas. Se o parâmetro estiver vazio ou nulo, os arquivos SVG (se houver) serão salvos junto com os demais arquivos de imagem (próximos ao arquivo de saída) ou em pasta especial para imagens (se especificada na opção SpecialImagesFolderIfAny). Não afeta nada se a propriedade CustomImageSavingStrategy foi usada com sucesso para processar o arquivo de imagem relevante.

### setSplitCssIntoPages {#setSplitCssIntoPages-boolean-}
```
public void setSplitCssIntoPages(boolean value)
```

Quando o modo multipágina está selecionado (ou seja, 'SplitIntoPages' está 'true'), este atributo define se deve ser criado um arquivo CSS separado para cada página HTML de resultado. Por padrão, esse atributo é false, portanto será criado um único CSS comum para todas as páginas criadas. O tamanho total de todos os CSSs gerados neste modo (um CSS por página) costuma ser muito maior que o tamanho de um único CSS grande, porque no primeiro caso as classes CSS são duplicadas em vários arquivos CSS para cada página. Assim, essa configuração deve ser usada apenas quando você está interessado no processamento futuro de cada página HTML de forma independente, e portanto o tamanho do CSS de cada página individual é a questão mais crítica.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setSplitIntoPages {#setSplitIntoPages-boolean-}
```
public void setSplitIntoPages(boolean value)
```

Define a bandeira que indica se cada página do documento de origem será convertida em seu próprio documento HTML de destino, ou seja, se o HTML resultante será dividido em várias páginas HTML.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |

### setTitle {#setTitle-java.lang.String-}
Obtém ou define o título da página HTML.

### setTrySaveTextUnderliningAndStrikeoutingInCss {#setTrySaveTextUnderliningAndStrikeoutingInCss-boolean-}
```
public void setTrySaveTextUnderliningAndStrikeoutingInCss(boolean trySaveTextUnderliningAndStrikeoutingInCss)
```

O próprio PDF não contém marcadores de sublinhado para textos. Ele os emula com uma linha situada sob o texto. Esta opção permite que o conversor tente adivinhar que esta ou aquela linha é o sublinhado de um texto e coloque essa informação no CSS em vez de desenhar o sublinhado graficamente.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| tentarSalvarSublinhadoETracadoTextoEmCss |  | valor booleano |

### setUseZOrder {#setUseZOrder-boolean-}
```
public void setUseZOrder(boolean value)
```

Se o atributo UseZORder for definido como true, gráficos e texto são adicionados ao documento HTML resultante de acordo com a ordem Z no documento PDF original. Se esse atributo for false, todos os gráficos são colocados em uma única camada, o que pode causar alguns efeitos indesejados em objetos sobrepostos.

**Parameters:**
| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| valor |  | valor booleano |
