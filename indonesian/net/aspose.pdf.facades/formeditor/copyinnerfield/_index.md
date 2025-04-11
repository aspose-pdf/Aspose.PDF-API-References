---
title: FormEditor.CopyInnerField
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Menyalin field yang ada ke posisi yang sama di nomor halaman yang ditentukan. Dokumen baru akan dihasilkan yang berisi semua yang dimiliki dokumen sumber kecuali untuk field yang baru disalin
type: docs
weight: 150
url: /id/net/aspose.pdf.facades/formeditor/copyinnerfield/
---
## CopyInnerField(string, string, int) {#copyinnerfield}

Menyalin field yang ada ke posisi yang sama di nomor halaman yang ditentukan. Dokumen baru akan dihasilkan, yang berisi semua yang dimiliki dokumen sumber kecuali untuk field yang baru disalin.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang lama dengan kualifikasi lengkap. |
| newFieldName | String | Nama field yang baru dengan kualifikasi lengkap. Jika null, akan diatur sebagai fieldName + "~". |
| pageNum | Int32 | Nomor halaman untuk menampung field baru. Jika -1, field baru akan disalin ke halaman yang sama dengan yang lama. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2);
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyInnerField(string, string, int, float, float) {#copyinnerfield_1}

Menyalin field yang ada ke posisi baru yang ditentukan oleh nomor halaman dan ordinat. Dokumen baru akan dihasilkan, yang berisi semua yang dimiliki dokumen sumber kecuali untuk field yang baru disalin.

```csharp
public void CopyInnerField(string fieldName, string newFieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| fieldName | String | Nama field yang lama dengan kualifikasi lengkap. |
| newFieldName | String | Nama field yang baru dengan kualifikasi lengkap. Jika null, akan diatur sebagai fieldName + "~". |
| pageNum | Int32 | Nomor halaman untuk menampung field baru. Jika -1, field baru akan disalin ke halaman yang sama dengan yang lama. |
| abscissa | Single | Abscissa dari field baru. Jika -1, abscissa akan disamakan dengan yang asli. |
| ordinate | Single | Ordinat dari field baru. Jika -1, ordinat akan disamakan dengan yang asli. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_out.pdf");
//Creates copy of text field on psecond page.
formEditor.CopyInnerField("textField", "textFieldCopy", 2, 100, 200);
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)