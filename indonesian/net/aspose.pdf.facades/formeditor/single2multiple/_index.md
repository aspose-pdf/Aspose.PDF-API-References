---
title: "FormEditor.Single2Multiple"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "FormEditor method. Mengubah field teks satu baris menjadi beberapa baris"
type: docs
weight: 350
url: /id/net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

Ubah bidang teks satu baris menjadi beberapa baris.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang memenuhi syarat. |

### Nilai Kembalian

Jika berhasil, mengembalikan true; jika tidak, false.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


