---
title: Form.FlattenField
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Meratakan field yang ditentukan dengan nama field yang sepenuhnya memenuhi syarat. Field lainnya akan tetap tidak dapat diubah. Jika fieldName tidak valid, semua field akan tetap tidak dapat diubah.
type: docs
weight: 170
url: /id/net/aspose.pdf.facades/form/flattenfield/
---
## Metode Form.FlattenField

Meratakan field yang ditentukan dengan nama field yang sepenuhnya memenuhi syarat. Field lainnya akan tetap tidak dapat diubah. Jika fieldName tidak valid, semua field akan tetap tidak dapat diubah.

```csharp
public void FlattenField(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang akan diratakan. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)