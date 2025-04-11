---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: Formegenskap. Hämtar alla namn på formulärsändningsknappar
type: docs
weight: 40
url: /sv/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames-egenskap

Hämtar alla namn på formulärsändningsknappar.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)