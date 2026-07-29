---
title: "FitVExplicitDestination"
linktitle: "FitVExplicitDestination"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat horizontal kiri diposisikan di tepi kiri jendela dan konten halaman diperbesar tepat."
type: docs
weight: 1580
url: /id/java/com.aspose.pdf/fitvexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitVExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitVExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitVExplicitDestination extends ExplicitDestination
```

Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat horizontal kiri ditempatkan pada tepi kiri jendela dan isi halaman diperbesar cukup untuk menyesuaikan tinggi seluruh halaman dalam jendela. Nilai null untuk left menunjukkan bahwa nilai parameter tersebut saat ini harus dipertahankan tanpa perubahan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Document-int-double-) | Membuat tujuan eksplisit jarak jauh. |
| [FitVExplicitDestination](#FitVExplicitDestination-int-double-) | Membuat tujuan eksplisit jarak jauh. |
| [FitVExplicitDestination](#FitVExplicitDestination-com.aspose.pdf.Page-double-) | Membuat instance dan menginisialisasinya dengan objek halaman DOM dan parameter left. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getLeft](#getLeft--) | Mendapatkan koordinat horizontal kiri yang diposisikan di tepi kiri jendela. |
| [toString](#toString--) | Mengonversi keadaan objek menjadi nilai string. Contoh: "1 FitV 100". |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Document-int-double-}
Membuat tujuan eksplisit jarak jauh.

### FitVExplicitDestination {#FitVExplicitDestination-int-double-}
```
public FitVExplicitDestination(int pageNumber, double left)
```

Membuat tujuan eksplisit jarak jauh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman tujuan dari dokumen jarak jauh. |
| kiri |  | Koordinat horizontal kiri yang diposisikan di tepi kiri jendela. |

### FitVExplicitDestination {#FitVExplicitDestination-com.aspose.pdf.Page-double-}
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

Mengonversi keadaan objek menjadi nilai string. Contoh: "1 FitV 100".

**Returns:**
Nilai string yang mewakili keadaan objek.
