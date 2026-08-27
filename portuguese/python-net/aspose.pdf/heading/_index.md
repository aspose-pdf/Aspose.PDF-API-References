---
title: "Heading"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa o cabeçalho."
type: docs
weight: 460
url: /pt/python-net/aspose.pdf/heading/
---

## Heading class

Representa o cabeçalho.

O tipo Heading expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| Heading(level) | Inicializa uma nova instância da classe Heading |
## Propriedades
| Nome | Descrição |
| :- | :- |
| vertical_alignment | Obtém ou define um alinhamento vertical do fragmento de texto. |
| horizontal_alignment | Obtém ou define um alinhamento horizontal do fragmento de texto. |
| margem | Obtém ou define uma margem externa para o parágrafo (para geração de PDF) |
| is_first_paragraph_in_column | Obtém ou define um valor bool que indica se este parágrafo ficará na próxima coluna.<br/>            O padrão é false. (para geração de PDF) |
| is_kept_with_next | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo.<br/>            O padrão é false. (para geração de PDF) |
| is_in_new_page | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página.<br/>            O padrão é false. (para geração de PDF) |
| is_in_line_paragraph | Obtém ou define se um parágrafo é inline.<br/>            O padrão é false. (para geração de PDF) |
| hiperlink | Define o hyperlink do fragmento |
| z_index | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com ZIndex maior <br/>            será colocado sobre o gráfico com ZIndex menor. ZIndex pode ser negativo. Gráfico com ZIndex negativo <br/>            será colocado atrás do texto na página. |
| replace_options | Obtém opções de substituição de texto. As opções definem o comportamento quando o texto do fragmento é substituído por um texto mais curto ou mais longo. |
| text | Obtém ou define o objeto de texto string que o objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) representa. |
| text_state | Obtém ou define o estado do texto para o texto que o objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) representa. |
| segments | Obtém segmentos de texto para o [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/) atual. |
| position | Obtém ou define a posição do texto para o texto, representado pelo objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| baseline_position | Obtém a posição do texto para o texto, representado pelo objeto [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/).<br/>            O YIndent da estrutura Position representa a coordenada da linha de base do fragmento de texto. |
| rectangle | Obtém o retângulo do TextFragment |
| página | Obtém a página que contém o TextFragment |
| formulário | Obtém o objeto de formulário que contém o TextFragment |
| wrap_lines_count | Obtém ou define wrap lines count para este parágrafo (somente para geração de PDF) |
| end_note | Obtém ou define a nota final do parágrafo (somente para geração de PDF) |
| foot_note | Obtém ou define a nota de rodapé do parágrafo (somente para geração de PDF) |
| toc_page | Obtém a página que contém este cabeçalho. |
| top | Obtém o Y superior destes cabeçalhos. |
| start_number | Obtém o número inicial do cabeçalho. |
| is_auto_sequence | Obtém se o cabeçalho deve ser numerado automaticamente. |
| is_in_list | Obtém se o cabeçalho deve estar na lista de índice. |
| destination_page | Obtém a página de destino. |
| level | Obtém o nível. |
| style | Obtém ou define o estilo. |
| user_label | Obtém ou define o rótulo do usuário. |
## Métodos
| Nome | Descrição |
| :- | :- |
| clone() | Clona o cabeçalho. |
| isolate_text_segments(start_index, length) | Obtém [TextSegment](/pdf/python-net/aspose.pdf.text/textsegment/)(s) que representam a parte especificada do texto do [TextFragment](/pdf/python-net/aspose.pdf.text/textfragment/). |
| clone_with_segments() | Clona o cabeçalho com todos os segmentos. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

