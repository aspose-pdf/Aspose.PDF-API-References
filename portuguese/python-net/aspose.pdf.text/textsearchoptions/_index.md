---
title: "TextSearchOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa opções de pesquisa de texto"
type: docs
weight: 460
url: /pt/python-net/aspose.pdf.text/textsearchoptions/
---

## TextSearchOptions class

Representa opções de pesquisa de texto

O tipo TextSearchOptions expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| TextSearchOptions(is_regular_expression_used) | Inicializa uma nova instância da classe TextSearchOptions |
| TextSearchOptions(rectangle) | Inicializa uma nova instância da classe TextSearchOptions |
| TextSearchOptions(rectangle, is_regular_expression_used) | Inicializa uma nova instância da classe TextSearchOptions |
## Propriedades
| Nome | Descrição |
| :- | :- |
| is_regular_expression_used | Obtém ou define a indicação de que a expressão regular é usada. |
| limit_to_page_bounds | Obtém ou define a indicação de que o texto é pesquisado dentro dos limites da página. |
| rectangle | Obtém ou define o retângulo que delimita o texto pesquisado. |
| use_font_engine_encoding | Obtém ou define a indicação de que o texto será pesquisado usando a codificação do mecanismo de fontes.<br/>            true - significa que a codificação do mecanismo de fontes será usada (tente isso se a pesquisa de texto falhar devido a codificação imperfeita no documento)<br/>            false - significa que a codificação de fontes do documento será usada (valor padrão) |
| ignore_shadow_text | Obtém ou define a indicação de que fragmentos de texto que representam a sombra do texto normal serão ignorados durante a pesquisa.<br/>            true - significa que o texto sombra não será encontrado (tente isso se a pesquisa de texto retornar fragmentos duplicados em posições próximas)<br/>            false - significa que o texto sombra será encontrado juntamente com o texto normal (valor padrão) |
| log_text_extraction_errors | Obtém ou define a indicação de que erros de extração de texto (decodificação) serão registrados no absorvedor de texto (fragmento).<br/>            true - significa que os erros de extração de texto (decodificação) serão registrados. Isso pode diminuir o desempenho.<br/>            false (default) - nenhum registro de erro. |
| ignore_resource_font_errors | Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados pelo absorvedor de texto (fragmento).<br/>            true - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que referem recursos incorretos serão ignorados durante o processamento.<br/>            false (padrão) - o erro de ausência de fonte encerrará o processamento lançando uma exceção. |
| search_for_text_related_graphics | Obtém ou define o valor que permite a busca de gráficos relacionados ao texto (sublinhado, fundo etc.) durante a pesquisa de texto.<br/>            true - a busca de gráficos relacionados ao texto será realizada (valor padrão).<br/>            false - elementos gráficos que possam estar presentes no documento fonte serão ignorados. Defina isso em caso de problemas de desempenho ou quando não for necessário lidar com sublinhado, fundo ou recorte. |
| stored_graphic_elements_max_count | Obtém ou define o valor que limita a busca de gráficos relacionados ao texto (sublinhado, fundo etc.) em uma página para o número especificado de elementos.<br/>            O padrão é 250. Defina um valor menor em caso de problemas de desempenho, experimente um valor maior caso alguns elementos gráficos não sejam encontrados. |
| search_in_annotations | Obtém ou define o valor que permite a busca de texto em Anotações.<br/>            true - o texto será buscado nas Anotações.<br/>            false - o texto nas Anotações não será analisado pelo TextFragmentAbsorber. |

### Veja Também

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

