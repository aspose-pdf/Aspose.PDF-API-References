---
title: "AnnotationFlags"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Sekumpulan flag yang menentukan berbagai karakteristik anotasi."
type: docs
weight: 930
url: /id/python-net/aspose.pdf.annotations/annotationflags/
---

## AnnotationFlags enumeration

Sekumpulan flag yang menentukan berbagai karakteristik anotasi.

## Members
| Nama anggota | Deskripsi |
| :- | :- |
| DEFAULT | Nilai default. |
| INVISIBLE | Jika diatur, jangan tampilkan anotasi jika tidak termasuk dalam salah satu tipe anotasi standar<br/>            dan tidak ada penangan anotasi yang tersedia. Jika tidak diatur, tampilkan anotasi tidak dikenal tersebut<br/>            menggunakan aliran tampilan yang ditentukan oleh kamus tampilan‑nya, jika ada. |
| HIDDEN | Jika diatur, jangan tampilkan atau cetak anotasi atau izinkan interaksi dengan pengguna,<br/>            terlepas dari tipe anotasinya atau apakah penangan anotasi tersedia.<br/>            Dalam kasus di mana ruang layar terbatas, kemampuan untuk menyembunyikan dan menampilkan anotasi secara selektif<br/>            dapat digunakan bersama aliran tampilan untuk menampilkan informasi pop‑up tambahan<br/>            yang fungsinya mirip dengan sistem bantuan daring. |
| CETAK | Jika diatur, cetak anotasi saat halaman dicetak. Jika tidak diatur, jangan pernah mencetak anotasi,<br/>            terlepas dari apakah anotasi tersebut ditampilkan di layar. Ini dapat berguna, misalnya, untuk anotasi<br/>            yang mewakili tombol tekan interaktif, yang tidak memiliki tujuan berarti pada halaman cetak. |
| NO_ZOOM | Jika diatur, jangan skala tampilan anotasi agar sesuai dengan perbesaran halaman.<br/>            Lokasi anotasi pada halaman (ditentukan oleh sudut kiri atas persegi panjang anotasinya)<br/>            tetap, terlepas dari perbesaran halaman. |
| NO_ROTATE | Jika diatur, jangan putar tampilan anotasi agar sesuai dengan rotasi halaman.<br/>            Sudut kiri atas persegi panjang anotasi tetap berada pada lokasi tetap di halaman,<br/>            terlepas dari rotasi halaman. |
| NO_VIEW | Jika diatur, jangan tampilkan anotasi di layar atau izinkan interaksi dengan pengguna.<br/>            Anotasi dapat dicetak (tergantung pada pengaturan flag Print)<br/>            tetapi harus dianggap tersembunyi untuk tujuan tampilan di layar dan interaksi pengguna. |
| READ_ONLY | Jika diatur, jangan izinkan anotasi berinteraksi dengan pengguna. Anotasi dapat ditampilkan<br/>            atau dicetak (tergantung pada pengaturan flag NoView dan Print) tetapi tidak boleh merespons klik mouse<br/>            atau mengubah tampilannya sebagai respons terhadap gerakan mouse. Flag ini diabaikan untuk anotasi widget;<br/>            fungsinya diambil alih oleh flag ReadOnly dari bidang formulir yang terkait. |
| LOCKED | Jika diatur, jangan izinkan anotasi dihapus atau propertinya (termasuk posisi dan ukuran)<br/>            dimodifikasi oleh pengguna. Namun, flag ini tidak membatasi perubahan pada isi anotasi,<br/>            seperti nilai bidang formulir. |
| TOGGLE_NO_VIEW | Jika diatur, balikkan interpretasi flag NoView untuk beberapa peristiwa.<br/>            Penggunaan umum adalah memiliki anotasi yang muncul hanya ketika kursor mouse ditahan di atasnya. |
| LOCKED_CONTENTS | Jika diatur, jangan izinkan isi anotasi diubah oleh pengguna.<br/>            Flag ini tidak membatasi penghapusan anotasi atau perubahan properti anotasi lainnya,<br/>            seperti posisi dan ukuran. |

### Lihat Juga

* namespace [aspose.pdf.annotations](/pdf/python-net/aspose.pdf.annotations/)
* assembly [Aspose.PDF](/pdf/python-net/)

