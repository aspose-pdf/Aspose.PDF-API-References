---
title: "FitHExplicitDestination"
linktitle: "FitHExplicitDestination"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat vertikal atas ditempatkan di tepi atas jendela dan konten halaman diperbesar secara tepat."
type: docs
weight: 1560
url: /id/java/com.aspose.pdf/fithexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.FitHExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.FitHExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class FitHExplicitDestination extends ExplicitDestination
```

Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat vertikal atas ditempatkan pada tepi atas jendela dan isi halaman diperbesar cukup untuk menyesuaikan lebar seluruh halaman dalam jendela. Nilai null untuk top menunjukkan bahwa nilai parameter tersebut saat ini harus dipertahankan tanpa perubahan.

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Document-int-double-) | Membuat tujuan eksplisit jarak jauh. |
| [FitHExplicitDestination](#FitHExplicitDestination-int-double-) | Membuat tujuan eksplisit jarak jauh. |
| [FitHExplicitDestination](#FitHExplicitDestination-com.aspose.pdf.Page-double-) | Membuat instance dan menginisialisasinya dengan objek halaman DOM serta parameter top. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [getTop](#getTop--) | Mendapatkan koordinat vertikal atas yang ditempatkan di tepi atas jendela. |
| [toString](#toString--) | Mengonversi keadaan objek menjadi nilai string. Contoh: "1 FitH 100". |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Document-int-double-}
Membuat tujuan eksplisit jarak jauh.

### FitHExplicitDestination {#FitHExplicitDestination-int-double-}
```
public FitHExplicitDestination(int pageNumber, double top)
```

Membuat tujuan eksplisit jarak jauh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman tujuan dari dokumen jarak jauh. |
| atas |  | Koordinat vertikal atas yang ditempatkan di tepi atas jendela. |

### FitHExplicitDestination {#FitHExplicitDestination-com.aspose.pdf.Page-double-}
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

Mengonversi keadaan objek menjadi nilai string. Contoh: "1 FitH 100".

**Returns:**
Nilai string yang mewakili keadaan objek.
