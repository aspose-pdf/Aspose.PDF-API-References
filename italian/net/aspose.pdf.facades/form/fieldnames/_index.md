---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: Proprietà del modulo. Ottiene l'elenco dei nomi dei campi nel modulo
type: docs
weight: 30
url: /it/net/aspose.pdf.facades/form/fieldnames/
---
## Proprietà Form.FieldNames

Ottiene l'elenco dei nomi dei campi nel modulo.

```csharp
public string[] FieldNames { get; }
```

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)