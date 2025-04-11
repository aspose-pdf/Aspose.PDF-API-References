---
title: Form.ExportJson
second_title: Aspose.PDF for .NET API Reference
description: Metodo Form. Esporta il contenuto di tutti i campi nel documento in un flusso JSON. I valori dei campi pulsante non vengono esportati
type: docs
weight: 80
url: /it/net/aspose.pdf.facades/form/exportjson/
---
## Metodo Form.ExportJson

Esporta il contenuto di tutti i campi nel documento in un flusso JSON. I valori dei campi pulsante non vengono esportati.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputJsonStream | Stream | Il flusso JSON di output in cui verranno scritti i dati dei campi del documento. |
| indented | Boolean | Facoltativo. Specifica se l'output JSON deve essere indentato per una migliore leggibilità. Il valore predefinito è true. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)