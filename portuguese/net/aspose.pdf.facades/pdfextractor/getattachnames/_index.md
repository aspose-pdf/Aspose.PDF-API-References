---
title: PdfExtractor.GetAttachNames
second_title: Aspose.PDF for .NET API Reference
description: Método PdfExtractor. Retorna a lista de anexos no arquivo PDF. Nota: ExtractAttachments deve ser chamado antes de usar este método
type: docs
weight: 160
url: /pt/net/aspose.pdf.facades/pdfextractor/getattachnames/
---
## Método PdfExtractor.GetAttachNames

Retorna a lista de anexos no arquivo PDF. Nota: ExtractAttachments deve ser chamado antes de usar este método.

```csharp
public IList<string> GetAttachNames()
```

### Valor de Retorno

Lista de anexos

## Exemplos

O exemplo demonstra como extrair nomes de anexos de um arquivo PDF.

```csharp
PdfExtractor extractor = new PdfExtractor();
extractor.BindPdf(TestSettings.GetInputFile("sample.pdf"));
extractor.ExtractAttachment();
IList attachments = extractor.GetAttachNames();
foreach (string name in attachments)
	Console.WriteLine(name);
```

### Veja Também

* classe [PdfExtractor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)