---
title: "Enum AnnotationFlags"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.Annotations.AnnotationFlags enum. Sekumpulan flag yang menentukan berbagai karakteristik dari annotation"
type: docs
weight: 1530
url: /id/net/aspose.pdf.annotations/annotationflags/
---
## AnnotationFlags enumeration

Sekumpulan flag yang menentukan berbagai karakteristik anotasi.

```csharp
[Flags]
public enum AnnotationFlags
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Default | `0` | Nilai default. |
| Invisible | `1` | Jika diatur, jangan tampilkan annotation jika tidak termasuk dalam salah satu tipe annotation standar dan tidak ada handler annotation yang tersedia. Jika tidak diatur, tampilkan annotation tidak dikenal tersebut menggunakan aliran tampilan yang ditentukan oleh kamus tampilan-nya, jika ada. |
| Hidden | `2` | Jika diatur, jangan tampilkan atau cetak annotation atau izinkan berinteraksi dengan pengguna, terlepas dari tipe annotation atau apakah handler annotation tersedia. Dalam kasus di mana ruang layar terbatas, kemampuan untuk menyembunyikan dan menampilkan annotation secara selektif dapat digunakan bersama aliran tampilan untuk menampilkan informasi pop-up tambahan yang fungsinya mirip dengan sistem bantuan online. |
| Print | `4` | Jika diatur, cetak annotation ketika halaman dicetak. Jika tidak diatur, jangan pernah mencetak annotation, terlepas dari apakah ia ditampilkan di layar. Ini dapat berguna, misalnya, untuk annotation yang mewakili tombol tekan interaktif, yang tidak memiliki tujuan berarti pada halaman cetak. |
| NoZoom | `8` | Jika diatur, jangan skala tampilan annotation agar sesuai dengan pembesaran halaman. Lokasi annotation pada halaman (didefinisikan oleh sudut kiri atas persegi panjang annotation) tetap, terlepas dari pembesaran halaman. |
| NoRotate | `10` | Jika diatur, jangan putar tampilan annotation agar sesuai dengan rotasi halaman. Sudut kiri atas persegi panjang annotation tetap berada di lokasi tetap pada halaman, terlepas dari rotasi halaman. |
| NoView | `20` | Jika diatur, jangan tampilkan annotation di layar atau izinkan berinteraksi dengan pengguna. Annotation dapat dicetak (tergantung pada pengaturan flag Print) tetapi harus dianggap tersembunyi untuk tujuan tampilan di layar dan interaksi pengguna. |
| ReadOnly | `40` | Jika diatur, jangan izinkan annotation berinteraksi dengan pengguna. Annotation dapat ditampilkan atau dicetak (tergantung pada pengaturan flag NoView dan Print) tetapi tidak boleh merespons klik mouse atau mengubah tampilannya sebagai respons terhadap gerakan mouse. Flag ini diabaikan untuk widget annotation; fungsinya diambil alih oleh flag ReadOnly dari bidang formulir terkait. |
| Locked | `80` | Jika diatur, jangan izinkan annotation dihapus atau propertinya (termasuk posisi dan ukuran) diubah oleh pengguna. Namun, flag ini tidak membatasi perubahan pada isi annotation, seperti nilai bidang formulir. |
| ToggleNoView | `100` | Jika diatur, balikkan interpretasi flag NoView untuk peristiwa tertentu. Penggunaan tipikal adalah memiliki annotation yang muncul hanya ketika kursor mouse ditahan di atasnya. |
| LockedContents | `200` | Jika diatur, jangan izinkan isi annotation diubah oleh pengguna. Flag ini tidak membatasi penghapusan annotation atau perubahan properti annotation lainnya, seperti posisi dan ukuran. |

### Lihat Juga

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)


