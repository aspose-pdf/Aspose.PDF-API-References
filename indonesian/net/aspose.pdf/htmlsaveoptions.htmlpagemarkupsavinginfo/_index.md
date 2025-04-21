---
title: Class HtmlSaveOptions.HtmlPageMarkupSavingInfo
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo. Jika properti SplitToPages dari HtmlSaveOptions, maka beberapa file HTML dibuat selama konversi PDF ke HTML. Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan khusus markup satu halaman HTML selama konversi PDF ke HTML
type: docs
weight: 5670
url: /id/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## Kelas HtmlSaveOptions.HtmlPageMarkupSavingInfo

Jika properti SplitToPages dari HtmlSaveOptions, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama konversi PDF ke HTML. Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan khusus markup satu halaman HTML selama konversi PDF ke HTML

```csharp
public class HtmlPageMarkupSavingInfo
```

## Fields

| Nama | Deskripsi |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Diatur oleh konverter. Mewakili HTML yang disimpan sebagai stream |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Harus diatur dalam kode khusus jika perlu. Flag ini harus diatur ke "true" dalam kode khusus jika karena alasan tertentu markup HTML yang disuplai harus diproses bukan dengan kode khusus tetapi dengan kode konverter itu sendiri dengan cara standar untuk konverter. Jadi, pengaturan jika flag ini dalam kode khusus berarti bahwa kode khusus tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Diatur oleh konverter. Jika properti SplitToPages diatur, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama konversi. Properti ini berisi urutan file halaman HTML yang disimpan. Properti ini dapat digunakan dalam logika kode khusus untuk memutuskan bagaimana memproses atau di mana menyimpan halaman HTML dan jika pemisahan pada halaman dimatikan, nilai ini selalu berisi '1' karena dalam kasus seperti itu hanya satu halaman HTML besar yang dihasilkan untuk seluruh dokumen sumber. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Diatur oleh konverter. Jika properti SplitToPages diatur, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama konversi. Properti ini memberi tahu kode khusus dari halaman mana dari PDF asli markup HTML yang disimpan dibuat. Jika nomor halaman asli karena alasan tertentu tidak diketahui atau SplitOnPages=false, maka properti ini selalu berisi '0' yang menandakan bahwa konverter tidak dapat memberikan nomor halaman PDF asli yang tepat untuk file markup HTML yang disuplai. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Diatur oleh konverter. Nama file yang diharapkan yang berasal dari konverter ke kode metode khusus. Dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau di mana menyimpan konten |

### Lihat Juga

* kelas [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)