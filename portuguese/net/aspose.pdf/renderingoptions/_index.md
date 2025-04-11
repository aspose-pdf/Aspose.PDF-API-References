---
title: Class RenderingOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.RenderingOptions. Representa opções de renderização
type: docs
weight: 9760
url: /pt/net/aspose.pdf/renderingoptions/
---
## Classe RenderingOptions

Representa opções de renderização.

```csharp
public sealed class RenderingOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [RenderingOptions](renderingoptions/)() | O construtor padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [AnalyzeFonts](../../aspose.pdf/renderingoptions/analyzefonts/) { get; set; } | Substitui fontes conforme necessário para garantir que todos os caracteres no texto possam ser exibidos. O algoritmo de substituição de fontes segue estas etapas: 1. Se o usuário definir explicitamente a propriedade DefaultFontName, verifique se a fonte especificada pode exibir os caracteres desejados. 2. Se nenhuma fonte definida pelo usuário estiver configurada, procure entre as fontes adicionadas via !:FontRepository.Sources. 3. Analise o texto para identificar seu alfabeto ou script e sugira nomes de fontes de acordo. Tente localizar e usar essas fontes do sistema. 4. Como uma alternativa, procure no sistema qualquer fonte capaz de exibir os caracteres necessários. |
| [BarcodeOptimization](../../aspose.pdf/renderingoptions/barcodeoptimization/) { get; set; } | Obtém ou define o modo de otimização de código de barras. |
| [ConvertFontsToUnicodeTTF](../../aspose.pdf/renderingoptions/convertfontstounicodettf/) { get; set; } | Indica que todas as fontes serão convertidas para versões TTF unicode. Isso é útil por razões de compatibilidade e para otimizar o uso de fontes, pois cada nova fonte TTF não terá todos os símbolos da fonte original, mas apenas os símbolos que são usados no texto. |
| [DefaultFontName](../../aspose.pdf/renderingoptions/defaultfontname/) { get; set; } | Obtém/define o nome padrão da fonte usada para substituir fontes ausentes. |
| [HeightExtraUnits](../../aspose.pdf/renderingoptions/heightextraunits/) { get; set; } | Obtém ou define um valor usado para aumentar ou diminuir a largura do retângulo para o operador AppendRectangle. |
| [IgnoreResourceFontErrors](../../aspose.pdf/renderingoptions/ignoreresourcefonterrors/) { get; set; } | Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados. true - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que se referem a recursos incorretos serão ignorados durante o processamento. false por padrão |
| [InterpolationHighQuality](../../aspose.pdf/renderingoptions/interpolationhighquality/) { get; set; } | Obtém ou define o modo de alta qualidade para interpolação. |
| [MaxFontsCacheSize](../../aspose.pdf/renderingoptions/maxfontscachesize/) { get; set; } | Contagem máxima de fontes no cache de fontes. O valor padrão é 10. |
| [MaxSymbolsCacheSize](../../aspose.pdf/renderingoptions/maxsymbolscachesize/) { get; set; } | Contagem máxima de símbolos no cache de símbolos. O valor padrão é 100. |
| [OptimizeDimensions](../../aspose.pdf/renderingoptions/optimizedimensions/) { get; set; } | Obtém ou define o modo de otimização de dimensões. |
| [SystemFontsNativeRendering](../../aspose.pdf/renderingoptions/systemfontsnativerendering/) { get; set; } | Obtém ou define um modo onde fontes do sistema são renderizadas nativamente. |
| [UseFontHinting](../../aspose.pdf/renderingoptions/usefonthinting/) { get; set; } | O uso deste sinalizador ativa o mecanismo de hinting de fontes. O hinting de fontes é o uso de instruções matemáticas para ajustar a exibição de uma fonte contornada. Em alguns casos, ativar este sinalizador pode resolver problemas de legibilidade do texto. No momento atual, o uso deste sinalizador pode ter efeito apenas para fontes TTF, se essas fontes forem usadas no documento de origem. |
| [WidthExtraUnits](../../aspose.pdf/renderingoptions/widthextraunits/) { get; set; } | Obtém ou define um valor usado para aumentar ou diminuir a largura do retângulo para o operador AppendRectangle. |

### Veja Também

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)