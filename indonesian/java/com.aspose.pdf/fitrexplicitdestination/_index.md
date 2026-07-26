---
title: "FitRExplicitDestination"
linktitle: "FitRExplicitDestination"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili tujuan eksplisit yang menampilkan halaman dengan isinya diperbesar cukup untuk menyesuaikan persegi panjang yang ditentukan oleh koordinat kiri, bawah, kanan, dan."
type: docs
weight: 1570
url: /id/java/com.aspose.pdf/fitrexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitRExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitRExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitRExplicitDestination extends ExplicitDestination
```

Mewakili tujuan eksplisit yang menampilkan halaman dengan isinya diperbesar cukup untuk menyesuaikan persegi panjang yang ditentukan oleh koordinat left, bottom, right, dan top sepenuhnya dalam jendela baik secara horizontal maupun vertikal. Jika faktor pembesaran horizontal dan vertikal yang diperlukan berbeda, gunakan yang lebih kecil di antara keduanya, dengan memusatkan persegi panjang dalam jendela pada dimensi lainnya. Nilai null untuk salah satu parameter dapat mengakibatkan perilaku yang tidak dapat diprediksi.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-) | Membuat tujuan eksplisit jarak jauh. |
| [FitRExplicitDestination](#FitRExplicitDestination-int-double-double-double-double-) | Membuat tujuan eksplisit jarak jauh. |
| [FitRExplicitDestination](#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-) | Membuat instance dan menginisialisasinya dengan objek halaman DOM serta parameter yang terlihat. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getBottom](#getBottom--) | Mendapatkan koordinat vertikal bawah dari persegi panjang yang terlihat. |
| [getLeft](#getLeft--) | Mendapatkan koordinat horizontal kiri dari persegi panjang yang terlihat. |
| [getRight](#getRight--) | Mendapatkan koordinat horizontal kanan dari persegi panjang yang terlihat. |
| [getTop](#getTop--) | Mendapatkan koordinat vertikal atas dari persegi panjang yang terlihat. |
| [toString](#toString--) | Mengonversi keadaan objek menjadi nilai string. Contoh: "1 FitR 100 200 300 400". |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Document-int-double-double-double-double-}
Membuat tujuan eksplisit jarak jauh.

### FitRExplicitDestination {#FitRExplicitDestination-int-double-double-double-double-}
```
public FitRExplicitDestination(int pageNumber, double left, double bottom, double right, double top)
```

Membuat tujuan eksplisit jarak jauh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman tujuan dari dokumen jarak jauh. |
| kiri |  | Koordinat horizontal kiri dari persegi panjang yang terlihat. |
| bawah |  | Koordinat vertikal bawah dari persegi panjang yang terlihat. |
| kanan |  | Koordinat horizontal kanan dari persegi panjang yang terlihat. |
| atas |  | Koordinat vertikal atas dari persegi panjang yang terlihat. |

### FitRExplicitDestination {#FitRExplicitDestination-com.aspose.pdf.Page-double-double-double-double-}
Membuat instance dan menginisialisasinya dengan objek halaman DOM serta parameter yang terlihat.

### getBottom {#getBottom--}
```
public double getBottom()
```

Mendapatkan koordinat vertikal bawah dari persegi panjang yang terlihat.

**Returns:**
nilai double

### getLeft {#getLeft--}
```
public double getLeft()
```

Mendapatkan koordinat horizontal kiri dari persegi panjang yang terlihat.

**Returns:**
nilai double

### getRight {#getRight--}
```
public double getRight()
```

Mendapatkan koordinat horizontal kanan dari persegi panjang yang terlihat.

**Returns:**
nilai double

### getTop {#getTop--}
```
public double getTop()
```

Mendapatkan koordinat vertikal atas dari persegi panjang yang terlihat.

**Returns:**
nilai double

### toString {#toString--}
```
public String toString()
```

Mengonversi keadaan objek menjadi nilai string. Contoh: "1 FitR 100 200 300 400".

**Returns:**
Nilai string yang mewakili keadaan objek.
