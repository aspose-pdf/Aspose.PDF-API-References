---
title: Class PdfExtractor
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfExtractor. Classe para extrair imagens e texto de documentos PDF
type: docs
weight: 4450
url: /pt/net/aspose.pdf.facades/pdfextractor/
---
## Classe PdfExtractor

Classe para extrair imagens e texto de documentos PDF.

```csharp
public sealed class PdfExtractor : Facade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfExtractor](pdfextractor/#constructor)() | Inicializa um novo objeto `PdfExtractor`. |
| [PdfExtractor](pdfextractor/#constructor_1)(Document) | Inicializa um novo objeto `PdfExtractor` com base no *documento*. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |
| [EndPage](../../aspose.pdf.facades/pdfextractor/endpage/) { get; set; } | Obtém ou define a página final no intervalo de páginas onde a operação de extração será realizada. |
| [ExtractImageMode](../../aspose.pdf.facades/pdfextractor/extractimagemode/) { get; set; } | Define o modo para o processo de extração de imagens. |
| [ExtractTextMode](../../aspose.pdf.facades/pdfextractor/extracttextmode/) { get; set; } | Define o modo para o resultado da extração de texto. |
| [IsBidi](../../aspose.pdf.facades/pdfextractor/isbidi/) { get; } | É verdadeiro quando o texto contém símbolos hebraicos ou árabes. Este caso deve ser considerado especialmente porque as funções de string mudam seu comportamento e começam a processar o texto da direita para a esquerda (exceto números e outros caracteres não textuais). |
| [Password](../../aspose.pdf.facades/pdfextractor/password/) { get; set; } | Obtém ou define a senha do arquivo de entrada. |
| [Resolution](../../aspose.pdf.facades/pdfextractor/resolution/) { get; set; } | Define ou obtém a resolução para as imagens extraídas. O valor padrão é 150. Imagens com um valor de resolução maior são mais nítidas. No entanto, aumentar o valor da resolução resulta em um aumento do tempo e da memória necessários para extrair imagens. Geralmente, para obter uma imagem clara, é suficiente definir a resolução para 150 ou 300. |
| [StartPage](../../aspose.pdf.facades/pdfextractor/startpage/) { get; set; } | Obtém ou define a página inicial no intervalo de páginas onde a operação de extração será realizada. |
| [TextSearchOptions](../../aspose.pdf.facades/pdfextractor/textsearchoptions/) { get; set; } | Obtém ou define as opções de pesquisa de texto. |

## Métodos

| Nome | Descrição |
| --- | --- |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Document) | Inicializa a fachada. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_1)(Stream) | Vincula o documento PDF a partir do stream. |
| override [BindPdf](../../aspose.pdf.facades/pdfextractor/bindpdf/#bindpdf_2)(string) | Vincula o arquivo PDF de entrada. |
| virtual [Close](../../aspose.pdf.facades/facade/close/)() | Desfaz o Aspose.Pdf.Document vinculado a uma fachada. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment)() | Extrai anexos de um documento PDF. |
| [ExtractAttachment](../../aspose.pdf.facades/pdfextractor/extractattachment/#extractattachment_1)(string) | Extrai anexo para o arquivo PDF pelo nome do anexo. |
| [ExtractImage](../../aspose.pdf.facades/pdfextractor/extractimage/)() | Extrai imagens de um arquivo PDF. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext)() | Extrai texto de um documento PDF usando codificação Unicode. |
| [ExtractText](../../aspose.pdf.facades/pdfextractor/extracttext/#extracttext_1)(Encoding) | Extrai texto de um documento PDF usando a codificação especificada. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment)() | Salva todos os arquivos de anexo em streams. |
| [GetAttachment](../../aspose.pdf.facades/pdfextractor/getattachment/#getattachment_1)(string) | Armazena o anexo em um arquivo. |
| [GetAttachmentInfo](../../aspose.pdf.facades/pdfextractor/getattachmentinfo/)() | Obtém a lista de anexos. |
| [GetAttachNames](../../aspose.pdf.facades/pdfextractor/getattachnames/)() | Retorna a lista de anexos no arquivo PDF. Nota: ExtractAttachments deve ser chamado antes de usar este método. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage)(Stream) | Recupera a próxima imagem do arquivo PDF e a armazena no stream. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_2)(string) | Recupera a próxima imagem do documento PDF. Nota: ExtractImage deve ser chamado antes de usar este método. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_1)(Stream, ImageFormat) | Recupera a próxima imagem do arquivo PDF e a armazena no stream com o formato de imagem dado. |
| [GetNextImage](../../aspose.pdf.facades/pdfextractor/getnextimage/#getnextimage_3)(string, ImageFormat) | Recupera a próxima imagem do documento PDF com o formato de imagem dado. Nota: ExtractImage deve ser chamado antes de usar este método. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext)(Stream) | Salva o texto de uma página no stream. |
| [GetNextPageText](../../aspose.pdf.facades/pdfextractor/getnextpagetext/#getnextpagetext_1)(string) | Salva o texto de uma página em um arquivo. |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext)(Stream) | Salva o texto no stream. veja também:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_2)(string) | Salva o texto em um arquivo. veja também:[`ExtractText`](./extracttext/) |
| [GetText](../../aspose.pdf.facades/pdfextractor/gettext/#gettext_1)(Stream, bool) | Salva o texto no stream. veja também:[`ExtractText`](./extracttext/) |
| [HasNextImage](../../aspose.pdf.facades/pdfextractor/hasnextimage/)() | Verifica se mais imagens estão acessíveis no documento PDF. Nota: ExtractImage deve ser chamado antes de usar este método. |
| [HasNextPageText](../../aspose.pdf.facades/pdfextractor/hasnextpagetext/)() | Indica se é possível obter mais textos ou não. |

### Veja Também

* classe [Facade](../facade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)