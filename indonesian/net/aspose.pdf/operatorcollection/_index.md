---
title: Class OperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.OperatorCollection. Kelas ini mewakili koleksi operator
type: docs
weight: 7080
url: /id/net/aspose.pdf/operatorcollection/
---
## Kelas OperatorCollection

Kelas ini mewakili koleksi operator

```csharp
public class OperatorCollection : BaseOperatorCollection, IDisposable
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| override [Count](../../aspose.pdf/operatorcollection/count/) { get; } | Mendapatkan jumlah operator dalam koleksi. |
| override [IsFastTextExtractionMode](../../aspose.pdf/operatorcollection/isfasttextextractionmode/) { get; } | Menunjukkan apakah koleksi dibatasi untuk ekstraksi teks cepat |
| override [IsReadOnly](../../aspose.pdf/operatorcollection/isreadonly/) { get; } | Mendapatkan nilai yang menunjukkan apakah koleksi bersifat hanya-baca. |
| override [Item](../../aspose.pdf/operatorcollection/item/) { get; set; } | Mendapatkan operator berdasarkan indeksnya. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [Accept](../../aspose.pdf/operatorcollection/accept/)(IOperatorSelector) | Menerima objek pengunjung IOperatorSelector untuk memproses operator. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_2)(ICollection&lt;Operator&gt;) | Menambahkan semua operator dari koleksi lain ke dalam koleksi. |
| override [Add](../../aspose.pdf/operatorcollection/add/#add)(Operator) | Menambahkan operator baru ke dalam koleksi. |
| [Add](../../aspose.pdf/operatorcollection/add/#add_1)(Operator[]) | Menambahkan operator di akhir daftar operator. |
| override [CancelUpdate](../../aspose.pdf/operatorcollection/cancelupdate/)() | Membatalkan pembaruan terakhir. Metode ini dapat dipanggil ketika perubahan tidak boleh memicu pembaruan konten. |
| override [Clear](../../aspose.pdf/operatorcollection/clear/)() | Menghapus semua operator dari daftar. |
| override [Contains](../../aspose.pdf/operatorcollection/contains/)(Operator) | Mengembalikan true jika koleksi mengandung operator yang diberikan. |
| override [CopyTo](../../aspose.pdf/operatorcollection/copyto/)(Operator[], int) | Menyalin operator ke dalam daftar operator. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_2)(IList&lt;Operator&gt;) | Menghapus operator dari koleksi. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete_1)(int) | Menghapus operator dari koleksi. |
| [Delete](../../aspose.pdf/operatorcollection/delete/#delete)(Operator[]) | Menghapus operator dari koleksi. |
| [Dispose](../../aspose.pdf/operatorcollection/dispose/)() | Melakukan tugas yang ditentukan aplikasi yang terkait dengan membebaskan, melepaskan, atau mereset sumber daya yang tidak dikelola. |
| override [GetEnumerator](../../aspose.pdf/operatorcollection/getenumerator/)() | Mengembalikan enumerator untuk koleksi |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_2)(int, IList&lt;Operator&gt;) | Menyisipkan operator pada posisi yang diberikan. |
| override [Insert](../../aspose.pdf/operatorcollection/insert/#insert)(int, Operator) | Menyisipkan operator ke dalam koleksi. |
| [Insert](../../aspose.pdf/operatorcollection/insert/#insert_1)(int, Operator[]) | Menyisipkan operator pada posisi yang diberikan. |
| override [Remove](../../aspose.pdf/operatorcollection/remove/)(Operator) | Menghapus operator dari koleksi. |
| [Replace](../../aspose.pdf/operatorcollection/replace/)(IList&lt;Operator&gt;) | Mengganti operator dalam koleksi dengan operator lain. |
| override [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate)() | Melanjutkan pembaruan dokumen. Memperbarui aliran konten jika ada perubahan yang tertunda. |
| [ResumeUpdate](../../aspose.pdf/operatorcollection/resumeupdate/#resumeupdate_1)(bool) | Melanjutkan pembaruan dokumen. Memperbarui aliran konten jika ada perubahan yang tertunda. Menandai semua operator sebagai "berubah" jika parameter invalidate adalah true. |
| override [SuppressUpdate](../../aspose.pdf/operatorcollection/suppressupdate/)() | Menekan pembaruan data konten. Aliran konten tidak diperbarui sampai ResumeUpdate dipanggil. |
| override [ToString](../../aspose.pdf/operatorcollection/tostring/)() | Mengembalikan representasi teks dari operator. |

### Lihat Juga

* kelas [BaseOperatorCollection](../baseoperatorcollection/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)