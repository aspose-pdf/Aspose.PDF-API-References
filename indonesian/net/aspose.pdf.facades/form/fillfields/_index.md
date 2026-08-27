---
title: "Form.FillFields"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode Form. Mengisi bidang kotak teks dengan nilai teks dan menyimpan dokumen. Relevan untuk dokumen yang ditandatangani. Perhatikan hanya diterapkan pada Kotak Teks. Baik nama bidang maupun nilai bersifat sensitif huruf."
type: docs
weight: 140
url: /id/net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields method

Isi bidang kotak teks dengan nilai teks dan simpan dokumen. Relevan untuk dokumen yang ditandatangani. Catatan: Hanya berlaku untuk Text Box. Baik nama bidang maupun nilai bersifat sensitif huruf.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldNames | String[] | Nama-nama bidang. |
| fieldValues | String[] | Nilai baru bidang. |
| output | Stream& | Stream tempat dokumen akan disimpan. |

### Nilai Kembalian

true jika bidang ditemukan dan berhasil diisi.

## Contoh

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### Lihat Juga

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


