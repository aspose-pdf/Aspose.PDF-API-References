---
title: "Enum Permissions"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Enum Aspose.Pdf.Permissions. Enum ini mewakili izin pengguna untuk sebuah pdf"
type: docs
weight: 8610
url: /id/net/aspose.pdf/permissions/
---
## Permissions enumeration

Enum ini mewakili izin pengguna untuk pdf.

```csharp
[Flags]
public enum Permissions
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| PrintDocument | `4` | (Security handlers of revision 2) Cetak dokumen. (Security handlers of revision 3 atau lebih) Cetak dokumen (mungkin tidak pada tingkat kualitas tertinggi, tergantung apakah PrintingQuality juga diatur). |
| ModifyContent | `8` | Modifikasi isi dokumen dengan operasi selain yang dikendalikan oleh ModifyTextAnnotations, FillForm, dan 11. |
| ExtractContent | `10` | (Security handlers of revision 2) Salin atau ekstrak teks dan grafik dari dokumen, termasuk mengekstrak teks dan grafik (untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain). (Security handlers of revision 3 atau lebih) Salin atau ekstrak teks dan grafik dari dokumen dengan operasi selain yang dikendalikan oleh ExtractContentWithDisabilities. |
| ModifyTextAnnotations | `20` | Tambahkan atau modifikasi anotasi teks, isi bidang formulir interaktif, dan, jika ModifyContent juga diatur, buat atau modifikasi bidang formulir interaktif (termasuk bidang tanda tangan). |
| FillForm | `100` | (Security handlers of revision 3 atau lebih) Isi bidang formulir interaktif yang ada (termasuk bidang tanda tangan), bahkan jika ModifyTextAnnotations tidak diatur. |
| ExtractContentWithDisabilities | `200` | (Security handlers of revision 3 atau lebih) Ekstrak teks dan grafik (untuk mendukung aksesibilitas bagi pengguna dengan disabilitas atau untuk tujuan lain). |
| AssembleDocument | `400` | (Security handlers of revision 3 atau lebih) Susun dokumen (sisipkan, putar, atau hapus halaman serta buat bookmark atau gambar thumbnail), bahkan jika ModifyContent tidak diatur. |
| PrintingQuality | `800` | (Security handlers of revision 3 atau lebih) Cetak dokumen ke representasi yang dapat menghasilkan salinan digital yang setia dari konten PDF. Ketika bit ini tidak diatur (dan bit 3 diatur), pencetakan dibatasi pada representasi tingkat rendah dari tampilan, mungkin dengan kualitas yang menurun. |

### Lihat Juga

* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


