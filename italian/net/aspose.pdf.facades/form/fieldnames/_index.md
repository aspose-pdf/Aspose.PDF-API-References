---
title: "Form.FieldNames"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Proprietà Form. Ottiene l'elenco dei nomi dei campi nel modulo."
type: docs
weight: 30
url: /it/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames property

Ottiene l'elenco dei nomi dei campi sul modulo.

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

### Vedi anche

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


