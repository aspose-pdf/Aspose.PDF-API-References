---
title: "PdfFileMend"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma classe para adicionar textos e imagens nas páginas de um documento PDF existente."
type: docs
weight: 280
url: /pt/python-net/aspose.pdf.facades/pdffilemend/
---

## PdfFileMend class

Representa uma classe para adicionar textos e imagens nas páginas de um documento PDF existente.

O tipo PdfFileMend expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfFileMend() | Construtor. |
| PdfFileMend(input_file_name, output_file_name) | Inicializa uma nova instância da classe PdfFileMend |
| PdfFileMend(input_stream, output_stream) | Inicializa uma nova instância da classe PdfFileMend |
| PdfFileMend(document) | Inicializa uma nova instância da classe PdfFileMend |
| PdfFileMend(document, output_file_name) | Inicializa uma nova instância da classe PdfFileMend |
| PdfFileMend(document, dest_stream) | Inicializa uma nova instância da classe PdfFileMend |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| input_stream | Define o fluxo de entrada. |
| output_stream | Define o fluxo de saída. |
| input_file | Define o arquivo de entrada. |
| output_file | Define o arquivo de saída. |
| wrap_mode | Define ou obtém o algoritmo de quebra de linha. Veja WordWrapMode e IsWordWrap. |
| text_positioning_mode | Define ou obtém a estratégia de posicionamento de texto. [PositioningMode](/pdf/python-net/aspose.pdf.facades/positioningmode/)<br/>            O modo padrão é Legacy. |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(src_file) | Vincula o documento PDF para edição. |
| bind_pdf(src_stream) | Vincula o documento PDF para edição. |
| bind_pdf(src_doc) | Vincula o documento PDF para edição. |
| save(dest_file) | Salva o documento PDF no arquivo especificado. |
| save(dest_stream) | Salva o documento PDF no fluxo especificado. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Adiciona a imagem à página especificada do documento PDF nas coordenadas especificadas. |
| add_image(image_stream, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Adiciona a imagem à página especificada do documento PDF nas coordenadas especificadas. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Adiciona a imagem às páginas especificadas do documento PDF nas coordenadas especificadas. |
| add_image(image_stream, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Adiciona a imagem às páginas especificadas do documento PDF nas coordenadas especificadas. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Adiciona a imagem à página especificada do documento PDF nas coordenadas especificadas. |
| add_image(image_name, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Adiciona a imagem à página especificada do documento PDF nas coordenadas especificadas. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Adiciona a imagem às páginas especificadas do documento PDF nas coordenadas especificadas. |
| add_image(image_name, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y, compositing_parameters) | Adiciona a imagem às páginas especificadas do documento PDF nas coordenadas especificadas. |
| add_text(text, page_num, lower_left_x, lower_left_y) | Não implementado. |
| add_text(text, page_num, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Não implementado. |
| add_text(text, page_nums, lower_left_x, lower_left_y, upper_right_x, upper_right_y) | Não implementado. |
| close() | Fecha o objeto PdfFileMend. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

