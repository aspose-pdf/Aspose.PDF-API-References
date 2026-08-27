---
title: "FormEditor.CopyInnerField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Menyalin bidang yang ada ke posisi yang sama pada nomor halaman yang ditentukan. Dokumen baru akan dihasilkan yang berisi semua isi dokumen sumber kecuali bidang yang baru disalin."
type: docs
weight: 150
url: /id/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Menyalin field yang ada ke posisi yang sama pada nomor halaman yang ditentukan. Dokumen baru akan dihasilkan, yang berisi semua yang dimiliki dokumen sumber kecuali field yang baru disalin.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang sepenuhnya memenuhi syarat lama. |
| newFieldName | String | Nama bidang yang sepenuhnya memenuhi syarat baru. Jika null, akan diatur menjadi fieldName + "~". |
| pageNum | Int32 | Jumlah halaman untuk menampung bidang baru. Jika -1, bidang baru akan disalin ke halaman yang sama dengan yang lama. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Membuat salinan bidang teks pada halaman kedua.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Menyalin field yang ada ke posisi baru yang ditentukan oleh nomor halaman dan ordinat. Dokumen baru akan dihasilkan, yang berisi semua yang dimiliki dokumen sumber kecuali field yang baru disalin.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama bidang yang sepenuhnya memenuhi syarat lama. |
| newFieldName | String | Nama bidang yang sepenuhnya memenuhi syarat baru. Jika null, akan diatur menjadi fieldName + "~". |
| pageNum | Int32 | Jumlah halaman untuk menampung bidang baru. Jika -1, bidang baru akan disalin ke halaman yang sama dengan yang lama. |
| absis | Single | Absis bidang baru. Jika -1, absis akan disamakan dengan yang asli. |
| ordinat | Single | Ordinat bidang baru. Jika -1, ordinat akan disamakan dengan yang asli. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Membuat salinan bidang teks pada halaman kedua.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


