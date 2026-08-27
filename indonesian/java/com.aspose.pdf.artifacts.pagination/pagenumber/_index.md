---
title: "PageNumber"
linktitle: "PageNumber"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili format nomor halaman yang mencakup indeks, total jumlah halaman, dan pemisah."
type: docs
weight: 150
url: /id/java/com.aspose.pdf.artifacts.pagination/pagenumber/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.artifacts.pagination.PageNumber

```
public final class PageNumber extends Object
```

Mewakili format nomor halaman yang mencakup indeks, total jumlah halaman, dan pemisah.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [PageNumber](#PageNumber--) |  |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getDelimiter](#getDelimiter--) | Mendapatkan atau mengatur pemisah yang digunakan dalam format nomor halaman. String yang diformat akan diperbarui berdasarkan pemisah yang ditentukan. |
| [getIndex](#getIndex--) | Mendapatkan atau mengatur komponen indeks halaman dari format nomor halaman. String yang diformat akan menyertakan placeholder untuk indeks halaman. |
| [getOffset](#getOffset--) | Mendapatkan atau mengatur offset yang akan ditambahkan ke indeks halaman. |
| [getPageNumberString](#getPageNumberString-int-int-) | Mengembalikan string yang diformat yang mewakili nomor halaman berdasarkan pengaturan saat ini. |
| [getTotalNum](#getTotalNum--) | Mendapatkan atau mengatur komponen total jumlah halaman dari format nomor halaman. String yang diformat akan menyertakan placeholder untuk total jumlah halaman. |
| [setDelimiter](#setDelimiter-java.lang.String-) | Mendapatkan atau mengatur pemisah yang digunakan dalam format nomor halaman. String yang diformat akan diperbarui berdasarkan pemisah yang ditentukan. |
| [setIndex](#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-) | Mendapatkan atau mengatur komponen indeks halaman dari format nomor halaman. |
| [setOffset](#setOffset-int-) | Mendapatkan atau mengatur offset yang akan ditambahkan ke indeks halaman. |
| [setTotalNum](#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-) | Mendapatkan atau mengatur komponen total jumlah halaman dari format nomor halaman. |

### PageNumber {#PageNumber--}
```
public PageNumber()
```



### getDelimiter {#getDelimiter--}
```
public final String getDelimiter()
```

Mendapatkan atau mengatur pemisah yang digunakan dalam format nomor halaman. String yang diformat akan diperbarui berdasarkan pemisah yang ditentukan.

**Returns:**
nilai String

### getIndex {#getIndex--}
```
public final PageNumber.PageIndex getIndex()
```

Mendapatkan atau mengatur komponen indeks halaman dari format nomor halaman. String yang diformat akan menyertakan placeholder untuk indeks halaman.

**Returns:**
PageIndex instance

### getOffset {#getOffset--}
```
public final int getOffset()
```

Mendapatkan atau mengatur offset yang akan ditambahkan ke indeks halaman.

**Returns:**
nilai int

### getPageNumberString {#getPageNumberString-int-int-}
```
public final String getPageNumberString(int pageNumber, int count)
```

Mengembalikan string yang diformat yang mewakili nomor halaman berdasarkan pengaturan saat ini.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman saat ini. |
| jumlah |  | Total jumlah halaman. |

**Returns:**
String nomor halaman yang diformat.

### getTotalNum {#getTotalNum--}
```
public final PageNumber.PageTotalNum getTotalNum()
```

Mendapatkan atau mengatur komponen total jumlah halaman dari format nomor halaman. String yang diformat akan menyertakan placeholder untuk total jumlah halaman.

**Returns:**
PageTotalNum instance

### setDelimiter {#setDelimiter-java.lang.String-}
Mendapatkan atau mengatur pemisah yang digunakan dalam format nomor halaman. String yang diformat akan diperbarui berdasarkan pemisah yang ditentukan.

### setIndex {#setIndex-com.aspose.pdf.artifacts.pagination.PageNumber.PageIndex-}
Mendapatkan atau mengatur komponen indeks halaman dari format nomor halaman.

### setOffset {#setOffset-int-}
```
public final void setOffset(int value)
```

Mendapatkan atau mengatur offset yang akan ditambahkan ke indeks halaman.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| nilai |  | nilai int |

### setTotalNum {#setTotalNum-com.aspose.pdf.artifacts.pagination.PageNumber.PageTotalNum-}
Mendapatkan atau mengatur komponen total jumlah halaman dari format nomor halaman.
