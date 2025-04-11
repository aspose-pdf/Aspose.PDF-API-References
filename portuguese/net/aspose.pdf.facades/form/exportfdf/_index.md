---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: Método Form. Exporta o conteúdo dos campos do pdf para o fluxo fdf
type: docs
weight: 70
url: /pt/net/aspose.pdf.facades/form/exportfdf/
---
## Método Form.ExportFdf

Exporta o conteúdo dos campos do pdf para o fluxo fdf.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| outputFdfStream | Stream | O fluxo fdf de saída. |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)