---
title: "PdfBookmarkEditor"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma classe para trabalhar com marcadores de arquivos PDF, incluindo criar, modificar, exportar, importar e excluir."
type: docs
weight: 180
url: /pt/python-net/aspose.pdf.facades/pdfbookmarkeditor/
---

## PdfBookmarkEditor class

Representa uma classe para trabalhar com marcadores de arquivos PDF, incluindo criar, modificar, exportar, importar e excluir.

O tipo PdfBookmarkEditor expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfBookmarkEditor() | Inicializa um novo objeto [PdfBookmarkEditor](/pdf/python-net/aspose.pdf.facades/pdfbookmarkeditor/). |
| PdfBookmarkEditor(document) | Inicializa uma nova instância da classe PdfBookmarkEditor |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(src_file) | Vincula o documento PDF para edição. |
| bind_pdf(src_stream) | Vincula o documento PDF para edição. |
| bind_pdf(src_doc) | Vincula o documento PDF para edição. |
| save(dest_file) | Salva o documento PDF no arquivo especificado. |
| save(dest_stream) | Salva o documento PDF no fluxo especificado. |
| create_bookmarks() | Cria marcadores para todas as páginas. |
| create_bookmarks(bookmark) | Cria marcadores para todas as páginas. |
| create_bookmarks(color, bold_flag, italic_flag) | Crie marcadores para todas as páginas com cor e estilo especificados (negrito, itálico). |
| create_bookmark_of_page(bookmark_name, page_number) | Cria marcador para a página especificada. |
| create_bookmark_of_page(bookmark_name, page_number) | Cria marcadores para as páginas especificadas. |
| delete_bookmarks() | Exclui todos os marcadores do documento PDF. |
| delete_bookmarks(title) | Exclui o marcador do documento PDF. |
| extract_bookmarks() | Extrai marcadores de todos os níveis do documento. |
| extract_bookmarks(upper_level) | Extrai marcadores de todos os níveis do documento. |
| extract_bookmarks(title) | Extrai os marcadores com o título especificado. |
| extract_bookmarks(bookmark) | Extrai marcadores de todos os níveis do documento. |
| export_bookmarks_to_xml(xml_file) | Exporta marcadores para um arquivo XML. |
| export_bookmarks_to_xml(stream) | Exporta marcadores para um fluxo XML. |
| import_bookmarks_with_xml(xml_file) | Importa marcadores para o documento a partir de um arquivo XML. |
| import_bookmarks_with_xml(stream) | Importa marcadores para o documento a partir de um arquivo XML. |
| close() | Libera quaisquer recursos associados à fachada atual. |
| modify_bookmarks(s_title, d_title) | Modifica o título do marcador de acordo com o título de marcador especificado. |
| extract_bookmarks_to_html(pdf_file, css_file) | Exporta marcadores para um arquivo HTML. |
| export_bookmarks_to_html(in_pdf_file, out_html_file) | Exporta marcadores para um arquivo HTML. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

