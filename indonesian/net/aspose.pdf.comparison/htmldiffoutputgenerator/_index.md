---
title: Class HtmlDiffOutputGenerator
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Comparison.HtmlDiffOutputGenerator. Mewakili kelas untuk menghasilkan representasi html dari perbedaan teks. Baris yang dihapus ditunjukkan dengan tanda paragraf
type: docs
weight: 3200
url: /id/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## Kelas HtmlDiffOutputGenerator

Mewakili kelas untuk menghasilkan representasi html dari perbedaan teks. Baris yang dihapus ditunjukkan dengan tanda paragraf.

```csharp
public class HtmlDiffOutputGenerator : IFileOutputGenerator, IStringOutputGenerator
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor)() | Membuat instance dari kelas `HtmlDiffOutputGenerator`. |
| [HtmlDiffOutputGenerator](htmldiffoutputgenerator/#constructor_1)(OutputTextStyle) | Membuat instance dari kelas `HtmlDiffOutputGenerator`. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Mendapatkan dan mengatur string gaya CSS untuk operasi Hapus. Contoh: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Mendapatkan dan mengatur string gaya CSS untuk operasi Sama. Contoh: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Mendapatkan dan mengatur string gaya CSS untuk operasi Sisipkan. Contoh: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Mendapatkan atau mengatur gaya text-decoration: line-through untuk operasi hapus. Nilai default adalah `False`. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Menghasilkan output berdasarkan perbedaan antara teks dan menyimpannya ke file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Menghasilkan output berdasarkan perbedaan antara teks dan menyimpannya ke file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Menghasilkan output berdasarkan perbedaan antara teks dan menyimpannya ke file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Menghasilkan output berdasarkan perbedaan antara teks dan menyimpannya ke file. |

### Lihat Juga

* antarmuka [IFileOutputGenerator](../ifileoutputgenerator/)
* antarmuka [IStringOutputGenerator](../istringoutputgenerator/)
* ruang nama [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)