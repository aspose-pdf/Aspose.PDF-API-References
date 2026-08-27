---
title: "PdfViewer"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma classe para visualizar ou imprimir um pdf."
type: docs
weight: 370
url: /pt/python-net/aspose.pdf.facades/pdfviewer/
---

## PdfViewer class

Representa uma classe para visualizar ou imprimir um pdf.

O tipo PdfViewer expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfViewer() | Inicializa um novo objeto [PdfViewer](/pdf/python-net/aspose.pdf.facades/pdfviewer/). |
| PdfViewer(document) | Inicializa uma nova instância da classe PdfViewer |
## Propriedades
| Nome | Descrição |
| :- | :- |
| show_hidden_areas | Obtém ou define o indicador que controla a visibilidade das áreas ocultas na página. |
| print_status | Obtém o resultado da tarefa de impressão. Se for bem-sucedido, retorna null; caso contrário, objeto de exceção. |
| use_intermidiate_image | Obtém/define o uso da conversão da página PDF em arquivo PNG intermidiate durante a impressão no modo de arquivo. Use isso quando o tamanho do arquivo de saída for importante. |
| coordinate_type | Obtém ou define o tipo de coordenada da página (caixas Media/Crop). O valor CropBox é usado por padrão. |
| print_as_image | Define ou obtém um modo para o PdfViewer imprimir como imagem. |
| page_count | Obtém a contagem de páginas do arquivo PDF atual. |
| password | Obtém ou define a senha do documento de entrada. |
| print_page_dialog | Obtém ou define um valor booleano que indica se produz o diálogo de número de página ao imprimir. |
| print_as_grayscale | Obtém ou define um valor booleano que indica se a página está sendo impressa em escala de cinza. Por padrão, é false. |
| printer_job_name | Obtém ou define o nome do documento na fila da impressora quando o documento é impresso. O valor padrão é o nome do arquivo. |
| form_presentation_mode | Obtém ou define o modo de apresentação do formulário. |
| rendering_options | Obtém ou define as opções de renderização. |
| vertical_alignment | Obtém ou define um valor que indica o alinhamento vertical |
| horizontal_alignment | Obtém ou define um valor que indica o alinhamento horizontal |
| auto_resize | Obtém ou define um valor booleano que indica se o arquivo será impresso com tamanho otimizado. |
| auto_rotate | Obtém ou define um valor booleano que indica se o arquivo será impresso com rotação automática |
| auto_rotate_mode | Obtém ou define um valor AutoRotateMode que indica a direção da rotação |
| resolution | Obtém ou define a resolução durante a visualização e impressão. Quanto maior a resolução, mais lenta a velocidade. O valor padrão é 150. |
| scale_factor | Obtém ou define um valor de ponto flutuante que indica o fator de escala. O valor padrão é 1.0. |
## Métodos
| Nome | Descrição |
| :- | :- |
| print_large_pdf(file_path) | Abre e imprime um arquivo Pdf grande. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é <br/>             mais de 3 MB, este método é recomendado para obter melhor desempenho. |
| print_large_pdf(input_stream) | Abre e imprime um fluxo Pdf grande. Se o seu arquivo Pdf tem centenas de páginas ou mais ou seu tamanho é <br/>             mais de 3 MB, este método é recomendado para obter melhor desempenho. |
| print_large_pdf(file_path, printer_settings) | Abre e imprime um arquivo Pdf grande com as configurações de impressora especificadas. Se o seu arquivo Pdf tem centenas <br/>             de páginas ou mais ou seu tamanho é mais de 3 MB, este método é recomendado para obter melhor desempenho. |
| print_large_pdf(input_stream, printer_settings) | Abre e imprime um fluxo Pdf grande com as configurações de impressora especificadas. Se o seu arquivo Pdf tem centenas <br/>             de páginas ou mais ou seu tamanho é mais de 3 MB, este método é recomendado para obter melhor desempenho. |
| print_large_pdf(file_path, page_settings, printer_settings) | Abre e imprime um arquivo Pdf grande com as configurações de página e de impressora especificadas. Se o seu Pdf <br/>             tem centenas de páginas ou mais ou seu tamanho é mais de 3 MB, este método é recomendado para <br/>             obter melhor desempenho. |
| print_large_pdf(input_stream, page_settings, printer_settings) | Abre e imprime um grande fluxo Pdf com configurações de página e de impressora especificadas. Se o seu arquivo Pdf <br/>             tem centenas de páginas ou mais ou seu tamanho é superior a 3 MB, este método é recomendado para <br/>             obter melhor desempenho. |
| print_document_with_settings(page_settings, printer_settings) | Imprime o documento Pdf com configurações. Se o tamanho do documento não for compatível com o tamanho da página, pdf.kit o estenderá para caber no tamanho da página. |
| print_document_with_settings(printer_settings) | Imprime o documento Pdf com configurações. Se o tamanho do documento não for compatível com o tamanho da página, pdf.kit o estenderá para caber no tamanho da página. |
| open_pdf_file(file_path) | Abre um arquivo Pdf, mas não decodifica realmente as páginas do arquivo Pdf. |
| open_pdf_file(input_stream) | Abre um fluxo de arquivo Pdf. Mas não decodifica realmente as páginas do arquivo Pdf. |
| bind_pdf(src_file) | Inicializa a fachada. |
| bind_pdf(src_stream) | Inicializa a fachada. |
| bind_pdf(src_doc) | Inicializa a fachada. |
| save(dest_file) | Salva o documento PDF resultante em um arquivo. |
| save(dest_stream) | Salva o documento PDF resultante em um fluxo. |
| decode_all_pages() | Obtém as páginas do arquivo pdf atual. |
| decode_page(page_number) | Decodifica uma página de um arquivo Pdf. |
| print_document_with_setup() | Imprime o documento Pdf com uma caixa de diálogo de configuração. Escolha uma impressora usando a caixa de diálogo. |
| print_document() | Imprime o documento Pdf com uma caixa de diálogo de configuração. Escolha uma impressora usando a caixa de diálogo. |
| get_default_page_settings() | Obtém as configurações de página padrão. |
| get_default_printer_settings() | Obtém as configurações de impressora padrão. |
| close_pdf_file() | Fecha o arquivo Pdf atual. |
| close() | Fecha o arquivo Pdf atual. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

