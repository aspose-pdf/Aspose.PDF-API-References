---
title: "PdfViewer"
linktitle: "PdfViewer"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk melihat atau mencetak PDF."
type: docs
weight: 610
url: /id/java/com.aspose.pdf.facades/pdfviewer/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.PdfViewer

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfViewer extends Object implements IFacade
```

Mewakili kelas untuk melihat atau mencetak PDF.

## Fields

| Field | Deskripsi |
| --- | --- |
| [CustomPrint](#CustomPrint) |  |
| [EndPrint](#EndPrint) | Menambahkan/menghapus langganan pada peristiwa pencetakan halaman terakhir. |
| [PdfQueryPageSettings](#PdfQueryPageSettings) | Menambahkan/menghapus langganan pada peristiwa pencetakan halaman terakhir. |

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfViewer](#PdfViewer--) | Menginisialisasi objek {@code PdfViewer} baru. |
| [PdfViewer](#PdfViewer-com.aspose.pdf.IDocument-) | Menginisialisasi objek {@code PdfViewer} baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.IDocument-) | Menginisialisasi facade. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Menginisialisasi facade. |
| [bindPdf](#bindPdf-java.lang.String-) | Menginisialisasi facade. |
| [close](#close--) | Menutup file Pdf saat ini. |
| [closePdfFile](#closePdfFile--) | Menutup file Pdf saat ini. |
| [decodeAllPages](#decodeAllPages--) | Mendapatkan halaman dari file pdf saat ini. |
| [decodePage](#decodePage-int-) | Mendekode sebuah halaman dari satu file Pdf. |
| [decodePageToImage](#decodePageToImage-int-com.aspose.pdf.ImageType-) | Mendekode halaman menjadi BufferedImage |
| [dispose](#dispose--) | Membuang sumber daya facade. Metode ini sudah usang, gunakan close() sebagai gantinya. |
| [getAutoResize](#getAutoResize--) | Mengatur nilai bool yang menunjukkan apakah file akan dicetak dengan ukuran yang dioptimalkan. |
| [getAutoRotate](#getAutoRotate--) | Mendapatkan nilai bool yang menunjukkan apakah file akan dicetak dengan rotasi otomatis |
| [getAutoRotateMode](#getAutoRotateMode--) | Mendapatkan nilai AutoRotateMode yang menunjukkan arah rotasi |
| [getCoordinateType](#getCoordinateType--) | Mendapatkan tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [getCopiesPrinted](#getCopiesPrinted--) | Mendapatkan jumlah salinan yang dicetak |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Mendapatkan pengaturan halaman default. |
| [getDefaultPrinterSettings](#getDefaultPrinterSettings--) | Mendapatkan pengaturan printer default. |
| [getFormPresentationMode](#getFormPresentationMode--) | Mendapatkan mode presentasi formulir. |
| [getHorizontalAlignment](#getHorizontalAlignment--) | Mendapatkan nilai yang menunjukkan perataan horizontal |
| [getPageCount](#getPageCount--) | Mendapatkan jumlah halaman dari file Pdf saat ini. |
| [getPassword](#getPassword--) | Mendapatkan kata sandi dokumen input. |
| [getPrintAsGrayscale](#getPrintAsGrayscale--) | <p> Mendapatkan atau mengatur nilai bool yang menunjukkan apakah halaman dicetak dalam skala abu-abu. Secara default adalah false. </p> <hr> Default false adalah false. |
| [getPrintAsImage](#getPrintAsImage--) | <p> Mendapatkan mode untuk PdfViewer mencetak sebagai gambar. </p> |
| [getPrinterJobName](#getPrinterJobName--) | Mendapatkan nama dokumen dalam antrian printer saat dokumen dicetak. Nilai default adalah nama file. |
| [getPrintPageDialog](#getPrintPageDialog--) | Mendapatkan nilai bool yang menunjukkan apakah menghasilkan dialog nomor halaman saat mencetak. |
| [getPrintStatus](#getPrintStatus--) | Mendapatkan hasil pekerjaan pencetakan. Jika berhasil maka null; jika tidak, objek pengecualian. |
| [getRenderingOptions](#getRenderingOptions--) | Mendapatkan opsi rendering. |
| [getResolution](#getResolution--) | Mendapatkan atau mengatur resolusi selama melihat dan mencetak. Semakin tinggi resolusi, semakin lambat kecepatan. Nilai default adalah 150. Properti ini mengubah resolusi gambar dalam alur konversi halaman-ke-gambar: ketika {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) diatur ke {@code }, atau ketika metode {@link #decodePage(int)} atau {@link #decodeAllPages} dipanggil. Untuk mengatur resolusi printer untuk pencetakan langsung ke printer, gunakan properti {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) dalam kelas {@code PageSettings}. |
| [getScaleFactor](#getScaleFactor--) | Mendapatkan nilai titik mengambang yang menunjukkan faktor skala. Nilai default adalah 1.0. |
| [getUseIntermidiateImage](#getUseIntermidiateImage--) | Mendapatkan penggunaan konversi halaman pdf menjadi file png perantara selama pencetakan dalam mode file. Gunakan ketika ukuran file output penting. |
| [getVerticalAlignment](#getVerticalAlignment--) | Mendapatkan nilai yang menunjukkan perataan vertikal |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Metode ini sudah tidak dipakai lagi. Mendapatkan flag yang mengontrol visibilitas area tersembunyi pada halaman. |
| [openPdfFile](#openPdfFile-java.io.InputStream-) | <p> Membuka aliran file Pdf. Tetapi tidak benar-benar mendekode halaman-halaman file Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream(\"d:\\\\test.pdf\"))); viewer.closePdfFile(); </pre> |
| [openPdfFile](#openPdfFile-java.lang.String-) | <p> Membuka file Pdf, tetapi tidak benar-benar mendekode halaman-halaman file Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(\"d:\\\\test.pdf\"); viewer.closePdfFile(); </pre> |
| [printDocument](#printDocument--) | <p> Mencetak dokumen Pdf menggunakan printer default. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(\"d:\\\\test.pdf\"); viewer.setAutoResize ( true); //cetak file dengan ukuran yang disesuaikan viewer.setAutoRotate ( true); //cetak file dengan rotasi yang disesuaikan viewer.setPrintPageDialog ( false); //jangan menghasilkan dialog nomor halaman saat mencetak viewer.printDocument(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Mencetak dokumen Pdf dengan pengaturan printer. Ukuran halaman output akan menyesuaikan ukuran halaman pertama dokumen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(\"d:\\\\test.pdf\"); viewer.setAutoResize ( true); //cetak file dengan ukuran yang disesuaikan viewer.setAutoRotate ( true); //cetak file dengan rotasi yang disesuaikan viewer.setPrintPageDialog ( false); //jangan menghasilkan dialog nomor halaman saat mencetak PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre> |
| [printDocumentWithSettings](#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Mencetak dokumen Pdf dengan pengaturan. Jika ukuran dokumen tidak cocok dengan ukuran halaman, pdf.kit akan memperluasnya agar sesuai dengan ukuran halaman. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\\\test.pdf"); viewer.setAutoResize ( true); //cetak file dengan ukuran yang disesuaikan viewer.setAutoRotate ( true); //cetak file dengan rotasi yang disesuaikan viewer.setPrintPageDialog ( false);//jangan tampilkan dialog nomor halaman saat mencetak PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre> |
| [printLargePdf](#printLargePdf-java.io.InputStream-) | <p> Membuka dan mencetak aliran Pdf besar. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //cetak file dengan ukuran yang disesuaikan viewer.setAutoRotate ( true); //cetak file dengan rotasi yang disesuaikan viewer.printPageDialog=false;//jangan tampilkan dialog nomor halaman saat mencetak viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Metode ini telah mengintegrasikan pembukaan dan pencetakan file sehingga Anda tidak perlu memanggil OpenPdfFile() secara eksplisit. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Membuka dan mencetak aliran Pdf besar dengan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); //cetak file dengan ukuran yang disesuaikan viewer.setAutoRotate(true); //cetak file dengan rotasi yang disesuaikan viewer.setPrintPageDialog(false); //jangan tampilkan dialog nomor halaman saat //mencetak PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Metode ini telah mengintegrasikan pembukaan dan pencetakan file sehingga Anda tidak perlu memanggil OpenPdfFile() secara eksplisit. |
| [printLargePdf](#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Membuka dan mencetak aliran Pdf besar dengan pengaturan halaman dan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //cetak file dengan ukuran yang disesuaikan viewer.setAutoRotate ( true); //cetak file dengan rotasi yang disesuaikan viewer.setPrintPageDialog ( false);//jangan tampilkan dialog nomor halaman saat mencetak PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Metode ini telah mengintegrasikan pembukaan dan pencetakan file sehingga Anda tidak perlu memanggil OpenPdfFile() secara eksplisit. |
| [printLargePdf](#printLargePdf-java.lang.String-) | <p> Membuka dan mencetak file Pdf besar. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); //cetak file dengan ukuran yang disesuaikan viewer.setAutoRotate(true); //cetak file dengan rotasi yang disesuaikan viewer.setPrintPageDialog(false);//jangan tampilkan dialog nomor halaman saat //mencetak viewer.setPrintLargePdf("d:\\test.pdf"); </pre> |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Membuka dan mencetak file Pdf besar dengan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Metode ini telah mengintegrasikan pembukaan dan pencetakan file sehingga Anda tidak perlu memanggil OpenPdfFile() secara eksplisit. |
| [printLargePdf](#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | <p> Membuka dan mencetak file Pdf besar dengan pengaturan halaman dan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Metode ini telah mengintegrasikan pembukaan dan pencetakan file sehingga Anda tidak perlu memanggil OpenPdfFile() secara eksplisit. |
| [save](#save-java.io.InputStream-) | Menyimpan dokumen PDF hasil ke stream. |
| [save](#save-java.lang.String-) | Menyimpan dokumen PDF hasil ke file. |
| [setAutoResize](#setAutoResize-boolean-) | Mengatur nilai bool yang menunjukkan apakah file akan dicetak dengan ukuran yang dioptimalkan. |
| [setAutoRotate](#setAutoRotate-boolean-) | Mengatur nilai bool yang menunjukkan apakah file akan dicetak dengan rotasi otomatis |
| [setAutoRotateMode](#setAutoRotateMode-int-) | Mengatur nilai AutoRotateMode yang menunjukkan arah rotasi |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Mengatur mode presentasi formulir. |
| [setHorizontalAlignment](#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-) | Mengatur nilai yang menunjukkan perataan horizontal |
| [setPassword](#setPassword-java.lang.String-) | Mengatur kata sandi dokumen input. |
| [setPrintAsGrayscale](#setPrintAsGrayscale-boolean-) | <p> Mendapatkan atau mengatur nilai bool yang menunjukkan apakah halaman dicetak dalam skala abu-abu. Secara default adalah false. </p> <hr> Default false adalah false. |
| [setPrintAsImage](#setPrintAsImage-boolean-) | <p> Mengatur mode untuk PdfViewer mencetak sebagai gambar. </p> |
| [setPrinterJobName](#setPrinterJobName-java.lang.String-) | Mengatur nama dokumen dalam antrean printer saat dokumen dicetak. Nilai default adalah nama file. |
| [setPrintPageDialog](#setPrintPageDialog-boolean-) | Mengatur nilai boolean yang menunjukkan apakah menghasilkan dialog nomor halaman saat mencetak. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Mengatur opsi rendering. |
| [setResolution](#setResolution-int-) | Mengatur resolusi selama melihat dan mencetak. Semakin tinggi resolusi, semakin lambat kecepatan. Nilai default adalah 150. Properti ini mengubah resolusi gambar dalam alur konversi halaman-ke-gambar: ketika {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) diatur ke {@code }, atau ketika metode {@link #decodePage(int)} atau {@link #decodeAllPages} dipanggil. Untuk mengatur resolusi printer untuk pencetakan langsung ke printer, gunakan properti {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) dalam kelas {@code PageSettings}. |
| [setScaleFactor](#setScaleFactor-float-) | Mengatur nilai floating point yang menunjukkan faktor skala. Nilai default adalah 1.0. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Usang. |
| [setUseIntermidiateImage](#setUseIntermidiateImage-boolean-) | Mengatur penggunaan konversi halaman pdf menjadi file png perantara selama pencetakan dalam mode file. Gunakan ini ketika ukuran file output penting. |
| [setVerticalAlignment](#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-) | Mengatur nilai yang menunjukkan perataan vertikal |

### CustomPrint {#CustomPrint}
```
public final com.aspose.ms.lang.Event<com.aspose.ms.System.EventHandler< CustomPrintEventArgs >> CustomPrint
```



### EndPrint {#EndPrint}
```
public final PdfEvent <com.aspose.ms.System.Drawing.Printing.PrintEventHandler> EndPrint
```

Menambahkan/menghapus langganan pada peristiwa pencetakan halaman terakhir.

### PdfQueryPageSettings {#PdfQueryPageSettings}
```
public final PdfEvent < PdfQueryPageSettingsEventHandler > PdfQueryPageSettings
```

Menambahkan/menghapus langganan pada peristiwa pencetakan halaman terakhir.

### PdfViewer {#PdfViewer--}
```
public PdfViewer()
```

Menginisialisasi objek {@code PdfViewer} baru.

### PdfViewer {#PdfViewer-com.aspose.pdf.IDocument-}
Menginisialisasi objek {@code PdfViewer} baru.

### bindPdf {#bindPdf-com.aspose.pdf.IDocument-}
Menginisialisasi facade.

### bindPdf {#bindPdf-java.io.InputStream-}
Menginisialisasi facade.

### bindPdf {#bindPdf-java.lang.String-}
Menginisialisasi facade.

### close {#close--}
```
public void close()
```

Menutup file Pdf saat ini.

### closePdfFile {#closePdfFile--}
```
public void closePdfFile()
```

Menutup file Pdf saat ini.

### decodeAllPages {#decodeAllPages--}
```
public BufferedImage [] decodeAllPages()
```

Mendapatkan halaman dari file pdf saat ini.

**Returns:**
mengembalikan array gambar halaman Pdf.

### decodePage {#decodePage-int-}
```
public BufferedImage decodePage(int pageNumber)
```

Mendekode sebuah halaman dari satu file Pdf.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman dari satu file Pdf yang harus berada di antara 1 dan PageCount. |

**Returns:**
mengembalikan gambar halaman Pdf.

### decodePageToImage {#decodePageToImage-int-com.aspose.pdf.ImageType-}
Mendekode halaman menjadi BufferedImage

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Membuang sumber daya facade. Metode ini sudah usang, gunakan close() sebagai gantinya.

### getAutoResize {#getAutoResize--}
```
public boolean getAutoResize()
```

Mengatur nilai bool yang menunjukkan apakah file akan dicetak dengan ukuran yang dioptimalkan.

**Returns:**
nilai boolean: Jika false mencetak halaman tanpa skala halaman. Jika true mencetak halaman dengan skala agar sesuai area yang dapat dicetak.

### getAutoRotate {#getAutoRotate--}
```
public boolean getAutoRotate()
```

Mendapatkan nilai bool yang menunjukkan apakah file akan dicetak dengan rotasi otomatis

**Returns:**
nilai boolean

### getAutoRotateMode {#getAutoRotateMode--}
```
public int getAutoRotateMode()
```

Mendapatkan nilai AutoRotateMode yang menunjukkan arah rotasi

**Returns:**
elemen AutoRotateMode @see AutoRotateMode

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Mendapatkan tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default.

**Returns:**
Elemen PageCoordinateType @see PageCoordinateType

### getCopiesPrinted {#getCopiesPrinted--}
```
public int getCopiesPrinted()
```

Mendapatkan jumlah salinan yang dicetak

**Returns:**
nilai int

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Mendapatkan pengaturan halaman default.

**Returns:**
Objek pengaturan halaman.

### getDefaultPrinterSettings {#getDefaultPrinterSettings--}
```
public PdfPrinterSettings getDefaultPrinterSettings()
```

Mendapatkan pengaturan printer default.

**Returns:**
Objek pengaturan halaman.

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Mendapatkan mode presentasi formulir.

**Returns:**
Elemen FormPresentationMode @see FormPresentationMode

### getHorizontalAlignment {#getHorizontalAlignment--}
```
public HorizontalAlignment getHorizontalAlignment()
```

Mendapatkan nilai yang menunjukkan perataan horizontal

**Returns:**
Elemen HorizontalAlignment @see HorizontalAlignment

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Mendapatkan jumlah halaman dari file Pdf saat ini.

**Returns:**
mengembalikan jumlah halaman.

### getPassword {#getPassword--}
```
public String getPassword()
```

Mendapatkan kata sandi dokumen input.

**Returns:**
nilai String

### getPrintAsGrayscale {#getPrintAsGrayscale--}
```
public boolean getPrintAsGrayscale()
```

<p> Mendapatkan atau mengatur nilai bool yang menunjukkan apakah halaman dicetak dalam skala abu-abu. Secara default adalah false. </p> <hr> Default false adalah false.

**Returns:**
nilai boolean

### getPrintAsImage {#getPrintAsImage--}
```
public boolean getPrintAsImage()
```

<p> Mendapatkan mode untuk PdfViewer mencetak sebagai gambar. </p>

**Returns:**
nilai boolean <hr> Jika true selalu mencetak sebagai gambar (menghasilkan gambar yang dicetak) Jika false mencetak langsung ke perangkat jika semua fitur didukung. Jika dokumen berisi fitur yang tidak didukung, sistem dapat secara otomatis memutuskan untuk mencetak sebagai gambar. Nilai default adalah false.

### getPrinterJobName {#getPrinterJobName--}
```
public String getPrinterJobName()
```

Mendapatkan nama dokumen dalam antrian printer saat dokumen dicetak. Nilai default adalah nama file.

**Returns:**
nilai String

### getPrintPageDialog {#getPrintPageDialog--}
```
public boolean getPrintPageDialog()
```

Mendapatkan nilai bool yang menunjukkan apakah menghasilkan dialog nomor halaman saat mencetak.

**Returns:**
nilai boolean

### getPrintStatus {#getPrintStatus--}
```
public Object getPrintStatus()
```

Mendapatkan hasil pekerjaan pencetakan. Jika berhasil maka null; jika tidak, objek pengecualian.

**Returns:**
objek exception atau null

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Mendapatkan opsi rendering.

**Returns:**
objek RenderingOptions

### getResolution {#getResolution--}
```
public int getResolution()
```

Mendapatkan atau mengatur resolusi selama melihat dan mencetak. Semakin tinggi resolusi, semakin lambat kecepatan. Nilai default adalah 150. Properti ini mengubah resolusi gambar dalam alur konversi halaman-ke-gambar: ketika {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) diatur ke {@code }, atau ketika metode {@link #decodePage(int)} atau {@link #decodeAllPages} dipanggil. Untuk mengatur resolusi printer untuk pencetakan langsung ke printer, gunakan properti {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) dalam kelas {@code PageSettings}.

**Returns:**
nilai int

### getScaleFactor {#getScaleFactor--}
```
public float getScaleFactor()
```

Mendapatkan nilai titik mengambang yang menunjukkan faktor skala. Nilai default adalah 1.0.

**Returns:**
nilai titik mengambang.

### getUseIntermidiateImage {#getUseIntermidiateImage--}
```
public boolean getUseIntermidiateImage()
```

Mendapatkan penggunaan konversi halaman pdf menjadi file png perantara selama pencetakan dalam mode file. Gunakan ketika ukuran file output penting.

**Returns:**
nilai boolean.

### getVerticalAlignment {#getVerticalAlignment--}
```
public VerticalAlignment getVerticalAlignment()
```

Mendapatkan nilai yang menunjukkan perataan vertikal

**Returns:**
Elemen VerticalAlignment @see VerticalAlignment

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Metode ini sudah tidak dipakai lagi. Mendapatkan flag yang mengontrol visibilitas area tersembunyi pada halaman.

**Returns:**
nilai boolean

### openPdfFile {#openPdfFile-java.io.InputStream-}
<p> Membuka aliran file Pdf. Tetapi tidak benar-benar mendekode halaman-halaman file Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile(new FileInputStream("d:\\test.pdf"))); viewer.closePdfFile(); </pre>

### openPdfFile {#openPdfFile-java.lang.String-}
<p> Membuka file Pdf, tetapi tidak benar-benar mendekode halaman-halaman file Pdf. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.closePdfFile(); </pre>

### printDocument {#printDocument--}
```
public void printDocument()
```

<p> Mencetak dokumen Pdf menggunakan printer default. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //cetak file dengan ukuran yang disesuaikan viewer.setAutoRotate ( true); //cetak file dengan rotasi yang disesuaikan viewer.setPrintPageDialog ( false); //jangan tampilkan dialog nomor halaman saat mencetak viewer.printDocument(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Mencetak dokumen Pdf dengan pengaturan printer. Ukuran halaman output akan menyesuaikan ukuran halaman pertama dokumen. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //cetak file dengan ukuran yang disesuaikan viewer.setAutoRotate ( true); //cetak file dengan rotasi yang disesuaikan viewer.setPrintPageDialog ( false); //jangan tampilkan dialog nomor halaman saat mencetak PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().PrinterName()); viewer.printDocumentWithSettings(ps); viewer.closePdfFile(); </pre>

### printDocumentWithSettings {#printDocumentWithSettings-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Mencetak dokumen Pdf dengan pengaturan. Jika ukuran dokumen tidak kompatibel dengan ukuran halaman, pdf.kit akan memperluasnya agar sesuai dengan ukuran halaman. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.openPdfFile("d:\\test.pdf"); viewer.setAutoResize ( true); //cetak file dengan ukuran yang disesuaikan viewer.setAutoRotate ( true); //cetak file dengan rotasi yang disesuaikan viewer.setPrintPageDialog ( false);//jangan tampilkan dialog nomor halaman saat mencetak PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings.getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printDocumentWithSettings(pgs, ps); viewer.closePdfFile(); </pre>

### printLargePdf {#printLargePdf-java.io.InputStream-}
<p> Membuka dan mencetak aliran Pdf besar. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //cetak file dengan ukuran yang disesuaikan viewer.setAutoRotate ( true); //cetak file dengan rotasi yang disesuaikan viewer.printPageDialog=false;//jangan tampilkan dialog nomor halaman saat mencetak viewer.printLargePdf(new MemoryStream(File.ReadAllBytes(@"d:\test.pdf"))); viewer.closePdfFile(); </pre> <hr> Metode ini telah mengintegrasikan pembukaan dan pencetakan file sehingga Anda tidak perlu memanggil OpenPdfFile() secara eksplisit.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Membuka dan mencetak aliran Pdf besar dengan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // cetak file dengan ukuran yang disesuaikan viewer.setAutoRotate(true); // cetak file dengan rotasi yang disesuaikan viewer.setPrintPageDialog(false); // jangan tampilkan dialog nomor halaman saat // mencetak PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"), ps); viewer.closePdfFile(); </pre> <hr> Metode ini telah mengintegrasikan pembukaan dan pencetakan file sehingga Anda tidak perlu memanggil OpenPdfFile() secara eksplisit.

### printLargePdf {#printLargePdf-java.io.InputStream-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Membuka dan mencetak aliran Pdf besar dengan pengaturan halaman dan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize ( new PaperSize("A4", 827, 1169)); pgs.setMargins ( new Margins(0, 0, 0, 0)); viewer.printLargePdf(new FileInputStream("d:\\middleware.pdf"),pgs,ps); viewer.closePdfFile(); </pre> <hr> Metode ini telah mengintegrasikan pembukaan dan pencetakan file sehingga Anda tidak perlu memanggil OpenPdfFile() secara eksplisit.

### printLargePdf {#printLargePdf-java.lang.String-}
<p> Membuka dan mencetak file Pdf besar. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false);// do not produce the page number dialog when // printing viewer.setPrintLargePdf("d:\test.pdf"); </pre>

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Membuka dan mencetak file Pdf besar dengan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize ( true); //print the file with adjusted size viewer.setAutoRotate ( true); //print the file with adjusted rotation viewer.setPrintPageDialog ( false);//do not produce the page number dialog when printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName ( prtdoc.getPrinterSettings().getPrinterName()); viewer.printLargePdf("d:\\test.pdf",ps); viewer.closePdfFile(); </pre> <hr> Metode ini telah mengintegrasikan pembukaan dan pencetakan file sehingga Anda tidak perlu memanggil OpenPdfFile() secara eksplisit.

### printLargePdf {#printLargePdf-java.lang.String-com.aspose.pdf.printing.PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
<p> Membuka dan mencetak file Pdf besar dengan pengaturan halaman dan pengaturan printer yang ditentukan. Jika file Pdf Anda memiliki ratusan halaman atau lebih atau ukurannya lebih dari 3 MB, metode ini disarankan untuk mendapatkan kinerja yang lebih baik. </p> <hr> <pre> PdfViewer viewer = new PdfViewer(); viewer.setAutoResize(true); // print the file with adjusted size viewer.setAutoRotate(true); // print the file with adjusted rotation viewer.setPrintPageDialog(false); // do not produce the page number dialog when // printing PrinterSettings ps = new PrinterSettings(); PrintDocument prtdoc = new PrintDocument(); ps.setPrinterName(prtdoc.getPrinterSettings().getPrinterName()); PageSettings pgs = new PageSettings(); pgs.setPaperSize(new PaperSize("A4", 827, 1169)); pgs.setMargins(new Margins(0, 0, 0, 0)); viewer.printLargePdf("d:\\test.pdf", pgs, ps); viewer.closePdfFile(); </pre> <hr> Metode ini telah mengintegrasikan pembukaan dan pencetakan file sehingga Anda tidak perlu memanggil OpenPdfFile() secara eksplisit.

### save {#save-java.io.InputStream-}
Menyimpan dokumen PDF hasil ke stream.

### save {#save-java.lang.String-}
Menyimpan dokumen PDF hasil ke file.

### setAutoResize {#setAutoResize-boolean-}
```
public void setAutoResize(boolean value)
```

Mengatur nilai bool yang menunjukkan apakah file akan dicetak dengan ukuran yang dioptimalkan.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean: Jika false mencetak halaman tanpa skala halaman. Jika true mencetak halaman dengan skala agar sesuai area yang dapat dicetak. |

### setAutoRotate {#setAutoRotate-boolean-}
```
public void setAutoRotate(boolean value)
```

Mengatur nilai bool yang menunjukkan apakah file akan dicetak dengan rotasi otomatis

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setAutoRotateMode {#setAutoRotateMode-int-}
```
public void setAutoRotateMode(int value)
```

Mengatur nilai AutoRotateMode yang menunjukkan arah rotasi

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | elemen AutoRotateMode @see AutoRotateMode |

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default.

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Mengatur mode presentasi formulir.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | Elemen FormPresentationMode |

### setHorizontalAlignment {#setHorizontalAlignment-com.aspose.pdf.HorizontalAlignment-}
Mengatur nilai yang menunjukkan perataan horizontal

### setPassword {#setPassword-java.lang.String-}
Mengatur kata sandi dokumen input.

### setPrintAsGrayscale {#setPrintAsGrayscale-boolean-}
```
public void setPrintAsGrayscale(boolean value)
```

<p> Mendapatkan atau mengatur nilai bool yang menunjukkan apakah halaman dicetak dalam skala abu-abu. Secara default adalah false. </p> <hr> Default false adalah false.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setPrintAsImage {#setPrintAsImage-boolean-}
```
public void setPrintAsImage(boolean value)
```

<p> Mengatur mode untuk PdfViewer mencetak sebagai gambar. </p>

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean <hr> Jika true selalu mencetak sebagai gambar (menghasilkan gambar yang dicetak) Jika false mencetak langsung ke perangkat jika semua fitur didukung. Jika dokumen berisi fitur yang tidak didukung, sistem dapat secara otomatis memutuskan untuk mencetak sebagai gambar. Nilai default adalah false. |

### setPrinterJobName {#setPrinterJobName-java.lang.String-}
Mengatur nama dokumen dalam antrean printer saat dokumen dicetak. Nilai default adalah nama file.

### setPrintPageDialog {#setPrintPageDialog-boolean-}
```
public void setPrintPageDialog(boolean value)
```

Mengatur nilai boolean yang menunjukkan apakah menghasilkan dialog nomor halaman saat mencetak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Mengatur opsi rendering.

### setResolution {#setResolution-int-}
```
public void setResolution(int value)
```

Mengatur resolusi selama melihat dan mencetak. Semakin tinggi resolusi, semakin lambat kecepatan. Nilai default adalah 150. Properti ini mengubah resolusi gambar dalam alur konversi halaman-ke-gambar: ketika {@code PrintAsImage}({@link #getPrintAsImage}/{@link #setPrintAsImage(boolean)}) diatur ke {@code }, atau ketika metode {@link #decodePage(int)} atau {@link #decodeAllPages} dipanggil. Untuk mengatur resolusi printer untuk pencetakan langsung ke printer, gunakan properti {@code PageSettings.PrinterResolution}({@code PageSettings#getPrinterResolution}/{@code PageSettings#setPrinterResolution(PrinterResolution)}) dalam kelas {@code PageSettings}.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setScaleFactor {#setScaleFactor-float-}
```
public void setScaleFactor(float value)
```

Mengatur nilai floating point yang menunjukkan faktor skala. Nilai default adalah 1.0.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai titik mengambang. |

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Usang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  |  |

### setUseIntermidiateImage {#setUseIntermidiateImage-boolean-}
```
public void setUseIntermidiateImage(boolean value)
```

Mengatur penggunaan konversi halaman pdf menjadi file png perantara selama pencetakan dalam mode file. Gunakan ini ketika ukuran file output penting.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean. |

### setVerticalAlignment {#setVerticalAlignment-com.aspose.pdf.VerticalAlignment-}
Mengatur nilai yang menunjukkan perataan vertikal
