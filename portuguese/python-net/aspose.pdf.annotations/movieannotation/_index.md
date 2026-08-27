---
title: "MovieAnnotation"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma anotação de filme que contém gráficos animados e som a serem apresentados na tela do computador e pelos alto-falantes. Quando a anotação é ativada, o filme é reproduzido."
type: docs
weight: 480
url: /pt/python-net/aspose.pdf.annotations/movieannotation/
---

## MovieAnnotation class

Representa uma anotação de filme que contém gráficos animados e som a serem apresentados na tela do computador e pelos alto-falantes. Quando a anotação é ativada, o filme é reproduzido.

O tipo MovieAnnotation expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| MovieAnnotation(document, movie_file) | Inicializa uma nova instância da classe MovieAnnotation |
| MovieAnnotation(page, rect, movie_file) | Inicializa uma nova instância da classe MovieAnnotation |
## Propriedades
| Nome | Descrição |
| :- | :- |
| vertical_alignment | Obtém ou define um alinhamento vertical do parágrafo |
| horizontal_alignment | Obtém ou define o alinhamento de texto da anotação. |
| margem | Obtém ou define uma margem externa para o parágrafo (para geração de PDF) |
| is_first_paragraph_in_column | Obtém ou define um valor bool que indica se este parágrafo ficará na próxima coluna.<br/>            O padrão é false. (para geração de PDF) |
| is_kept_with_next | Obtém ou define um valor bool que indica se o parágrafo atual permanece na mesma página junto com o próximo parágrafo.<br/>            O padrão é false. (para geração de PDF) |
| is_in_new_page | Obtém ou define um valor bool que força este parágrafo a ser gerado em uma nova página.<br/>            O padrão é false. (para geração de PDF) |
| is_in_line_paragraph | Obtém ou define se um parágrafo é inline.<br/>            O padrão é false. (para geração de PDF) |
| hiperlink | Obtém ou define o hyperlink do fragmento (para gerador de PDF). |
| z_index | Obtém ou define um valor int que indica a ordem Z do gráfico. Um gráfico com ZIndex maior <br/>            será colocado sobre o gráfico com ZIndex menor. ZIndex pode ser negativo. Gráfico com ZIndex negativo <br/>            será colocado atrás do texto na página. |
| atualizar_aparência_ao_converter | Se verdadeiro, a aparência da anotação será atualizada antes de converter o documento PF em imagem. Isso permite converter os campos corretamente, mas provavelmente exigirá mais tempo. |
| usar_subconjunto_de_fonte | Se esta propriedade for definida como true, as fontes serão adicionadas ao documento como subconjuntos. O valor padrão é true. |
| sinalizadores | Sinalizadores da anotação. |
| tipo_de_anotação | Obtém o tipo da anotação. |
| largura | Obtém ou define a largura da anotação. |
| ações | Obtém a lista de ações de anotação. |
| altura | Obtém ou define a altura da anotação. |
| retângulo | Obtém ou define o retângulo da anotação. |
| conteúdo | Obtém ou define o texto da anotação. |
| nome | Obtém ou define o nome da anotação na página. |
| modificado | Obtém ou define a data e hora em que a anotação foi modificada recentemente. |
| cor | Obtém ou define a cor da anotação. |
| border | Obtém ou define as características da borda da anotação. [border](/pdf/python-net/aspose.pdf.annotations/annotation/) |
| estado_ativo | Obtém ou define o estado atual de aparência da anotação. |
| características | Obtém as características da anotação. |
| estados | Obtém o dicionário de aparência da anotação. |
| alinhamento | Alinhamento da anotação. Esta propriedade está obsoleta. Use HorizontalAligment em vez disso. |
| alinhamento_horizontal_do_texto | Obtém ou define o alinhamento de texto da anotação. |
| nome_completo | Obtém o nome totalmente qualificado da anotação. |
| aparência | Obtém o dicionário de aparência da anotação. |
| índice_da_página | Obtém o índice da página que contém a anotação. |
| title | Obtém ou define o título da anotação de filme. |
| file | Obtém ou define uma especificação de arquivo que identifica um arquivo de filme auto‑descritivo. |
| poster | Obtém ou define uma bandeira ou fluxo que especifica se e como uma imagem de pôster representando o filme deve ser exibida. Se verdadeiro, a imagem de pôster deve ser recuperada do arquivo de filme; se for falso, nenhum pôster deve ser exibido. |
| aspect | Obtém ou define a largura e a altura da caixa delimitadora do filme, em pixels. |
| girar | Obtém ou define o número de graus pelos quais o filme deve ser girado no sentido horário em relação à página. O valor deve ser um múltiplo de 90. |
## Métodos
| Nome | Descrição |
| :- | :- |
| clone() | Clona esta instância.<br/>            Método virtual. Sempre retorna null. |
| get_rectangle(consider_rotation) | Retorna o retângulo da anotação levando em consideração a rotação da página. |
| accept(visitor) | Aceita um objeto visitante para processar a anotação. |
| flatten() | Coloca o conteúdo da anotação diretamente na página,<br/>            o objeto de anotação será removido. |
| change_after_resize(transform) | Atualiza parâmetros e aparência, de acordo com a transformação da matriz. |

### Veja Também

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

