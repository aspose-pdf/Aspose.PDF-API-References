---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: Propriedade do Form. Obtém todos os nomes dos botões de envio do formulário
type: docs
weight: 40
url: /pt/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Propriedade Form.FormSubmitButtonNames

Obtém todos os nomes dos botões de envio do formulário.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## Exemplos

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### Veja Também

* classe [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)