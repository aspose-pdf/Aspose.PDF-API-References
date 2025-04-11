---
title: Class PdfFileInfo
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Facades.PdfFileInfo. Representa uma classe para acessar informações meta do documento PDF
type: docs
weight: 4520
url: /pt/net/aspose.pdf.facades/pdffileinfo/
---
## Classe PdfFileInfo

Representa uma classe para acessar informações meta do documento PDF.

```csharp
public sealed class PdfFileInfo : SaveableFacade
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [PdfFileInfo](pdffileinfo/#constructor)() | Inicializa uma nova instância da classe Aspose.Pdf.Facades.PdfFileInfo com valores padrão. |
| [PdfFileInfo](pdffileinfo/#constructor_1)(Document) | Inicializa um novo objeto `PdfFileInfo` com base no *documento*. |
| [PdfFileInfo](pdffileinfo/#constructor_2)(Stream) | Inicializa uma nova instância da classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_4)(string) | Inicializa uma nova instância da classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_3)(Stream, string) | Inicializa uma nova instância da classe Aspose.Pdf.Facades.PdfFileInfo. |
| [PdfFileInfo](pdffileinfo/#constructor_5)(string, string) | Inicializa uma nova instância da classe Aspose.Pdf.Facades.PdfFileInfo. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Author](../../aspose.pdf.facades/pdffileinfo/author/) { get; set; } | Obtém ou define as informações do Autor do documento PDF. |
| [CreationDate](../../aspose.pdf.facades/pdffileinfo/creationdate/) { get; set; } | Obtém ou define as informações da Data de Criação do documento PDF. |
| [Creator](../../aspose.pdf.facades/pdffileinfo/creator/) { get; set; } | Obtém ou define as informações do Criador do documento PDF. |
| [Document](../../aspose.pdf.facades/facade/document/) { get; } | Obtém a fachada do documento em que está trabalhando. |
| [HasCollection](../../aspose.pdf.facades/pdffileinfo/hascollection/) { get; } | Retorna verdadeiro se o arquivo de entrada atual for um arquivo 'Portfolio' contendo uma coleção de arquivos PDF. |
| [HasEditPassword](../../aspose.pdf.facades/pdffileinfo/haseditpassword/) { get; } | Retorna verdadeiro se uma senha for necessária para modificar permissões ou a propriedade de segurança do documento. Atenção que esta propriedade pode ser lida apenas se uma senha válida foi fornecida no construtor `PdfFileInfo`. Caso o PasswordType seja Inaccessible (significa que uma senha inválida foi fornecida), a leitura desta propriedade falhará com [`InvalidPasswordException`](../../aspose.pdf/invalidpasswordexception/). |
| [HasOpenPassword](../../aspose.pdf.facades/pdffileinfo/hasopenpassword/) { get; } | Retorna verdadeiro se uma senha for necessária para abrir o documento PDF protegido por senha. |
| [Header](../../aspose.pdf.facades/pdffileinfo/header/) { get; set; } | Obtém ou define as informações personalizadas do documento PDF. |
| [IsEncrypted](../../aspose.pdf.facades/pdffileinfo/isencrypted/) { get; } | Verifica se o documento PDF está criptografado. |
| [IsPdfFile](../../aspose.pdf.facades/pdffileinfo/ispdffile/) { get; } | Verifica se a entrada de origem é um arquivo PDF válido. |
| [Keywords](../../aspose.pdf.facades/pdffileinfo/keywords/) { get; set; } | Obtém ou define as informações de Palavras-chave do documento PDF. |
| [ModDate](../../aspose.pdf.facades/pdffileinfo/moddate/) { get; set; } | Obtém ou define as informações da data de Modificação do documento PDF. |
| [NumberOfPages](../../aspose.pdf.facades/pdffileinfo/numberofpages/) { get; } | Obtém o número de páginas do documento. |
| [PasswordType](../../aspose.pdf.facades/pdffileinfo/passwordtype/) { get; } | Retorna o tipo de senha que foi passada para criar a instância PdfFileInfo. Veja os valores possíveis em [`PasswordType`](./passwordtype/). Atenção que o documento PDF pode ser aberto usando tanto a senha do usuário (ou senha de abertura) quanto a senha do proprietário (ou permissões, edição). |
| [Producer](../../aspose.pdf.facades/pdffileinfo/producer/) { get; } | Obtém as informações do Produtor do documento PDF. |
| [Subject](../../aspose.pdf.facades/pdffileinfo/subject/) { get; set; } | Obtém ou define as informações do Assunto do documento PDF. |
| [Title](../../aspose.pdf.facades/pdffileinfo/title/) { get; set; } | Obtém ou define as informações do Título do documento PDF. |
| [UseStrictValidation](../../aspose.pdf.facades/pdffileinfo/usestrictvalidation/) { get; set; } | Usa regras de validação estritas através da propriedade [`IsPdfFile`](./ispdffile/). |

## Métodos

| Nome | Descrição |
| --- | --- |
| override [BindPdf](../../aspose.pdf.facades/pdffileinfo/bindpdf/#bindpdf)(Document) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(Stream) | Inicializa a fachada. |
| virtual [BindPdf](../../aspose.pdf.facades/facade/bindpdf/)(string) | Inicializa a fachada. |
| [ClearInfo](../../aspose.pdf.facades/pdffileinfo/clearinfo/)() | Limpa todas as informações meta do documento PDF. |
| override [Close](../../aspose.pdf.facades/pdffileinfo/close/)() | Desinicializa a instância. |
| [Dispose](../../aspose.pdf.facades/facade/dispose/)() | Desfaz a fachada. |
| [GetDocumentPrivilege](../../aspose.pdf.facades/pdffileinfo/getdocumentprivilege/)() | Obtém as configurações de privilégio do documento PDF. |
| [GetMetaInfo](../../aspose.pdf.facades/pdffileinfo/getmetainfo/)(string) | Obtém informações personalizadas do documento PDF com o nome da propriedade. Se não houver correspondência com o nome, retornará uma string em branco. |
| [GetPageHeight](../../aspose.pdf.facades/pdffileinfo/getpageheight/)(int) | Obtém a altura da página especificada. |
| [GetPageRotation](../../aspose.pdf.facades/pdffileinfo/getpagerotation/)(int) | Obtém a rotação da página especificada. |
| [GetPageWidth](../../aspose.pdf.facades/pdffileinfo/getpagewidth/)(int) | Obtém a largura da página especificada. |
| [GetPageXOffset](../../aspose.pdf.facades/pdffileinfo/getpagexoffset/)(int) | Obtém o deslocamento horizontal da área de exibição da página especificada. |
| [GetPageYOffset](../../aspose.pdf.facades/pdffileinfo/getpageyoffset/)(int) | Obtém o deslocamento vertical da área de exibição da página especificada. |
| [GetPdfVersion](../../aspose.pdf.facades/pdffileinfo/getpdfversion/)() | Obtém as informações da versão do documento PDF. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save)(Stream) | Salva o documento PDF no arquivo especificado. |
| override [Save](../../aspose.pdf.facades/pdffileinfo/save/#save_1)(string) | Salva o documento PDF no arquivo especificado. |
| [SaveNewInfo](../../aspose.pdf.facades/pdffileinfo/savenewinfo/#savenewinfo_1)(string) | Salva o documento PDF atualizado no arquivo especificado. |
| [SaveNewInfoWithXmp](../../aspose.pdf.facades/pdffileinfo/savenewinfowithxmp/)(string) | Altera as propriedades especificadas explicitamente definindo informações do arquivo, outras propriedades permanecem. |
| [SetMetaInfo](../../aspose.pdf.facades/pdffileinfo/setmetainfo/)(string, string) | Define informações personalizadas do documento PDF. |

### Veja Também

* classe [SaveableFacade](../saveablefacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)