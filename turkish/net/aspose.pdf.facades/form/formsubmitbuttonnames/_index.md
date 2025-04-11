---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: Form özelliği. Tüm form gönderme butonu adlarını alır
type: docs
weight: 40
url: /tr/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames özelliği

Tüm form gönderme butonu adlarını alır.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)