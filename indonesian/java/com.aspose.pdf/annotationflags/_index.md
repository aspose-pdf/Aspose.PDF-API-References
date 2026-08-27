---
title: "AnnotationFlags"
linktitle: "AnnotationFlags"
second_title: "Referensi API Aspose.PDF untuk Java"
description: "Flags Sekumpulan flag biner yang menentukan berbagai karakteristik anotasi."
type: docs
weight: 90
url: /id/java/com.aspose.pdf/annotationflags/
---
**Inheritance:**
java.lang.Object, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum> com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.ValueType<com.aspose.ms.System.Enum>, com.aspose.ms.System.Enum com.aspose.pdf.AnnotationFlags, com.aspose.ms.System.Enum, com.aspose.pdf.AnnotationFlags

```
public final class AnnotationFlags extends com.aspose.ms.System.Enum
```

Flags Sekumpulan flag biner yang menentukan berbagai karakteristik anotasi.

## Fields

| Field | Deskripsi |
| --- | --- |
| [Default](#Default) | Nilai default. |
| [Hidden](#Hidden) | Jika diatur, jangan tampilkan atau cetak anotasi atau izinkan interaksi dengan pengguna, terlepas dari tipe anotasinya atau apakah penangan anotasi tersedia. Dalam kasus di mana ruang layar terbatas, kemampuan untuk menyembunyikan dan menampilkan anotasi secara selektif dapat digunakan bersama aliran tampilan untuk menampilkan informasi pop-up tambahan yang fungsinya mirip dengan sistem bantuan daring. |
| [Invisible](#Invisible) | Jika diatur, jangan tampilkan anotasi jika tidak termasuk dalam salah satu tipe anotasi standar dan tidak ada penangan anotasi yang tersedia. Jika dibersihkan, tampilkan anotasi tidak dikenal tersebut menggunakan aliran tampilan yang ditentukan oleh kamus tampilanannya, bila ada. |
| [Locked](#Locked) | Jika diatur, jangan izinkan anotasi dihapus atau propertinya (termasuk posisi dan ukuran) dimodifikasi oleh pengguna. Namun, flag ini tidak membatasi perubahan pada isi anotasi, seperti nilai bidang formulir. |
| [LockedContents](#LockedContents) | Jika diatur, jangan izinkan isi anotasi dimodifikasi oleh pengguna. Flag ini tidak membatasi penghapusan anotasi atau perubahan pada properti anotasi lainnya, seperti posisi dan ukuran. |
| [NoRotate](#NoRotate) | Jika diatur, jangan putar tampilan anotasi agar sesuai dengan rotasi halaman. Sudut kiri atas persegi panjang anotasi tetap berada pada lokasi tetap di halaman, terlepas dari rotasi halaman. |
| [NoView](#NoView) | Jika diatur, jangan tampilkan anotasi di layar atau izinkan berinteraksi dengan pengguna. Anotasi dapat dicetak (tergantung pada pengaturan flag Print) tetapi harus dianggap tersembunyi untuk tujuan tampilan di layar dan interaksi pengguna. |
| [NoZoom](#NoZoom) | Jika diatur, jangan skala tampilan anotasi agar sesuai dengan pembesaran halaman. Lokasi anotasi pada halaman (ditentukan oleh sudut kiri atas persegi panjang anotasinya) tetap tetap, terlepas dari pembesaran halaman. |
| [Print](#Print) | Jika diatur, cetak anotasi saat halaman dicetak. Jika tidak diatur, jangan pernah mencetak anotasi, terlepas dari apakah anotasi ditampilkan di layar. Ini dapat berguna, misalnya, untuk anotasi yang mewakili tombol tekan interaktif, yang tidak memiliki tujuan berarti pada halaman cetak. |
| [ReadOnly](#ReadOnly) | Jika diatur, jangan izinkan anotasi berinteraksi dengan pengguna. Anotasi dapat ditampilkan atau dicetak (tergantung pada pengaturan flag NoView dan Print) tetapi tidak boleh merespons klik mouse atau mengubah tampilannya sebagai respons terhadap gerakan mouse. Flag ini diabaikan untuk anotasi widget; fungsinya diambil alih oleh flag ReadOnly pada bidang formulir terkait. |
| [ToggleNoView](#ToggleNoView) | Jika diatur, balikkan interpretasi flag NoView untuk peristiwa tertentu. Penggunaan umum adalah memiliki anotasi yang muncul hanya ketika kursor mouse ditahan di atasnya. |

### Default {#Default}
```
public static final int Default
```

Nilai default.

### Hidden {#Hidden}
```
public static final int Hidden
```

Jika diatur, jangan tampilkan atau cetak anotasi atau izinkan interaksi dengan pengguna, terlepas dari tipe anotasinya atau apakah penangan anotasi tersedia. Dalam kasus di mana ruang layar terbatas, kemampuan untuk menyembunyikan dan menampilkan anotasi secara selektif dapat digunakan bersama aliran tampilan untuk menampilkan informasi pop-up tambahan yang fungsinya mirip dengan sistem bantuan daring.

### Invisible {#Invisible}
```
public static final int Invisible
```

Jika diatur, jangan tampilkan anotasi jika tidak termasuk dalam salah satu tipe anotasi standar dan tidak ada penangan anotasi yang tersedia. Jika dibersihkan, tampilkan anotasi tidak dikenal tersebut menggunakan aliran tampilan yang ditentukan oleh kamus tampilanannya, bila ada.

### Locked {#Locked}
```
public static final int Locked
```

Jika diatur, jangan izinkan anotasi dihapus atau propertinya (termasuk posisi dan ukuran) dimodifikasi oleh pengguna. Namun, flag ini tidak membatasi perubahan pada isi anotasi, seperti nilai bidang formulir.

### LockedContents {#LockedContents}
```
public static final int LockedContents
```

Jika diatur, jangan izinkan isi anotasi dimodifikasi oleh pengguna. Flag ini tidak membatasi penghapusan anotasi atau perubahan pada properti anotasi lainnya, seperti posisi dan ukuran.

### NoRotate {#NoRotate}
```
public static final int NoRotate
```

Jika diatur, jangan putar tampilan anotasi agar sesuai dengan rotasi halaman. Sudut kiri atas persegi panjang anotasi tetap berada pada lokasi tetap di halaman, terlepas dari rotasi halaman.

### NoView {#NoView}
```
public static final int NoView
```

Jika diatur, jangan tampilkan anotasi di layar atau izinkan berinteraksi dengan pengguna. Anotasi dapat dicetak (tergantung pada pengaturan flag Print) tetapi harus dianggap tersembunyi untuk tujuan tampilan di layar dan interaksi pengguna.

### NoZoom {#NoZoom}
```
public static final int NoZoom
```

Jika diatur, jangan skala tampilan anotasi agar sesuai dengan pembesaran halaman. Lokasi anotasi pada halaman (ditentukan oleh sudut kiri atas persegi panjang anotasinya) tetap tetap, terlepas dari pembesaran halaman.

### Print {#Print}
```
public static final int Print
```

Jika diatur, cetak anotasi saat halaman dicetak. Jika tidak diatur, jangan pernah mencetak anotasi, terlepas dari apakah anotasi ditampilkan di layar. Ini dapat berguna, misalnya, untuk anotasi yang mewakili tombol tekan interaktif, yang tidak memiliki tujuan berarti pada halaman cetak.

### ReadOnly {#ReadOnly}
```
public static final int ReadOnly
```

Jika diatur, jangan izinkan anotasi berinteraksi dengan pengguna. Anotasi dapat ditampilkan atau dicetak (tergantung pada pengaturan flag NoView dan Print) tetapi tidak boleh merespons klik mouse atau mengubah tampilannya sebagai respons terhadap gerakan mouse. Flag ini diabaikan untuk anotasi widget; fungsinya diambil alih oleh flag ReadOnly pada bidang formulir terkait.

### ToggleNoView {#ToggleNoView}
```
public static final int ToggleNoView
```

Jika diatur, balikkan interpretasi flag NoView untuk peristiwa tertentu. Penggunaan umum adalah memiliki anotasi yang muncul hanya ketika kursor mouse ditahan di atasnya.
