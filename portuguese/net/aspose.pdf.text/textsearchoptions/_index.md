---
title: Class TextSearchOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Text.TextSearchOptions. Representa opções de busca de texto
type: docs
weight: 11040
url: /pt/net/aspose.pdf.text/textsearchoptions/
---
## Classe TextSearchOptions

Representa opções de busca de texto

```csharp
public sealed class TextSearchOptions : TextOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [TextSearchOptions](textsearchoptions/#constructor_2)(bool) | Inicializa uma nova instância do objeto `TextSearchOptions`. Especifica o modo de uso de expressões regulares. |
| [TextSearchOptions](textsearchoptions/#constructor)(Rectangle) | Inicializa uma nova instância do objeto `TextSearchOptions`. Especifica o retângulo que delimita o texto pesquisado. |
| [TextSearchOptions](textsearchoptions/#constructor_1)(Rectangle, bool) | Inicializa uma nova instância do objeto `TextSearchOptions`. Especifica o retângulo que delimita o texto pesquisado e o modo de uso de expressões regulares. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [IgnoreResourceFontErrors](../../aspose.pdf.text/textsearchoptions/ignoreresourcefonterrors/) { get; set; } | Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados pelo absorvedor de texto (fragmento). verdadeiro - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que se referem a recursos incorretos serão ignorados durante o processamento. falso (padrão) - erro de ausência de fonte encerrará o processamento lançando uma exceção. |
| [IgnoreShadowText](../../aspose.pdf.text/textsearchoptions/ignoreshadowtext/) { get; set; } | Obtém ou define a indicação de que fragmentos de texto representando sombra de texto normal serão ignorados durante a busca. verdadeiro - significa que texto sombra não será encontrado (tente isso se a busca de texto retornar fragmentos duplicados em posições próximas) falso - significa que texto sombra será encontrado assim como texto normal (valor padrão) |
| [IsRegularExpressionUsed](../../aspose.pdf.text/textsearchoptions/isregularexpressionused/) { get; set; } | Obtém ou define a indicação de que uma expressão regular está sendo usada. |
| [LimitToPageBounds](../../aspose.pdf.text/textsearchoptions/limittopagebounds/) { get; set; } | Obtém ou define a indicação de que o texto é pesquisado dentro dos limites da página. |
| [LogTextExtractionErrors](../../aspose.pdf.text/textsearchoptions/logtextextractionerrors/) { get; set; } | Obtém ou define a indicação de que erros de extração de texto (decodificação) serão registrados no absorvedor de texto (fragmento). verdadeiro - significa que erros de extração de texto (decodificação) serão registrados. Isso pode diminuir o desempenho. falso (padrão) - sem registro de erro. |
| [Rectangle](../../aspose.pdf.text/textsearchoptions/rectangle/) { get; set; } | Obtém ou define o retângulo que delimita o texto pesquisado. |
| [SearchForTextRelatedGraphics](../../aspose.pdf.text/textsearchoptions/searchfortextrelatedgraphics/) { get; set; } | Obtém ou define o valor que permite a busca por gráficos relacionados ao texto (sublinhado, fundo etc.) durante a busca de texto. verdadeiro - a busca por gráficos relacionados ao texto será realizada (valor padrão). falso - elementos gráficos que podem estar presentes no documento de origem serão ignorados. Defina isso em caso de problemas de desempenho ou se não houver necessidade de lidar com sublinhado, fundo ou recorte. |
| [SearchInAnnotations](../../aspose.pdf.text/textsearchoptions/searchinannotations/) { get; set; } | Obtém ou define o valor que permite a busca por texto em Anotações. verdadeiro - o texto será pesquisado em Anotações. falso - o texto em Anotações não será analisado pelo TextFragmentAbsorber. |
| [StoredGraphicElementsMaxCount](../../aspose.pdf.text/textsearchoptions/storedgraphicelementsmaxcount/) { get; set; } | Obtém ou define o valor que limita a busca por gráficos relacionados ao texto (sublinhado, fundo etc.) em uma página para o número especificado de elementos. O padrão é 250. Defina um valor menor em caso de problemas de desempenho, tente um valor maior no caso de alguns elementos gráficos não terem sido encontrados. |
| [UseFontEngineEncoding](../../aspose.pdf.text/textsearchoptions/usefontengineencoding/) { get; set; } | Obtém ou define a indicação de que o texto será pesquisado usando a codificação do mecanismo de fonte. verdadeiro - significa que a codificação do mecanismo de fonte será usada (tente isso se a busca de texto falhar devido à codificação imperfeita no documento) falso - significa que a codificação da fonte do documento será usada (valor padrão) |

### Veja Também

* classe [TextOptions](../textoptions/)
* namespace [Aspose.Pdf.Text](../../aspose.pdf.text/)
* assembly [Aspose.PDF](../../)