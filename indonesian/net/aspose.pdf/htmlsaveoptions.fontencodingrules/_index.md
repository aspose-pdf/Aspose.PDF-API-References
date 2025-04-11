---
title: Enum HtmlSaveOptions.FontEncodingRules
second_title: Aspose.PDF for .NET API Reference
description: Enum Aspose.Pdf.HtmlSaveOptionsFontEncodingRules. Enumerasi ini mendefinisikan aturan yang menyesuaikan logika pengkodean
type: docs
weight: 5620
url: /id/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## Enumerasi HtmlSaveOptions.FontEncodingRules

Enumerasi ini mendefinisikan aturan yang menyesuaikan logika pengkodean

```csharp
public enum FontEncodingRules : byte
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Default | `0` | Biarkan logika pengkodean "apa adanya" - sesuai dengan spesifikasi PDF |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode adalah mekanisme khusus yang membantu mendekode kode input menjadi simbol unicode. Menurut spesifikasi, itu harus digunakan sebagai mekanisme pertama untuk mendapatkan simbol unicode untuk kode input tertentu. Namun, beberapa dokumen memiliki font non-standar dan untuk mengonversi dokumen ini dengan benar, mungkin perlu untuk mengurangi prioritas ToUnicode dan menggunakan mekanisme lain untuk mendekode kode input. |

### Lihat Juga

* kelas [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)