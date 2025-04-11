---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Form method. Imports the content of the fields from the xfdfxml file and put them into the new pdf
type: docs
weight: 300
url: /it/net/aspose.pdf.facades/form/importxfdf/
---
## Metodo Form.ImportXfdf

Importa il contenuto dei campi dal file xfdf(xml) e li inserisce nel nuovo pdf.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputXfdfStream | Stream | Il flusso xfdf(xml) di input. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)