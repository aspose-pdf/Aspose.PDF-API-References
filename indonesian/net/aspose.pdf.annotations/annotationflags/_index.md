---
title: Enum AnnotationFlags
second_title: Aspose.PDF for .NET API Reference
description: Enum AnnotationFlags dari Aspose.Pdf.Annotations. Sekumpulan bendera yang menentukan berbagai karakteristik dari anotasi
type: docs
weight: 1440
url: /id/net/aspose.pdf.annotations/annotationflags/
---
## Enumerasi AnnotationFlags

Sekumpulan bendera yang menentukan berbagai karakteristik dari anotasi.

```csharp
[Flags]
public enum AnnotationFlags
```

### Nilai

| Nama | Nilai | Deskripsi |
| --- | --- | --- |
| Default | `0` | Nilai default. |
| Invisible | `1` | Jika diatur, jangan tampilkan anotasi jika tidak termasuk dalam salah satu jenis anotasi standar dan tidak ada pengelola anotasi yang tersedia. Jika dibersihkan, tampilkan anotasi yang tidak dikenal tersebut menggunakan aliran penampilan yang ditentukan oleh kamus penampilannya, jika ada. |
| Hidden | `2` | Jika diatur, jangan tampilkan atau cetak anotasi atau izinkan untuk berinteraksi dengan pengguna, terlepas dari jenis anotasinya atau apakah pengelola anotasi tersedia. Dalam kasus di mana ruang layar terbatas, kemampuan untuk menyembunyikan dan menampilkan anotasi secara selektif dapat digunakan dalam kombinasi dengan aliran penampilan untuk menampilkan informasi pop-up tambahan yang mirip fungsinya dengan sistem bantuan online. |
| Print | `4` | Jika diatur, cetak anotasi saat halaman dicetak. Jika dibersihkan, jangan pernah cetak anotasi, terlepas dari apakah ditampilkan di layar. Ini bisa berguna, misalnya, untuk anotasi yang mewakili tombol interaktif, yang tidak akan memiliki tujuan berarti di halaman yang dicetak. |
| NoZoom | `8` | Jika diatur, jangan skala penampilan anotasi untuk mencocokkan pembesaran halaman. Lokasi anotasi di halaman (ditentukan oleh sudut kiri atas dari persegi panjang anotasinya) tetap tetap, terlepas dari pembesaran halaman. |
| NoRotate | `10` | Jika diatur, jangan putar penampilan anotasi untuk mencocokkan rotasi halaman. Sudut kiri atas dari persegi panjang anotasi tetap di lokasi tetap di halaman, terlepas dari rotasi halaman. |
| NoView | `20` | Jika diatur, jangan tampilkan anotasi di layar atau izinkan untuk berinteraksi dengan pengguna. Anotasi dapat dicetak (tergantung pada pengaturan bendera Print) tetapi harus dianggap tersembunyi untuk tujuan tampilan di layar dan interaksi pengguna. |
| ReadOnly | `40` | Jika diatur, jangan izinkan anotasi untuk berinteraksi dengan pengguna. Anotasi dapat ditampilkan atau dicetak (tergantung pada pengaturan bendera NoView dan Print) tetapi tidak boleh merespons klik mouse atau mengubah penampilannya sebagai respons terhadap gerakan mouse. Bendera ini diabaikan untuk anotasi widget; fungsinya diambil alih oleh bendera ReadOnly dari bidang formulir yang terkait. |
| Locked | `80` | Jika diatur, jangan izinkan anotasi dihapus atau propertinya (termasuk posisi dan ukuran) diubah oleh pengguna. Namun, bendera ini tidak membatasi perubahan pada konten anotasi, seperti nilai dari bidang formulir. |
| ToggleNoView | `100` | Jika diatur, balikkan interpretasi bendera NoView untuk peristiwa tertentu. Penggunaan yang umum adalah memiliki anotasi yang hanya muncul ketika kursor mouse diletakkan di atasnya. |
| LockedContents | `200` | Jika diatur, jangan izinkan konten anotasi diubah oleh pengguna. Bendera ini tidak membatasi penghapusan anotasi atau perubahan pada properti anotasi lainnya, seperti posisi dan ukuran. |

### Lihat Juga

* namespace [Aspose.Pdf.Annotations](../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../)