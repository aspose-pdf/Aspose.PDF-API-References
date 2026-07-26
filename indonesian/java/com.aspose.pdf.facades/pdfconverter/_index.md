---
title: "PdfConverter"
linktitle: "PdfConverter"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili kelas untuk mengonversi setiap halaman file pdf menjadi gambar, kini mendukung BMP, JPEG, PNG, dan TIFF. Konten yang didukung dalam pdf: gambar, formulir, komentar."
type: docs
weight: 390
url: /id/java/com.aspose.pdf.facades/pdfconverter/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.facades.Facade com.aspose.pdf.facades.PdfConverter, com.aspose.pdf.facades.Facade, com.aspose.pdf.facades.PdfConverter

**All Implemented Interfaces:**
com.aspose.ms.System.IDisposable, IFacade, Closeable, AutoCloseable

```
public final class PdfConverter extends Facade
```

Mewakili kelas untuk mengonversi setiap halaman file pdf menjadi gambar, kini mendukung BMP, JPEG, PNG, dan TIFF. Konten yang didukung dalam pdf: gambar, formulir, komentar.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfConverter](#PdfConverter--) | Menginisialisasi objek {@code PdfConverter} baru. |
| [PdfConverter](#PdfConverter-com.aspose.pdf.IDocument-) | Menginisialisasi objek {@code PdfConverter} baru. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [bindPdf](#bindPdf-com.aspose.pdf.Document-) | Mengikat dokumen PDF ke instance {@link PdfConverter} untuk pemrosesan lebih lanjut. |
| [bindPdf](#bindPdf-java.io.InputStream-) | Mengikat aliran Pdf untuk konversi. |
| [bindPdf](#bindPdf-java.lang.String-) | Mengikat file Pdf untuk konversi. |
| [close](#close--) | Tutup instance PdfConverter dan bebaskan sumber daya. |
| [convertPageToPNGMemoryStream](#convertPageToPNGMemoryStream-com.aspose.pdf.Page-) | Hanya untuk penggunaan internal |
| [dispose](#dispose--) | Tutup instance PdfConverter dan bebaskan sumber daya. Metode ini sudah usang, gunakan close() sebagai gantinya. |
| [doConvert](#doConvert--) | <p> Lakukan beberapa pekerjaan awal untuk mengonversi dokumen pdf menjadi gambar. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre> |
| [getCoordinateType](#getCoordinateType--) | Mendapatkan tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [getEndPage](#getEndPage--) | Mendapatkan posisi akhir yang ingin Anda konversi. |
| [getFormPresentationMode](#getFormPresentationMode--) | Mendapatkan mode presentasi formulir. |
| [getNextImage](#getNextImage-java.io.OutputStream-) | Menyimpan gambar ke aliran dengan format gambar default - jpeg. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-) | Menyimpan gambar ke aliran dengan format gambar yang diberikan. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-) | Menyimpan gambar ke aliran dengan format gambar yang diberikan, ukuran, dan kualitas. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-) | Menyimpan gambar ke aliran dengan format gambar dan kualitas yang diberikan. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-) | Menyimpan gambar ke aliran dengan format gambar yang diberikan, ukuran, dan kualitas. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-) | Menyimpan gambar ke aliran dengan format gambar yang diberikan, dimensi, dan kualitas. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-) | Menyimpan gambar ke aliran dengan ukuran halaman yang diberikan. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Menyimpan gambar ke aliran dengan ukuran halaman yang diberikan. |
| [getNextImage](#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Menyimpan gambar ke aliran dengan ukuran halaman, format gambar, dan kualitas yang diberikan. |
| [getNextImage](#getNextImage-java.lang.String-) | Menyimpan gambar ke file dengan format gambar default - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-) | <p> Menyimpan gambar ke file dengan format gambar yang diberikan. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.DoConvert(); String prefix = @"D:\\Test\\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-) | <p> Menyimpan gambar ke file dengan format gambar yang diberikan, ukuran gambar, dan kualitas. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-) | Menyimpan gambar ke file dengan format gambar yang diberikan dan kualitas. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-) | <p> Menyimpan gambar ke file dengan format gambar dan dimensi yang diberikan. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-) | <p> Menyimpan gambar ke file dengan format gambar, dimensi, dan kualitas yang diberikan. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); String prefix = @"D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre> |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-) | Menyimpan gambar ke file dengan ukuran halaman yang diberikan dan format gambar default - jpeg. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-) | Menyimpan gambar ke file dengan ukuran halaman yang diberikan dan format gambar. |
| [getNextImage](#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-) | Menyimpan gambar ke file dengan ukuran halaman, format gambar, dan kualitas yang diberikan. |
| [getPageCount](#getPageCount--) | Mendapatkan jumlah halaman. |
| [getPassword](#getPassword--) | Mendapatkan OwnerPassword dokumen. |
| [getRenderingOptions](#getRenderingOptions--) | Mendapatkan opsi rendering. |
| [getResolution](#getResolution--) | Mendapatkan resolusi selama konversi. Semakin tinggi resolusi, semakin lambat kecepatan konversi. Nilai default adalah 150. |
| [getStartPage](#getStartPage--) | Mendapatkan posisi awal yang ingin Anda konversi. Nilai minimum adalah 1. |
| [getUserPassword](#getUserPassword--) | Mendapatkan UserPassword dokumen. |
| [hasNextImage](#hasNextImage--) | Menunjukkan apakah file pdf memiliki lebih banyak gambar atau tidak. |
| [isShowHiddenAreas](#isShowHiddenAreas--) | Mendapatkan flag yang mengontrol visibilitas area tersembunyi pada halaman. Metode ini sudah usang. |
| [mergeImages](#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-) | Menggabungkan daftar aliran gambar menjadi satu aliran gambar. |
| [mergeImagesAsTiff](#mergeImagesAsTiff-java.util.List-) | Menggabungkan daftar aliran tiff menjadi satu aliran tiff multi-frame. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu aliran TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu aliran TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu aliran TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu aliran TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu aliran TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman, dan menyimpan gambar ke satu aliran TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman, dan menyimpan gambar ke satu aliran TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu aliran TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu aliran TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-) | <p> Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-) | <p> Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\\Test\\test.tiff"); </pre> |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke satu file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke satu file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dan menyimpan gambar ke satu file TIFF. |
| [saveAsTIFF](#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dan menyimpan gambar ke satu file TIFF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu aliran TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-int-int-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu aliran TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu aliran TIFF ClassF. |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-) | <p> Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-int-int-) | <p> Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\\Test\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF(@"D:\\Test\\test.tiff",204,196); </pre> |
| [saveAsTIFFClassF](#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-) | Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF. |
| [setCoordinateType](#setCoordinateType-com.aspose.pdf.PageCoordinateType-) | Mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default. |
| [setEndPage](#setEndPage-int-) | Mengatur posisi akhir yang ingin Anda konversi. gunakan setEndPage(int) sebelum setStartPage(int) |
| [setFormPresentationMode](#setFormPresentationMode-int-) | Mengatur mode presentasi formulir. |
| [setPassword](#setPassword-java.lang.String-) | Mengatur OwnerPassword dokumen. |
| [setRangeOfPages](#setRangeOfPages-int-int-) | Mengatur rentang halaman yang ingin Anda konversi. |
| [setRenderingOptions](#setRenderingOptions-com.aspose.pdf.RenderingOptions-) | Mengatur opsi rendering. |
| [setResolution](#setResolution-com.aspose.pdf.devices.Resolution-) | Mengatur resolusi selama konversi. Semakin tinggi resolusi, semakin lambat kecepatan konversi. Nilai default adalah 150. |
| [setShowHiddenAreas](#setShowHiddenAreas-boolean-) | Usang. |
| [setStartPage](#setStartPage-int-) | Mengatur posisi awal yang ingin Anda konversi. Nilai minimum adalah 1. gunakan setEndPage(int) sebelum setStartPage(int) |
| [setUserPassword](#setUserPassword-java.lang.String-) | Mengatur UserPassword dokumen. |

### PdfConverter {#PdfConverter--}
```
public PdfConverter()
```

Menginisialisasi objek {@code PdfConverter} baru.

### PdfConverter {#PdfConverter-com.aspose.pdf.IDocument-}
Menginisialisasi objek {@code PdfConverter} baru.

### bindPdf {#bindPdf-com.aspose.pdf.Document-}
Mengikat dokumen PDF ke instance {@link PdfConverter} untuk pemrosesan lebih lanjut.

### bindPdf {#bindPdf-java.io.InputStream-}
Mengikat aliran Pdf untuk konversi.

### bindPdf {#bindPdf-java.lang.String-}
Mengikat file Pdf untuk konversi.

### close {#close--}
```
public void close()
```

Tutup instance PdfConverter dan bebaskan sumber daya.

### convertPageToPNGMemoryStream {#convertPageToPNGMemoryStream-com.aspose.pdf.Page-}
Hanya untuk penggunaan internal

### dispose {#dispose--}
```
@Deprecated public void dispose()
```

Tutup instance PdfConverter dan bebaskan sumber daya. Metode ini sudah usang, gunakan close() sebagai gantinya.

### doConvert {#doConvert--}
```
public void doConvert()
```

<p> Lakukan beberapa pekerjaan awal untuk mengonversi dokumen pdf menjadi gambar. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\Test\\test.pdf"); converter.doConvert(); String prefix = "D:\\Test\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix); imageCount++; } </pre>

### getCoordinateType {#getCoordinateType--}
```
public PageCoordinateType getCoordinateType()
```

Mendapatkan tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default.

**Returns:**
Elemen PageCoordinateType @see PageCoordinateType

### getEndPage {#getEndPage--}
```
public int getEndPage()
```

Mendapatkan posisi akhir yang ingin Anda konversi.

**Returns:**
nilai int

### getFormPresentationMode {#getFormPresentationMode--}
```
public int getFormPresentationMode()
```

Mendapatkan mode presentasi formulir.

**Returns:**
mode presentasi formulir. @see FormPresentationMode

### getNextImage {#getNextImage-java.io.OutputStream-}
Menyimpan gambar ke aliran dengan format gambar default - jpeg.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-}
Menyimpan gambar ke aliran dengan format gambar yang diberikan.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-double-double-int-}
Menyimpan gambar ke aliran dengan format gambar yang diberikan, ukuran, dan kualitas.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-}
Menyimpan gambar ke aliran dengan format gambar dan kualitas yang diberikan.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-}
Menyimpan gambar ke aliran dengan format gambar yang diberikan, ukuran, dan kualitas.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.ImageType-int-int-int-}
Menyimpan gambar ke aliran dengan format gambar yang diberikan, dimensi, dan kualitas.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-}
Menyimpan gambar ke aliran dengan ukuran halaman yang diberikan.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Menyimpan gambar ke aliran dengan ukuran halaman yang diberikan.

### getNextImage {#getNextImage-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Menyimpan gambar ke aliran dengan ukuran halaman, format gambar, dan kualitas yang diberikan.

### getNextImage {#getNextImage-java.lang.String-}
Menyimpan gambar ke file dengan format gambar default - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-}
<p> Menyimpan gambar ke file dengan format gambar yang diberikan. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.DoConvert(); String prefix = @"D:\Test\"; String suffix = ".png"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Png); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-double-double-int-}
<p> Menyimpan gambar ke file dengan format gambar, ukuran gambar, dan kualitas yang diberikan. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; float pixelX=800f; float pixelY=600f; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, pixelX, pixelY, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-}
Menyimpan gambar ke file dengan format gambar yang diberikan dan kualitas.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-}
<p> Menyimpan gambar ke file dengan format gambar dan dimensi yang diberikan. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.DoConvert(); String prefix = "D:\\\\Test\\\\"; String suffix = ".jpg"; int imageCount = 1; while (converter.hasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.ImageType-int-int-int-}
<p> Menyimpan gambar ke file dengan format gambar, dimensi, dan kualitas yang diberikan. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); String prefix = @"D:\Test\"; String suffix = ".jpg"; int imageCount = 1; while (converter.HasNextImage()) { converter.getNextImage(prefix + imageCount + suffix, ImageFormat.Jpeg, 800, 1000, 50); imageCount++; } </pre>

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-}
Menyimpan gambar ke file dengan ukuran halaman yang diberikan dan format gambar default - jpeg.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-}
Menyimpan gambar ke file dengan ukuran halaman yang diberikan dan format gambar.

### getNextImage {#getNextImage-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.ImageType-int-}
Menyimpan gambar ke file dengan ukuran halaman, format gambar, dan kualitas yang diberikan.

### getPageCount {#getPageCount--}
```
public int getPageCount()
```

Mendapatkan jumlah halaman.

**Returns:**
nilai int

### getPassword {#getPassword--}
```
public String getPassword()
```

Mendapatkan OwnerPassword dokumen.

**Returns:**
nilai String

### getRenderingOptions {#getRenderingOptions--}
```
public RenderingOptions getRenderingOptions()
```

Mendapatkan opsi rendering.

**Returns:**
opsi rendering.

### getResolution {#getResolution--}
```
public Resolution getResolution()
```

Mendapatkan resolusi selama konversi. Semakin tinggi resolusi, semakin lambat kecepatan konversi. Nilai default adalah 150.

**Returns:**
Elemen Resolusi

### getStartPage {#getStartPage--}
```
public int getStartPage()
```

Mendapatkan posisi awal yang ingin Anda konversi. Nilai minimum adalah 1.

**Returns:**
nilai int

### getUserPassword {#getUserPassword--}
```
public String getUserPassword()
```

Mendapatkan UserPassword dokumen.

**Returns:**
nilai String

### hasNextImage {#hasNextImage--}
```
public boolean hasNextImage()
```

Menunjukkan apakah file pdf memiliki lebih banyak gambar atau tidak.

**Returns:**
Dapat mengambil lebih banyak gambar atau tidak, true jika dapat, atau false.

### isShowHiddenAreas {#isShowHiddenAreas--}
```
@Deprecated public boolean isShowHiddenAreas()
```

Mendapatkan flag yang mengontrol visibilitas area tersembunyi pada halaman. Metode ini sudah usang.

**Returns:**
nilai boolean

### mergeImages {#mergeImages-java.util.List-com.aspose.pdf.ImageFormat-com.aspose.pdf.facades.ImageMergeMode-java.lang.Integer-java.lang.Integer-}
Menggabungkan daftar aliran gambar menjadi satu aliran gambar.

### mergeImagesAsTiff {#mergeImagesAsTiff-java.util.List-}
Menggabungkan daftar aliran tiff menjadi satu aliran tiff multi-frame.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu aliran TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.CompressionType-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu aliran TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.CompressionType-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu aliran TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu aliran TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu aliran TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman, dan menyimpan gambar ke satu aliran TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman, dan menyimpan gambar ke satu aliran TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu aliran TIFF.

### saveAsTIFF {#saveAsTIFF-java.io.OutputStream-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu aliran TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-}
<p> Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.CompressionType-}
<p> Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@"D:\Test\test.pdf"); converter.doConvert(); converter.saveAsTIFF(@"D:\Test\test.tiff"); </pre>

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.CompressionType-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-int-int-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dimensi, dan menyimpan gambar ke satu file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke satu file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.PageSize-com.aspose.pdf.devices.TiffSettings-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan ukuran halaman dan menyimpan gambar ke satu file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dan menyimpan gambar ke satu file TIFF.

### saveAsTIFF {#saveAsTIFF-java.lang.String-com.aspose.pdf.devices.TiffSettings-com.aspose.pdf.IIndexBitmapConverter-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dengan dan menyimpan gambar ke satu file TIFF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu aliran TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-int-int-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu aliran TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.io.OutputStream-com.aspose.pdf.PageSize-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu aliran TIFF ClassF.

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-}
<p> Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf("D:\\\\Test\\\\test.pdf"); converter.doConvert(); converter.saveAsTIFFClassF("D:\\\\Test\\\\test.tiff"); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-int-int-}
<p> Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF. </p> <hr> <pre> PdfConverter converter = new PdfConverter(); converter.bindPdf(@\"D:\\Test\\test.pdf\"); converter.doConvert(); converter.saveAsTIFFClassF(@\"D:\\Test\\test.tiff\",204,196); </pre>

### saveAsTIFFClassF {#saveAsTIFFClassF-java.lang.String-com.aspose.pdf.PageSize-}
Mengonversi setiap halaman dokumen pdf menjadi gambar dan menyimpan gambar ke satu file TIFF ClassF.

### setCoordinateType {#setCoordinateType-com.aspose.pdf.PageCoordinateType-}
Mengatur tipe koordinat halaman (Media/Crop boxes). Nilai CropBox digunakan secara default.

### setEndPage {#setEndPage-int-}
```
public void setEndPage(int value)
```

Mengatur posisi akhir yang ingin Anda konversi. gunakan setEndPage(int) sebelum setStartPage(int)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setFormPresentationMode {#setFormPresentationMode-int-}
```
public void setFormPresentationMode(int value)
```

Mengatur mode presentasi formulir.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | mode presentasi formulir. @see FormPresentationMode |

### setPassword {#setPassword-java.lang.String-}
Mengatur OwnerPassword dokumen.

### setRangeOfPages {#setRangeOfPages-int-int-}
```
public void setRangeOfPages(int startPage, int EndPage)
```

Mengatur rentang halaman yang ingin Anda konversi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| startPage |  | nilai int |
| EndPage |  | nilai int |

### setRenderingOptions {#setRenderingOptions-com.aspose.pdf.RenderingOptions-}
Mengatur opsi rendering.

### setResolution {#setResolution-com.aspose.pdf.devices.Resolution-}
Mengatur resolusi selama konversi. Semakin tinggi resolusi, semakin lambat kecepatan konversi. Nilai default adalah 150.

### setShowHiddenAreas {#setShowHiddenAreas-boolean-}
```
@Deprecated public void setShowHiddenAreas(boolean value)
```

Usang.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  |  |

### setStartPage {#setStartPage-int-}
```
public void setStartPage(int value)
```

Mengatur posisi awal yang ingin Anda konversi. Nilai minimum adalah 1. gunakan setEndPage(int) sebelum setStartPage(int)

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setUserPassword {#setUserPassword-java.lang.String-}
Mengatur UserPassword dokumen.
