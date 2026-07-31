---
title: "Kelas HtmlSaveOptions.HtmlPageMarkupSavingInfo"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Kelas Aspose.Pdf.HtmlSaveOptionsHtmlPageMarkupSavingInfo. Jika properti SplitToPages dari HtmlSaveOptions maka beberapa file HTML, satu file HTML per halaman yang dikonversi, dibuat selama konversi PDF ke HTML. Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan khusus markup satu halaman HTML selama konversi PDF ke HTML."
type: docs
weight: 5800
url: /id/net/aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/
---
## HtmlSaveOptions.HtmlPageMarkupSavingInfo class

Jika properti SplitToPages dari HtmlSaveOptions, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama konversi PDF ke HTML. Kelas ini mewakili sekumpulan data yang terkait dengan penyimpanan khusus markup satu halaman HTML selama konversi PDF ke HTML.

```csharp
public class HtmlPageMarkupSavingInfo
```

## Bidang

| Nama | Deskripsi |
| --- | --- |
| [ContentStream](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/contentstream) | Ditentukan oleh konverter. Mewakili HTML yang disimpan sebagai aliran. |
| [CustomProcessingCancelled](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/customprocessingcancelled) | Harus diatur dalam kode khusus bila diperlukan. Bendera ini harus diset ke "true" dalam kode khusus jika karena alasan tertentu markup html yang diberikan harus diproses bukan dengan kode khusus tetapi dengan kode konverter itu sendiri dengan cara standar untuk konverter. Jadi, mengatur bendera ini dalam kode khusus berarti bahwa kode khusus tidak memproses file yang dirujuk dan konverter harus menanganinya sendiri. |
| [HtmlHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/htmlhostpagenumber) | Ditentukan oleh konverter. Jika properti SplitToPages diatur, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama proses konversi. Properti ini berisi urutan file halaman HTML yang disimpan. Properti ini dapat digunakan dalam logika kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan halaman HTML, dan jika pemisahan halaman dimatikan nilai ini selalu berisi '1' karena dalam kasus tersebut hanya satu halaman HTML besar yang dihasilkan untuk seluruh dokumen sumber. |
| [PdfHostPageNumber](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/pdfhostpagenumber) | Ditentukan oleh konverter. Jika properti SplitToPages diatur, maka beberapa file HTML (satu file HTML per halaman yang dikonversi) dibuat selama proses konversi. Properti ini memberi tahu kode khusus dari halaman mana dari PDF asli markup HTML yang disimpan dibuat. Jika nomor halaman asli karena alasan tertentu tidak diketahui atau SplitOnPages=false, maka properti ini selalu berisi '0' yang menandakan bahwa konverter tidak dapat menyediakan nomor halaman PDF asli yang tepat untuk file markup HTML yang diberikan. |
| [SupposedFileName](../../aspose.pdf/htmlsaveoptions.htmlpagemarkupsavinginfo/supposedfilename) | Ditentukan oleh konverter. Nama file yang diharapkan yang dikirim dari konverter ke kode metode khusus. Dapat digunakan dalam kode khusus untuk memutuskan bagaimana memproses atau dimana menyimpan konten. |

### Lihat Juga

* class [HtmlSaveOptions](../htmlsaveoptions/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)


