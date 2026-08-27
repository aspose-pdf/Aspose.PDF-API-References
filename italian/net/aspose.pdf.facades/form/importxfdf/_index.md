---
title: "Form.ImportXfdf"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Importa il contenuto dei campi dal file xfdfxml e lo inserisce nel nuovo PDF"
type: docs
weight: 300
url: /it/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf method

Importa il contenuto dei campi dal file xfdf(xml) e lo inserisce nel nuovo pdf.

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

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


