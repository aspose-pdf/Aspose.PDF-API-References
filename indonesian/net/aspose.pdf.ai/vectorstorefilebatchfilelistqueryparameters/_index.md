---
title: Class VectorStoreFileBatchFileListQueryParameters
second_title: Aspose.PDF for .NET API Reference
description: Kelas Aspose.Pdf.AI.VectorStoreFileBatchFileListQueryParameters. Objek parameter kueri untuk daftar file batch file penyimpanan vektor
type: docs
weight: 1290
url: /id/net/aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/
---
## Kelas VectorStoreFileBatchFileListQueryParameters

Objek parameter kueri untuk daftar file batch file penyimpanan vektor.

```csharp
public class VectorStoreFileBatchFileListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [VectorStoreFileBatchFileListQueryParameters](vectorstorefilebatchfilelistqueryparameters/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Mengambil atau mengatur kursor untuk digunakan dalam paginasi. after adalah ID objek yang mendefinisikan posisi Anda dalam daftar. Misalnya, jika Anda membuat permintaan daftar dan menerima 100 objek, diakhiri dengan obj_foo, panggilan Anda berikutnya dapat menyertakan after=obj_foo untuk mengambil halaman berikutnya dari daftar. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Mengambil atau mengatur kursor untuk digunakan dalam paginasi. before adalah ID objek yang mendefinisikan posisi Anda dalam daftar. Misalnya, jika Anda membuat permintaan daftar dan menerima 100 objek, diakhiri dengan obj_foo, panggilan Anda berikutnya dapat menyertakan before=obj_foo untuk mengambil halaman sebelumnya dari daftar. |
| [Filter](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/filter/) { get; set; } | Mengambil atau mengatur filter berdasarkan status file. Salah satu dari in_progress, completed, failed, cancelled. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Mengambil atau mengatur batasan pada jumlah objek yang akan dikembalikan. Limit dapat berkisar antara 1 dan 100, dan defaultnya adalah 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Mengambil atau mengatur urutan pengurutan berdasarkan timestamp created_at dari objek. asc untuk urutan menaik dan desc untuk urutan menurun. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/vectorstorefilebatchfilelistqueryparameters/getqueryparameters/)() | Mengambil parameter kueri untuk daftar file batch file penyimpanan. |

### Lihat Juga

* kelas [BaseListQueryParameters](../baselistqueryparameters/)
* antarmuka [IQueryParameters](../iqueryparameters/)
* ruang nama [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)