---
title: FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Referansı
description: Tüm form gönderme düğmesi adlarını alır.
type: docs
weight: 60
url: /tr/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames property

Tüm form gönderme düğmesi adlarını alır.

```csharp
public string[] FormSubmitButtonNames { get; }
```

### Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### Ayrıca bakınız

* class [Form](../../form)
* ad alanı [Aspose.Pdf.Facades](../../form)
* toplantı [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->
