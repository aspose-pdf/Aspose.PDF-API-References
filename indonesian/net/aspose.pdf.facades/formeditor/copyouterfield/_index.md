---
title: "FormEditor.CopyOuterField"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode FormEditor. Menyalin field yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan koordinat asli. Catatan: Hanya untuk field AcroForm kecuali kotak radio."
type: docs
weight: 160
url: /id/net/aspose.pdf.facades/formeditor/copyouterfield/
---
## CopyOuterField(string, string) {#copyouterfield}

Menyalin field yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan ordinat asli. Catatan: Hanya untuk field AcroForm (tidak termasuk kotak radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcFileName | String | Nama dokumen PDF yang berisi bidang yang akan disalin. |
| fieldName | String | Nama bidang lengkap yang asli. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
//menyalin bidang teks dari source.pdf ke PdfForm.pdf
formEditor.CopyOuterField("source.pdf", "textField");
formEditor.Save();
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int) {#copyouterfield_1}

Menyalin field yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman yang ditentukan dan ordinat asli. Catatan: Hanya untuk field AcroForm (tidak termasuk kotak radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcFileName | String | Nama dokumen PDF yang berisi bidang yang akan disalin. |
| fieldName | String | Nama bidang lengkap yang asli. |
| pageNum | Int32 | Jumlah halaman untuk menampung bidang baru. Jika -1, bidang baru akan disalin ke halaman yang sama dengan yang lama. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField", 2);
formEditor.Save();
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

---

## CopyOuterField(string, string, int, float, float) {#copyouterfield_2}

Menyalin field yang ada dari satu dokumen PDF ke dokumen lain dengan nomor halaman dan ordinat yang ditentukan. Catatan: Hanya untuk field AcroForm (tidak termasuk kotak radio).

```csharp
public void CopyOuterField(string srcFileName, string fieldName, int pageNum, float abscissa, 
    float ordinate)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| srcFileName | String | Nama dokumen PDF yang berisi bidang yang akan disalin. |
| fieldName | String | Nama bidang lengkap yang asli. |
| pageNum | Int32 | Jumlah halaman untuk menampung bidang baru. Jika -1, bidang baru akan disalin ke halaman yang sama dengan yang lama. |
| absis | Single | Absis bidang baru. Jika -1, absis akan disamakan dengan yang asli. |
| ordinat | Single | Ordinat bidang baru. Jika -1, ordinat akan disamakan dengan yang asli. |

## Contoh

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.CopyOuterField("source.pdf", "textField" , 2, 100, 200);
```

### Lihat Juga

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


