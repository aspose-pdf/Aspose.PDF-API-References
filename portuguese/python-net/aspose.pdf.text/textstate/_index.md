---
title: "TextState"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa o estado de texto de um texto"
type: docs
weight: 490
url: /pt/python-net/aspose.pdf.text/textstate/
---

## TextState class

Representa o estado de texto de um texto

O tipo TextState expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| TextState() | Cria um objeto de estado de texto. |
| TextState(font_size) | Inicializa uma nova instância da classe TextState |
| TextState(foreground_color) | Inicializa uma nova instância da classe TextState |
| TextState(foreground_color, font_size) | Inicializa uma nova instância da classe TextState |
| TextState(font_family) | Inicializa uma nova instância da classe TextState |
| TextState(font_family, bold, italic) | Inicializa uma nova instância da classe TextState |
| TextState(font_family, font_size) | Inicializa uma nova instância da classe TextState |
## Propriedades
| Nome | Descrição |
| :- | :- |
| character_spacing | Obtém ou define o espaçamento de caracteres do texto. |
| line_spacing | Obtém ou define o espaçamento entre linhas do texto. |
| horizontal_scaling | Obtém ou define a escala horizontal do texto. |
| subscript | Obtém ou define o subscrito do texto. |
| superscript | Obtém ou define o sobrescrito do texto. |
| word_spacing | Obtém ou define o espaçamento entre palavras do texto. |
| invisible | Obtém ou define a invisibilidade do texto. Isso basicamente reflete o estado [rendering_mode](/pdf/python-net/aspose.pdf.text/textstate/), exceto em alguns casos especiais (como recorte). |
| rendering_mode | Obtém ou define o modo de renderização do texto. |
| font_size | Obtém ou define o tamanho da fonte do texto. |
| font | Obtém ou define a fonte do texto. |
| foreground_color | Obtém ou define a cor de primeiro plano do texto. |
| stroking_color | Obtém ou define a cor de primeiro plano do texto. |
| underline | Obtém ou define o sublinhado para o texto, representado pelo objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) |
| strike_out | Define o tachado para o texto, representado pelo objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) |
| background_color | Define a cor de fundo do texto. |
| font_style | Define o estilo da fonte do texto. |
| horizontal_alignment | Obtém ou define o alinhamento horizontal para o texto. |
| TAB_TAG | Você pode colocar esta tag no texto para declarar tabulação. |
| TABSTOP_DEFAULT_VALUE | Valor padrão da tabulação nas larguras do caractere de espaço da fonte padrão. |
## Métodos
| Nome | Descrição |
| :- | :- |
| apply_changes_from(text_state) | Aplica configurações de outro textState. |
| measure_string(str) | Mede a string. |

### Veja Também

* namespace [aspose.pdf.text](/pdf/python-net/aspose.pdf.text/)
* assembly [Aspose.PDF](/pdf/python-net/)

