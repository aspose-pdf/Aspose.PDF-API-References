---
title: "XYZExplicitDestination"
linktitle: "XYZExplicitDestination"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "<p> Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat (kiri, atas) yang diposisikan di sudut kiri atas jendela dan isi halaman."
type: docs
weight: 5800
url: /id/java/com.aspose.pdf/xyzexplicitdestination/
---
**Inheritance:**
java.lang.Object, com.aspose.pdf.ExplicitDestination com.aspose.pdf.XYZExplicitDestination, com.aspose.pdf.ExplicitDestination, com.aspose.pdf.XYZExplicitDestination

**All Implemented Interfaces:**
IAppointment

```
public final class XYZExplicitDestination extends ExplicitDestination
```

<p> Mewakili tujuan eksplisit yang menampilkan halaman dengan koordinat (kiri, atas) yang diposisikan di sudut kiri atas jendela dan konten halaman diperbesar dengan faktor zoom. Nilai null untuk salah satu parameter kiri, atas, atau zoom menunjukkan bahwa nilai saat ini dari parameter tersebut harus dipertahankan tidak berubah. Nilai zoom 0 memiliki arti yang sama dengan nilai null. </p> <hr> <p> Document doc = new Document(\"example.pdf\"); XYZExplicitDestination dest = (XYZExplicitDestination)doc.getOutlines().get_Item(1).getDestination(); String left = dest.getLeft(); String top = dest.getTop(); String zoom = dest.getZoom(); </p>

## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-) | Membuat tujuan eksplisit jarak jauh. |
| [XYZExplicitDestination](#XYZExplicitDestination-int-double-double-double-) | Membuat tujuan eksplisit jarak jauh. |
| [XYZExplicitDestination](#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-) | Membuat instance dan menginisialisasinya dengan objek halaman DOM serta parameter yang terlihat. |

## Metode

| Metode | Deskripsi |
| --- | --- |
| [createDestination](#createDestination-com.aspose.pdf.Page-double-double-double-boolean-) | Buat tujuan ke lokasi yang ditentukan pada halaman dengan mempertimbangkan rotasi halaman jika diperlukan. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-) | Buat tujuan ke halaman yang ditentukan. |
| [createDestinationToUpperLeftCorner](#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-) | Buat tujuan ke sudut kiri atas halaman yang ditentukan. |
| [getLeft](#getLeft--) | Mendapatkan koordinat horizontal kiri dari sudut kiri atas jendela. |
| [getTop](#getTop--) | Mendapatkan koordinat vertikal atas dari sudut kiri atas jendela. |
| [getZoom](#getZoom--) | Mendapatkan faktor zoom. |
| [toString](#toString--) | Mengonversi keadaan objek menjadi nilai string. Contoh: "1 XYZ 100 200 3". |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.IDocument-int-double-double-double-}
Membuat tujuan eksplisit jarak jauh.

### XYZExplicitDestination {#XYZExplicitDestination-int-double-double-double-}
```
public XYZExplicitDestination(int pageNumber, double left, double top, double zoom)
```

Membuat tujuan eksplisit jarak jauh.

**Parameters:**
| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| pageNumber |  | Nomor halaman tujuan dari dokumen jarak jauh. |
| kiri |  | Koordinat horizontal kiri dari sudut kiri atas jendela. |
| atas |  | Koordinat vertikal atas dari sudut kiri atas jendela. |
| zoom |  | Faktor zoom. |

### XYZExplicitDestination {#XYZExplicitDestination-com.aspose.pdf.Page-double-double-double-}
Membuat instance dan menginisialisasinya dengan objek halaman DOM serta parameter yang terlihat.

### createDestination {#createDestination-com.aspose.pdf.Page-double-double-double-boolean-}
Buat tujuan ke lokasi yang ditentukan pada halaman dengan mempertimbangkan rotasi halaman jika diperlukan.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-}
Buat tujuan ke halaman yang ditentukan.

### createDestinationToUpperLeftCorner {#createDestinationToUpperLeftCorner-com.aspose.pdf.Page-double-}
Buat tujuan ke sudut kiri atas halaman yang ditentukan.

### getLeft {#getLeft--}
```
public double getLeft()
```

Mendapatkan koordinat horizontal kiri dari sudut kiri atas jendela.

**Returns:**
double

### getTop {#getTop--}
```
public double getTop()
```

Mendapatkan koordinat vertikal atas dari sudut kiri atas jendela.

**Returns:**
double

### getZoom {#getZoom--}
```
public double getZoom()
```

Mendapatkan faktor zoom.

**Returns:**
double

### toString {#toString--}
```
public String toString()
```

Mengonversi keadaan objek menjadi nilai string. Contoh: "1 XYZ 100 200 3".

**Returns:**
Nilai string yang mewakili keadaan objek.
