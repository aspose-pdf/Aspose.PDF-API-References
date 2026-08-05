---
title: "ButtonField"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe representa campo de botão de comando."
type: docs
weight: 20
url: /pt/python-net/aspose.pdf.forms/buttonfield/
---

## ButtonField class

Classe representa campo de botão de comando.

O tipo ButtonField expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| ButtonField() | Construtor de campo de botão para Generator. |
| ButtonField(page, rect) | Inicializa uma nova instância da classe ButtonField |
| ButtonField(doc, rect) | Inicializa uma nova instância da classe ButtonField |
## Propriedades
| Nome | Descrição |
| :- | :- |
| vertical_alignment | Nenhum |
| horizontal_alignment | Nenhum |
| margem | Nenhum |
| is_first_paragraph_in_column | Nenhum |
| is_kept_with_next | Nenhum |
| is_in_new_page | Nenhum |
| is_in_line_paragraph | Nenhum |
| hiperlink | Nenhum |
| z_index | Nenhum |
| atualizar_aparência_ao_converter | Nenhum |
| usar_subconjunto_de_fonte | Nenhum |
| sinalizadores | Nenhum |
| tipo_de_anotação | Obtém o tipo da anotação. |
| largura | Nenhum |
| ações | Obtém as ações da anotação. |
| altura | Nenhum |
| retângulo | Obtém ou define o retângulo do campo. |
| conteúdo | Nenhum |
| nome | Nenhum |
| modificado | Nenhum |
| cor | Nenhum |
| borda | Nenhum |
| estado_ativo | Nenhum |
| características | Nenhum |
| estados | Nenhum |
| alinhamento | Nenhum |
| alinhamento_horizontal_do_texto | Nenhum |
| nome_completo | Nenhum |
| aparência | Nenhum |
| índice_da_página | Obtém o índice da página que contém este campo. |
| ao_ativar | Uma ação que deve ser executada quando a anotação for ativada. |
| realce | Modo de realce da anotação. |
| pai | Obtém o pai da anotação. |
| default_appearance | Obtém ou define a aparência padrão do campo. |
| read_only | Obtém ou define o status somente leitura do campo. |
| required | Obtém ou define o status obrigatório do campo. |
| exportable | Obtém ou define a bandeira exportável do campo. |
| partial_name | Obtém ou define o nome parcial do campo. |
| alternate_name | Obtém ou define o nome alternativo do campo (Um campo alternativo <br/>            nome que deve ser usado no lugar do nome real do campo <br/>            onde quer que o campo seja identificado na interface do usuário).<br/>            O nome alternativo é usado como dica de ferramenta do campo no Adobe Acrobat. |
| mapping_name | Obtém ou define o nome de mapeamento do campo que deve ser usado ao exportar dados de campos de formulário interativos do documento. |
| valor | Obtém ou define o valor do campo. |
| is_synchronized | Retorna verdadeiro se o dicionário estiver sincronizado. |
| sync_root | Objeto de sincronização. |
| is_group | Obtém ou define o valor booleano que indica se este campo é um campo não terminal, ou seja, um grupo de campos. |
| annotation_index | Obtém ou define o índice desta anotação na página. |
| is_shared_field | Propriedade para suporte ao Gerador. Usada quando o campo é adicionado ao cabeçalho ou rodapé. Se verdadeiro, este campo será criado uma vez e sua aparência será visível em todas as páginas do documento. Se falso, um campo separado será criado para cada página do documento. |
| fit_into_rectangle | Se verdadeiro, o tamanho da fonte será reduzido para ajustar o texto ao retângulo especificado. |
| max_font_size | Tamanho máximo da fonte que pode ser usado para o conteúdo do campo. -1 para não verificar o tamanho. |
| min_font_size | Tamanho mínimo da fonte que pode ser usado para o conteúdo do campo. -1 para não verificar o tamanho. |
| tab_order | Obtém ou define a ordem de tabulação do campo. |
| normal_caption | Obtém ou define a legenda normal. |
| rollover_caption | Obtém ou define a legenda de rollover do botão que deve ser exibida quando o usuário move o cursor <br/>            para sua área ativa sem pressionar o botão do mouse. |
| alternate_caption | Obtém ou define a legenda alternativa do botão que deve ser exibida <br/>            quando o botão do mouse é pressionado dentro de sua área ativa. |
| normal_icon | Obtém ou define o ícone normal do botão que deve ser exibido quando não está interagindo com o usuário. |
| rollover_icon | Obtém ou define o ícone de rollover do botão que deve ser exibido quando o usuário <br/>            move o cursor para sua área ativa sem pressionar o botão do mouse. |
| alternate_icon | Obtém ou define o ícone alternativo que deve ser exibido quando o botão do mouse é pressionado dentro de sua área ativa. |
| icon_fit | Obtém o objeto de ajuste de ícone que especifica como o ícone da anotação de widget deve ser exibido dentro de seu retângulo de anotação. |
| ic_position | Obtém ou define a posição da legenda do ícone. |
## Indexer
| Nome | Descrição |
| :- | :- |
| [index] | Obtém o subcampo contido neste campo por índice. |
## Métodos
| Nome | Descrição |
| :- | :- |
| clone() | Nenhum |
| get_rectangle(consider_rotation) | Nenhum |
| accept(visitor) | Aceita o visitante. |
| flatten() | Remove este campo e coloca seu valor diretamente na página. |
| change_after_resize(transform) | Nenhum |
| recalculate() | Recalcula todos os campos calculados no formulário. |
| copy_to(array, index) | Copia os subcampos deste campo para o array a partir do índice especificado. |
| set_position(point) | Define a posição do campo. |
| add_image(image) | Adiciona a imagem aos recursos do campo e a desenha. |

### Veja Também

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

