---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: Formulareigenschaft. Ruft alle Namen der Formular-Submit-Buttons ab
type: docs
weight: 40
url: /de/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames-Eigenschaft

Ruft alle Namen der Formular-Submit-Buttons ab.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)