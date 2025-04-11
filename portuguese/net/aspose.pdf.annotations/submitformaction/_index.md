---
title: Class SubmitFormAction
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Annotations.SubmitFormAction. Classe que descreve a ação de envio de formulário
type: docs
weight: 2640
url: /pt/net/aspose.pdf.annotations/submitformaction/
---
## Classe SubmitFormAction

Classe que descreve a ação de envio de formulário.

```csharp
public sealed class SubmitFormAction : PdfAction
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [SubmitFormAction](submitformaction/)() | Inicializa o objeto SubmitFormAction. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [Flags](../../aspose.pdf.annotations/submitformaction/flags/) { get; set; } | Obtém ou define as flags da ação de envio |
| [Next](../../aspose.pdf.annotations/pdfaction/next/) { get; } | Próximas ações na sequência. |
| [Url](../../aspose.pdf.annotations/submitformaction/url/) { get; set; } | URL de destino. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [GetECMAScriptString](../../aspose.pdf.annotations/pdfaction/getecmascriptstring/)() | Obtém a string para a Ação ECMAScript. |

## Campos

| Nome | Descrição |
| --- | --- |
| const [CanonicalFormat](../../aspose.pdf.annotations/submitformaction/canonicalformat/) | Se definido, quaisquer valores de campo enviados representando datas serão convertidos para o formato padrão. |
| const [EmbedForm](../../aspose.pdf.annotations/submitformaction/embedform/) | Se definido, a entrada F do FDF enviado será uma especificação de arquivo contendo um fluxo de arquivo incorporado representando o arquivo PDF do qual o FDF está sendo enviado. |
| const [ExclFKey](../../aspose.pdf.annotations/submitformaction/exclfkey/) | Se definido, o FDF enviado excluirá a entrada F. |
| const [ExclNonUserAnnots](../../aspose.pdf.annotations/submitformaction/exclnonuserannots/) | Se definido, incluirá apenas aquelas anotações de marcação cuja entrada T corresponda ao nome do usuário atual. |
| const [Exclude](../../aspose.pdf.annotations/submitformaction/exclude/) | Se limpo, o array Fields especifica quais campos incluir na submissão. |
| const [ExportFormat](../../aspose.pdf.annotations/submitformaction/exportformat/) | Se definido, os nomes e valores dos campos serão enviados no formato de Formulário HTML. |
| const [GetMethod](../../aspose.pdf.annotations/submitformaction/getmethod/) | Se definido, os nomes e valores dos campos serão enviados usando uma solicitação HTTP GET. |
| const [IncludeAnnotations](../../aspose.pdf.annotations/submitformaction/includeannotations/) | Se definido, o arquivo FDF enviado incluirá todas as anotações de marcação no documento PDF subjacente. |
| const [IncludeAppendSaves](../../aspose.pdf.annotations/submitformaction/includeappendsaves/) | Se definido, o arquivo FDF enviado incluirá o conteúdo de todas as atualizações incrementais. |
| const [IncludeNoValueFields](../../aspose.pdf.annotations/submitformaction/includenovaluefields/) | Se definido, todos os campos designados pelo array Fields e a flag Include/Exclude serão enviados. |
| const [SubmitCoordinates](../../aspose.pdf.annotations/submitformaction/submitcoordinates/) | Se definido, as coordenadas do clique do mouse que causou a ação de envio de formulário serão transmitidas como parte dos dados do formulário. |
| const [SubmitPdf](../../aspose.pdf.annotations/submitformaction/submitpdf/) | Se definido, o documento será enviado como PDF, usando o tipo de conteúdo MIME application/pdf. |
| const [Xfdf](../../aspose.pdf.annotations/submitformaction/xfdf/) | Se definido, os nomes e valores dos campos serão enviados como XFDF. |

### Veja Também

* classe [PdfAction](../pdfaction/)
* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)