---
title: "FormEditor.SetSubmitUrl"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Mengatur URL tombol"
type: docs
weight: 340
url: /id/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

Mengatur URL tombol.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama tombol kirim. |
| url | String | URL lengkap. |

### Nilai Kembalian

true jika URL untuk tombol berhasil diatur.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


