---
title: "Form.FieldNames"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form-egenskap. Hämtar lista över fältnamn på formuläret"
type: docs
weight: 30
url: /sv/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames property

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

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


