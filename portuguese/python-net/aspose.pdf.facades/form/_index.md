---
title: "Form"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe que representa o objeto de formulário Acro."
type: docs
weight: 80
url: /pt/python-net/aspose.pdf.facades/form/
---

## Form class

Classe que representa o objeto de formulário Acro.

O tipo Form expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| Form(src_stream, dest_stream) | Inicializa uma nova instância da classe Form |
| Form() | Construtor do Form sem parâmetros. |
| Form(src_file_name) | Inicializa uma nova instância da classe Form |
| Form(src_stream) | Inicializa uma nova instância da classe Form |
| Form(src_file_name, dest_file_name) | Inicializa uma nova instância da classe Form |
| Form(src_file_name, dest_stream) | Inicializa uma nova instância da classe Form |
| Form(src_stream, dest_file_name) | Inicializa uma nova instância da classe Form |
| Form(document) | Inicializa uma nova instância da classe Form |
| Form(document, dest_file_name) | Inicializa uma nova instância da classe Form |
| Form(document, dest_stream) | Inicializa uma nova instância da classe Form |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| import_result | Resultado da última operação de importação. Array de objetos que descrevem o resultado da importação para cada campo. |
| src_file_name | Obtém ou define o nome do arquivo de origem. |
| dest_file_name | Obtém ou define o nome do arquivo de destino. |
| src_stream | Obtém ou define o fluxo de origem. |
| dest_stream | Obtém ou define o fluxo de destino. |
| field_names | Obtém a lista de nomes de campos no formulário. |
| form_submit_button_names | Obtém todos os nomes dos botões de envio do formulário. |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(src_file) | Vincula o documento PDF para edição. |
| bind_pdf(src_stream) | Vincula o documento PDF para edição. |
| bind_pdf(src_doc) | Vincula o documento PDF para edição. |
| save() | Salva o valor dos campos preenchidos e fecha o documento PDF aberto. |
| save(dest_file) | Salva o documento no arquivo especificado. |
| save(dest_stream) | Salva o documento no fluxo especificado. |
| fill_field(field_name, field_value) | Preenche o campo com um valor válido de acordo com um nome de campo totalmente qualificado.<br/>            Antes de preencher os campos, todos os nomes dos campos e seus respectivos valores válidos devem ser conhecidos.<br/>            Tanto o nome dos campos quanto os valores diferenciam maiúsculas de minúsculas.<br/>            Observe que Aspose.Pdf.Facades suporta apenas nomes de campo completos e não funciona com nomes parciais <br/>            em contraste com Aspose.Pdf.Kit;<br/>            Por exemplo, se o campo tem o nome completo "Form.Subform.TextField" você deve especificar o nome completo e não "TextField". <br/>            Você pode usar a propriedade FieldNames para explorar os nomes de campo existentes e buscar o campo necessário pelo seu nome parcial. |
| fill_field(field_name, index) | Preenche o campo de caixa de seleção (radio box) com um valor de índice válido de acordo com um nome de campo totalmente qualificado.<br/>            Antes de preencher os campos, apenas o nome do campo deve ser conhecido. Enquanto o valor pode ser especificado pelo seu índice.<br/>            Aviso: Aplicável somente a campos Radio Box, Combo Box e List Box.<br/>            Observe que Aspose.Pdf.Facades suporta apenas nomes de campo completos e não funciona com nomes parciais <br/>            em contraste com Aspose.Pdf.Kit;<br/>            Por exemplo, se o campo tem o nome completo "Form.Subform.ListBoxField" você deve especificar o nome completo e não "ListBoxField". <br/>            Você pode usar a propriedade FieldNames para explorar os nomes de campo existentes e buscar o campo necessário pelo seu nome parcial. |
| fill_field(field_name, be_checked) | Preenche o campo de caixa de seleção (check box) com um valor booleano.<br/>            Aviso: Aplicável somente a Check Box.<br/>            Observe que Aspose.Pdf.Facades suporta apenas nomes de campo completos e não funciona com nomes parciais <br/>            em contraste com Aspose.Pdf.Kit;<br/>            Por exemplo, se o campo tem o nome completo "Form.Subform.CheckBoxField" você deve especificar o nome completo e não "CheckBoxField". <br/>            Você pode usar a propriedade FieldNames para explorar os nomes de campo existentes e buscar o campo necessário pelo seu nome parcial. |
| fill_field(field_name, field_values) | Preenche os campos de caixa de texto com valores de texto e salva o documento.<br/>            Relevante para documentos assinados.<br/>            Aviso: Aplicável somente a Text Box.<br/>            Tanto o nome dos campos quanto os valores diferenciam maiúsculas de minúsculas. |
| fill_field(field_name, value, fit_font_size) | Preenche o campo de caixa de seleção (check box) com um valor booleano.<br/>            Aviso: Aplicável somente a Check Box.<br/>            Observe que Aspose.Pdf.Facades suporta apenas nomes de campo completos e não funciona com nomes parciais <br/>            em contraste com Aspose.Pdf.Kit;<br/>            Por exemplo, se o campo tem o nome completo "Form.Subform.CheckBoxField" você deve especificar o nome completo e não "CheckBoxField". <br/>            Você pode usar a propriedade FieldNames para explorar os nomes de campo existentes e buscar o campo necessário pelo seu nome parcial. |
| import_xml(input_xml_stream) | Importa o conteúdo dos campos do arquivo XML e os coloca no novo PDF. |
| import_xml(input_xml_stream, ignore_form_template_changes) | Importa o conteúdo dos campos do arquivo XML e os coloca no novo PDF. |
| fill_image_field(field_name, image_file_name) | Cola uma imagem no campo de botão existente como sua aparência de acordo com <br/>            seu nome de campo totalmente qualificado. |
| fill_image_field(field_name, image_stream) | Sobrecarga da função FillImageField.<br/>            A entrada é um fluxo de imagem. |
| close() | Fecha arquivos abertos sem nenhuma alteração. |
| get_field_facade(field_name) | Retorna o objeto FrohmFieldFacade contendo todos os atributos de aparência. |
| fill_fields(field_names, field_values, output) | Preenche os campos de caixa de texto com valores de texto e salva o documento.<br/>            Relevante para documentos assinados.<br/>            Aviso: Aplicável somente a Text Box.<br/>            Tanto o nome dos campos quanto os valores diferenciam maiúsculas de minúsculas. |
| get_button_option_current_value(field_name) | Retorna o valor atual dos campos de opção de botão de rádio. |
| get_field(field_name) | Retorna o objeto FrohmFieldFacade contendo todos os atributos de aparência. |
| get_full_field_name(field_name) | Obtém o nome completo do campo de acordo com seu nome curto. |
| get_field_limit(field_name) | Obtém a limitação do campo de texto. |
| flatten_all_fields() | Aplainar todos os campos. |
| flatten_field(field_name) | Aplainar um campo especificado com o nome de campo totalmente qualificado.<br/>            Qualquer outro campo permanecerá inalterável. Se o fieldName for inválido, <br/>            todos os campos permanecerão inalteráveis. |
| fill_barcode_field(field_name, data) | Preencher um campo de código de barras de acordo com seu nome de campo totalmente qualificado. |
| import_fdf(input_fdf_stream) | Importa o conteúdo dos campos do arquivo fdf e os coloca no novo pdf. |
| export_fdf(output_fdf_stream) | Exporta o conteúdo dos campos do pdf para o fluxo fdf. |
| export_xml(output_xml_stream) | Exporta o conteúdo dos campos do pdf para o fluxo xml.<br/>            O valor do campo de botão não será exportado. |
| extract_xfa_data(output_xml_stream) | Extrai o pacote de dados XFA |
| set_xfa_data(input_xml_stream) | Substitui os dados XFA pelo pacote de dados especificado. O pacote de dados pode ser extraído usando ExtractXfaData. |
| import_xfdf(input_xfdf_stream) | Importa o conteúdo dos campos do arquivo xfdf(xml) e os coloca no novo PDF. |
| export_xfdf(output_xfdf_stream) | Exporta o conteúdo dos campos do pdf para o fluxo xml.<br/>            O valor do campo de botão não será exportado. |
| rename_field(field_name, new_field_name) | Renomeia um campo. Tanto campo AcroForm quanto campo XFA são aceitos. |
| get_rich_text(field_name) | Obtém o valor de um campo Rich Text, incluindo as informações de formatação de cada caractere. |
| get_submit_flags(field_name) | Retorna as flags de envio do botão de submissão. |
| get_field_type(field_name) | Retorna o tipo do campo. |
| is_required_field(field_name) | Determina se o campo é obrigatório ou não. |
| get_field_flag(field_name) | Retorna as flags do campo. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

