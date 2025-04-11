---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Mengatur jumlah comb untuk bidang teks tunggal reguler yang secara otomatis dibagi menjadi sebanyak posisi atau comb yang terdistribusi secara merata sesuai dengan nilai parameter combNumber
type: docs
weight: 300
url: /id/net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## Metode FormEditor.SetFieldCombNumber

Mengatur jumlah comb untuk bidang teks tunggal reguler (bidang secara otomatis dibagi menjadi sebanyak posisi yang terdistribusi secara merata, atau comb, sesuai dengan nilai parameter combNumber).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang memenuhi syarat. |
| combNumber | Int32 | Jumlah comb untuk membagi bidang. |

### Nilai Kembali

Jika berhasil, kembalikan true; jika tidak, false.

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)