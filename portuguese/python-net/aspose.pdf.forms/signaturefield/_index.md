---
title: "SignatureField"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa o campo de formulário de assinatura."
type: docs
weight: 270
url: /pt/python-net/aspose.pdf.forms/signaturefield/
---

## SignatureField class

Representa o campo de formulário de assinatura.

O tipo SignatureField expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| SignatureField(page, rect) | Inicializa uma nova instância da classe SignatureField |
| SignatureField(doc, rect) | Inicializa uma nova instância da classe SignatureField |
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
| signature | Obtém o objeto de assinatura.<br/>            Este objeto contém dados de assinatura referentes a padrões criptográficos de chave pública.<br/>            Classes [PKCS1](/pdf/python-net/aspose.pdf.forms/pkcs1/), [PKCS7](/pdf/python-net/aspose.pdf.forms/pkcs7/) e [PKCS7Detached](/pdf/python-net/aspose.pdf.forms/pkcs7detached/) <br/>            representam todos os tipos suportados de objetos de assinatura. |
## Indexer
| Nome | Descrição |
| :- | :- |
| [index] | Obtém o subcampo contido neste campo por índice. |
## Métodos
| Nome | Descrição |
| :- | :- |
| sign(signature, pfx, pass) | Assina o documento usando este campo de assinatura. |
| sign(signature) | Assina o documento usando este campo de assinatura. |
| extract_image() | Extrai a imagem da assinatura como fluxo codificado em jpeg. |
| extract_image(format) | Extrai a imagem da assinatura como fluxo codificado. |
| clone() | Nenhum |
| get_rectangle(consider_rotation) | Nenhum |
| accept(visitor) | Aceita o visitante. |
| flatten() | Remove este campo e coloca seu valor diretamente na página. |
| change_after_resize(transform) | Nenhum |
| recalculate() | Recalcula todos os campos calculados no formulário. |
| copy_to(array, index) | Copia os subcampos deste campo para o array a partir do índice especificado. |
| set_position(point) | Define a posição do campo. |
| extract_certificate() | Extrai o único certificado X.509 no formato DER como um fluxo. |

### Veja Também

* namespace [aspose.pdf.forms](/pdf/python-net/aspose.pdf.forms/)
* assembly [Aspose.PDF](/pdf/python-net/)

