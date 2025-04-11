---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengisi bidang barcode sesuai dengan nama bidang yang sepenuhnya memenuhi syarat
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Metode Form.FillBarcodeField

Mengisi bidang barcode sesuai dengan nama bidang yang sepenuhnya memenuhi syarat.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang sepenuhnya memenuhi syarat. |
| data | String | Nilai barcode baru. |

### Nilai Kembali

Jika pengisian berhasil, kembalikan true; jika tidak, false.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)