---
title: "Kelas HtmlSaveOptions.HtmlImageSavingInfo"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo. Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file gambar sumber daya eksternal selama konversi PDF ke HTML"
type: docs
weight: 5770
url: /id/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## HtmlSaveOptions.HtmlImageSavingInfo class

Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file gambar sumber daya eksternal selama konversi PDF ke HTML.

```csharp
public class HtmlImageSavingInfo : ResourceSavingInfo
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [HtmlImageSavingInfo](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/.ctor)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Ditentukan oleh konverter. Nama file yang diharapkan yang diteruskan dari konverter ke kode metode khusus. Dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan file tersebut. |

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Ditentukan oleh konverter. Mewakili konten biner dari file yang disimpan. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | bendera ini harus disetel ke "true" dalam kode khusus jika karena alasan tertentu file yang diusulkan harus diproses bukan dengan kode khusus melainkan dengan kode konverter itu sendiri dengan cara standar konverter. Jadi, pengaturannya disetel ke true berarti bahwa kode khusus tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri (dalam kedua konteks - untuk menyimpan di suatu tempat dan untuk penamaan dalam file referensi). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Memberitahu kode khusus pada halaman mana dari kumpulan file halaman HTML yang dihasilkan gambar yang disimpan terkait. Jika pemisahan pada halaman dimatikan nilai ini selalu berisi '1' karena dalam kasus tersebut hanya satu halaman HTML yang dihasilkan. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Mewakili tipe gambar yang disimpan yang direferensikan dalam HTML. Diatur oleh konverter dan dapat digunakan dalam kode khusus untuk memutuskan apa yang harus dilakukan. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | Gambar yang disimpan dapat terkait dengan HTML itu sendiri atau dapat diekstrak dari SVG yang disematkan ke HTML. Properti ini dapat memberi tahu kode khusus tipe orang tua dari gambar yang diproses. Ini diatur oleh konverter dan dapat digunakan dalam kode khusus untuk memutuskan apa yang harus dilakukan dengan gambar tersebut (misalnya kode khusus dapat memutuskan di mana menyimpan gambar atau bagaimana gambar harus direferensikan dalam konten orang tua). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Memberitahu kode khusus pada halaman mana dari dokumen PDF asli gambar yang disimpan terkait. Karena mungkin tidak semua halaman dokumen asli akan disimpan, nilai ini memberi tahu kita tentang nomor halaman host dalam PDF asli. Jika nomor halaman asli karena suatu alasan tidak diketahui, selalu mengembalikan '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Ditentukan oleh konverter. Nama file yang diharapkan yang diteruskan dari konverter ke kode metode khusus. Dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan file tersebut. |

### Lihat Juga

* class [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


