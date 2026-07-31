---
title: "Form.ExportFdf"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Esporta il contenuto dei campi del pdf nello stream fdf"
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf method

Esporta il contenuto dei campi del pdf nello stream fdf.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputFdfStream | Stream | Lo stream fdf di output. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


