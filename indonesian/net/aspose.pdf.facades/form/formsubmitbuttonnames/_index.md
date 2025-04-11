---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: Properti Form. Mendapatkan semua nama tombol kirim formulir
type: docs
weight: 40
url: /id/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Properti Form.FormSubmitButtonNames

Mendapatkan semua nama tombol kirim formulir.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)