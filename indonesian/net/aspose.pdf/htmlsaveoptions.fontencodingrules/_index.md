---
title: "Enum HtmlSaveOptions.FontEncodingRules"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.HtmlSaveOptionsFontEncodingRules enum. Enumerasi ini mendefinisikan aturan yang menyesuaikan logika pengkodean"
type: docs
weight: 5750
url: /id/net/aspose.pdf/htmlsaveoptions.fontencodingrules/
---
## HtmlSaveOptions.FontEncodingRules enumeration

Enumerasi ini mendefinisikan aturan yang menyesuaikan logika pengkodean

```csharp
public enum FontEncodingRules : byte
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Default | `0` | Biarkan logika pengkodean "as is" - sesuai dengan spesifikasi PDF |
| DecreaseToUnicodePriorityLevel | `1` | ToUnicode adalah mekanisme khusus yang membantu mendekode kode input menjadi simbol unicode. Menurut spesifikasi, mekanisme ini harus menjadi yang pertama digunakan untuk mendapatkan simbol unicode untuk kode input tertentu. Namun beberapa dokumen memiliki font non-standar dan untuk mengonversi dokumen tersebut dengan benar mungkin perlu menurunkan prioritas ToUnicode dan menggunakan mekanisme lain untuk mendekode kode input. |

### Lihat Juga

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


