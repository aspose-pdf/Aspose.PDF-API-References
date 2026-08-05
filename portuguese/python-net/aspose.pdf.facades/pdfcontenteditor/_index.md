---
title: "PdfContentEditor"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma classe para editar o conteúdo de arquivos PDF."
type: docs
weight: 190
url: /pt/python-net/aspose.pdf.facades/pdfcontenteditor/
---

## PdfContentEditor class

Representa uma classe para editar o conteúdo de arquivos PDF.

O tipo PdfContentEditor expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfContentEditor() | O construtor do objeto PdfContentEditor. |
| PdfContentEditor(document) | Inicializa uma nova instância da classe PdfContentEditor |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| text_search_options | Obtém ou define as opções de pesquisa de texto. |
| text_edit_options | Obtém ou define as opções de edição de texto. |
| text_replace_options | Obtém ou define as opções de substituição de texto. |
| replace_text_strategy | Um conjunto de parâmetros para a operação de substituição de texto |
| DOCUMENT_OPEN | Um tipo de evento de documento. Abre um documento. |
| DOCUMENT_CLOSE | Um tipo de evento de documento. Fecha um documento. |
| DOCUMENT_WILL_SAVE | Um tipo de evento de documento. Executa uma ação antes de salvar. |
| DOCUMENT_SAVED | Um tipo de evento de documento. Executa uma ação após salvar. |
| DOCUMENT_WILL_PRINT | Um tipo de evento de documento. Executa uma ação antes de imprimir. |
| DOCUMENT_PRINTED | Um tipo de evento de documento. Execute uma ação após a impressão. |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(input_file) | Vincula um arquivo PDF para edição. |
| bind_pdf(input_stream) | Vincula um fluxo PDF para edição. |
| bind_pdf(src_doc) | Vincula o documento PDF para edição. |
| save(dest_file) | Salva o documento PDF no arquivo especificado. |
| save(dest_stream) | Salva o documento PDF no fluxo especificado. |
| create_web_link(rect, url, original_page, clr) | Cria um link da web no documento PDF. |
| create_web_link(rect, url, original_page) | Cria um link da web no documento PDF. |
| create_local_link(rect, des_page, original_page, clr) | Cria um link local no documento PDF. |
| create_local_link(rect, des_page, original_page) | Cria um link local no documento PDF. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page, clr) | Cria um link para outra página de documento PDF. |
| create_pdf_document_link(rect, remote_pdf, original_page, destination_page) | Cria um link para outra página de documento PDF. |
| create_application_link(rect, application, page, clr) | Cria um link para iniciar um aplicativo no documento PDF. |
| create_application_link(rect, application, page) | Cria um link para iniciar um aplicativo no documento PDF. |
| create_file_attachment(rect, contents, file_path, page, name) | Cria anotação de anexo de arquivo. |
| create_file_attachment(rect, contents, file_path, page, name, opacity) | Cria anotação de anexo de arquivo. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name) | Cria anotação de anexo de arquivo. |
| create_file_attachment(rect, contents, attachment_stream, attachment_name, page, name, opacity) | Cria anotação de anexo de arquivo. |
| add_document_attachment(file_attachment_path, description) | Adiciona anexo de documento sem anotação. |
| add_document_attachment(file_attachment_stream, file_attachment_name, description) | Adiciona anexo de documento sem anotação. |
| create_rubber_stamp(page, annot_rect, icon, annot_contents, color) | Cria uma anotação de selo de borracha. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_file) | Cria uma anotação de selo de borracha. |
| create_rubber_stamp(page, annot_rect, annot_contents, color, appearance_stream) | Cria uma anotação de selo de borracha. |
| delete_image(page_number, index) | Exclui as imagens especificadas na página especificada. |
| delete_image() | Exclui as imagens especificadas na página especificada. |
| replace_text(src_string, the_page, dest_string, text_state) | Substitui texto no arquivo PDF na página especificada. O objeto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (família de fontes, cor) pode ser especificado para o texto a ser substituído. |
| replace_text(src_string, dest_string) | Substitui texto no arquivo PDF na página especificada. O objeto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (família de fontes, cor) pode ser especificado para o texto a ser substituído. |
| replace_text(src_string, the_page, dest_string) | Substitui texto no arquivo PDF na página especificada. O objeto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (família de fontes, cor) pode ser especificado para o texto a ser substituído. |
| replace_text(src_string, dest_string, text_state) | Substitui texto no arquivo PDF na página especificada. O objeto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (família de fontes, cor) pode ser especificado para o texto a ser substituído. |
| replace_text(src_string, dest_string, font_size) | Substitui texto no arquivo PDF na página especificada. O objeto [TextState](/pdf/python-net/aspose.pdf.text/textstate/) (família de fontes, cor) pode ser especificado para o texto a ser substituído. |
| delete_stamp_by_ids(stamp_ids) | Exclui carimbos com IDs especificados de todas as páginas do documento. |
| delete_stamp_by_ids(page_number, stamp_ids) | Exclui carimbos com IDs especificados de todas as páginas do documento. |
| delete_stamp_by_id(page_number, stamp_id) | Exclui carimbos com IDs especificados de todas as páginas do documento. |
| delete_stamp_by_id(stamp_id) | Exclui carimbos com IDs especificados de todas as páginas do documento. |
| close() | Fecha o documento aberto. |
| extract_link() | Extrai a coleção de instâncias de Link contidas no documento PDF. |
| create_java_script_link(code, rect, original_page, color) | Cria um link para JavaScript no documento PDF. |
| create_text(rect, title, contents, open, icon, page) | Cria anotação de texto no documento PDF |
| create_free_text(rect, contents, page) | Cria anotação de texto livre no documento PDF |
| create_markup(rect, contents, type, page, clr) | Cria anotação de marcação no documento PDF. |
| create_popup(rect, contents, open, page) | Cria anotação popup no documento PDF. |
| delete_attachments() | Exclui todos os anexos no documento PDF. |
| create_line(rect, contents, x1, y1, x2, y2, page, border, clr, border_style, dash_array, le_array) | Cria anotação de linha. |
| create_square_circle(rect, contents, clr, square, page, border_width) | Cria anotação quadrado-círculo. |
| draw_curve(line_info, page, annot_rect, annot_contents) | Cria anotação de curva. |
| create_polygon(line_info, page, annot_rect, annot_contents) | Cria anotação de polígono. |
| create_poly_line(line_info, page, annot_rect, annot_contents) | Cria anotação de polilinha. |
| create_caret(page, annot_rect, caret_rect, symbol, annot_contents, color) | Cria anotação de cursor. |
| create_bookmarks_action(title, color, bold_flag, italic_flag, file, action_type, destination) | Cria um marcador com a ação especificada. |
| add_document_additional_action(event_type, code) | Adiciona ação adicional para evento de documento. |
| remove_document_open_action() | Remove a ação de abertura do documento. Esta operação é útil ao concatenar vários documentos que utilizam ação 'GoTo' explícita na inicialização. |
| change_viewer_preference(viewer_attribution) | Altera a preferência de visualização. |
| get_viewer_preference() | Retorna a preferência de visualização. |
| replace_image(page_number, index, image_file) | Substitui a imagem especificada na página especificada do documento PDF por outra imagem. |
| create_movie(rect, file_path, page) | Cria anotações de filme. |
| create_sound(rect, file_path, name, page, rate) | Cria anotações de som. |
| delete_stamp(page_number, index) | Exclui vários selos na página especificada pelos índices dos selos. |
| hide_stamp_by_id(page_number, stamp_id) | Oculta o selo. Após ocultar, a visibilidade do selo pode ser restaurada com o método ShowStampById. |
| show_stamp_by_id(page_number, stamp_id) | Mostra o selo que foi ocultado por HiddenStampById. |
| move_stamp_by_id(page_number, stamp_id, x, y) | Altera a posição do selo na página. |
| move_stamp(page_number, stamp_index, x, y) | Altera a posição do selo na página. |
| get_stamps(page_number) | Retorna um array de selos na página. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

