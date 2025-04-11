---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: Metodo delle form. Esporta il contenuto dei campi del PDF nella fdf stream.
type: docs
weight: 70
url: /it/net/aspose.pdf.facades/form/exportfdf/
---
## Metodo Form.ExportFdf

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

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)