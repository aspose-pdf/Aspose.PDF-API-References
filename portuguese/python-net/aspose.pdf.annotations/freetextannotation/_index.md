---
title: "FreeTextAnnotation"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma anotação de texto livre que exibe texto diretamente na página. Ao contrário de uma anotação de texto comum, uma anotação de texto livre não possui estado aberto ou fechado; em vez de ser exibida em uma janela pop-up, o texto está sempre visível."
type: docs
weight: 260
url: /pt/python-net/aspose.pdf.annotations/freetextannotation/
---

## FreeTextAnnotation class

Representa uma anotação de texto livre que exibe texto diretamente na página. Ao contrário de uma anotação de texto comum, uma anotação de texto livre não possui estado aberto ou fechado; em vez de ser exibida em uma janela pop-up, o texto está sempre visível.

O tipo FreeTextAnnotation expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| FreeTextAnnotation(document, appearance) | Inicializa uma nova instância da classe FreeTextAnnotation |
| FreeTextAnnotation(page, rect, appearance) | Inicializa uma nova instância da classe FreeTextAnnotation |
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
| starting_style | Obtém ou define o estilo de terminação de linha para o ponto final da linha.<br/>            Esta propriedade está obsoleta, por favor use EndingStyle. |
| ending_style | Obtém ou define o estilo de terminação de linha para o ponto final da linha. |
| justification | Obtém ou define um código que especifica a forma de quadding (justification) a ser usada na exibição do texto da anotação. |
| default_appearance | Obtém ou define a string de aparência padrão a ser usada na formatação do texto. |
| default_appearance_object | Objeto que representa a aparência padrão da anotação FreeText. |
| intent | Obtém ou define a intenção da anotação de texto livre. |
| default_style | Obtém ou define uma string de estilo padrão. |
| text_style | Obtém ou define o estilo do texto na aparência. Quando o estilo do texto é alterado, a aparência do texto é atualizada. |
| girar | Ângulo da rotação da anotação. |
| chamada | Matriz de pontos que especifica a linha de chamada. |
| text_rectangle | Retângulo que descreve as diferenças numéricas entre dois retângulos: a entrada Rect da anotação<br/>             e um retângulo contido dentro desse retângulo. O retângulo interno é onde o texto da anotação deve ser exibido. |
## Métodos
| Nome | Descrição |
| :- | :- |
| clone() | Nenhum |
| get_rectangle(consider_rotation) | Retorna o retângulo da anotação levando em consideração a rotação da página. |
| accept(visitor) | Aceita um objeto visitante para processar a anotação. |
| flatten() | Coloca o conteúdo da anotação diretamente na página,<br/>            o objeto de anotação será removido. |
| change_after_resize(transform) | Atualiza parâmetros e aparência, de acordo com a transformação da matriz. |

### Veja Também

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

