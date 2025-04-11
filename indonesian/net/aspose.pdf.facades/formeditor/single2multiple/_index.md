---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Ubah bidang teks satu baris menjadi beberapa baris
type: docs
weight: 350
url: /id/net/aspose.pdf.facades/formeditor/single2multiple/
---
## Metode FormEditor.Single2Multiple

Ubah bidang teks satu baris menjadi beberapa baris.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang memenuhi syarat. |

### Nilai Kembali

Jika berhasil, kembalikan true; jika tidak false.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)