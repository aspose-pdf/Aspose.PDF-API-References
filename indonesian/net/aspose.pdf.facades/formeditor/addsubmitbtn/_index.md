---
title: "FormEditor.AddSubmitBtn"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Tambahkan tombol kirim pada formulir"
type: docs
weight: 130
url: /id/net/aspose.pdf.facades/formeditor/addsubmitbtn/
---
## FormEditor.AddSubmitBtn method

Tambahkan tombol submit pada formulir.

```csharp
public void AddSubmitBtn(string fieldName, int page, string label, string url, float llx, 
    float lly, float urx, float ury)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama tombol baru. |
| halaman | Int32 | Halaman tempat tombol akan ditempatkan. |
| label | String | Keterangan tombol. |
| url | String | URL tombol kirim. |
| llx | Single | Abskis sudut kiri bawah. |
| lly | Single | Ordinat sudut kiri bawah. |
| urx | Single | Abskis sudut kanan atas. |
| ury | Single | Ordinat sudut kanan atas. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_AddSubmitBtn.pdf");
formEditor.AddSubmitBtn("submit", 1, "Submit", "www.check.com", 10, 200, 70, 270);
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


