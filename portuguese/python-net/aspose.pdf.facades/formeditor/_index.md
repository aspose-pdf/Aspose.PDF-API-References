---
title: "FormEditor"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe para editar formulários (adicionar/excluir campos etc)."
type: docs
weight: 110
url: /pt/python-net/aspose.pdf.facades/formeditor/
---

## FormEditor class

Classe para editar formulários (adicionar/excluir campos etc).

O tipo FormEditor expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| FormEditor(src_stream, dest_stream) | Inicializa uma nova instância da classe FormEditor |
| FormEditor(src_file_name, dest_file_name) | Inicializa uma nova instância da classe FormEditor |
| FormEditor() | Construtor para FormEditor. |
| FormEditor(document) | Inicializa uma nova instância da classe FormEditor |
| FormEditor(document, dest_file_name) | Inicializa uma nova instância da classe FormEditor |
| FormEditor(document, dest_stream) | Inicializa uma nova instância da classe FormEditor |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| src_file_name | Obtém ou define o nome do arquivo de origem. |
| dest_file_name | Obtém ou define o nome do arquivo de destino. |
| src_stream | Obtém ou define o fluxo de origem. |
| dest_stream | Obtém ou define o fluxo de destino. |
| items | Define os itens que serão adicionados a uma caixa de lista ou caixa de combinação recém-criada. |
| export_items | Define opções para a caixa de combinação com valores de exportação. |
| facade | Define atributos visuais do campo. |
| radio_gap | O membro para registrar o espaço entre dois botões de opção vizinhos em pixels, o padrão é 50. |
| radio_horiz | A bandeira que indica se os botões de opção estão dispostos horizontalmente ou verticalmente, o valor padrão é verdadeiro. |
| radio_button_item_size | Obtém ou define o tamanho do item do botão de opção (quando um novo campo de botão de opção é adicionado). |
| submit_flag | Define as bandeiras de envio do botão de envio |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(src_file) | Vincula o documento PDF para edição. |
| bind_pdf(src_stream) | Vincula o documento PDF para edição. |
| bind_pdf(src_doc) | Vincula o documento PDF para edição. |
| save() | Salva as alterações no arquivo de destino. |
| save(dest_file) | Salva as alterações no arquivo de destino. |
| save(dest_stream) | Salva as alterações no arquivo de destino. |
| add_field(field_type, field_name, page_num, llx, lly, urx, ury) | Adiciona um campo do tipo especificado ao formulário. |
| add_field(field_type, field_name, init_value, page_num, llx, lly, urx, ury) | Adiciona um campo do tipo especificado ao formulário. |
| copy_inner_field(field_name, new_field_name, page_num) | Copia um campo existente para a mesma posição no número de página especificado.<br/>            Um novo documento será produzido, contendo tudo o que o documento de origem tem, exceto o campo recém‑copiado. |
| copy_inner_field(field_name, new_field_name, page_num, abscissa, ordinate) | Copia um campo existente para uma nova posição especificada tanto pelo número da página quanto pelas coordenadas.<br/>            Um novo documento será produzido, contendo tudo o que o documento de origem tem, exceto o campo recém‑copiado. |
| copy_outer_field(src_file_name, field_name) | Copia um campo existente de um documento PDF para outro documento com o número de página e coordenadas originais.<br/>            Aviso: Apenas para campos AcroForm (excluindo botão de opção). |
| copy_outer_field(src_file_name, field_name, page_num) | Copia um campo existente de um documento PDF para outro documento com o número de página especificado e coordenadas originais.<br/>             Aviso: Apenas para campos AcroForm (excluindo botão de opção). |
| copy_outer_field(src_file_name, field_name, page_num, abscissa, ordinate) | Copia um campo existente de um documento PDF para outro documento com o número de página e coordenadas especificados.<br/>            Aviso: Apenas para campos AcroForm (excluindo botão de opção). |
| decorate_field(field_name) | Altera os atributos visuais do campo especificado. |
| decorate_field(field_type) | Altera os atributos visuais de todos os campos com o tipo de campo especificado. |
| decorate_field() | Altera os atributos visuais do campo especificado. |
| add_list_item(field_name, item_name) | Adiciona um novo item à caixa de lista. |
| add_list_item(field_name, export_name) | Adiciona um novo item com valor Export ao campo de caixa de lista existente, apenas para campo de caixa de combinação AcroForm. |
| close() | Fecha a fachada. |
| set_field_attribute(field_name, flag) | Define atributos do campo. |
| set_field_appearance(field_name, flags) | Define flags do campo |
| get_field_appearance(field_name) | Obtém flags do campo. |
| set_submit_flag(field_name, submit_form_flag) | Define a flag de envio do botão de envio. |
| set_submit_url(field_name, url) | Define a URL do botão. |
| set_field_limit(field_name, field_limit) | Define o número máximo de caracteres do campo de texto. |
| set_field_comb_number(field_name, comb_number) | Define o número de divisões (combs) para um campo de texto de linha única regular (o campo é <br/>            automaticamente dividido em tantas posições igualmente espaçadas, ou divisões, <br/>            quanto ao valor do parâmetro combNumber). |
| move_field(field_name, llx, lly, urx, ury) | Define nova posição do campo. |
| remove_field(field_name) | Remove o campo do formulário. |
| reset_facade() | Redefina todos os atributos visuais para valor vazio. |
| reset_inner_facade() | Redefina todos os atributos visuais da fachada interna para valor vazio. |
| rename_field(field_name, new_field_name) | Altere o nome do campo. |
| remove_field_action(field_name) | Remova a ação de envio do campo. |
| add_submit_btn(field_name, page, label, url, llx, lly, urx, ury) | Adicione um botão de envio no formulário. |
| del_list_item(field_name, item_name) | Exclua o item do campo de lista. |
| set_field_script(field_name, script) | Defina JavaScript para um campo PushButton. Se houver JavaScript antigo, ele será substituído pelo novo. |
| add_field_script(field_name, script) | Adicione JavaScript para um campo PushButton. Se existir evento antigo, o novo evento será adicionado após ele. |
| single_2_multiple(field_name) | Altere um campo de texto de linha única para um de múltiplas linhas. |
| set_field_alignment(field_name, alignment) | Defina o estilo de alinhamento de um campo de texto. |
| set_field_alignment_v(field_name, alignment) | Defina o estilo de alinhamento vertical de um campo de texto. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

