---
title: "Izin"
linktitle: "Izin"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Bendera Biner Enum ini mewakili izin pengguna untuk sebuah pdf."
type: docs
weight: 3830
url: /id/java/com.aspose.pdf/permissions/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.Permissions, com.aspose.ms.System.Enum, com.aspose.pdf.Permissions

```
public final class Permissions extends com.aspose.ms.System.Enum
```

Bendera Biner Enum ini mewakili izin pengguna untuk sebuah pdf.

## Fields

| Field | Deskripsi |
| --- | --- |
| [AssembleDocument](#AssembleDocument) | (Penangan keamanan revisi 3 atau lebih) Menyusun dokumen (menyisipkan, memutar, atau menghapus halaman dan membuat penanda atau gambar mini), bahkan jika {@code ModifyContent} tidak diatur. |
| [ExtractContent](#ExtractContent) | (Penangan keamanan revisi 2) Menyalin atau mengekstrak teks dan grafik dari dokumen, termasuk mengekstrak teks dan grafik (untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain). (Penangan keamanan revisi 3 atau lebih) Menyalin atau mengekstrak teks dan grafik dari dokumen melalui operasi selain yang dikendalikan oleh {@code ExtractContentWithDisabilities}. |
| [ExtractContentWithDisabilities](#ExtractContentWithDisabilities) | (Penangan keamanan revisi 3 atau lebih) Mengekstrak teks dan grafik (untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain). |
| [FillForm](#FillForm) | (Penangan keamanan revisi 3 atau lebih) Mengisi bidang formulir interaktif yang ada (termasuk bidang tanda tangan), bahkan jika {@code ModifyTextAnnotations} tidak diatur. |
| [ModifyContent](#ModifyContent) | Memodifikasi isi dokumen melalui operasi selain yang dikendalikan oleh {@code ModifyTextAnnotations}, {@code FillForm}, dan 11. |
| [ModifyTextAnnotations](#ModifyTextAnnotations) | Menambahkan atau memodifikasi anotasi teks, mengisi bidang formulir interaktif, dan, jika {@code ModifyContent} juga diatur, membuat atau memodifikasi bidang formulir interaktif (termasuk bidang tanda tangan). |
| [PrintDocument](#PrintDocument) | (Penangan keamanan revisi 2) Mencetak dokumen. (Penangan keamanan revisi 3 atau lebih) Mencetak dokumen (mungkin tidak pada tingkat kualitas tertinggi, tergantung apakah {@code PrintingQuality} juga diatur). |
| [PrintingQuality](#PrintingQuality) | (Penangan keamanan revisi 3 atau lebih) Cetak dokumen ke representasi dari mana salinan digital yang setia dari konten PDF dapat dihasilkan. Ketika bit ini tidak disetel (dan bit 3 disetel), pencetakan dibatasi pada representasi tingkat rendah dari tampilan, mungkin dengan kualitas yang menurun. |

### AssembleDocument {#AssembleDocument}
```
public static final int AssembleDocument
```

(Penangan keamanan revisi 3 atau lebih) Menyusun dokumen (menyisipkan, memutar, atau menghapus halaman dan membuat penanda atau gambar mini), bahkan jika {@code ModifyContent} tidak diatur.

### ExtractContent {#ExtractContent}
```
public static final int ExtractContent
```

(Penangan keamanan revisi 2) Menyalin atau mengekstrak teks dan grafik dari dokumen, termasuk mengekstrak teks dan grafik (untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain). (Penangan keamanan revisi 3 atau lebih) Menyalin atau mengekstrak teks dan grafik dari dokumen melalui operasi selain yang dikendalikan oleh {@code ExtractContentWithDisabilities}.

### ExtractContentWithDisabilities {#ExtractContentWithDisabilities}
```
public static final int ExtractContentWithDisabilities
```

(Penangan keamanan revisi 3 atau lebih) Mengekstrak teks dan grafik (untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain).

### FillForm {#FillForm}
```
public static final int FillForm
```

(Penangan keamanan revisi 3 atau lebih) Mengisi bidang formulir interaktif yang ada (termasuk bidang tanda tangan), bahkan jika {@code ModifyTextAnnotations} tidak diatur.

### ModifyContent {#ModifyContent}
```
public static final int ModifyContent
```

Memodifikasi isi dokumen melalui operasi selain yang dikendalikan oleh {@code ModifyTextAnnotations}, {@code FillForm}, dan 11.

### ModifyTextAnnotations {#ModifyTextAnnotations}
```
public static final int ModifyTextAnnotations
```

Menambahkan atau memodifikasi anotasi teks, mengisi bidang formulir interaktif, dan, jika {@code ModifyContent} juga diatur, membuat atau memodifikasi bidang formulir interaktif (termasuk bidang tanda tangan).

### PrintDocument {#PrintDocument}
```
public static final int PrintDocument
```

(Penangan keamanan revisi 2) Mencetak dokumen. (Penangan keamanan revisi 3 atau lebih) Mencetak dokumen (mungkin tidak pada tingkat kualitas tertinggi, tergantung apakah {@code PrintingQuality} juga diatur).

### PrintingQuality {#PrintingQuality}
```
public static final int PrintingQuality
```

(Penangan keamanan revisi 3 atau lebih) Cetak dokumen ke representasi dari mana salinan digital yang setia dari konten PDF dapat dihasilkan. Ketika bit ini tidak disetel (dan bit 3 disetel), pencetakan dibatasi pada representasi tingkat rendah dari tampilan, mungkin dengan kualitas yang menurun.
