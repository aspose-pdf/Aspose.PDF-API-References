---
title: "Form.FlattenField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Meratakan bidang yang ditentukan dengan nama bidang yang sepenuhnya memenuhi syarat. Semua bidang lain akan tetap tidak dapat diubah. Jika fieldName tidak valid, semua bidang akan tetap tidak dapat diubah."
type: docs
weight: 170
url: /id/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField method

Menyatukan bidang tertentu dengan nama bidang yang sepenuhnya memenuhi syarat. Semua bidang lain akan tetap tidak dapat diubah. Jika fieldName tidak valid, semua bidang akan tetap tidak dapat diubah.

```csharp
public void FlattenField(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang akan diratakan. |

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


