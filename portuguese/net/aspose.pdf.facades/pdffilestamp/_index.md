---
title: Class PdfFileStamp
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileStamp. Classe para adicionar carimbos, marcas d'água ou fundo a arquivos PDF
type: docs
weight: 4570
url: /pt/net/aspose.pdf.facades/pdffilestamp/
---
## Classe PdfFileStamp

Classe para adicionar carimbos (marca d'água ou fundo) a arquivos PDF.

```csharp
public sealed class PdfFileStamp : SaveableFacade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfFileStamp](pdffilestamp/#constructor)() | Construtor da classe PdfFileStamp. O arquivo de entrada e o arquivo de saída podem ser especificados através das propriedades correspondentes. |
| [PdfFileStamp](pdffilestamp/#constructor_1)(Document) | Inicializa um novo objeto `PdfFileStamp` com base no *documento*. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [ConvertTo](../../aspose.pdf.facades/pdffilestamp/convertto/) { set; } | Define o formato do arquivo PDF. O arquivo resultante será salvo no formato de arquivo especificado. Se esta propriedade não for especificada, o arquivo será salvo no formato PDF padrão sem conversão. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |
| [KeepSecurity](../../aspose.pdf.facades/pdffilestamp/keepsecurity/) { get; set; } | Mantém a segurança se verdadeiro. (Esse recurso será implementado nas próximas versões). |
| [NumberingStyle](../../aspose.pdf.facades/pdffilestamp/numberingstyle/) { get; set; } | Obtém ou define o estilo de numeração de páginas. Valores possíveis: NumeraisÁrabes, NumeraisRomanosMaiúsculos, NumeraisRomanosMinúsculos, LetrasMaiúsculas, LetrasMinúsculas |
| [OptimizeSize](../../aspose.pdf.facades/pdffilestamp/optimizesize/) { get; set; } | Obtém ou define a flag de otimização. Fluxos de recursos iguais no arquivo resultante são mesclados em um objeto PDF se essa flag estiver definida. Isso permite diminuir o tamanho do arquivo resultante, mas pode causar execução mais lenta e maiores requisitos de memória. Valor padrão: falso. |
| [PageHeight](../../aspose.pdf.facades/pdffilestamp/pageheight/) { get; } | Obtém a altura da primeira página no arquivo de origem. |
| [PageNumberRotation](../../aspose.pdf.facades/pdffilestamp/pagenumberrotation/) { get; set; } | Obtém ou define a rotação do número da página. A rotação é em graus. O padrão é 0. |
| [PageWidth](../../aspose.pdf.facades/pdffilestamp/pagewidth/) { get; } | Obtém a largura da primeira página no arquivo de entrada. |
| [StampId](../../aspose.pdf.facades/pdffilestamp/stampid/) { get; set; } | ID do carimbo do próximo carimbo adicionado (incluindo cabeçalhos/rodapés de página/números de página). |
| [StartingNumber](../../aspose.pdf.facades/pdffilestamp/startingnumber/) { get; set; } | Obtém ou define o número inicial para a primeira página no arquivo de entrada. As próximas páginas serão numeradas a partir desse valor. Por exemplo, se StartingNumber for definido como 100, as páginas do documento terão os números 100, 101, 102... |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter)(FormattedText, float) | Adiciona rodapé às páginas do documento. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_2)(Stream, float) | Adiciona imagem como rodapé da página. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_4)(string, float) | Adiciona imagem como rodapé às páginas do documento. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_1)(FormattedText, float, float, float) | Adiciona rodapé às páginas do documento. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_3)(Stream, float, float, float) | Adiciona imagem como rodapé da página. |
| [AddFooter](../../aspose.pdf.facades/pdffilestamp/addfooter/#addfooter_5)(string, float, float, float) | Adiciona imagem como rodapé das páginas. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader)(FormattedText, float) | Adiciona cabeçalho à página. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_2)(Stream, float) | Adiciona imagem como cabeçalho nas páginas. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_4)(string, float) | Adiciona imagem como cabeçalho às páginas do arquivo. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_1)(FormattedText, float, float, float) | Adiciona cabeçalho às páginas do arquivo. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_3)(Stream, float, float, float) | Adiciona imagem na parte superior da página. |
| [AddHeader](../../aspose.pdf.facades/pdffilestamp/addheader/#addheader_5)(string, float, float, float) | Adiciona imagem como cabeçalho nas páginas. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber)(FormattedText) | Adiciona número da página à página. O número da página pode conter o sinal # que será substituído pelo número da página. O número da página é colocado na parte inferior da página centralizado horizontalmente. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_4)(string) | Adiciona número da página ao arquivo. O texto do número da página pode conter o sinal # que será substituído pelo número da página. O número da página é colocado na parte inferior da página centralizado horizontalmente. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_1)(FormattedText, int) | Adiciona número da página às páginas. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_5)(string, int) | Adiciona número da página às páginas. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_3)(FormattedText, float, float) | Adiciona número da página na posição especificada na página. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_7)(string, float, float) | Adiciona número da página na posição especificada na página. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_2)(FormattedText, int, float, float, float, float) | Adiciona número da página às páginas do documento. |
| [AddPageNumber](../../aspose.pdf.facades/pdffilestamp/addpagenumber/#addpagenumber_6)(string, int, float, float, float, float) | Adiciona número da página às páginas do documento. |
| [AddStamp](../../aspose.pdf.facades/pdffilestamp/addstamp/)(Stamp) | Adiciona carimbo ao arquivo. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa a fachada. |
| override [Close](../../aspose.pdf.facades/pdffilestamp/close/)() | Fecha arquivos abertos e salva as alterações. Aviso. Se fluxos de entrada ou saída forem especificados, eles não são fechados pelo método Close(). |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save)(Stream) | Salva o documento no fluxo especificado. |
| override [Save](../../aspose.pdf.facades/pdffilestamp/save/#save_1)(string) | Salva o resultado no arquivo especificado. |

## Campos

| Nome | Descrição |
| --- | --- |
| const [PosBottomLeft](../../aspose.pdf.facades/pdffilestamp/posbottomleft/) | Posição inferior esquerda. |
| const [PosBottomMiddle](../../aspose.pdf.facades/pdffilestamp/posbottommiddle/) | Posição inferior central. |
| const [PosBottomRight](../../aspose.pdf.facades/pdffilestamp/posbottomright/) | Posição inferior direita. |
| const [PosSidesLeft](../../aspose.pdf.facades/pdffilestamp/possidesleft/) | Posição esquerda. |
| const [PosSidesRight](../../aspose.pdf.facades/pdffilestamp/possidesright/) | Posição direita. |
| const [PosUpperLeft](../../aspose.pdf.facades/pdffilestamp/posupperleft/) | Posição superior esquerda. |
| const [PosUpperMiddle](../../aspose.pdf.facades/pdffilestamp/posuppermiddle/) | Posição superior central. |
| const [PosUpperRight](../../aspose.pdf.facades/pdffilestamp/posupperright/) | Posição superior direita. |

### Veja Também

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)