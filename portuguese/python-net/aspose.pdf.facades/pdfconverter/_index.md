---
title: "PdfConverter"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma classe para converter cada página de um arquivo pdf em imagens, suportando agora BMP, JPEG, PNG e TIFF.<br/>            Conteúdo suportado em PDFs: imagens, formulários, comentários."
type: docs
weight: 200
url: /pt/python-net/aspose.pdf.facades/pdfconverter/
---

## PdfConverter class

Representa uma classe para converter cada página de um arquivo PDF em imagens, suportando BMP, JPEG, PNG e TIFF atualmente.<br/>            Conteúdo suportado em PDFs: imagens, formulário, comentário.

O tipo PdfConverter expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfConverter() | Inicializa um novo objeto [PdfConverter](/pdf/python-net/aspose.pdf.facades/pdfconverter/). |
| PdfConverter(document) | Inicializa uma nova instância da classe PdfConverter |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| coordinate_type | Obtém ou define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| show_hidden_areas | Obtém ou define o indicador que controla a visibilidade das áreas ocultas na página. |
| rendering_options | Obtém ou define as opções de renderização. |
| form_presentation_mode | Obtém ou define o modo de apresentação do formulário. |
| resolution | Obtém ou define a resolução durante a conversão. Quanto maior a resolução, mais lenta a velocidade de conversão. O valor padrão é 150. |
| start_page | Obtém ou define a posição inicial que você deseja converter. O valor mínimo é 1. |
| end_page | Obtém ou define a posição final que você deseja converter. |
| password | Obtém ou define a OwnerPassword do documento. |
| user_password | Obtém ou define a UserPassword do documento. |
| page_count | Obtém a contagem de páginas. |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(input_file) | Associa um arquivo Pdf para conversão. |
| bind_pdf(input_stream) | Associa um Stream Pdf para conversão. |
| bind_pdf(src_doc) | Inicializa a fachada. |
| save_as_tiff(output_file) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF. |
| save_as_tiff(output_file, compression_type) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF. |
| save_as_tiff(output_file, image_width, image_height) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| save_as_tiff(output_file, page_size) | Converte cada página de um documento pdf em imagens com tamanho de página e salva as imagens em um único arquivo TIFF. |
| save_as_tiff(output_file, page_size, settings) | Converte cada página de um documento pdf em imagens com tamanho de página e salva as imagens em um único arquivo TIFF. |
| save_as_tiff(output_file, image_width, image_height, compression_type) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| save_as_tiff(output_file, image_width, image_height, settings) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| save_as_tiff(output_file, image_width, image_height, settings, converter) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| save_as_tiff(output_stream) | Converte cada página de um documento pdf em imagens e salva as imagens em um único stream TIFF ClassF. |
| save_as_tiff(output_stream, compression_type) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF. |
| save_as_tiff(output_stream, page_size) | Converte cada página de um documento pdf em imagens e salva as imagens em um único stream TIFF ClassF. |
| save_as_tiff(output_stream, page_size, settings) | Converte cada página de um documento pdf em imagens com tamanho de página e salva as imagens em um único fluxo TIFF. |
| save_as_tiff(output_stream, image_width, image_height) | Converte cada página de um documento pdf em imagens e salva as imagens em um único stream TIFF ClassF. |
| save_as_tiff(output_stream, image_width, image_height, compression_type) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único fluxo TIFF. |
| save_as_tiff(output_stream, image_width, image_height, settings) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único fluxo TIFF. |
| save_as_tiff(output_stream, image_width, image_height, settings, converter) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único fluxo TIFF. |
| save_as_tiff(output_file, settings) | Converte cada página de um documento pdf em imagens com tamanho de página e salva as imagens em um único arquivo TIFF. |
| save_as_tiff(output_file, settings, converter) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único arquivo TIFF. |
| save_as_tiff(output_stream, settings) | Converte cada página de um documento pdf em imagens com tamanho de página e salva as imagens em um único fluxo TIFF. |
| save_as_tiff(output_stream, settings, converter) | Converte cada página de um documento pdf em imagens com dimensões e salva as imagens em um único fluxo TIFF. |
| save_as_tiff_class_f(output_file, image_width, image_height) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF. |
| save_as_tiff_class_f(output_file, page_size) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF. |
| save_as_tiff_class_f(output_stream, image_width, image_height) | Converte cada página de um documento pdf em imagens e salva as imagens em um único stream TIFF ClassF. |
| save_as_tiff_class_f(output_stream, page_size) | Converte cada página de um documento pdf em imagens e salva as imagens em um único stream TIFF ClassF. |
| save_as_tiff_class_f(output_file) | Converte cada página de um documento pdf em imagens e salva as imagens em um único arquivo TIFF ClassF. |
| save_as_tiff_class_f(output_stream) | Converte cada página de um documento pdf em imagens e salva as imagens em um único stream TIFF ClassF. |
| get_next_image(output_file) | Salva a imagem em um arquivo com o formato de imagem padrão - jpeg. |
| get_next_image(output_file, page_size) | Salva a imagem em um arquivo com o tamanho de página fornecido e o formato de imagem padrão - jpeg. |
| get_next_image(output_file, format) | Salva a imagem em um arquivo com o formato de imagem fornecido. |
| get_next_image(output_file, page_size, format) | Salva a imagem em um arquivo com o tamanho de página e o formato de imagem fornecidos. |
| get_next_image(output_stream) | Salva a imagem no fluxo com o formato de imagem padrão - jpeg. |
| get_next_image(output_stream, page_size) | Salva a imagem no fluxo com o tamanho de página fornecido. |
| get_next_image(output_stream, format) | Salva a imagem no fluxo com o formato de imagem fornecido. |
| get_next_image(output_stream, page_size, format) | Salva a imagem no fluxo com o tamanho de página fornecido. |
| get_next_image(output_file, format, image_width, image_height, quality) | Salva a imagem no arquivo com o formato de imagem, dimensões e qualidade fornecidos. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Salva a imagem no fluxo com o formato de imagem, dimensões e qualidade fornecidos. |
| get_next_image(output_file, format, image_width, image_height, quality) | Salva a imagem no arquivo com o formato de imagem, tamanho da imagem e qualidade fornecidos. |
| get_next_image(output_stream, format, image_width, image_height, quality) | Salva a imagem no fluxo com o formato de imagem, tamanho e qualidade fornecidos. |
| get_next_image(output_file, format, image_width, image_height) | Salva a imagem no arquivo com o formato de imagem, dimensões e qualidade fornecidos. |
| get_next_image(output_stream, format, image_width, image_height) | Salva a imagem no fluxo com o formato de imagem, dimensões e qualidade fornecidos. |
| get_next_image(output_stream, format, quality) | Salva a imagem no fluxo com o formato de imagem, dimensões e qualidade fornecidos. |
| get_next_image(output_stream, page_size, format, quality) | Salva a imagem no fluxo com o tamanho de página, formato de imagem e qualidade fornecidos. |
| get_next_image(output_file, format, quality) | Salva a imagem no arquivo com o formato de imagem, dimensões e qualidade fornecidos. |
| get_next_image(output_file, page_size, format, quality) | Salva a imagem no arquivo com o tamanho de página, formato de imagem e qualidade fornecidos. |
| close() | Feche a instância de PdfConverter e libere os recursos. |
| do_convert() | Execute alguns trabalhos iniciais para converter um documento pdf em imagens. |
| has_next_image() | Indica se o arquivo pdf tem mais imagens ou não. |
| merge_images(input_images_streams, output_image_format, merge_mode, horizontal, vertical) | Nenhum |
| merge_images_as_tiff(input_images_streams) | Mescla uma lista de fluxos tiff em um único fluxo tiff de múltiplas quadros. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

