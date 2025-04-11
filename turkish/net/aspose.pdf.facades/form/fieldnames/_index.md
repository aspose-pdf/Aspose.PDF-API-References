---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: Form özelliği. Form üzerindeki alan adlarının listesini alır
type: docs
weight: 30
url: /tr/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames özelliği

Form üzerindeki alan adlarının listesini alır.

```csharp
public string[] FieldNames { get; }
```

## Örnekler

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### Ayrıca Bakınız

* sınıf [Form](../)
* ad alanı [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* derleme [Aspose.PDF](../../../)