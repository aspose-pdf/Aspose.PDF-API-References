---
title: "FormEditor.SetFieldLimit"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Menetapkan jumlah karakter maksimum dari field teks"
type: docs
weight: 310
url: /id/net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit method

Mengatur jumlah karakter maksimum dari bidang teks.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field teks. |
| fieldLimit | Int32 | Nilai baru batas untuk field. |

### Nilai Kembalian

true jika batas field berhasil diatur.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


