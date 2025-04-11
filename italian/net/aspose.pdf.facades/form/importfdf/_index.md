---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: Metodo di form. Importa il contenuto dei campi dal file fdf e li imposta nel nuovo pdf.
type: docs
weight: 280
url: /it/net/aspose.pdf.facades/form/importfdf/
---
## Metodo Form.ImportFdf

Importa il contenuto dei campi dal file fdf e li inserisce nel nuovo pdf.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputFdfStream | Stream | Il flusso fdf di input. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)