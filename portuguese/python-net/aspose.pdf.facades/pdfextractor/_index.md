---
title: "PdfExtractor"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Classe para extrair imagens e texto de documentos PDF."
type: docs
weight: 210
url: /pt/python-net/aspose.pdf.facades/pdfextractor/
---

## PdfExtractor class

Classe para extrair imagens e texto de documentos PDF.

O tipo PdfExtractor expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfExtractor() | Inicializa um novo objeto [PdfExtractor](/pdf/python-net/aspose.pdf.facades/pdfextractor/). |
| PdfExtractor(document) | Inicializa uma nova instância da classe PdfExtractor |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| start_page | Obtém ou define a página inicial no intervalo de páginas onde a operação de extração será executada. |
| end_page | Obtém ou define a página final no intervalo de páginas onde a operação de extração será executada. |
| extract_text_mode | Define o modo para o resultado da extração de texto. |
| text_search_options | Obtém ou define as opções de pesquisa de texto. |
| extract_image_mode | Define o modo para o processo de extração de imagens. |
| is_bidi | É verdadeiro quando o texto contém símbolos hebraicos ou árabes. Esse caso deve ser considerado especialmente porque<br/>            as funções de string mudam seu comportamento e iniciam o processamento do texto da direita para a esquerda (exceto números <br/>            e outros caracteres não textuais). |
| resolution | Define ou obtém a resolução para imagens extraídas.<br/>            O valor padrão é 150.<br/>            Imagens com resolução maior são mais nítidas.<br/>            No entanto, aumentar o valor da resolução resulta em maior tempo e memória necessários para extrair imagens.<br/>            Geralmente, para obter uma imagem nítida, basta definir a resolução para 150 ou 300. |
| password | Obtém ou define a senha do arquivo de entrada. |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(input_file) | Vincula o arquivo PDF de entrada. |
| bind_pdf(input_stream) | Vincula o documento PDF a partir de um fluxo. |
| bind_pdf(src_doc) | Inicializa a fachada. |
| extract_text() | Extrai texto de um documento PDF usando codificação Unicode. |
| extract_text(encoding) | Extrai texto de um documento PDF usando a codificação especificada. |
| get_text(output_file) | Salva o texto em um arquivo. veja também:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream) | Salva o texto em um fluxo. veja também:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_text(output_stream, filter_not_ascii) | Salva o texto em um fluxo. veja também:[None](/pdf/python-net/aspose.pdf.facades/pdfextractor/) |
| get_next_image(output_file) | Recupera a próxima imagem do documento PDF. Observação: ExtractImage deve ser chamado antes do uso deste método. |
| get_next_image(output_file, format) | Recupera a próxima imagem do documento PDF com o formato de imagem especificado. Observação: ExtractImage deve ser chamado antes do uso deste método. |
| get_next_image(output_stream, format) | Recupera a próxima imagem do arquivo PDF e a armazena em um fluxo com o formato de imagem especificado. |
| get_next_image(output_stream) | Recupera a próxima imagem do arquivo PDF e a armazena em um fluxo com o formato de imagem especificado. |
| extract_attachment() | Extrai anexos de um documento PDF. |
| extract_attachment(attachment_file_name) | Extrai anexo para o arquivo PDF pelo nome do anexo. |
| get_next_page_text(output_file) | Salva o texto de uma página em um arquivo. |
| get_next_page_text(output_stream) | Salva o texto de uma página em um fluxo. |
| close() | Descarta o Aspose.Pdf.Document associado a uma fachada. |
| extract_image() | Extrai imagens de um arquivo PDF. |
| has_next_image() | Verifica se há mais imagens acessíveis no documento PDF. Nota: ExtractImage deve ser chamado antes do uso deste método. |
| get_attach_names() | Retorna a lista de anexos no arquivo PDF. Nota: ExtractAttachments deve ser chamado antes do uso deste método. |
| get_attachment(output_path) | Armazena o anexo em um arquivo. |
| has_next_page_text() | Indica se é possível obter mais textos ou não. |
| get_attachment_info() | Obtém a lista de anexos. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

