---
title: "PageNumberStamp"
linktitle: "PageNumberStamp"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili stempel nomor halaman dan digunakan untuk memberi nomor pada halaman."
type: docs
weight: 3440
url: /id/java/com.aspose.pdf/pagenumberstamp/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.Stamp com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.Stamp, com.aspose.pdf.TextStamp com.aspose.pdf.PageNumberStamp, com.aspose.pdf.TextStamp, com.aspose.pdf.PageNumberStamp

```
public final class PageNumberStamp extends TextStamp
```

Mewakili stempel nomor halaman dan digunakan untuk memberi nomor pada halaman.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PageNumberStamp](#PageNumberStamp--) | Menginisialisasi instance baru dari kelas {@code PageNumberStamp}. Format diatur ke "#". |
| [PageNumberStamp](#PageNumberStamp-com.aspose.pdf.facades.FormattedText-) | Menginisialisasi instance baru dari kelas {@code PageNumberStamp}. Format diatur ke "#". |
| [PageNumberStamp](#PageNumberStamp-java.lang.String-) | Menginisialisasi instance baru dari kelas {@code PageNumberStamp}. Format diatur ke "#". |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getFormat](#getFormat--) | Mendapatkan nilai String untuk menandai nomor halaman. Nilai harus menyertakan karakter '#' yang akan diganti dengan nomor halaman dalam proses penandaan. |
| [getNumberingStyle](#getNumberingStyle--) | Gaya penomoran yang digunakan oleh stempel ini. |
| [getStartingNumber](#getStartingNumber--) | Mendapatkan nilai dari nomor halaman awal. Halaman lain akan diberi nomor mulai dari nilai ini. |
| [put](#put-com.aspose.pdf.Page-) | Menambahkan nomor halaman. |
| [setFormat](#setFormat-java.lang.String-) | Menetapkan nilai String untuk mencap nomor halaman. Nilai harus menyertakan karakter '#' yang akan diganti dengan nomor halaman dalam proses pencap. |
| [setNumberingStyle](#setNumberingStyle-com.aspose.pdf.NumberingStyle-) | Gaya penomoran yang digunakan oleh stempel ini. |
| [setStartingNumber](#setStartingNumber-int-) | Menetapkan nilai dari nomor halaman awal. Halaman lain akan diberi nomor mulai dari nilai ini. |

### PageNumberStamp {#PageNumberStamp--}
```
public PageNumberStamp()
```

Menginisialisasi instance baru dari kelas {@code PageNumberStamp}. Format diatur ke "#".

### PageNumberStamp {#PageNumberStamp-com.aspose.pdf.facades.FormattedText-}
Menginisialisasi instance baru dari kelas {@code PageNumberStamp}. Format diatur ke "#".

### PageNumberStamp {#PageNumberStamp-java.lang.String-}
Menginisialisasi instance baru dari kelas {@code PageNumberStamp}. Format diatur ke "#".

### getFormat {#getFormat--}
```
public String getFormat()
```

Mendapatkan nilai String untuk menandai nomor halaman. Nilai harus menyertakan karakter '#' yang akan diganti dengan nomor halaman dalam proses penandaan.

**Returns:**
nilai String

### getNumberingStyle {#getNumberingStyle--}
```
public NumberingStyle getNumberingStyle()
```

Gaya penomoran yang digunakan oleh stempel ini.

**Returns:**
Nilai NumberingStyle @see NumberingStyle

### getStartingNumber {#getStartingNumber--}
```
public int getStartingNumber()
```

Mendapatkan nilai dari nomor halaman awal. Halaman lain akan diberi nomor mulai dari nilai ini.

**Returns:**
nilai int

### put {#put-com.aspose.pdf.Page-}
Menambahkan nomor halaman.

### setFormat {#setFormat-java.lang.String-}
Menetapkan nilai String untuk mencap nomor halaman. Nilai harus menyertakan karakter '#' yang akan diganti dengan nomor halaman dalam proses pencap.

### setNumberingStyle {#setNumberingStyle-com.aspose.pdf.NumberingStyle-}
Gaya penomoran yang digunakan oleh stempel ini.

### setStartingNumber {#setStartingNumber-int-}
```
public void setStartingNumber(int value)
```

Menetapkan nilai dari nomor halaman awal. Halaman lain akan diberi nomor mulai dari nilai ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |
