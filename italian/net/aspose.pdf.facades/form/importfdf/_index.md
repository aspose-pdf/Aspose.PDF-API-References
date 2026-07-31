---
title: "Form.ImportFdf"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Importa il contenuto dei campi dal file fdf e lo inserisce nel nuovo pdf."
type: docs
weight: 280
url: /it/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf method

Importa il contenuto dei campi dal file fdf e lo inserisce nel nuovo pdf.

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

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


