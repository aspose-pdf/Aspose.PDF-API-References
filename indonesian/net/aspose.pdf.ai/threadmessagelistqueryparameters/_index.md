---
title: "Kelas ThreadMessageListQueryParameters"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Aspose.Pdf.AI.ThreadMessageListQueryParameters kelas. Objek parameter kueri untuk menampilkan pesan thread"
type: docs
weight: 1220
url: /id/net/aspose.pdf.ai/threadmessagelistqueryparameters/
---
## ThreadMessageListQueryParameters class

Objek parameter kueri untuk menampilkan daftar pesan thread.

```csharp
public class ThreadMessageListQueryParameters : BaseListQueryParameters, IQueryParameters
```

## Konstruktor

| Nama | Deskripsi |
| --- | --- |
| [ThreadMessageListQueryParameters](threadmessagelistqueryparameters/)() | Konstruktor default. |

## Properti

| Nama | Deskripsi |
| --- | --- |
| [After](../../aspose.pdf.ai/baselistqueryparameters/after/) { get; set; } | Mendapatkan atau mengatur kursor untuk digunakan dalam paginasi. after adalah ID objek yang menentukan posisi Anda dalam daftar. Misalnya, jika Anda melakukan permintaan daftar dan menerima 100 objek, yang berakhir dengan obj_foo, panggilan berikutnya dapat menyertakan after=obj_foo untuk mengambil halaman berikutnya dari daftar. |
| [Before](../../aspose.pdf.ai/baselistqueryparameters/before/) { get; set; } | Mendapatkan atau mengatur kursor untuk digunakan dalam paginasi. before adalah ID objek yang menentukan posisi Anda dalam daftar. Misalnya, jika Anda melakukan permintaan daftar dan menerima 100 objek, yang berakhir dengan obj_foo, panggilan berikutnya dapat menyertakan before=obj_foo untuk mengambil halaman sebelumnya dari daftar. |
| [Limit](../../aspose.pdf.ai/baselistqueryparameters/limit/) { get; set; } | Mendapatkan atau mengatur batas pada jumlah objek yang akan dikembalikan. Batas dapat berada antara 1 hingga 100, dan nilai defaultnya adalah 20. |
| [Order](../../aspose.pdf.ai/baselistqueryparameters/order/) { get; set; } | Mendapatkan atau mengatur urutan penyortiran berdasarkan timestamp created_at dari objek. asc untuk urutan naik dan desc untuk urutan turun. |
| [RunId](../../aspose.pdf.ai/threadmessagelistqueryparameters/runid/) { get; set; } | Saring pesan berdasarkan ID run yang menghasilkan mereka. |

## Metode

| Nama | Deskripsi |
| --- | --- |
| [GetQueryParameters](../../aspose.pdf.ai/threadmessagelistqueryparameters/getqueryparameters/)() | Mendapatkan parameter kueri untuk menampilkan pesan thread. |

### Lihat Juga

* class [BaseListQueryParameters](../baselistqueryparameters/)
* interface [IQueryParameters](../iqueryparameters/)
* namespace [Aspose.Pdf.AI](../../aspose.pdf.ai/)
* assembly [Aspose.PDF](../../)


