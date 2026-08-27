---
title: "FitBVExplicitDestination"
linktitle: "FitBVExplicitDestination"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat horizontal kiri diposisikan di tepi kiri jendela dan konten halaman diperbesar tepat."
type: docs
weight: 1540
url: /id/java/com.aspose.pdf/fitbvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitBVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitBVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitBVExplicitDestination extends ExplicitDestination
```

Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat horizontal kiri ditempatkan pada tepi kiri jendela dan isi halaman diperbesar cukup untuk menyesuaikan tinggi seluruh kotak pembatasnya dalam jendela. Nilai null untuk left menunjukkan bahwa nilai parameter tersebut saat ini harus dipertahankan tanpa perubahan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FitBVExplicitDestination](#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-) | Membuat tujuan eksplisit jarak jauh. |
| [FitBVExplicitDestination](#FitBVExplicitDestination-int-double-) | Membuat tujuan eksplisit jarak jauh. |
| [FitBVExplicitDestination](#FitBVExplicitDestination-com.aspose.pdf.Page-double-) | Membuat instance dan menginisialisasinya dengan objek halaman DOM dan parameter left. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLeft](#getLeft--) | Mendapatkan koordinat horizontal kiri yang diposisikan di tepi kiri jendela. |
| [toString](#toString--) | Mengonversi status objek menjadi nilai string. Contoh: "1 FitBV 100". |

### FitBVExplicitDestination {#FitBVExplicitDestination-com.aspose.pdf.Document-int-double-}
Membuat tujuan eksplisit jarak jauh.

### FitBVExplicitDestination {#FitBVExplicitDestination-int-double-}
```
public FitBVExplicitDestination(int pageNumber, double left)
```

Membuat tujuan eksplisit jarak jauh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman tujuan dari dokumen jarak jauh. |
| kiri |  | Koordinat horizontal kiri yang diposisikan di tepi kiri jendela. |

### FitBVExplicitDestination {#FitBVExplicitDestination-com.aspose.pdf.Page-double-}
Membuat instance dan menginisialisasinya dengan objek halaman DOM dan parameter left.

### getLeft {#getLeft--}
```
public double getLeft()
```

Mendapatkan koordinat horizontal kiri yang diposisikan di tepi kiri jendela.

**Returns:**
nilai double

### toString {#toString--}
```
public String toString()
```

Mengonversi status objek menjadi nilai string. Contoh: "1 FitBV 100".

**Returns:**
Nilai string yang mewakili keadaan objek.
