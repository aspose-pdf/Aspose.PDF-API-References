---
title: Class SignOptions
second_title: Aspose.PDF for .NET API Reference
description: Classe Aspose.Pdf.Plugins.SignOptions. Representa Opções de Assinatura para o plugin de Assinatura
type: docs
weight: 9250
url: /pt/net/aspose.pdf.plugins/signoptions/
---
## Classe SignOptions

Representa Opções de Assinatura para o plugin [`Signature`](../signature/).

```csharp
public sealed class SignOptions : OrganizerBaseOptions
```

## Construtores

| Nome | Descrição |
| --- | --- |
| [SignOptions](signoptions/#constructor)(Stream, string) | Inicializa uma nova instância do objeto `SignOptions` com opções padrão. |
| [SignOptions](signoptions/#constructor_1)(string, string) | Inicializa uma nova instância do objeto `SignOptions` com opções padrão. |

## Propriedades

| Nome | Descrição |
| --- | --- |
| [CloseInputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeinputstreams/) { get; set; } | Fecha os fluxos de entrada após a operação ser concluída. |
| [CloseOutputStreams](../../aspose.pdf.plugins/organizerbaseoptions/closeoutputstreams/) { get; set; } | Fecha os fluxos de saída após a operação ser concluída. |
| [Contact](../../aspose.pdf.plugins/signoptions/contact/) { get; set; } | O contato da assinatura. |
| [Inputs](../../aspose.pdf.plugins/organizerbaseoptions/inputs/) { get; } | Retorna a coleção de dados do plugin OrganizerOptions. |
| [Location](../../aspose.pdf.plugins/signoptions/location/) { get; set; } | A localização da assinatura. |
| [Name](../../aspose.pdf.plugins/signoptions/name/) { get; set; } | O nome do campo de assinatura existente. Nulo para criar um novo campo. |
| [Outputs](../../aspose.pdf.plugins/organizerbaseoptions/outputs/) { get; } | Obtém a coleção de alvos adicionados para salvar os resultados da operação. |
| [PageNumber](../../aspose.pdf.plugins/signoptions/pagenumber/) { get; set; } | O número da página na qual a assinatura é feita. |
| [Reason](../../aspose.pdf.plugins/signoptions/reason/) { get; set; } | O motivo da assinatura. |
| [Rectangle](../../aspose.pdf.plugins/signoptions/rectangle/) { get; set; } | O retângulo da assinatura. |
| [Visible](../../aspose.pdf.plugins/signoptions/visible/) { get; set; } | A visibilidade da assinatura. |

## Métodos

| Nome | Descrição |
| --- | --- |
| [AddInput](../../aspose.pdf.plugins/organizerbaseoptions/addinput/)(IDataSource) | Adiciona uma nova fonte de dados à coleção de dados do plugin PdfOrganizer. |
| [AddOutput](../../aspose.pdf.plugins/organizerbaseoptions/addoutput/)(IDataSource) | Adiciona uma nova fonte de dados à coleção de dados do plugin PdfOrganizer. |

### Veja Também

* classe [OrganizerBaseOptions](../organizerbaseoptions/)
* namespace [Aspose.Pdf.Plugins](../../aspose.pdf.plugins/)
* assembly [Aspose.PDF](../../)