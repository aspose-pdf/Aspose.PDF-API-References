---
title: "ListBoxField"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe que representa o campo ListBox."
type: docs
weight: 140
url: /pt/python-net/aspose.pdf.forms/listboxfield/
---

## ListBoxField class

Classe que representa o campo ListBox.

O tipo ListBoxField expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| ListBoxField() | Construtor para ListBoxField a ser usado no Generator. |
| ListBoxField(page, rect) | Inicializa uma nova instância da classe ListBoxField |
| ListBoxField(doc, rect) | Inicializa uma nova instância da classe ListBoxField |
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
| tipo_de_anotação | Nenhum |
| largura | Nenhum |
| ações | Nenhum |
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
| ao_ativar | Nenhum |
| realce | Nenhum |
| pai | Nenhum |
| default_appearance | Nenhum |
| read_only | Nenhum |
| required | Nenhum |
| exportable | Nenhum |
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
| commit_immediately | Obtém ou define a bandeira de commit ao mudar a seleção. |
| multi_select | Obtém ou define a bandeira de multiseleção. |
| selecionado | Obtém ou define o índice do item selecionado. Os itens são numerados a partir de 1. |
| selected_items | Obtém ou define o array dos itens selecionados na lista de múltipla seleção. Para lista de seleção única, retorna um array com um único item. |
| opções | Obtém a coleção de opções de escolha. |
| top_index | Obtém ou define o índice do elemento visível superior da lista. |
## Indexer
| Nome | Descrição |
| :- | :- |
| [index] | Obtém o subcampo contido neste campo por índice. |
## Métodos
| Nome | Descrição |
| :- | :- |
| add_option(option_name) | Adiciona uma nova opção com o nome especificado. |
| add_option(export, name) | Adiciona uma nova opção com o nome especificado. |
| clone() | Nenhum |
| get_rectangle(consider_rotation) | Nenhum |
| accept(visitor) | Nenhum |
| flatten() | Remove este campo e coloca seu valor diretamente na página. |
| change_after_resize(transform) | Nenhum |
| recalculate() | Recalcula todos os campos calculados no formulário. |
| copy_to(array, index) | Copia os subcampos deste campo para o array a partir do índice especificado. |
| set_position(point) | Define a posição do campo. |
| delete_option(option_name) | Exclui a opção pelo seu nome. |

### Veja Também

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

