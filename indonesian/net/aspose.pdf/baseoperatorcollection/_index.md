---
title: Class BaseOperatorCollection
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.BaseOperatorCollection. Mewakili kelas dasar untuk koleksi operator
type: docs
weight: 2830
url: /id/net/aspose.pdf/baseoperatorcollection/
---
## Kelas BaseOperatorCollection

Mewakili kelas dasar untuk koleksi operator.

```csharp
public abstract class BaseOperatorCollection : ICollection<Operator>
```

## Properti

| Nama | Deskripsi |
| --- | --- |
| abstract [Count](../../aspose.pdf/baseoperatorcollection/count/) { get; } | Mendapatkan jumlah operator dalam koleksi. |
| abstract [IsFastTextExtractionMode](../../aspose.pdf/baseoperatorcollection/isfasttextextractionmode/) { get; } | Menunjukkan apakah koleksi dibatasi untuk ekstraksi teks cepat |
| abstract [IsReadOnly](../../aspose.pdf/baseoperatorcollection/isreadonly/) { get; } | Mengembalikan true jika koleksi hanya baca. |
| abstract [Item](../../aspose.pdf/baseoperatorcollection/item/) { get; set; } | Mendapatkan operator berdasarkan indeksnya. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| abstract [Add](../../aspose.pdf/baseoperatorcollection/add/)(Operator) | Menambahkan operator baru ke dalam koleksi. |
| abstract [CancelUpdate](../../aspose.pdf/baseoperatorcollection/cancelupdate/)() | Membatalkan pembaruan terakhir. Metode ini dapat dipanggil ketika perubahan tidak seharusnya memicu pembaruan konten. |
| abstract [Clear](../../aspose.pdf/baseoperatorcollection/clear/)() | Menghapus koleksi. |
| abstract [Contains](../../aspose.pdf/baseoperatorcollection/contains/)(Operator) | Memeriksa apakah operator ada dalam koleksi. |
| abstract [CopyTo](../../aspose.pdf/baseoperatorcollection/copyto/)(Operator[], int) | Menyalin operator ke dalam daftar operator. |
| abstract [GetEnumerator](../../aspose.pdf/baseoperatorcollection/getenumerator/)() | Mengembalikan enumerator untuk koleksi |
| abstract [Insert](../../aspose.pdf/baseoperatorcollection/insert/)(int, Operator) | Menyisipkan operator ke dalam koleksi. |
| abstract [Remove](../../aspose.pdf/baseoperatorcollection/remove/)(Operator) | Menghapus operator dari koleksi. |
| abstract [ResumeUpdate](../../aspose.pdf/baseoperatorcollection/resumeupdate/)() | Melanjutkan pembaruan dokumen. Memperbarui aliran konten jika ada perubahan yang tertunda. |
| abstract [SuppressUpdate](../../aspose.pdf/baseoperatorcollection/suppressupdate/)() | Menekan pembaruan data konten. Aliran konten tidak diperbarui sampai ResumeUpdate dipanggil. |

### Lihat Juga

* kelas [Operator](../operator/)
* namespace [Aspose.Pdf](../../aspose.pdf/)
* assembly [Aspose.PDF](../../)