---
title: FormEditor.CopyOuterField
second_title: Aspose.PDF for .NET API Reference
description: Metode FormEditor. Menyalin field yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan ordinat asli. Catatan: Hanya untuk field AcroForm.
type: docs
weight: 160
url: /id/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Menyalin field yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan ordinat asli. Catatan: Hanya untuk field AcroForm (tidak termasuk radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcFileName | String | Nama dokumen PDF yang berisi field yang akan disalin. |
| fieldName | String | Nama field yang sepenuhnya terqualified asli. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//copies text field from source.pdf to PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Menyalin field yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman yang ditentukan dan ordinat asli. Catatan: Hanya untuk field AcroForm (tidak termasuk radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcFileName | String | Nama dokumen PDF yang berisi field yang akan disalin. |
| fieldName | String | Nama field yang sepenuhnya terqualified asli. |
| pageNum | Int32 | Nomor halaman untuk menampung field baru. Jika -1, field baru akan disalin ke halaman yang sama dengan yang lama. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Menyalin field yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan ordinat yang ditentukan. Catatan: Hanya untuk field AcroForm (tidak termasuk radio box).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcFileName | String | Nama dokumen PDF yang berisi field yang akan disalin. |
| fieldName | String | Nama field yang sepenuhnya terqualified asli. |
| pageNum | Int32 | Nomor halaman untuk menampung field baru. Jika -1, field baru akan disalin ke halaman yang sama dengan yang lama. |
| abscissa | Single | Abscissa dari field baru. Jika -1, abscissa akan disamakan dengan yang asli. |
| ordinate | Single | Ordinat dari field baru. Jika -1, ordinat akan disamakan dengan yang asli. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Lihat Juga

* kelas [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)