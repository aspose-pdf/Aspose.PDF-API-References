---
title: "TeXFragment"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa um fragmento TeX."
type: docs
weight: 1510
url: /pt/python-net/aspose.pdf/texfragment/
---

## TeXFragment class

Representa um fragmento TeX.

O tipo TeXFragment expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| TeXFragment(text) | Inicializa uma nova instância da classe TeXFragment |
| TeXFragment(text, remove_indents) | Inicializa uma nova instância da classe TeXFragment |
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
| te_x_load_options_of_instance | Obtém ou define TeXLoadOptions que serão usados para carregar (e renderizar) LaTeX nesta instância da classe.<br/>            Use-o quando for necessário usar uma configuração específica para a importação de LaTeX para esta ou aquela instância<br/>             (por exemplo, quando esta ou aquela instância deve usar um BasePath específico para LaTeX importado ou deve usar um carregador específico de recursos externos)<br/>            Se o parâmetro for padrão (null), então serão usadas as opções padrão de carregamento de LaTeX. |
| latex_load_options_of_instance | Obtém ou define TeXLoadOptions que serão usados para carregar (e renderizar) LaTeX nesta instância da classe.<br/>            Use-o quando for necessário usar uma configuração específica para a importação de LaTeX para esta ou aquela instância<br/>             (por exemplo, quando esta ou aquela instância deve usar um BasePath específico para LaTeX importado ou deve usar um carregador específico de recursos externos)<br/>            Se o parâmetro for padrão (null), então serão usadas as opções padrão de carregamento de LaTeX. |
## Métodos
| Nome | Descrição |
| :- | :- |
| clone() | Clona o fragmento. |

### Veja Também

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

