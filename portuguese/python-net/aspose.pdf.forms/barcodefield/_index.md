---
title: "BarcodeField"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe representa campo de código de barras."
type: docs
weight: 10
url: /pt/python-net/aspose.pdf.forms/barcodefield/
---

## BarcodeField class

Classe representa campo de código de barras.

O tipo BarcodeField expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| BarcodeField(page, rect) | Inicializa uma nova instância da classe BarcodeField |
| BarcodeField(doc, rect) | Inicializa uma nova instância da classe BarcodeField |
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
| multiline | Obtém ou define a bandeira multiline do campo. Se Multiline for verdadeiro, o campo pode conter várias linhas de texto. |
| spell_check | Obtém ou define a bandeira de correção ortográfica para o campo. Se verdadeiro, o campo será verificado ortograficamente. |
| scrollable | Obtém ou define a bandeira rolável do campo. Se verdadeiro, o campo pode ser rolado. |
| force_combs | Obtém ou define a bandeira que indica se o campo está dividido em posições espaçadas. |
| max_len | Obtém ou define o comprimento máximo do texto no campo. |
| text_vertical_alignment | Obtém ou define o alinhamento vertical do texto para a anotação. |
| resolution | Obtém a resolução, em pontos por polegada (dpi), na qual o objeto de código de barras é renderizado. |
| caption | Obtém a legenda do objeto de código de barras. |
| symbology | Especifica qual tecnologia de código de barras ou glifo deve ser usada nesta anotação,<br/>            veja [symbology](/pdf/python-net/aspose.pdf.forms/barcodefield/) para detalhes. |
| x_sym_width | Obtém a distância horizontal, em pixels, entre dois módulos de código de barras. |
| x_sym_height | Obtém a distância vertical entre dois módulos de código de barras, medida em pixels. <br/>            A proporção XSymHeight/XSymWidth deve ser um valor inteiro. <br/>            Para PDF417, a faixa de proporção aceitável é de 1 a 4. Para QRCode e DataMatrix, <br/>            esta proporção deve ser sempre 1 |
| ecc | Obtém um valor inteiro que representa o coeficiente de correção de erro. <br/>            Para PDF417, deve ser de 0 a 8. Para QRCode, deve ser de 0 a 3 <br/>            (0 para �L�, 1 para �M�, 2 para �Q� e 3 para �H�). |
## Indexer
| Nome | Descrição |
| :- | :- |
| [index] | Obtém o subcampo contido neste campo por índice. |
## Métodos
| Nome | Descrição |
| :- | :- |
| clone() | Nenhum |
| get_rectangle(consider_rotation) | Nenhum |
| accept(visitor) | Nenhum |
| flatten() | Remove este campo e coloca seu valor diretamente na página. |
| change_after_resize(transform) | Nenhum |
| recalculate() | Recalcula todos os campos calculados no formulário. |
| copy_to(array, index) | Copia os subcampos deste campo para o array a partir do índice especificado. |
| set_position(point) | Define a posição do campo. |
| add_image(image) | Adiciona a imagem aos recursos do campo e a desenha. |
| add_barcode(code) | Adiciona o código de barras 128 ao campo. <br/>            O valor do campo será alterado para o código e o campo se tornará somente leitura. |

### Veja Também

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

