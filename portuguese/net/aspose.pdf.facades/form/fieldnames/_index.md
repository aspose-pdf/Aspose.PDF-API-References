---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: Propriedade do formulário. Obtém a lista de nomes de campos no formulário
type: docs
weight: 30
url: /pt/net/aspose.pdf.facades/form/fieldnames/
---
## Propriedade Form.FieldNames

Obtém a lista de nomes de campos no formulário.

```csharp
public string[] FieldNames { get; }
```

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)