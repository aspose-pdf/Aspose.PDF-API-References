---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Mengatur URL tombol
type: docs
weight: 340
url: /id/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## Metode FormEditor.SetSubmitUrl

Mengatur URL tombol.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama tombol kirim. |
| url | String | URL yang sepenuhnya memenuhi syarat. |

### Nilai Kembali

true jika URL untuk tombol berhasil diatur.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)