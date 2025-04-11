---
title: Class PdfViewer
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.Facades.PdfViewer. Mewakili kelas untuk melihat atau mencetak pdf
type: docs
weight: 4630
url: /id/net/aspose.pdf.facades/pdfviewer/
---
## Kelas PdfViewer

Mewakili kelas untuk melihat atau mencetak pdf.

```csharp
public sealed class PdfViewer : IFacade
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [PdfViewer](pdfviewer/#constructor)() | Menginisialisasi objek `PdfViewer` baru. |
| [PdfViewer](pdfviewer/#constructor_1)(Document) | Menginisialisasi objek `PdfViewer` baru. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [AutoResize](../../aspose.pdf.facades/pdfviewer/autoresize/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah file akan dicetak dengan ukuran yang dioptimalkan. Jika false, cetak halaman tanpa skala halaman. Jika true, cetak halaman dengan skala agar sesuai dengan area yang dapat dicetak. |
| [AutoRotate](../../aspose.pdf.facades/pdfviewer/autorotate/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah file akan dicetak dengan rotasi otomatis |
| [AutoRotateMode](../../aspose.pdf.facades/pdfviewer/autorotatemode/) { get; set; } | Mendapatkan atau mengatur nilai AutoRotateMode yang menunjukkan arah rotasi |
| [CoordinateType](../../aspose.pdf.facades/pdfviewer/coordinatetype/) { get; set; } | Mendapatkan atau mengatur jenis koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [FormPresentationMode](../../aspose.pdf.facades/pdfviewer/formpresentationmode/) { get; set; } | Mendapatkan atau mengatur mode presentasi formulir. |
| [HorizontalAlignment](../../aspose.pdf.facades/pdfviewer/horizontalalignment/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan perataan horizontal |
| [PageCount](../../aspose.pdf.facades/pdfviewer/pagecount/) { get; } | Mendapatkan jumlah halaman dari file Pdf saat ini. |
| [Password](../../aspose.pdf.facades/pdfviewer/password/) { get; set; } | Mendapatkan atau mengatur kata sandi dokumen input. |
| [PrintAsGrayscale](../../aspose.pdf.facades/pdfviewer/printasgrayscale/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah halaman dicetak sebagai grayscale. Secara default adalah false. |
| [PrintAsImage](../../aspose.pdf.facades/pdfviewer/printasimage/) { get; set; } | Mengatur atau mendapatkan mode untuk PdfViewer mencetak sebagai gambar. |
| [PrinterJobName](../../aspose.pdf.facades/pdfviewer/printerjobname/) { get; set; } | Mendapatkan atau mengatur nama dokumen dalam antrean printer saat dokumen dicetak. Nilai default adalah nama file. |
| [PrintPageDialog](../../aspose.pdf.facades/pdfviewer/printpagedialog/) { get; set; } | Mendapatkan atau mengatur nilai bool yang menunjukkan apakah menghasilkan dialog nomor halaman saat mencetak. |
| [PrintStatus](../../aspose.pdf.facades/pdfviewer/printstatus/) { get; } | Mendapatkan hasil dari pekerjaan pencetakan. Jika berhasil maka null; jika tidak, objek pengecualian. |
| [RenderingOptions](../../aspose.pdf.facades/pdfviewer/renderingoptions/) { get; set; } | Mendapatkan atau mengatur opsi rendering. |
| [Resolution](../../aspose.pdf.facades/pdfviewer/resolution/) { get; set; } | Mendapatkan atau mengatur resolusi selama melihat dan mencetak. Semakin tinggi resolusi, semakin lambat kecepatannya. Nilai default adalah 150. |
| [ScaleFactor](../../aspose.pdf.facades/pdfviewer/scalefactor/) { get; set; } | Mendapatkan atau mengatur nilai floating point yang menunjukkan faktor skala. Nilai default adalah 1.0. |
| [UseIntermidiateImage](../../aspose.pdf.facades/pdfviewer/useintermidiateimage/) { get; set; } | Mendapatkan/mengatur penggunaan konversi halaman pdf menjadi file png intermidiate selama pencetakan dalam mode file. Gunakan ini ketika ukuran file output penting. |
| [VerticalAlignment](../../aspose.pdf.facades/pdfviewer/verticalalignment/) { get; set; } | Mendapatkan atau mengatur nilai yang menunjukkan perataan vertikal |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf)(Document) | Menginisialisasi facade. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_1)(Stream) | Menginisialisasi facade. |
| [BindPdf](../../aspose.pdf.facades/pdfviewer/bindpdf/#bindpdf_2)(string) | Menginisialisasi facade. |
| [Close](../../aspose.pdf.facades/pdfviewer/close/)() | Menutup facade. |
| [DecodeAllPages](../../aspose.pdf.facades/pdfviewer/decodeallpages/)() | Mendapatkan halaman dari file pdf saat ini. |
| [DecodePage](../../aspose.pdf.facades/pdfviewer/decodepage/)(int) | Mendekode sebuah halaman dari satu file Pdf. |
| [Dispose](../../aspose.pdf.facades/pdfviewer/dispose/)() | Menghapus sumber daya facade. |
| [GetDefaultPageSettings](../../aspose.pdf.facades/pdfviewer/getdefaultpagesettings/)() | Mendapatkan pengaturan halaman default. |
| [GetDefaultPrinterSettings](../../aspose.pdf.facades/pdfviewer/getdefaultprintersettings/)() | Mendapatkan pengaturan printer default. |
| [PrintDocument](../../aspose.pdf.facades/pdfviewer/printdocument/)() | Mencetak dokumen Pdf menggunakan printer default. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings_1)(PrinterSettings) | Mencetak dokumen Pdf dengan pengaturan printer. Ukuran halaman output akan sesuai dengan ukuran halaman pertama dokumen. |
| [PrintDocumentWithSettings](../../aspose.pdf.facades/pdfviewer/printdocumentwithsettings/#printdocumentwithsettings)(PageSettings, PrinterSettings) | Mencetak dokumen Pdf dengan pengaturan. Jika ukuran dokumen tidak sesuai dengan ukuran halaman, itu akan diperpanjang agar sesuai dengan ukuran halaman. |
| [PrintDocumentWithSetup](../../aspose.pdf.facades/pdfviewer/printdocumentwithsetup/)() | Mencetak dokumen Pdf dengan dialog pengaturan. Pilih printer menggunakan dialog. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf)(Stream) | Membuka dan mencetak aliran Pdf besar. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_3)(string) | Membuka dan mencetak file Pdf besar. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_2)(Stream, PrinterSettings) | Membuka dan mencetak aliran Pdf besar dengan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_5)(string, PrinterSettings) | Membuka dan mencetak file Pdf besar dengan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_1)(Stream, PageSettings, PrinterSettings) | Membuka dan mencetak aliran Pdf besar dengan pengaturan halaman dan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. |
| [PrintLargePdf](../../aspose.pdf.facades/pdfviewer/printlargepdf/#printlargepdf_4)(string, PageSettings, PrinterSettings) | Membuka dan mencetak file Pdf besar dengan pengaturan halaman dan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save)(Stream) | Menyimpan dokumen PDF hasil ke aliran. |
| [Save](../../aspose.pdf.facades/pdfviewer/save/#save_1)(string) | Menyimpan dokumen PDF hasil ke file. |

## Acara

| Nama | Deskripsi |
| --- | --- |
| event [CustomPrint](../../aspose.pdf.facades/pdfviewer/customprint/) | Terjadi sebelum pencetakan dimulai dan memungkinkan untuk menyediakan pengendali cetak kustom sebagai pengganti yang default. |
| event [EndPage](../../aspose.pdf.facades/pdfviewer/endpage/) | Terjadi ketika pencetakan sebuah halaman berakhir di PdfViewer. |
| event [EndPrint](../../aspose.pdf.facades/pdfviewer/endprint/) | Menambah/menghapus langganan pada acara pencetakan halaman terakhir. |
| event [PdfQueryPageSettings](../../aspose.pdf.facades/pdfviewer/pdfquerypagesettings/) | Menambah/menghapus langganan pada acara pencetakan halaman terakhir. |
| event [StartPage](../../aspose.pdf.facades/pdfviewer/startpage/) | Terjadi sebelum sebuah halaman mulai dicetak. |

### Lihat Juga

* interface [IFacade](../ifacade/)
* namespace [Aspose.Pdf.Facades](../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../)