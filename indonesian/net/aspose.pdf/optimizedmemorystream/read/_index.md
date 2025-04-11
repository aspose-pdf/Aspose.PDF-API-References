---
title: OptimizedMemoryStream.Read
second_title: Aspose.PDF for .NET API Reference
description: Metode OptimizedMemoryStream. Ketika dioverride dalam kelas turunan, membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran berdasarkan jumlah byte yang dibaca
type: docs
weight: 100
url: /id/net/aspose.pdf/optimizedmemorystream/read/
---
## Metode OptimizedMemoryStream.Read

Ketika dioverride dalam kelas turunan, membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran berdasarkan jumlah byte yang dibaca.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | Byte[] | Sebuah array byte. Ketika metode ini mengembalikan, buffer berisi array byte yang ditentukan dengan nilai-nilai |
| offset | Int32 | Offset byte berbasis nol di mana untuk mulai menyimpan data yang dibaca dari aliran saat ini. |
| count | Int32 | Jumlah maksimum byte yang akan dibaca dari aliran saat ini. |

### Nilai Kembali

Jumlah total byte yang dibaca ke dalam buffer. Ini bisa kurang dari jumlah byte yang diminta jika sebanyak itu byte tidak tersedia saat ini, atau nol (0) jika akhir aliran telah tercapai.

### Lihat Juga

* kelas [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)