---
title: "PrintPageSettings"
linktitle: "PrintPageSettings"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Menentukan pengaturan yang berlaku untuk satu halaman yang dicetak."
type: docs
weight: 90
url: /id/java/com.aspose.pdf.printing/printpagesettings/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.printing.PrintPageSettings

```
public class PrintPageSettings extends Object
```

Menentukan pengaturan yang berlaku untuk satu halaman yang dicetak.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PrintPageSettings](#PrintPageSettings--) | Menginisialisasi instance baru dari kelas PageSettings menggunakan printer default. |
| [PrintPageSettings](#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Menginisialisasi instance baru dari kelas PageSettings menggunakan printer default. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBounds](#getBounds--) | Mendapatkan ukuran halaman, dengan memperhitungkan orientasi halaman yang ditentukan oleh properti Landscape. |
| [getHardMarginX](#getHardMarginX--) | Mendapatkan koordinat x, dalam satuan per seratus inci, dari margin keras di sisi kiri halaman. |
| [getHardMarginY](#getHardMarginY--) | Mendapatkan koordinat y, dalam satuan per seratus inci, dari margin keras di bagian atas halaman. |
| [getMargins](#getMargins--) | Mendapatkan margin untuk halaman ini. |
| [getPageSettings](#getPageSettings--) | Mendapatkan Pengaturan Halaman |
| [getPaperSize](#getPaperSize--) | Mendapatkan ukuran kertas untuk halaman. |
| [getPaperSource](#getPaperSource--) | Mendapatkan sumber kertas halaman; misalnya, baki atas printer. |
| [getPrintableArea](#getPrintableArea--) | Mendapatkan batas area yang dapat dicetak pada halaman untuk printer. |
| [getPrinterResolution](#getPrinterResolution--) | Mendapatkan resolusi printer untuk halaman. |
| [getPrinterSettings](#getPrinterSettings--) | Mendapatkan pengaturan printer yang terkait dengan halaman. |
| [isColor](#isColor--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah halaman harus dicetak berwarna. |
| [isLandscape](#isLandscape--) | Mendapatkan atau mengatur nilai yang menunjukkan apakah halaman dicetak dalam orientasi lanskap atau potret. |
| [setColor](#setColor-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah halaman harus dicetak berwarna. |
| [setLandscape](#setLandscape-boolean-) | Mendapatkan atau mengatur nilai yang menunjukkan apakah halaman dicetak dalam orientasi lanskap atau potret. |
| [setMargins](#setMargins-com.aspose.pdf.printing.PrinterMargins-) | Mengatur margin untuk halaman ini. |
| [setPaperSize](#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-) | Mengatur ukuran kertas untuk halaman. |
| [setPaperSource](#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-) | Mengatur sumber kertas halaman; misalnya, baki atas printer. |
| [setPrinterResolution](#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-) | Mengatur resolusi printer untuk halaman. |
| [setPrinterSettings](#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-) | Mengatur pengaturan printer yang terkait dengan halaman. |

### PrintPageSettings {#PrintPageSettings--}
```
public PrintPageSettings()
```

Menginisialisasi instance baru dari kelas PageSettings menggunakan printer default.

### PrintPageSettings {#PrintPageSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Menginisialisasi instance baru dari kelas PageSettings menggunakan printer default.

### getBounds {#getBounds--}
```
public Rectangle getBounds()
```

Mendapatkan ukuran halaman, dengan memperhitungkan orientasi halaman yang ditentukan oleh properti Landscape.

**Returns:**
objek Rectangle

### getHardMarginX {#getHardMarginX--}
```
public float getHardMarginX()
```

Mendapatkan koordinat x, dalam satuan per seratus inci, dari margin keras di sisi kiri halaman.

**Returns:**
nilai float

### getHardMarginY {#getHardMarginY--}
```
public float getHardMarginY()
```

Mendapatkan koordinat y, dalam satuan per seratus inci, dari margin keras di bagian atas halaman.

**Returns:**
nilai float

### getMargins {#getMargins--}
```
public PrinterMargins getMargins()
```

Mendapatkan margin untuk halaman ini.

**Returns:**
Objek PrinterMargins

### getPageSettings {#getPageSettings--}
```
public com.aspose.ms.System.Drawing.Printing.PageSettings getPageSettings()
```

Mendapatkan Pengaturan Halaman

**Returns:**
Objek PageSettings

### getPaperSize {#getPaperSize--}
```
public PrintPaperSize getPaperSize()
```

Mendapatkan ukuran kertas untuk halaman.

**Returns:**
Objek PrintPaperSize

### getPaperSource {#getPaperSource--}
```
public PrintPaperSource getPaperSource()
```

Mendapatkan sumber kertas halaman; misalnya, baki atas printer.

**Returns:**
Objek PrintPaperSource

### getPrintableArea {#getPrintableArea--}
```
public Rectangle getPrintableArea()
```

Mendapatkan batas area yang dapat dicetak pada halaman untuk printer.

**Returns:**
objek Rectangle

### getPrinterResolution {#getPrinterResolution--}
```
public PdfPrinterResolution getPrinterResolution()
```

Mendapatkan resolusi printer untuk halaman.

**Returns:**
Objek PdfPrinterResolution

### getPrinterSettings {#getPrinterSettings--}
```
public PdfPrinterSettings getPrinterSettings()
```

Mendapatkan pengaturan printer yang terkait dengan halaman.

**Returns:**
Objek PdfPrinterSettings

### isColor {#isColor--}
```
public boolean isColor()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah halaman harus dicetak berwarna.

**Returns:**
nilai boolean

### isLandscape {#isLandscape--}
```
public boolean isLandscape()
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah halaman dicetak dalam orientasi lanskap atau potret.

**Returns:**
nilai boolean

### setColor {#setColor-boolean-}
```
public void setColor(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah halaman harus dicetak berwarna.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setLandscape {#setLandscape-boolean-}
```
public void setLandscape(boolean value)
```

Mendapatkan atau mengatur nilai yang menunjukkan apakah halaman dicetak dalam orientasi lanskap atau potret.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai boolean |

### setMargins {#setMargins-com.aspose.pdf.printing.PrinterMargins-}
Mengatur margin untuk halaman ini.

### setPaperSize {#setPaperSize-com.aspose.pdf.printing.PrintPaperSize-}
Mengatur ukuran kertas untuk halaman.

### setPaperSource {#setPaperSource-com.aspose.pdf.printing.PrintPaperSource-}
Mengatur sumber kertas halaman; misalnya, baki atas printer.

### setPrinterResolution {#setPrinterResolution-com.aspose.pdf.printing.PdfPrinterResolution-}
Mengatur resolusi printer untuk halaman.

### setPrinterSettings {#setPrinterSettings-com.aspose.pdf.printing.PdfPrinterSettings-}
Mengatur pengaturan printer yang terkait dengan halaman.
