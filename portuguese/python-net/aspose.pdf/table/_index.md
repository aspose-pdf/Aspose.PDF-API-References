---
title: "Tabela"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma tabela que pode ser adicionada à página."
type: docs
weight: 1480
url: /pt/python-net/aspose.pdf/table/
---

## Table class

Representa uma tabela que pode ser adicionada à página.

O tipo Tabela expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| Table() | Inicializa uma nova instância da classe Tabela |
## Propriedades
| Nome | Descrição |
| :- | :- |
| vertical_alignment | Obtém ou define um alinhamento vertical do parágrafo |
| horizontal_alignment | Obtém ou define um alinhamento horizontal do parágrafo |
| margem | Obtém ou define uma margem externa para o parágrafo (para geração de PDF) |
| is_first_paragraph_in_column | Obtém ou define um valor bool que indica se este parágrafo ficará na próxima coluna.<br/>            O padrão é false. (para geração de PDF) |
| is_kept_with_next | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo.<br/>            O padrão é false. (para geração de PDF) |
| is_in_new_page | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página.<br/>            O padrão é false. (para geração de PDF) |
| is_in_line_paragraph | Obtém ou define se um parágrafo é inline.<br/>            O padrão é false. (para geração de PDF) |
| hiperlink | Obtém ou define o hyperlink do fragmento (para gerador de PDF). |
| z_index | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com ZIndex maior <br/>            será colocado sobre o gráfico com ZIndex menor. ZIndex pode ser negativo. Gráfico com ZIndex negativo <br/>            será colocado atrás do texto na página. |
| background_color | Obtém ou define a cor de fundo da tabela |
| break_text | Obtém ou define o texto de quebra para a tabela |
| corner_style | Obtém ou define os estilos dos cantos da borda |
| repeating_rows_style | Obtém o estilo para linhas repetidas |
| repeating_columns_count | Obtém ou define a contagem máxima de colunas para a tabela |
| repeating_rows_count | Obtém a contagem de primeiras linhas repetidas em várias páginas |
| column_widths | Obtém as larguras das colunas da tabela. |
| broken | Obtém ou define a quebra vertical da tabela; |
| default_cell_border | Obtém a borda padrão da célula; |
| default_column_width | Obtém a borda padrão da célula; |
| linhas | Obtém as linhas da tabela. |
| borda | Obtém ou define a borda. |
| default_cell_padding | Obtém ou define o preenchimento padrão da célula. |
| default_cell_text_state | Obtém ou define o estado de texto padrão da célula. |
| alinhamento | Obtém ou define o alinhamento da tabela. |
| left | Obtém ou define a coordenada esquerda da tabela. |
| top | Obtém ou define a coordenada superior da tabela. |
| is_broken | Obtém ou define se a tabela está quebrada - será truncada para a próxima página. |
| is_borders_included | Obtém ou define a borda incluída nas larguras das colunas. |
| column_adjustment | Obtém ou define o ajuste de coluna da tabela. |
## Métodos
| Nome | Descrição |
| :- | :- |
| clone() | Clona a tabela. |
| get_width() | Obter largura. |
| get_height(parent_page) | Obter altura. |
| set_column_text_state(col_number, text_state) | Definir altura. |
| import_array(imported_array, first_filled_row, first_filled_column, is_left_columns_filled) | Importa um array unidimensional de dados para a tabela. A importação coloca uma célula por cada item do array e<br/>              começa na linha e coluna definidas nos parâmetros. Durante a importação, se for detectado que linhas necessárias<br/>              ainda estão ausentes (ou seja, a tabela de destino é muito pequena para absorver todos os dados), as linhas necessárias serão criadas |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

