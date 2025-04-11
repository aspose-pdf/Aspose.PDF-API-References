---
title: Form.ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Exporta o conteúdo dos campos do pdf para o fluxo xml. O valor dos campos de botão não será exportado
type: docs
weight: 90
url: /pt/net/aspose.pdf.facades/form/exportxfdf/
---
## Método Form.ExportXfdf

Exporta o conteúdo dos campos do pdf para o fluxo xml. O valor do campo de botão não será exportado.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputXfdfStream | Stream | O fluxo xml de saída. |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)