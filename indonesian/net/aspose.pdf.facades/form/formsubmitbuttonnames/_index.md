---
title: "Form.FormSubmitButtonNames"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti Form. Mendapatkan semua nama tombol kirim formulir."
type: docs
weight: 40
url: /id/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames property

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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


