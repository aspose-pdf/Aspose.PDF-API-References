---
title: Class MarkdownSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.MarkdownSaveOptions. Representa a classe de opções de salvamento de documentos no formato markdown
type: docs
weight: 6910
url: /pt/net/aspose.pdf/markdownsaveoptions/
---
## Classe MarkdownSaveOptions

Representa a classe de opções de salvamento de documentos no formato markdown.

```csharp
public class MarkdownSaveOptions : UnifiedSaveOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [MarkdownSaveOptions](markdownsaveoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AreaToExtract](../../aspose.pdf/markdownsaveoptions/areatoextract/) { get; set; } | Obtém ou define uma área retangular para extrair conteúdo para markdown. |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtém ou define um valor booleano que indica se os glifos da fonte serão armazenados em cache ao preparar páginas aps. Melhora o desempenho da conversão de pdf para outros formatos, mas aumenta o consumo de memória. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtém ou define um valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| [EmphasisStyle](../../aspose.pdf/markdownsaveoptions/emphasisstyle/) { get; set; } | Obtém ou define o estilo de ênfase para o documento gerado. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo ativou a funcionalidade para extrair imagem ou texto de documentos PDF com subcamada OCR. |
| [ExtractVectorGraphics](../../aspose.pdf/markdownsaveoptions/extractvectorgraphics/) { get; set; } | Obtém e define uma propriedade que indica se gráficos vetoriais devem ser extraídos. |
| [HeadingLevels](../../aspose.pdf/markdownsaveoptions/headinglevels/) { get; set; } | Define os níveis de cabeçalho esperados a serem usados na estratégia de reconhecimento de cabeçalhos FontSize. Se o valor desta propriedade for definido, então a estratégia de reconhecimento de cabeçalho !:PdfToMarkdown.HeadingRecognitionStrategy.Heuristic será selecionada quando as estratégias !:PdfToMarkdown.HeadingRecognitionStrategy.Auto forem definidas, mesmo que o documento contenha marcadores. |
| [HeadingRecognitionStrategy](../../aspose.pdf/markdownsaveoptions/headingrecognitionstrategy/) { get; set; } | Obtém ou define a estratégia de reconhecimento de cabeçalhos. |
| [HeadingStyle](../../aspose.pdf/markdownsaveoptions/headingstyle/) { get; set; } | Obtém ou define o estilo de cabeçalho para o documento gerado. |
| [LineBreakStyle](../../aspose.pdf/markdownsaveoptions/linebreakstyle/) { get; set; } | Obtém ou define o estilo de quebra de linha para o documento gerado. |
| [ResourcesDirectoryName](../../aspose.pdf/markdownsaveoptions/resourcesdirectoryname/) { get; set; } | Obtém e define o nome do diretório para salvar os recursos do documento, como imagens. Se o valor não for especificado, as imagens serão gravadas no mesmo diretório que o arquivo markdown. Este não é um caminho, é apenas um nome! Este diretório será criado automaticamente no diretório com o arquivo markdown salvo. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de salvamento de dados. |
| [SubscriptAndSuperscriptConversion](../../aspose.pdf/markdownsaveoptions/subscriptandsuperscriptconversion/) { get; set; } | Obtém e define a permissão para converter subscritos e sobrescritos. Este valor é verdadeiro por padrão. |
| [UseImageHtmlTag](../../aspose.pdf/markdownsaveoptions/useimagehtmltag/) { get; set; } | Obtém e define a permissão para usar uma tag img para inserir imagens à esquerda e à direita do texto. Nesse caso, no visualizador markdown, o texto será envolto em torno da imagem. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de salvamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de salvamento deve cessar. |

## Campos

| Nome | Descrição |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Processa páginas em várias threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo de azulejos iguais colocadas uma perto da outra. Nesse caso, renderizadores de formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram limites visíveis entre partes das imagens de fundo, pois suas técnicas de suavização de bordas de imagem (anti-aliasing) são diferentes do Acrobat Reader. Se parecer que o documento exportado contém tais limites visíveis entre partes das mesmas imagens de fundo, tente usar esta configuração para se livrar desse efeito indesejado. ATENÇÃO! Esta otimização de qualidade geralmente desacelera essencialmente a conversão, então, por favor, use esta opção apenas quando realmente necessário. |

### Veja Também

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)