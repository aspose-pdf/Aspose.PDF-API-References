---
title: "FormEditor.SetSubmitFlag"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Menetapkan bendera submit pada tombol submit"
type: docs
weight: 330
url: /id/net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag method

Atur flag submit pada tombol submit.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama tombol submit. |
| submitFormFlag | SubmitFormFlag | Bendera submit. |

### Nilai Kembalian

true jika field ditemukan dan flag submit berhasil diatur.

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


