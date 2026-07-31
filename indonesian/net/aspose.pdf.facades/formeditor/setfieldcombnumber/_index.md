---
title: "FormEditor.SetFieldCombNumber"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Menetapkan jumlah comb untuk bidang teks satu baris reguler; bidang tersebut secara otomatis dibagi menjadi sebanyak posisi atau comb yang berjarak sama sesuai nilai parameter combNumber"
type: docs
weight: 300
url: /id/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

Mengatur jumlah comb untuk field teks satu baris reguler (field secara otomatis dibagi menjadi sebanyak posisi yang berjarak sama, atau comb, sesuai nilai parameter combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang memenuhi syarat. |
| combNumber | Int32 | Jumlah comb untuk membagi bidang. |

### Nilai Kembalian

Jika berhasil, mengembalikan true; jika tidak, false.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


