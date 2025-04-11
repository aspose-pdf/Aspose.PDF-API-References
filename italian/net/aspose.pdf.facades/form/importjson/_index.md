---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: Form method. Imports all field data from a JSON stream into the document fields matching the fields by their full names
type: docs
weight: 290
url: /it/net/aspose.pdf.facades/form/importjson/
---
## Metodo Form.ImportJson

Importa tutti i dati dei campi da un flusso JSON nei campi del documento, abbinando i campi per i loro nomi completi.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| inputJsonStream | Stream | Il flusso JSON di input contenente i dati dei campi da importare nei campi del documento. |

## Esempi

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)