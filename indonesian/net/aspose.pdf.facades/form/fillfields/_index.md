---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: Metode Form. Mengisi kolom teks dengan nilai teks dan menyimpan dokumen. Relevan untuk dokumen yang ditandatangani. Perhatikan Hanya dapat diterapkan pada Text Box. Nama dan nilai kolom bersifat case sensitive.
type: docs
weight: 140
url: /id/net/aspose.pdf.facades/form/fillfields/
---
## Metode Form.FillFields

Mengisi kolom teks dengan nilai teks dan menyimpan dokumen. Relevan untuk dokumen yang ditandatangani. Perhatikan: Hanya dapat diterapkan pada Text Box. Nama dan nilai kolom bersifat case sensitive.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldNames | String[] | Nama-nama kolom. |
| fieldValues | String[] | Nilai baru dari kolom. |
| output | Stream& | Stream di mana dokumen akan disimpan. |

### Nilai Kembali

true jika kolom ditemukan dan berhasil diisi.

## Contoh

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### Lihat Juga

* kelas [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)