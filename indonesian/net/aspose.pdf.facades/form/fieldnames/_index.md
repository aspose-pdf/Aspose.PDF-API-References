---
title: "Form.FieldNames"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Form. Mendapatkan daftar nama bidang pada formulir."
type: docs
weight: 30
url: /id/net/aspose.pdf.facades/form/fieldnames/
---
## Form.FieldNames property

Mendapatkan daftar nama bidang pada formulir.

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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


