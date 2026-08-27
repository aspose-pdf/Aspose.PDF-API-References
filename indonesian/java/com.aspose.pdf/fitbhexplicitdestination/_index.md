---
title: "FitBHExplicitDestination"
linktitle: "FitBHExplicitDestination"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat vertikal atas ditempatkan di tepi atas jendela dan konten halaman diperbesar secara tepat."
type: docs
weight: 1530
url: /id/java/com.aspose.pdf/fitbhexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBHExplicitDestination extends ExplicitDestination
```

Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat vertikal atas ditempatkan pada tepi atas jendela dan isi halaman diperbesar cukup untuk menyesuaikan lebar seluruh kotak pembatasnya dalam jendela. Nilai null untuk top menunjukkan bahwa nilai parameter tersebut saat ini harus dipertahankan tanpa perubahan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-) | Membuat tujuan eksplisit jarak jauh. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-int-double-) | Membuat tujuan eksplisit jarak jauh. |
| [FitBHExplicitDestination](#FitBHExplicitDestination-com.aspose.pdf.Page-double-) | Membuat instance dan menginisialisasinya dengan objek halaman DOM serta parameter top. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTop](#getTop--) | Mendapatkan koordinat vertikal atas yang ditempatkan di tepi atas jendela. |
| [toString](#toString--) | Mengonversi keadaan objek menjadi nilai string. Example: "1 FitBH 100". |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Document-int-double-}
Membuat tujuan eksplisit jarak jauh.

### FitBHExplicitDestination {#FitBHExplicitDestination-int-double-}
```
public FitBHExplicitDestination(int pageNumber, double top)
```

Membuat tujuan eksplisit jarak jauh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman tujuan dari dokumen jarak jauh. |
| atas |  | Koordinat vertikal atas yang ditempatkan di tepi atas jendela. |

### FitBHExplicitDestination {#FitBHExplicitDestination-com.aspose.pdf.Page-double-}
Membuat instance dan menginisialisasinya dengan objek halaman DOM serta parameter top.

### getTop {#getTop--}
```
public double getTop()
```

Mendapatkan koordinat vertikal atas yang ditempatkan di tepi atas jendela.

**Returns:**
nilai double

### toString {#toString--}
```
public String toString()
```

Mengonversi keadaan objek menjadi nilai string. Example: "1 FitBH 100".

**Returns:**
Nilai string yang mewakili keadaan objek.
