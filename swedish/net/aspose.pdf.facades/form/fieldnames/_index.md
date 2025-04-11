---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: Formulär egenskap. Hämtar lista över fältnamn på formuläret
type: docs
weight: 30
url: /sv/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames egenskap

Hämtar lista över fältnamn på formuläret.

```csharp
public string[] FieldNames { get; }
```

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)