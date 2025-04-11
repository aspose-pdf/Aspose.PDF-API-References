---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Mengatur jumlah karakter maksimum dari field teks
type: docs
weight: 310
url: /id/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## Metode FormEditor.SetFieldLimit

Mengatur jumlah karakter maksimum dari field teks.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama dari field teks. |
| fieldLimit | Int32 | Nilai baru dari batas untuk field. |

### Nilai Kembali

true jika batas field berhasil diatur.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)