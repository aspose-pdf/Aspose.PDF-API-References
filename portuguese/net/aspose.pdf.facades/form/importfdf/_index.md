---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: Método do Form. Importa o conteúdo dos campos do arquivo fdf e os coloca no novo pdf
type: docs
weight: 280
url: /pt/net/aspose.pdf.facades/form/importfdf/
---
## Método Form.ImportFdf

Importa o conteúdo dos campos do arquivo fdf e os coloca no novo pdf.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Parâmetro | Tipo | Descrição |
| --- | --- | --- |
| inputFdfStream | Stream | O fluxo de entrada fdf. |

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)