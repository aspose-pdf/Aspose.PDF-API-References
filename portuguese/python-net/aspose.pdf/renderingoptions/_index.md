---
title: "RenderingOptions"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa opções de renderização."
type: docs
weight: 1330
url: /pt/python-net/aspose.pdf/renderingoptions/
---

## RenderingOptions class

Representa opções de renderização.

O tipo RenderingOptions expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| RenderingOptions() | Inicializa uma nova instância da classe RenderingOptions |
## Propriedades
| Nome | Descrição |
| :- | :- |
| barcode_optimization | Obtém ou define o modo de otimização de código de barras. |
| optimize_dimensions | Obtém ou define o modo de otimização de dimensões. |
| system_fonts_native_rendering | Obtém ou define um modo em que as fontes do sistema são renderizadas nativamente. |
| use_new_imaging_engine | Obtém ou define um sinalizador que determina se o novo mecanismo de imagens é usado ou não. |
| width_extra_units | Obtém ou define um valor usado para aumentar ou diminuir a largura do retângulo para o operador AppendRectangle. |
| height_extra_units | Obtém ou define um valor usado para aumentar ou diminuir a largura do retângulo para o operador AppendRectangle. |
| convert_fonts_to_unicode_ttf | Indica que todas as fontes serão convertidas para versões unicode TTF. Isso é útil por razões de compatibilidade <br/>             e para otimizar o uso de fontes, pois cada nova fonte TTF não terá todos os símbolos <br/>             da fonte original, mas apenas os símbolos que são usados no texto. |
| use_font_hinting | O uso deste sinalizador ativa o mecanismo de hinting de fontes. O hinting de fontes é o uso de instruções matemáticas para ajustar a exibição <br/>            de uma fonte contornada. Em alguns casos, ativar este sinalizador pode resolver problemas de legibilidade do texto. <br/>            No momento, o uso deste sinalizador pode ter efeito apenas para fontes TTF, se essas fontes forem usadas no documento de origem. |
| scale_images_to_fit_page_width | Obtém ou define um valor usado para escalar todas as imagens na página para ajustar à largura da página. |
| interpolation_high_quality | Obtém ou define o modo de alta qualidade para interpolação. |
| max_fonts_cache_size | Contagem máxima de fontes no cache de fontes. O valor padrão é 10. |
| max_symbols_cache_size | Contagem máxima de símbolos no cache de símbolos. O valor padrão é 100. |
| default_font_name | Obtém/define o nome padrão da fonte usada para substituir fontes ausentes. |
| ignore_resource_font_errors | Obtém ou define a indicação de que erros relacionados à ausência de fonte serão ignorados.<br/>            true - significa que erros de ausência de fonte serão ignorados. Segmentos de texto que referem recursos incorretos serão ignorados durante o processamento.<br/>            false por padrão |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

