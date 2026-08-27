---
title: "Form.ExportJson"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo Form. Esporta il contenuto di tutti i campi nel documento in uno stream JSON. I valori dei campi pulsante non vengono esportati"
type: docs
weight: 80
url: /it/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson method

Esporta il contenuto di tutti i campi nel documento in uno stream JSON. I valori dei campi pulsante non vengono esportati.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| outputJsonStream | Stream | Lo stream JSON di output in cui verranno scritti i dati dei campi del documento. |
| indentato | Boolean | Opzionale. Specifica se l'output JSON deve essere indentato per una migliore leggibilità. Il valore predefinito è true. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


