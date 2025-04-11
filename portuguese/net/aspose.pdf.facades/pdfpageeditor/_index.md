---
title: Class PdfPageEditor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfPageEditor. Representa uma classe para editar as páginas de arquivos PDF, incluindo rotação de página, zoom de página, movimentação de posição e alteração do tamanho da página.
type: docs
weight: 4590
url: /pt/net/aspose.pdf.facades/pdfpageeditor/
---
## Classe PdfPageEditor

Representa uma classe para editar a página do arquivo PDF, incluindo rotação de página, zoom de página, movimentação de posição e alteração do tamanho da página.

```csharp
public sealed class PdfPageEditor : SaveableFacade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfPageEditor](pdfpageeditor/#constructor)() | Construtor para a classe PdfPageEditor. |
| [PdfPageEditor](pdfpageeditor/#constructor_1)(Document) | Construtor para a classe PdfPageEditor. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [DisplayDuration](../../aspose.pdf.facades/pdfpageeditor/displayduration/) { get; set; } | Obtém ou define a duração de exibição para as páginas. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfpageeditor/horizontalalignment/) { get; set; } | Obtém ou define o alinhamento horizontal do conteúdo PDF original na página de resultado, o padrão é AlignmentType.Left. |
| [PageRotations](../../aspose.pdf.facades/pdfpageeditor/pagerotations/) { get; set; } | Um hashtable que contém o número da página e o grau de rotação, a chave representa o número da página, o valor da chave representa a rotação em graus. |
| [PageSize](../../aspose.pdf.facades/pdfpageeditor/pagesize/) { get; set; } | Obtém ou define o tamanho da página do arquivo de saída. |
| [ProcessPages](../../aspose.pdf.facades/pdfpageeditor/processpages/) { get; set; } | Obtém ou define os números das páginas a serem editadas. Por padrão, cada página seria editada. |
| [Rotation](../../aspose.pdf.facades/pdfpageeditor/rotation/) { get; set; } | Obtém ou define a rotação das páginas, a rotação deve ser 0, 90, 180 ou 270. O valor padrão é 0. |
| [TransitionDuration](../../aspose.pdf.facades/pdfpageeditor/transitionduration/) { get; set; } | Obtém ou define a duração do efeito de transição. |
| [TransitionType](../../aspose.pdf.facades/pdfpageeditor/transitiontype/) { get; set; } | Obtém ou define o estilo de transição a ser usado ao mover para esta página a partir de outra durante uma apresentação. |
| [VerticalAlignmentType](../../aspose.pdf.facades/pdfpageeditor/verticalalignmenttype/) { get; set; } | Obtém ou define o alinhamento vertical do conteúdo PDF original na página de resultado, o padrão é VerticalAlignmentType.Bottom. |
| [Zoom](../../aspose.pdf.facades/pdfpageeditor/zoom/) { get; set; } | Obtém ou define o coeficiente de zoom. O valor 1.0 corresponde a 100%. O valor padrão é 1.0. O seguinte exemplo demonstra como alterar o zoom das páginas do documento. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [ApplyChanges](../../aspose.pdf.facades/pdfpageeditor/applychanges/)() | Aplica as alterações feitas nas páginas do documento. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa a fachada. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Desfaz o Aspose.Pdf.Document vinculado a uma fachada. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| [GetPageBoxSize](../../aspose.pdf.facades/pdfpageeditor/getpageboxsize/)(int, string) | Retorna o tamanho da caixa especificada no documento. |
| [GetPageRotation](../../aspose.pdf.facades/pdfpageeditor/getpagerotation/)(int) | Retorna a rotação da página especificada. |
| [GetPages](../../aspose.pdf.facades/pdfpageeditor/getpages/)() | Retorna o número total de páginas. |
| [GetPageSize](../../aspose.pdf.facades/pdfpageeditor/getpagesize/)(int) | Retorna o tamanho da página da página especificada. |
| [MovePosition](../../aspose.pdf.facades/pdfpageeditor/moveposition/)(float, float) | Move a origem de (0, 0) para o ponto designado. A origem é a parte inferior esquerda e a unidade é ponto (1 polegada = 72 pontos). |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save)(Stream) | Salva o documento alterado em um stream. |
| override [Save](../../aspose.pdf.facades/pdfpageeditor/save/#save_1)(string) | Salva o documento alterado em um arquivo. |

## Campos

| Nome | Descrição |
| --- | --- |
| const [BLINDH](../../aspose.pdf.facades/pdfpageeditor/blindh/) | Persiana Vertical |
| const [BLINDV](../../aspose.pdf.facades/pdfpageeditor/blindv/) | Persiana Vertical |
| const [BTWIPE](../../aspose.pdf.facades/pdfpageeditor/btwipe/) | Limpeza de Baixo para Cima |
| const [DGLITTER](../../aspose.pdf.facades/pdfpageeditor/dglitter/) | Brilho Diagonal |
| const [DISSOLVE](../../aspose.pdf.facades/pdfpageeditor/dissolve/) | A página antiga se dissolve |
| const [INBOX](../../aspose.pdf.facades/pdfpageeditor/inbox/) | Caixa Interna |
| const [LRGLITTER](../../aspose.pdf.facades/pdfpageeditor/lrglitter/) | Brilho da Esquerda para a Direita |
| const [LRWIPE](../../aspose.pdf.facades/pdfpageeditor/lrwipe/) | Limpeza da Esquerda para a Direita |
| const [OUTBOX](../../aspose.pdf.facades/pdfpageeditor/outbox/) | Caixa Externa |
| const [RLWIPE](../../aspose.pdf.facades/pdfpageeditor/rlwipe/) | Limpeza da Direita para a Esquerda |
| const [SPLITHIN](../../aspose.pdf.facades/pdfpageeditor/splithin/) | Divisão Horizontal Interna |
| const [SPLITHOUT](../../aspose.pdf.facades/pdfpageeditor/splithout/) | Divisão Horizontal Externa |
| const [SPLITVIN](../../aspose.pdf.facades/pdfpageeditor/splitvin/) | Divisão Vertical Interna |
| const [SPLITVOUT](../../aspose.pdf.facades/pdfpageeditor/splitvout/) | Divisão Vertical Externa |
| const [TBGLITTER](../../aspose.pdf.facades/pdfpageeditor/tbglitter/) | Brilho de Cima para Baixo |
| const [TBWIPE](../../aspose.pdf.facades/pdfpageeditor/tbwipe/) | Limpeza de Cima para Baixo |

### Veja Também

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)