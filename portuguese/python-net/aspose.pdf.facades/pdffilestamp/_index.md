---
title: "PdfFileStamp"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe para adicionar carimbos (marca d'água ou plano de fundo) a arquivos PDF."
type: docs
weight: 320
url: /pt/python-net/aspose.pdf.facades/pdffilestamp/
---

## PdfFileStamp class

Classe para adicionar carimbos (marca d'água ou plano de fundo) a arquivos PDF.

O tipo PdfFileStamp expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfFileStamp(input_file, output_file) | Inicializa uma nova instância da classe PdfFileStamp |
| PdfFileStamp(input_stream, output_stream) | Inicializa uma nova instância da classe PdfFileStamp |
| PdfFileStamp(input_file, output_file, keep_security) | Inicializa uma nova instância da classe PdfFileStamp |
| PdfFileStamp(input_stream, output_stream, keep_security) | Inicializa uma nova instância da classe PdfFileStamp |
| PdfFileStamp() | Construtor do PdfFileStamp.<br/>            O arquivo de entrada e o arquivo de saída podem ser especificados via propriedades correspondentes. |
| PdfFileStamp(document) | Inicializa uma nova instância da classe PdfFileStamp |
| PdfFileStamp(document, output_file) | Inicializa uma nova instância da classe PdfFileStamp |
| PdfFileStamp(document, output_stream) | Inicializa uma nova instância da classe PdfFileStamp |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| optimize_size | Obtém ou define a bandeira de otimização. Fluxos de recursos iguais no arquivo resultante são mesclados em um único objeto PDF se esta bandeira estiver definida. <br/>            Isso permite diminuir o tamanho do arquivo resultante, mas pode causar execução mais lenta e maiores requisitos de memória.<br/>            Valor padrão: false. |
| keep_security | Mantém a segurança se verdadeiro. (Este recurso será implementado nas próximas versões). |
| input_file | Obtém ou define o nome e o caminho do arquivo de entrada. |
| input_stream | Obtém ou define o fluxo de entrada. |
| output_file | Obtém ou define o nome e o caminho do arquivo de saída. |
| output_stream | Obtém ou define o fluxo de saída. |
| page_number_rotation | Obtém ou define a rotação do número da página. A rotação está em graus. O padrão é 0. |
| page_height | Obtém a altura da primeira página no arquivo de origem. |
| page_width | Obtém a largura da primeira página no arquivo de entrada. |
| starting_number | Obtém ou define o número inicial para a primeira página no arquivo de entrada. As páginas subsequentes serão numeradas a partir deste valor. <br/>            Por exemplo, se StartingNumber for definido como 100, as páginas do documento terão os números 100, 101, 102... |
| numbering_style | Obtém ou define o estilo de numeração de página. Valores possíveis: NumeralsArabic, NumeralsRomanUppercase, NumeralsRomanLowercase, LettersAppercase, LettersLowercase |
| stamp_id | ID do carimbo do próximo carimbo adicionado (incluindo cabeçalhos/rodapés de página/números de página). |
| POS_BOTTOM_MIDDLE | Posição inferior central. |
| POS_BOTTOM_RIGHT | Posição inferior direita. |
| POS_UPPER_RIGHT | Posição superior direita. |
| POS_SIDES_RIGHT | Posição direita. |
| POS_UPPER_MIDDLE | Posição superior central. |
| POS_BOTTOM_LEFT | Posição inferior esquerda. |
| POS_SIDES_LEFT | Posição esquerda. |
| POS_UPPER_LEFT | Posição superior esquerda. |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(src_file) | Vincula o documento PDF para edição. |
| bind_pdf(src_stream) | Vincula o documento PDF para edição. |
| bind_pdf(src_doc) | Vincula o documento PDF para edição. |
| save(dest_file) | Salva o resultado no arquivo especificado. |
| save(dest_stream) | Salva o documento no fluxo especificado. |
| add_page_number(format_string) | Adiciona número de página ao arquivo. O texto do número de página pode conter o sinal # que será substituído pelo número da página. <br/>            O número de página é colocado na parte inferior da página, centralizado horizontalmente. |
| add_page_number(formatted_text) | Adiciona número de página à página. O número de página pode conter o sinal # que será substituído pelo número da página.<br/>            O número de página é colocado na parte inferior da página, centralizado horizontalmente. |
| add_page_number(format_string, position, left_margin, right_margin, top_margin, bottom_margin) | Adiciona número de página às páginas do documento. |
| add_page_number(format_string, x, y) | Adiciona número de página às páginas do documento. |
| add_page_number(formatted_text, position, left_margin, right_margin, top_margin, bottom_margin) | Adiciona número de página às páginas do documento. |
| add_page_number(formatted_text, x, y) | Adiciona número de página às páginas do documento. |
| add_page_number(format_string, position) | Adiciona número de página às páginas do documento. |
| add_page_number(formatted_text, position) | Adiciona número de página às páginas do documento. |
| add_header(formatted_text, top_margin) | Adiciona cabeçalho à página. |
| add_header(formatted_text, top_margin, left_margin, right_margin) | Adiciona cabeçalho à página. |
| add_header(image_file, top_margin) | Adiciona imagem como cabeçalho às páginas do arquivo. |
| add_header(image_file, top_margin, left_margin, right_margin) | Adiciona imagem como cabeçalho às páginas do arquivo. |
| add_header(image_stream, top_margin) | Adiciona imagem como cabeçalho nas páginas. |
| add_header(input_stream, top_margin, left_margin, right_margin) | Adiciona imagem como cabeçalho nas páginas. |
| add_footer(formatted_text, bottom_margin) | Adiciona rodapé às páginas do documento. |
| add_footer(formatted_text, bottom_margin, left_margin, right_margin) | Adiciona rodapé às páginas do documento. |
| add_footer(image_file, bottom_margin) | Adiciona imagem como rodapé às páginas do documento. |
| add_footer(image_file, bottom_margin, left_margin, right_margin) | Adiciona imagem como rodapé às páginas do documento. |
| add_footer(image_stream, bottom_margin) | Adiciona imagem como rodapé da página. |
| add_footer(image_stream, bottom_margin, left_margin, right_margin) | Adiciona imagem como rodapé da página. |
| close() | Fecha arquivos abertos e salva alterações. <br/>            Aviso. Se fluxos de entrada ou saída forem especificados, eles não são fechados pelo método Close(). |
| add_stamp(stamp) | Adiciona selo ao arquivo. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

