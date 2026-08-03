---
title: "Form.FormSubmitButtonNames"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form-egenskap. Hämtar alla namn på formulärskickknappar"
type: docs
weight: 40
url: /sv/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames property

Hämtar alla namn på formulärets skicka-knappar.

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

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


