---
title: "FormEditor.MoveField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Menetapkan posisi baru bidang"
type: docs
weight: 200
url: /id/net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField method

Mengatur posisi baru field.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang harus dipindahkan. |
| llx | Single | Absis sudut kiri bawah bidang. |
| lly | Single | Ordinat sudut kiri bawah bidang. |
| urx | Single | Absis sudut kanan atas bidang. |
| ury | Single | Ordinat sudut kanan atas bidang. |

### Nilai Kembalian

Benar jika posisi bidang berhasil diubah.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


