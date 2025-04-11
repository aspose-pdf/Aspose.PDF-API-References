---
title: Class HtmlSaveOptions.HtmlImageSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.HtmlSaveOptionsHtmlImageSavingInfo. Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file gambar sumber eksternal selama konversi PDF ke HTML
type: docs
weight: 5640
url: /id/net/aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/
---
## Kelas HtmlSaveOptions.HtmlImageSavingInfo

Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan file gambar sumber eksternal selama konversi PDF ke HTML.

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
| [ResourceType](../../aspose.pdf/saveoptions.resourcesavinginfo/resourcetype) { get; } | Ditentukan oleh konverter. Nama file yang diharapkan yang berasal dari konverter ke kode metode kustom. Dapat digunakan dalam kode kustom untuk memutuskan bagaimana memproses atau di mana menyimpan file tersebut. |

## Field

| Nama | Deskripsi |
| --- | --- |
| [ContentStream](../../aspose.pdf/saveoptions.resourcesavinginfo/contentstream) | Ditentukan oleh konverter. Mewakili konten biner dari file yang disimpan. |
| [CustomProcessingCancelled](../../aspose.pdf/saveoptions.resourcesavinginfo/customprocessingcancelled) | Flag ini harus diatur ke "true" dalam kode kustom jika karena alasan tertentu file yang diusulkan harus diproses tidak dengan kode kustom tetapi dengan kode konverter itu sendiri dengan cara standar untuk konverter. Jadi, pengaturannya ke true berarti bahwa kode kustom tidak memproses file yang dirujuk dan konverter harus menangani sendiri (dalam kedua arti - untuk menyimpan di suatu tempat dan untuk penamaan dalam file yang dirujuk). |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/htmlhostpagenumber) | Memberitahu kode kustom halaman mana dari set file halaman HTML yang dihasilkan yang berkaitan dengan gambar yang disimpan. Jika pemisahan halaman dimatikan, nilai ini selalu berisi '1' karena dalam kasus tersebut hanya satu halaman HTML yang dihasilkan. |
| [ImageType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/imagetype) | Mewakili jenis gambar yang disimpan yang dirujuk dalam HTML. Ditentukan oleh konverter dan dapat digunakan dalam kode kustom untuk memutuskan apa yang harus dilakukan. |
| [ParentType](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/parenttype) | Gambar yang disimpan dapat berkaitan dengan HTML itu sendiri atau dapat diekstrak dari SVG yang disematkan ke HTML. Properti ini dapat memberi tahu kode kustom tentang jenis induk dari gambar yang diproses. Ditentukan oleh konverter dan dapat digunakan dalam kode kustom untuk memutuskan apa yang harus dilakukan dengan gambar tersebut (misalnya, kode kustom dapat memutuskan di mana menyimpan gambar atau bagaimana gambar tersebut harus dirujuk dalam konten induknya). |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlimagesavinginfo/pdfhostpagenumber) | Memberitahu kode kustom halaman mana dari dokumen PDF asli yang berkaitan dengan gambar yang disimpan. Karena mungkin tidak semua halaman dari dokumen asli disimpan, nilai ini memberi tahu kita tentang nomor halaman induk dalam PDF asli. Jika nomor halaman asli karena alasan tertentu tidak diketahui, selalu mengembalikan '1'. |
| [SupposedFileName](../../aspose.pdf/saveoptions.resourcesavinginfo/supposedfilename) | Ditentukan oleh konverter. Nama file yang diharapkan yang berasal dari konverter ke kode metode kustom. Dapat digunakan dalam kode kustom untuk memutuskan bagaimana memproses atau di mana menyimpan file tersebut. |

### Lihat Juga

* kelas [ResourceSavingInfo](../saveoptions.resourcesavinginfo/)
* kelas [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)