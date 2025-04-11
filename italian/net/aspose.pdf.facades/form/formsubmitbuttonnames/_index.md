---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: Proprietà del modulo. Ottiene tutti i nomi dei pulsanti di invio del modulo
type: docs
weight: 40
url: /it/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Proprietà Form.FormSubmitButtonNames

Ottiene tutti i nomi dei pulsanti di invio del modulo.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## Esempi

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### Vedi Anche

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)