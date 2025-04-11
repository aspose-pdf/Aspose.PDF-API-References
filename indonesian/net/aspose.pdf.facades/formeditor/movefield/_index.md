---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Atur posisi baru dari field
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/formeditor/movefield/
---
## Metode FormEditor.MoveField

Atur posisi baru dari field.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang harus dipindahkan. |
| llx | Single | Abscissa dari sudut kiri bawah field. |
| lly | Single | Ordinat dari sudut kiri bawah field. |
| urx | Single | Abscissa dari sudut kanan atas field. |
| ury | Single | Ordinat dari sudut kanan atas field. |

### Nilai Kembali

true jika posisi field berhasil diubah.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)