---
title: "PdfPrinterSettings"
linktitle: "PdfPrinterSettings"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menentukan informasi tentang cara dokumen dicetak, termasuk printer yang mencetaknya."
type: docs
weight: 50
url: /id/java/com.aspose.pdf.printing/pdfprintersettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PdfPrinterSettings

```
public class PdfPrinterSettings extends Object
```

Menentukan informasi tentang cara dokumen dicetak, termasuk printer yang mencetaknya.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PdfPrinterSettings](#PdfPrinterSettings--) | Menginisialisasi instance baru dari kelas PrinterSettings. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [canDuplex](#canDuplex--) | Mendapatkan nilai yang menunjukkan apakah printer mendukung pencetakan dua sisi. |
| [createMeasurementGraphics](#createMeasurementGraphics--) | Dapatkan objek Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-boolean-) | Dapatkan objek Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-) | Dapatkan objek Graphics2D |
| [createMeasurementGraphics](#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-) | Dapatkan objek Graphics2D |
| [deepClone](#deepClone--) | Dapatkan objek yang dikloning |
| [getCopies](#getCopies--) | Mendapatkan jumlah salulan dokumen yang akan dicetak. |
| [getDefaultPageSettings](#getDefaultPageSettings--) | Mendapatkan pengaturan halaman default untuk printer ini. |
| [getDuplex](#getDuplex--) | Mendapatkan atau mengatur pengaturan printer untuk pencetakan dua sisi. |
| [getFromPage](#getFromPage--) | Mendapatkan atau mengatur nomor halaman dari halaman pertama yang akan dicetak. |
| [getInstalledPrinters](#getInstalledPrinters--) | Mendapatkan nama semua printer yang terpasang pada komputer. |
| [getLandscapeAngle](#getLandscapeAngle--) | Mendapatkan sudut, dalam derajat, yang memutar orientasi potret untuk menghasilkan orientasi lanskap. |
| [getMaximumCopies](#getMaximumCopies--) | Mendapatkan jumlah maksimum salinan yang dapat dicetak pengguna sekaligus oleh printer. |
| [getMaximumPage](#getMaximumPage--) | Mendapatkan atau mengatur nilai maksimum FromPage atau ToPage yang dapat dipilih dalam PrintDialog. |
| [getMinimumPage](#getMinimumPage--) | Mendapatkan atau mengatur nilai minimum FromPage atau ToPage yang dapat dipilih dalam PrintDialog. |
| [getPaperSizes](#getPaperSizes--) | Mendapatkan ukuran kertas yang didukung oleh printer ini. |
| [getPaperSources](#getPaperSources--) | Mendapatkan baki sumber kertas yang tersedia pada printer. |
| [getPrinterName](#getPrinterName--) | Mendapatkan atau mengatur nama printer yang akan digunakan. |
| [getPrinterResolutions](#getPrinterResolutions--) | Mendapatkan semua resolusi yang didukung oleh printer ini. |
| [getPrinterSettings](#getPrinterSettings--) | Mengembalikan objek PrinterSettings |
| [getPrintFileName](#getPrintFileName--) | Mendapatkan atau mengatur nama file, saat mencetak ke file. |
| [getPrintRange](#getPrintRange--) | Mendapatkan atau mengatur nomor halaman yang telah ditentukan pengguna untuk dicetak. |
| [getSelectedPages](#getSelectedPages--) | Mendapatkan jumlah halaman yang dipilih untuk dicetak. |
| [getToPage](#getToPage--) | Mendapatkan atau mengatur nomor halaman terakhir yang akan dicetak. |
| [isCollate](#isCollate--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah dokumen yang dicetak terkelompok. |
| [isDefaultPrinter](#isDefaultPrinter--) | Mendapatkan nilai yang menunjukkan apakah properti PrinterName menunjuk ke printer default, kecuali ketika pengguna secara eksplisit mengatur PrinterName. |
| [isDirectPrintingSupported](#isDirectPrintingSupported-com.aspose.pdf.ImageType-) | Mendapatkan nilai yang menunjukkan apakah printer mendukung DirectPrinting |
| [isDirectPrintingSupported](#isDirectPrintingSupported-java.lang.String-) | Mendapatkan nilai yang menunjukkan apakah printer mendukung DirectPrinting |
| [isPlotter](#isPlotter--) | Mendapatkan nilai yang menunjukkan apakah printer adalah plotter. |
| [isPrintToFile](#isPrintToFile--) | Mendapatkan nilai yang menunjukkan apakah output pencetakan dikirim ke file alih-alih ke port. |
| [isSupportsColor](#isSupportsColor--) | Mendapatkan nilai yang menunjukkan apakah printer ini mendukung pencetakan berwarna. |
| [isValid](#isValid--) | Mendapatkan nilai yang menunjukkan apakah properti PrinterName menunjuk ke printer yang valid. |
| [setCollate](#setCollate-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah dokumen yang dicetak terkelompok. |
| [setCopies](#setCopies-short-) | Mengatur jumlah salinan dokumen yang akan dicetak. |
| [setDuplex](#setDuplex-int-) | Mendapatkan atau mengatur pengaturan printer untuk pencetakan dua sisi. |
| [setFromPage](#setFromPage-int-) | Mendapatkan atau mengatur nomor halaman dari halaman pertama yang akan dicetak. |
| [setMaximumPage](#setMaximumPage-int-) | Mendapatkan atau mengatur nilai maksimum FromPage atau ToPage yang dapat dipilih dalam PrintDialog. |
| [setMinimumPage](#setMinimumPage-int-) | Mendapatkan atau mengatur nilai minimum FromPage atau ToPage yang dapat dipilih dalam PrintDialog. |
| [setPrinterName](#setPrinterName-java.lang.String-) | Mengatur nama printer yang akan digunakan. |
| [setPrintFileName](#setPrintFileName-java.lang.String-) | Mengatur nama file untuk dicetak. |
| [setPrintRange](#setPrintRange-int-) | Mengatur nomor halaman yang telah ditentukan pengguna untuk dicetak. |
| [setPrintToFile](#setPrintToFile-boolean-) | Mengatur nilai yang menunjukkan apakah output pencetakan dikirim ke file alih-alih ke port. |
| [setSelectedPages](#setSelectedPages-int:A-) | Mengatur jumlah halaman yang dipilih untuk dicetak. |
| [setToPage](#setToPage-int-) | Mengatur nomor halaman terakhir untuk dicetak. |

### PdfPrinterSettings {#PdfPrinterSettings--}
```
public PdfPrinterSettings()
```

Menginisialisasi instance baru dari kelas PrinterSettings.

### canDuplex {#canDuplex--}
```
public boolean canDuplex()
```

Mendapatkan nilai yang menunjukkan apakah printer mendukung pencetakan dua sisi.

**Returns:**
nilai boolean

### createMeasurementGraphics {#createMeasurementGraphics--}
```
public Graphics2D createMeasurementGraphics()
```

Dapatkan objek Graphics2D

**Returns:**
objek Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-boolean-}
```
public Graphics2D createMeasurementGraphics(boolean value)
```

Dapatkan objek Graphics2D

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

**Returns:**
objek Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-}
Dapatkan objek Graphics2D

**Returns:**
objek Graphics2D

### createMeasurementGraphics {#createMeasurementGraphics-com.aspose.pdf.printing.PrintPageSettings-boolean-}
Dapatkan objek Graphics2D

**Returns:**
objek Graphics2D

### deepClone {#deepClone--}
```
public PdfPrinterSettings deepClone()
```

Dapatkan objek yang dikloning

**Returns:**
Objek PdfPrinterSettings

### getCopies {#getCopies--}
```
public short getCopies()
```

Mendapatkan jumlah salulan dokumen yang akan dicetak.

**Returns:**
jumlah salinan

### getDefaultPageSettings {#getDefaultPageSettings--}
```
public PrintPageSettings getDefaultPageSettings()
```

Mendapatkan pengaturan halaman default untuk printer ini.

**Returns:**
pengaturan halaman default

### getDuplex {#getDuplex--}
```
public int getDuplex()
```

Mendapatkan atau mengatur pengaturan printer untuk pencetakan dua sisi.

**Returns:**
nilai int @see DuplexKind

### getFromPage {#getFromPage--}
```
public int getFromPage()
```

Mendapatkan atau mengatur nomor halaman dari halaman pertama yang akan dicetak.

**Returns:**
nilai int

### getInstalledPrinters {#getInstalledPrinters--}
```
public static ArrayList < String > getInstalledPrinters()
```

Mendapatkan nama semua printer yang terpasang pada komputer.

**Returns:**
objek {@code ArrayList<String>}

### getLandscapeAngle {#getLandscapeAngle--}
```
public int getLandscapeAngle()
```

Mendapatkan sudut, dalam derajat, yang memutar orientasi potret untuk menghasilkan orientasi lanskap.

**Returns:**
nilai int

### getMaximumCopies {#getMaximumCopies--}
```
public int getMaximumCopies()
```

Mendapatkan jumlah maksimum salinan yang dapat dicetak pengguna sekaligus oleh printer.

**Returns:**
nilai int

### getMaximumPage {#getMaximumPage--}
```
public int getMaximumPage()
```

Mendapatkan atau mengatur nilai maksimum FromPage atau ToPage yang dapat dipilih dalam PrintDialog.

**Returns:**
nilai int

### getMinimumPage {#getMinimumPage--}
```
public int getMinimumPage()
```

Mendapatkan atau mengatur nilai minimum FromPage atau ToPage yang dapat dipilih dalam PrintDialog.

**Returns:**
nilai int

### getPaperSizes {#getPaperSizes--}
```
public ArrayList < PrintPaperSize > getPaperSizes()
```

Mendapatkan ukuran kertas yang didukung oleh printer ini.

**Returns:**
objek {@code ArrayList<PrintPaperSize> }

### getPaperSources {#getPaperSources--}
```
public ArrayList < PrintPaperSource > getPaperSources()
```

Mendapatkan baki sumber kertas yang tersedia pada printer.

**Returns:**
objek {@code ArrayList<PrintPaperSource> }

### getPrinterName {#getPrinterName--}
```
public String getPrinterName()
```

Mendapatkan atau mengatur nama printer yang akan digunakan.

**Returns:**
objek string

### getPrinterResolutions {#getPrinterResolutions--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings.PrinterResolutionCollection getPrinterResolutions()
```

Mendapatkan semua resolusi yang didukung oleh printer ini.

**Returns:**
objek PrinterResolutionCollection

### getPrinterSettings {#getPrinterSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PrinterSettings getPrinterSettings()
```

Mengembalikan objek PrinterSettings

**Returns:**
objek PrinterSettings

### getPrintFileName {#getPrintFileName--}
```
public String getPrintFileName()
```

Mendapatkan atau mengatur nama file, saat mencetak ke file.

**Returns:**
objek string

### getPrintRange {#getPrintRange--}
```
public int getPrintRange()
```

Mendapatkan atau mengatur nomor halaman yang telah ditentukan pengguna untuk dicetak.

**Returns:**
nilai int @see PdfPrintRange

### getSelectedPages {#getSelectedPages--}
```
public int[] getSelectedPages()
```

Mendapatkan jumlah halaman yang dipilih untuk dicetak.

**Returns:**
array int pagesList @see PdfPrintRange

### getToPage {#getToPage--}
```
public int getToPage()
```

Mendapatkan atau mengatur nomor halaman terakhir yang akan dicetak.

**Returns:**
nilai int

### isCollate {#isCollate--}
```
public boolean isCollate()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah dokumen yang dicetak terkelompok.

**Returns:**
nilai boolean

### isDefaultPrinter {#isDefaultPrinter--}
```
public boolean isDefaultPrinter()
```

Mendapatkan nilai yang menunjukkan apakah properti PrinterName menunjuk ke printer default, kecuali ketika pengguna secara eksplisit mengatur PrinterName.

**Returns:**
nilai boolean

### isDirectPrintingSupported {#isDirectPrintingSupported-com.aspose.pdf.ImageType-}
Mendapatkan nilai yang menunjukkan apakah printer mendukung DirectPrinting

### isDirectPrintingSupported {#isDirectPrintingSupported-java.lang.String-}
Mendapatkan nilai yang menunjukkan apakah printer mendukung DirectPrinting

### isPlotter {#isPlotter--}
```
public boolean isPlotter()
```

Mendapatkan nilai yang menunjukkan apakah printer adalah plotter.

**Returns:**
nilai boolean

### isPrintToFile {#isPrintToFile--}
```
public boolean isPrintToFile()
```

Mendapatkan nilai yang menunjukkan apakah output pencetakan dikirim ke file alih-alih ke port.

**Returns:**
nilai boolean

### isSupportsColor {#isSupportsColor--}
```
public boolean isSupportsColor()
```

Mendapatkan nilai yang menunjukkan apakah printer ini mendukung pencetakan berwarna.

**Returns:**
nilai boolean

### isValid {#isValid--}
```
public boolean isValid()
```

Mendapatkan nilai yang menunjukkan apakah properti PrinterName menunjuk ke printer yang valid.

**Returns:**
nilai boolean

### setCollate {#setCollate-boolean-}
```
public void setCollate(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah dokumen yang dicetak terkelompok.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setCopies {#setCopies-short-}
```
public void setCopies(short value)
```

Mengatur jumlah salinan dokumen yang akan dicetak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | jumlah salinan |

### setDuplex {#setDuplex-int-}
```
public void setDuplex(int value)
```

Mendapatkan atau mengatur pengaturan printer untuk pencetakan dua sisi.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int @see DuplexKind |

### setFromPage {#setFromPage-int-}
```
public void setFromPage(int value)
```

Mendapatkan atau mengatur nomor halaman dari halaman pertama yang akan dicetak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setMaximumPage {#setMaximumPage-int-}
```
public void setMaximumPage(int value)
```

Mendapatkan atau mengatur nilai maksimum FromPage atau ToPage yang dapat dipilih dalam PrintDialog.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setMinimumPage {#setMinimumPage-int-}
```
public void setMinimumPage(int value)
```

Mendapatkan atau mengatur nilai minimum FromPage atau ToPage yang dapat dipilih dalam PrintDialog.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setPrinterName {#setPrinterName-java.lang.String-}
Mengatur nama printer yang akan digunakan.

### setPrintFileName {#setPrintFileName-java.lang.String-}
Mengatur nama file untuk dicetak.

### setPrintRange {#setPrintRange-int-}
```
public void setPrintRange(int value)
```

Mengatur nomor halaman yang telah ditentukan pengguna untuk dicetak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | elemen PdfPrintRange @see PdfPrintRange |

### setPrintToFile {#setPrintToFile-boolean-}
```
public void setPrintToFile(boolean value)
```

Mengatur nilai yang menunjukkan apakah output pencetakan dikirim ke file alih-alih ke port.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setSelectedPages {#setSelectedPages-int:A-}
```
public void setSelectedPages(int[] pagesList)
```

Mengatur jumlah halaman yang dipilih untuk dicetak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pagesList |  | array int @see PdfPrintRange |

### setToPage {#setToPage-int-}
```
public void setToPage(int value)
```

Mengatur nomor halaman terakhir untuk dicetak.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | elemen PdfPrintRange @see PdfPrintRange |
