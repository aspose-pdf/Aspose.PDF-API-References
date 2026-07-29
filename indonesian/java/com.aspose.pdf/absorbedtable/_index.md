---
title: "AbsorbedTable"
linktitle: "AbsorbedTable"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili tabel yang ada di halaman."
type: docs
weight: 30
url: /id/java/com.aspose.pdf/absorbedtable/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedTable

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedTable >

```
public class AbsorbedTable extends Object implements ITableElement , Comparable < AbsorbedTable >
```

Mewakili tabel yang ada di halaman.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedTable-) | Membandingkan objek AbsorbedTable saat ini dengan objek AbsorbedTable lain dan mengembalikan sebuah integer yang menunjukkan apakah objek saat ini mendahului, mengikuti, atau berada pada posisi yang sama dalam urutan penyortiran dibandingkan dengan objek lainnya. |
| [getPageNum](#getPageNum--) | Mendapatkan nomor halaman yang berisi tabel ini |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang yang menggambarkan posisi tabel pada halaman |
| [getRowList](#getRowList--) | <p> Mendapatkan IList readonly yang berisi baris-baris tabel </p> |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedTable-}
Membandingkan objek AbsorbedTable saat ini dengan objek AbsorbedTable lain dan mengembalikan sebuah integer yang menunjukkan apakah objek saat ini mendahului, mengikuti, atau berada pada posisi yang sama dalam urutan penyortiran dibandingkan dengan objek lainnya.

### getPageNum {#getPageNum--}
```
public int getPageNum()
```

Mendapatkan nomor halaman yang berisi tabel ini

**Returns:**
nilai int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan persegi panjang yang menggambarkan posisi tabel pada halaman

**Returns:**
objek Rectangle

### getRowList {#getRowList--}
```
public List < AbsorbedRow > getRowList()
```

<p> Mendapatkan IList readonly yang berisi baris-baris tabel </p>

**Returns:**
{@code IGenericList<AbsorbedRow>} objek
