---
title: "SvgSaveOptions"
second_title: "Aspose.PDF untuk Python via .NET Referensi API"
description: "Opsi penyimpanan untuk ekspor ke format SVG"
type: docs
weight: 1460
url: /id/python-net/aspose.pdf/svgsaveoptions/
---

## SvgSaveOptions class

Opsi penyimpanan untuk ekspor ke format SVG

Tipe SvgSaveOptions menampilkan anggota-anggota berikut:
## Konstruktor
| Nama | Deskripsi |
| :- | :- |
| SvgSaveOptions() | Menginisialisasi sebuah instansi baru dari kelas SvgSaveOptions |
## Properti
| Nama | Deskripsi |
| :- | :- |
| warning_handler | Callback untuk menangani peringatan apa pun yang dihasilkan. <br/>            WarningHandler mengembalikan item enum ReturnAction yang menentukan apakah Continue atau Abort. <br/>            Continue adalah aksi default dan operasi Save berlanjut, namun pengguna juga dapat mengembalikan Abort yang berarti operasi Save harus dihentikan. |
| save_format | Format penyimpanan data. |
| close_response | Mendapatkan atau mengatur nilai boolean yang menunjukkan apakah objek Response akan ditutup setelah dokumen disimpan ke dalam response. |
| extract_ocr_sublayer_only | None |
| try_merge_adjacent_same_background_images | None |
| treat_target_file_name_as_directory | Opsi ini menentukan apakah akan dibuat direktori target<br/>             (jika belum ada) dengan nama yang sama dengan file output yang diminta <br/>             alih-alih file output yang diminta itu sendiri.<br/>             Jadi, direktori tersebut akan berisi semua gambar SVG output dari halaman (seperti dijelaskan di bawah).<br/>               Jika tidak, file output halaman selain yang pertama akan dibuat tepat di direktori yang diminta<br/>            sebagai file output utama, tetapi akan memiliki akhiran nama file _[2...n], yang<br/>             ditentukan oleh nomor halaman, misalnya jika Anda menentukan file output "C:\\AsposeTests\\output.svg"<br/>             dan output akan berisi beberapa file svg halaman,<br/>             maka file halaman juga akan dibuat di direktori "C:\\AsposeTests\\" dan memiliki nama 'output.svg', 'output_2.svg', 'output_3.svg' dll. |
| compress_output_to_zip_archive | Menentukan apakah output akan dibuat sebagai satu arsip zip.<br/>             Silakan lihat komentar pada opsi 'TreatTargetFileNameAsDirectory' untuk melihat aturan penamaan<br/>             file svg halaman untuk dokumen sumber multipage, yang juga diterapkan pada set file output yang di-zip. |
| scale_to_pixels | Menentukan apakah dokumen output harus diubah skala dari poin tipografi ke piksel. |

### Lihat Juga

* namespace [aspose.pdf](/pdf/python-net/aspose.pdf/)
* assembly [Aspose.PDF](/pdf/python-net/)

