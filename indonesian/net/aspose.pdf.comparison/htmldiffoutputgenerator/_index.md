---
title: "Class HtmlDiffOutputGenerator"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Comparison.HtmlDiffOutputGenerator class. Mewakili kelas untuk menghasilkan representasi html dari perbedaan teks. Pemutusan baris yang dihapus ditandai dengan tanda paragraf"
type: docs
weight: 3310
url: /id/net/aspose.pdf.comparison/htmldiffoutputgenerator/
---
## HtmlDiffOutputGenerator class

Mewakili kelas untuk menghasilkan representasi html dari perbedaan teks. Pemutusan baris yang dihapus ditandai dengan tanda paragraf.

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
| [DeleteStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/deletestyle/) { get; set; } | Mendapatkan dan mengatur string gaya CSS untuk operasi Delete. Contoh: |
| [EqualStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/equalstyle/) { get; set; } | Mendapatkan dan mengatur string gaya CSS untuk operasi Equal. Contoh: |
| [InsertStyle](../../aspose.pdf.comparison/htmldiffoutputgenerator/insertstyle/) { get; set; } | Mendapatkan dan mengatur string gaya CSS untuk operasi Insert. Contoh: |
| [StrikethroughDeleted](../../aspose.pdf.comparison/htmldiffoutputgenerator/strikethroughdeleted/) { get; set; } | Dapatkan atau atur gaya text-decoration: line-through untuk operasi delete. Nilai default adalah `False`. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput)(List&lt;DiffOperation&gt;) | Menghasilkan output berdasarkan perbedaan antar teks dan menyimpannya ke file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_1)(List&lt;List&lt;DiffOperation&gt;&gt;) | Menghasilkan output berdasarkan perbedaan antar teks dan menyimpannya ke file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_2)(List&lt;DiffOperation&gt;, string) | Menghasilkan output berdasarkan perbedaan antar teks dan menyimpannya ke file. |
| [GenerateOutput](../../aspose.pdf.comparison/htmldiffoutputgenerator/generateoutput/#generateoutput_3)(List&lt;List&lt;DiffOperation&gt;&gt;, string) | Menghasilkan output berdasarkan perbedaan antar teks dan menyimpannya ke file. |

### Lihat Juga

* interface [IFileOutputGenerator](../ifileoutputgenerator/)
* interface [IStringOutputGenerator](../istringoutputgenerator/)
* namespace [Aspose.Pdf.Comparison](../../aspose.pdf.comparison/)
* assembly [Aspose.PDF](../../)


