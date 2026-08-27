---
title: "PdfAnnotationEditor"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma classe para trabalhar com anotações (comentários) de documentos PDF."
type: docs
weight: 170
url: /pt/python-net/aspose.pdf.facades/pdfannotationeditor/
---

## PdfAnnotationEditor class

Representa uma classe para trabalhar com anotações (comentários) de documentos PDF.

O tipo PdfAnnotationEditor expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfAnnotationEditor() | Inicializa um novo objeto [PdfAnnotationEditor](/pdf/python-net/aspose.pdf.facades/pdfannotationeditor/). |
| PdfAnnotationEditor(document) | Inicializa uma nova instância da classe PdfAnnotationEditor |
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
| import_annotations_from_xfdf(xfdf_file) | Importa todas as anotações do arquivo XFDF. |
| import_annotations_from_xfdf(xfdf_stream) | Importa todas as anotações do fluxo de dados XFDF. |
| import_annotation_from_xfdf(xfdf_file) | Importa todas as anotações do arquivo XFDF. |
| import_annotation_from_xfdf(xfdf_file, annot_type) | Importa as anotações especificadas do arquivo XFDF. |
| import_annotation_from_xfdf(xfdf_stream, annot_type) | Importa as anotações especificadas do fluxo de dados XFDF. |
| import_annotation_from_xfdf(xfdf_stream) | Importa as anotações especificadas do fluxo de dados XFDF. |
| import_annotations(annot_file, annot_type) | Importa as anotações especificadas para o documento a partir de um conjunto de outros documentos PDF. |
| import_annotations(annot_file) | Importa as anotações especificadas para o documento a partir de um conjunto de outros documentos PDF. |
| import_annotations(annot_file_stream, annot_type) | Importa as anotações especificadas para o documento a partir de um array de fluxos de outro documento PDF. |
| import_annotations(annot_file_stream) | Importa as anotações especificadas para o documento a partir de um array de fluxos de outro documento PDF. |
| flattening_annotations() | Aplana todas as anotações no documento. |
| flattening_annotations(flatten_settings) | Aplana todas as anotações no documento. |
| flattening_annotations(start, end, annot_type) | Aplana as anotações dos tipos especificados. |
| delete_annotations() | Exclui todas as anotações no documento. |
| delete_annotations(annot_type) | Exclui todas as anotações do tipo especificado no documento. |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Exporta o conteúdo dos tipos de anotação especificados para XFDF |
| export_annotations_xfdf(xml_output_stream, start, end, annot_types) | Exporta o conteúdo dos tipos de anotações especificados para XFDF |
| extract_annotations(start, end, annot_types) | Obtém a lista de anotações dos tipos especificados. |
| extract_annotations(start, end, annot_types) | Obtém a lista de anotações dos tipos especificados. |
| close() | Libera quaisquer recursos associados à fachada atual. |
| modify_annotations_author(start, end, src_author, des_author) | Modifica o autor das anotações no intervalo de páginas especificado. |
| delete_annotation(annot_name) | Exclui todas as anotações do tipo especificado no documento. |
| export_annotations_to_xfdf(xml_output_stream) | Exporta anotações para o fluxo. |
| modify_annotations(start, end, annotation) | Modifica as anotações do tipo especificado no intervalo de páginas especificado.<br/>            Ele suporta a modificação das seguintes propriedades da anotação: Modified, Title, Contents, Color, Subject e Open. |
| redact_area(page_index, rect, color) | Redige a área na página especificada. Todo o conteúdo é removido. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

