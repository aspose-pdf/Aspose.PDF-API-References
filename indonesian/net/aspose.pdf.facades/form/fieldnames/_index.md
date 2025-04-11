---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: Properti Form. Mendapatkan daftar nama field pada form
type: docs
weight: 30
url: /id/net/aspose.pdf.facades/form/fieldnames/
---
## Properti Form.FieldNames

Mendapatkan daftar nama field pada form.

```csharp
public string[] FieldNames { get; }
```

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)