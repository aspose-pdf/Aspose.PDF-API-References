---
title: "LineAnnotation"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe que representa anotação de linha."
type: docs
weight: 380
url: /pt/python-net/aspose.pdf.annotations/lineannotation/
---

## LineAnnotation class

Classe que representa anotação de linha.

O tipo LineAnnotation expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| LineAnnotation(document, start, end) | Inicializa uma nova instância da classe LineAnnotation |
| LineAnnotation(page, rect, start, end) | Inicializa uma nova instância da classe LineAnnotation |
## Propriedades
| Nome | Descrição |
| :- | :- |
| vertical_alignment | Nenhum |
| horizontal_alignment | Obtém ou define o alinhamento de texto da anotação. |
| margem | Nenhum |
| is_first_paragraph_in_column | Nenhum |
| is_kept_with_next | Nenhum |
| is_in_new_page | Nenhum |
| is_in_line_paragraph | Nenhum |
| hiperlink | Nenhum |
| z_index | Nenhum |
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
| title | Obtém ou define um texto que será exibido na barra de título da anotação. |
| rich_text | Obtém ou define uma string de texto rico a ser exibida na janela pop-up quando a anotação for aberta. |
| creation_date | Obtém a data e hora em que a anotação foi criada. |
| subject | Obtém o texto que representa a descrição do objeto. |
| popup | Anotação pop-up para inserir ou editar o texto associado a esta anotação. |
| opacidade | Obtém ou define o valor constante de opacidade a ser usado ao renderizar a anotação. |
| in_reply_to | Uma referência à anotação que esta anotação está "em resposta a".<br/>            Ambas as anotações devem estar na mesma página do documento. |
| reply_type | Uma string que especifica o relacionamento (o "tipo de resposta") entre esta anotação<br/>            e a especificada por InReplyTo. |
| início | Obtém ou define o ponto inicial da linha. |
| starting_style | Obtém ou define o estilo de terminação da linha para o ponto inicial da linha. |
| terminação | Obtém ou define o ponto final da linha. |
| ending_style | Obtém ou define o estilo de terminação para o ponto final da linha. |
| interior_color | Obtém ou define a cor interna da anotação. |
| leader_line | Obtém ou define o comprimento da linha guia. |
| leader_line_extension | Obtém ou define o comprimento da extensão da linha guia. |
| show_caption | Obtém ou define a bandeira booleana que determina se o conteúdo deve ser exibido como legenda. |
| leader_line_offset | Obtém ou define o deslocamento da linha guia. |
| caption_offset | Obtém ou define o deslocamento do texto da legenda em relação à sua posição normal. |
| caption_position | Obtém ou define a posição da legenda da anotação. |
| measure | Unidades de medida especificadas para esta anotação. |
| intent | Obtém ou define a intenção da anotação de linha. |
## Métodos
| Nome | Descrição |
| :- | :- |
| clone() | Nenhum |
| get_rectangle(consider_rotation) | Retorna o retângulo da anotação levando em consideração a rotação da página. |
| accept(visitor) | Aceita visitante para o processamento da anotação. |
| flatten() | Coloca o conteúdo da anotação diretamente na página,<br/>            o objeto de anotação será removido. |
| change_after_resize(transform) | Atualiza os pontos de Início e Fim, de acordo com a transformação de matriz. |

### Veja Também

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

