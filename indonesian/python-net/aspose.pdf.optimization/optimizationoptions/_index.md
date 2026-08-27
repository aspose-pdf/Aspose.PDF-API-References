---
title: "OptimizationOptions"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Kelas yang menjelaskan algoritma optimisasi dokumen.<br/>            Instance dari kelas ini dapat digunakan sebagai parameter metode OptimizeResources()."
type: docs
weight: 20
url: /id/python-net/aspose.pdf.optimization/optimizationoptions/
---

## OptimizationOptions class

Kelas yang menjelaskan algoritma optimisasi dokumen.<br/>            Instance dari kelas ini dapat digunakan sebagai parameter metode OptimizeResources().

Tipe OptimizationOptions menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| OptimizationOptions() | Menginisialisasi instance baru dari kelas OptimizationOptions |
## Properti
| Nama | Deskripsi |
| :- | :- |
| link_duplcate_streams | Jika flag ini diatur ke true, aliran Sumber Daya akan dianalisis. Jika aliran duplikat ditemukan (misalnya jika isi aliran sama), maka aliran tersebut akan disimpan sebagai satu objek. <br/>            Ini memungkinkan mengurangi ukuran dokumen dalam beberapa kasus (misalnya, ketika dokumen yang sama digabungkan beberapa kali). |
| allow_reuse_page_content | Jika true, konten halaman akan digunakan kembali ketika dokumen dioptimalkan untuk halaman yang sama. |
| remove_unused_streams | Jika flag ini diatur ke true, setiap sumber daya akan diperiksa penggunaannya. Jika sumber daya tidak pernah digunakan, maka sumber daya tersebut dihapus.<br/>            Ini dapat mengurangi ukuran dokumen, misalnya ketika halaman diekstrak dari dokumen. |
| remove_unused_objects | Jika flag ini diatur ke true, semua objek dokumen akan diperiksa dan objek yang tidak terpakai (misalnya objek yang tidak memiliki referensi apa pun) dihapus dari dokumen. |
| image_compression_options | Serangkaian opsi yang menjelaskan apakah gambar dalam dokumen akan dikompresi dan parameter kompresinya. |
| compress_images | Jika flag ini diatur ke true, gambar akan dikompresi dalam dokumen. Tingkat kompresi ditentukan dengan properti ImageQuality. |
| resize_images | Jika flag ini diatur ke true dan CompressImages bernilai true, gambar akan diubah ukurannya jika resolusi gambar lebih besar daripada parameter MaxResolution yang ditentukan. |
| image_quality | Menentukan tingkat kompresi gambar ketika flag CompressIamges digunakan. |
| max_resoultion | Menentukan resolusi maksimum gambar. Jika gambar memiliki resolusi lebih tinggi, gambar akan diubah skalanya. |
| unembed_fonts | Jadikan font tidak tersemat jika diatur ke true. |
| subset_fonts | Font akan dikonversi menjadi subset jika diatur ke true. |
| remove_private_info | Hapus informasi pribadi (informasi potongan halaman). |
| image_encoding | Enkoding gambar yang akan digunakan. |
## Metode
| Nama | Deskripsi |
| :- | :- |
| all() | Membuat strategi optimasi dengan semua opsi diaktifkan.<br/>            Harap perhatikan bahwa hanya opsi yang tidak mengubah fungsi dokumen yang diaktifkan.<br/>            Misalnya kompresi gambar dan penghapusan sematan font tidak akan diaktifkan (dan dapat disematkan secara manual). |

### Lihat Juga

* namespace [aspose.pdf.optimization](/pdf/python-net/aspose.pdf.optimization/)
* assembly [Aspose.PDF](/pdf/python-net/)

