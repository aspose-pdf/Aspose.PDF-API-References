---
title: Enum Permissions
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.Permissions. Enum ini mewakili izin pengguna untuk sebuah pdf
type: docs
weight: 8480
url: /id/net/aspose.pdf/permissions/
---
## Enumerasi Izin

Enum ini mewakili izin pengguna untuk sebuah pdf.

```csharp
[Flags]
public enum Permissions
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| PrintDocument | `4` | (Pengendali keamanan revisi 2) Mencetak dokumen. (Pengendali keamanan revisi 3 atau lebih) Mencetak dokumen (mungkin tidak pada tingkat kualitas tertinggi, tergantung pada apakah PrintingQuality juga diatur). |
| ModifyContent | `8` | Mengubah isi dokumen dengan operasi selain yang dikendalikan oleh ModifyTextAnnotations, FillForm, dan 11. |
| ExtractContent | `10` | (Pengendali keamanan revisi 2) Menyalin atau mengekstrak teks dan grafik dari dokumen, termasuk mengekstrak teks dan grafik (untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain). (Pengendali keamanan revisi 3 atau lebih) Menyalin atau mengekstrak teks dan grafik dari dokumen dengan operasi selain yang dikendalikan oleh ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Menambahkan atau mengubah anotasi teks, mengisi bidang formulir interaktif, dan, jika ModifyContent juga diatur, membuat atau mengubah bidang formulir interaktif (termasuk bidang tanda tangan). |
| FillForm | `100` | (Pengendali keamanan revisi 3 atau lebih) Mengisi bidang formulir interaktif yang sudah ada (termasuk bidang tanda tangan), bahkan jika ModifyTextAnnotations tidak diatur. |
| ExtractContentWithDisabilities | `200` | (Pengendali keamanan revisi 3 atau lebih) Mengekstrak teks dan grafik (untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain). |
| AssembleDocument | `400` | (Pengendali keamanan revisi 3 atau lebih) Merakit dokumen (menyisipkan, memutar, atau menghapus halaman dan membuat bookmark atau gambar mini), bahkan jika ModifyContent tidak diatur. |
| PrintingQuality | `800` | (Pengendali keamanan revisi 3 atau lebih) Mencetak dokumen ke representasi dari mana salinan digital yang setia dari konten PDF dapat dihasilkan. Ketika bit ini tidak diatur (dan bit 3 diatur), pencetakan dibatasi pada representasi tingkat rendah dari penampilan, mungkin dengan kualitas yang menurun. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)