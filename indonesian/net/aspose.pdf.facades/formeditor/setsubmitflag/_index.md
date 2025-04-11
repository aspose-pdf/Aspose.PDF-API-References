---
title: FormEditor.SetSubmitFlag
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Atur bendera pengiriman tombol kirim
type: docs
weight: 330
url: /id/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## Metode FormEditor.SetSubmitFlag

Atur bendera pengiriman tombol kirim.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama tombol kirim. |
| submitFormFlag | SubmitFormFlag | Bendera pengiriman. |

### Nilai Kembali

true jika field ditemukan dan bendera pengiriman berhasil diatur.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### Lihat Juga

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)