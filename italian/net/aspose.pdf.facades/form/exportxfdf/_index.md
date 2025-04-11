---
title: Form.ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Esporta il contenuto dei campi del pdf nello stream xml. Il valore dei campi pulsante non verrà esportato
type: docs
weight: 90
url: /it/net/aspose.pdf.facades/form/exportxfdf/
---
## Metodo Form.ExportXfdf

Esporta il contenuto dei campi del pdf nello stream xml. Il valore del campo pulsante non verrà esportato.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputXfdfStream | Stream | Lo stream xml di output. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)