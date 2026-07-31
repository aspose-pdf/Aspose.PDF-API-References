---
title: "Form.FillBarcodeField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Isi bidang barcode sesuai dengan nama bidang yang sepenuhnya memenuhi syarat"
type: docs
weight: 120
url: /id/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

Isi bidang barcode sesuai dengan nama bidang yang sepenuhnya memenuhi syarat.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang sepenuhnya memenuhi kualifikasi. |
| data | String | Nilai barcode baru. |

### Nilai Kembalian

Jika pengisian berhasil, kembalikan true; jika tidak, false.

## Contoh

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


