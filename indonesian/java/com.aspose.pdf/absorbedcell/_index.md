---
title: "AbsorbedCell"
linktitle: "AbsorbedCell"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili sel tabel yang ada di halaman."
type: docs
weight: 10
url: /id/java/com.aspose.pdf/absorbedcell/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.AbsorbedCell

**All Implemented Interfaces:**
ITableElement, Comparable < AbsorbedCell >

```
public class AbsorbedCell extends Object implements ITableElement , Comparable < AbsorbedCell >
```

Mewakili sel tabel yang ada di halaman.

## Metode

| Metode | Deskripsi |
| --- | --- |
| [compareTo](#compareTo-com.aspose.pdf.AbsorbedCell-) | Membandingkan objek AbsorbedCell saat ini dengan objek AbsorbedCell lainnya dan mengembalikan sebuah integer yang menunjukkan apakah objek saat ini mendahului, mengikuti, atau berada pada posisi yang sama dalam urutan pengurutan dibandingkan dengan objek lainnya. |
| [getBorderInfo](#getBorderInfo--) | Mengembalikan informasi batas untuk sel ketika properti FlowEngine.TableAbsorber.UseFlowEngine diatur ke true. |
| [getColSpan](#getColSpan--) | Kembalikan jumlah kolom yang harus ditempati sel ketika properti TableAbsorber.UseFlowEngine diatur ke true. |
| [getRectangle](#getRectangle--) | Mendapatkan persegi panjang yang menggambarkan posisi sel pada halaman |
| [getTextFragments](#getTextFragments--) | Mendapatkan koleksi objek {@code TextFragment} yang menggambarkan teks yang terdapat dalam sel |

### compareTo {#compareTo-com.aspose.pdf.AbsorbedCell-}
Membandingkan objek AbsorbedCell saat ini dengan objek AbsorbedCell lainnya dan mengembalikan sebuah integer yang menunjukkan apakah objek saat ini mendahului, mengikuti, atau berada pada posisi yang sama dalam urutan pengurutan dibandingkan dengan objek lainnya.

### getBorderInfo {#getBorderInfo--}
```
public final BorderInfo getBorderInfo()
```

Mengembalikan informasi batas untuk sel ketika properti FlowEngine.TableAbsorber.UseFlowEngine diatur ke true.

**Returns:**
Instansi BorderInfo

### getColSpan {#getColSpan--}
```
public final int getColSpan()
```

Kembalikan jumlah kolom yang harus ditempati sel ketika properti TableAbsorber.UseFlowEngine diatur ke true.

**Returns:**
nilai int

### getRectangle {#getRectangle--}
```
public Rectangle getRectangle()
```

Mendapatkan persegi panjang yang menggambarkan posisi sel pada halaman

**Returns:**
objek Rectangle

### getTextFragments {#getTextFragments--}
```
public TextFragmentCollection getTextFragments()
```

Mendapatkan koleksi objek {@code TextFragment} yang menggambarkan teks yang terdapat dalam sel

**Returns:**
Objek TextFragmentCollection
