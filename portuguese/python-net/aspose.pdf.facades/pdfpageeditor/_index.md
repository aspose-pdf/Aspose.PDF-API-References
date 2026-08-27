---
title: "PdfPageEditor"
second_title: "Aspose.PDF para Python via .NET Referência da API"
description: "Representa uma classe para editar a página do arquivo PDF, incluindo girar a página, ampliar a página, mover a posição e alterar o tamanho da página."
type: docs
weight: 340
url: /pt/python-net/aspose.pdf.facades/pdfpageeditor/
---

## PdfPageEditor class

Representa uma classe para editar a página do arquivo PDF, incluindo girar a página, ampliar a página, mover a posição e alterar o tamanho da página.

O tipo PdfPageEditor expõe os seguintes membros:
## Construtores
| Nome | Descrição |
| :- | :- |
| PdfPageEditor() | Construtor da classe PdfPageEditor. |
| PdfPageEditor(document) | Inicializa uma nova instância da classe PdfPageEditor |
## Propriedades
| Nome | Descrição |
| :- | :- |
| document | Obtém a fachada do documento em que está trabalhando. |
| transition_duration | Obtém ou define a duração do efeito de transição. |
| transition_type | Obtém ou define o estilo de transição a ser usado ao mover para esta página a partir de outra durante uma apresentação. |
| display_duration | Obtém ou define a duração de exibição das páginas. |
| process_pages | Obtém ou define os números das páginas a serem editados. Por padrão, cada página será editada. |
| rotation | Obtém ou define a rotação das páginas, a rotação deve ser 0, 90, 180 ou 270.<br/>            Valor padrão é 0. |
| zoom | Obtém ou define o coeficiente de zoom. Valor 1.0 corresponde a 100%.<br/>            Valor padrão é 1.0. |
| page_size | Obtém ou define o tamanho da página do arquivo de saída. |
| alinhamento | Obtém ou define o alinhamento horizontal do conteúdo PDF original na página resultante, o padrão é AlignmentType.Left. |
| horizontal_alignment | Obtém ou define o alinhamento horizontal do conteúdo PDF original na página resultante, o padrão é AlignmentType.Left. |
| vertical_alignment | Obtém ou define o alinhamento vertical do conteúdo PDF original na página resultante, o padrão é VerticalAlignmentType.Bottom. |
| vertical_alignment_type | Obtém ou define o alinhamento vertical do conteúdo PDF original na página resultante, o padrão é VerticalAlignmentType.Bottom. |
| SPLITVOUT | Divisão Vertical Externa |
| SPLITHOUT | Divisão Horizontal Externa |
| SPLITVIN | Divisão Vertical Interna |
| SPLITHIN | Divisão Horizontal Interna |
| BLINDV | Persianas Verticais |
| BLINDH | Persianas Verticais |
| INBOX | Caixa Interna |
| OUTBOX | Caixa Externa |
| LRWIPE | Limpeza Esquerda-Direita |
| RLWIPE | Limpeza Direita-Esquerda |
| BTWIPE | Varredura de baixo para cima |
| TBWIPE | Varredura de cima para baixo |
| DISSOLVE | A página antiga se dissolve |
| LRGLITTER | Brilho da esquerda para a direita |
| TBGLITTER | Brilho de cima para baixo |
| DGLITTER | Brilho diagonal |
## Métodos
| Nome | Descrição |
| :- | :- |
| bind_pdf(src_file) | Vincula o documento PDF para edição. |
| bind_pdf(src_stream) | Vincula o documento PDF para edição. |
| bind_pdf(src_doc) | Vincula o documento PDF para edição. |
| save(output_file) | Salva o documento alterado em um arquivo. |
| save(output_stream) | Salva o documento alterado em um fluxo. |
| close() | Libera quaisquer recursos associados à fachada atual. |
| move_position(move_x, move_y) | Move a origem de (0, 0) para o ponto designado. <br/>            A origem está no canto inferior esquerdo e a unidade é ponto (1 polegada = 72 pontos). |
| get_pages() | Retorna o número total de páginas. |
| get_page_size(page) | Retorna o tamanho da página especificada. |
| get_page_rotation(page) | Retorna a rotação da página especificada. |
| get_page_box_size(page, page_box_name) | Retorna o tamanho da caixa especificada no documento. |
| apply_changes() | Aplica as alterações feitas nas páginas do documento. |

### Veja Também

* namespace [aspose.pdf.facades](/pdf/python-net/aspose.pdf.facades/)
* assembly [Aspose.PDF](/pdf/python-net/)

