---
title: "PdfFileInfo"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma classe para acessar metainformações de documentos PDF."
type: docs
weight: 270
url: /pt/python-net/aspose.pdf.facades/pdffileinfo/
---

## PdfFileInfo class

Representa uma classe para acessar metainformações de documentos PDF.

O tipo PdfFileInfo expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfFileInfo() | Inicializa uma nova instância da classe Aspose.Pdf.Facades.PdfFileInfo com valores padrão. |
| PdfFileInfo(input_stream) | Inicializa uma nova instância da classe PdfFileInfo |
| PdfFileInfo(input_stream, password) | Inicializa uma nova instância da classe PdfFileInfo |
| PdfFileInfo(input_file) | Inicializa uma nova instância da classe PdfFileInfo |
| PdfFileInfo(input_file, password) | Inicializa uma nova instância da classe PdfFileInfo |
| PdfFileInfo(document) | Inicializa uma nova instância da classe PdfFileInfo |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| author | Obtém ou define a informação de Autor do documento PDF. |
| is_encrypted | Verifica se o documento PDF está criptografado. |
| is_pdf_file | Verifica se a entrada de origem é um arquivo PDF válido. |
| use_strict_validation | Usa regras de validação estritas através da propriedade [is_pdf_file](/pdf/python-net/aspose.pdf.facades/pdffileinfo/). |
| creation_date | Obtém ou define a informação de CreationDate do documento PDF. |
| creator | Obtém ou define a informação de Creator do documento PDF. |
| has_collection | Retorna true se o arquivo de entrada atual for um arquivo 'Portfolio' contendo uma coleção de arquivos PDF. |
| input_file | Obtém ou define o arquivo de entrada. |
| input_stream | Obtém ou define o fluxo de entrada. |
| keywords | Obtém ou define as informações de Keywords do documento PDF. |
| mod_date | Obtém ou define a informação de data ModDate do documento PDF. |
| number_of_pages | Obtém o número de páginas do documento. |
| producer | Obtém as informações de Producer do documento PDF. |
| subject | Obtém ou define as informações de Subject do documento PDF. |
| title | Obtém ou define as informações de Title do documento PDF. |
| password_type | Retorna o tipo de senha que foi passado ao criar a instância PdfFileInfo. Veja os valores possíveis em [password_type](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Observe que o documento PDF pode ser aberto usando tanto a senha de usuário (ou de abertura) quanto a senha de proprietário (ou de permissões, edição). |
| has_open_password | Retorna true se for necessária senha para abrir um documento PDF protegido por senha. |
| has_edit_password | Retorna true se for necessária senha para modificar permissões ou a propriedade de segurança do documento.<br/>            Observe que esta propriedade só pode ser lida se uma senha válida for fornecida no construtor [PdfFileInfo](/pdf/python-net/aspose.pdf.facades/pdffileinfo/).<br/>            Caso PasswordType seja Inaccessible (significa que uma senha inválida foi fornecida) a leitura desta propriedade falhará com [InvalidPasswordException](/pdf/python-net/aspose.pdf/invalidpasswordexception/). |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(src_doc) | Inicializa a fachada. |
| bind_pdf(src_file) | Inicializa a fachada. |
| bind_pdf(src_stream) | Inicializa a fachada. |
| save(dest_stream) | Salva o documento PDF atualizado no fluxo especificado. |
| save(dest_file) | Salva o documento PDF atualizado no arquivo especificado. |
| save_new_info(output_stream) | Salva o documento PDF atualizado no fluxo especificado. |
| save_new_info(output_file) | Salva o documento PDF atualizado no arquivo especificado. |
| close() | Desinicializa a instância. |
| clear_info() | Limpa todas as metainformações do documento PDF. |
| get_document_privilege() | Obtém as configurações de privilégios do documento PDF. |
| get_meta_info(name) | Obtém informações personalizadas do documento PDF com o nome da propriedade. Se não houver nenhuma propriedade que corresponda ao nome, retornará uma string vazia. |
| get_page_height(page_num) | Obtém a altura da página especificada. |
| get_page_rotation(page_num) | Obtém a rotação da página especificada. |
| get_page_width(page_num) | Obtém a largura da página especificada. |
| get_page_x_offset(page_num) | Obtém o deslocamento horizontal da área de exibição da página especificada. |
| get_page_y_offset(page_num) | Obtém o deslocamento vertical da área de exibição da página especificada. |
| get_pdf_version() | Obtém as informações de versão do documento PDF. |
| set_meta_info(name, value) | Define informações personalizadas do documento PDF. |
| save_new_info_with_xmp(output_file_name) | Altera as propriedades especificadas explicitamente ao definir informações do arquivo, as demais propriedades permanecem. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

