---
title: Class PsSaveOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.PsSaveOptions. Opções de salvamento para exportação para o formato PS PostScript ou EPS
type: docs
weight: 9740
url: /pt/net/aspose.pdf/pssaveoptions/
---
## Classe PsSaveOptions

Opções de salvamento para exportação para o formato PS (PostScript) ou EPS.

```csharp
public class PsSaveOptions : UnifiedSaveOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PsSaveOptions](pssaveoptions/#constructor)() | Construtor. |
| [PsSaveOptions](pssaveoptions/#constructor_1)(SaveFormat) | Construtor. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CacheGlyphs](../../aspose.pdf/saveoptions/cacheglyphs/) { get; set; } | Obtém ou define um valor booleano que indica se os glifos da fonte serão armazenados em cache enquanto prepara as páginas aps. Melhora o desempenho da conversão de pdf para outros formatos, mas aumenta o consumo de memória. |
| [CloseResponse](../../aspose.pdf/saveoptions/closeresponse/) { get; set; } | Obtém ou define um valor booleano que indica se o objeto Response será fechado após o documento ser salvo na resposta. |
| [EmbedFont](../../aspose.pdf/pssaveoptions/embedfont/) { get; set; } | Obtém/define uma flag que indica se as fontes devem ser incorporadas no documento PS resultante. |
| [EmbedFontAs](../../aspose.pdf/pssaveoptions/embedfontas/) { get; set; } | Obtém/define o tipo no qual as fontes devem ser incorporadas no documento PS resultante. |
| [ExtractOcrSublayerOnly](../../aspose.pdf/unifiedsaveoptions/extractocrsublayeronly/) { get; set; } | Este atributo ativa a funcionalidade para extrair imagem ou texto de documentos PDF com subcamada OCR. |
| [SaveFormat](../../aspose.pdf/saveoptions/saveformat/) { get; } | Formato de salvamento de dados. |
| [WarningHandler](../../aspose.pdf/saveoptions/warninghandler/) { get; set; } | Callback para lidar com quaisquer avisos gerados. O WarningHandler retorna um item do enum ReturnAction especificando Continue ou Abort. Continue é a ação padrão e a operação de salvamento continua, no entanto, o usuário também pode retornar Abort, caso em que a operação de salvamento deve cessar. |

## Campos

| Nome | Descrição |
| --- | --- |
| [IsMultiThreading](../../aspose.pdf/unifiedsaveoptions/ismultithreading/) | Processa páginas em várias threads. |
| [TryMergeAdjacentSameBackgroundImages](../../aspose.pdf/unifiedsaveoptions/trymergeadjacentsamebackgroundimages/) | Às vezes, PDFs contêm imagens de fundo (de páginas ou células de tabela) construídas a partir de várias imagens de fundo de azulejos iguais colocadas uma perto da outra. Nesse caso, os renderizadores dos formatos de destino (por exemplo, MsWord para o formato DOCS) às vezes geram limites visíveis entre partes das imagens de fundo, pois suas técnicas de suavização de bordas de imagem (anti-aliasing) são diferentes do Acrobat Reader. Se parecer que o documento exportado contém tais limites visíveis entre partes das mesmas imagens de fundo, tente usar esta configuração para se livrar desse efeito indesejado. ATENÇÃO! Esta otimização de qualidade geralmente desacelera essencialmente a conversão, portanto, use esta opção apenas quando realmente necessário. |

### Veja Também

* classe [UnifiedSaveOptions](../unifiedsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)