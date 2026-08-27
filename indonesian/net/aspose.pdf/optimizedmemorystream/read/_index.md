---
title: "OptimizedMemoryStream.Read"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode OptimizedMemoryStream. Ketika dioverride dalam kelas turunan membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebesar jumlah byte yang dibaca."
type: docs
weight: 100
url: /id/net/aspose.pdf/optimizedmemorystream/read/
---
## OptimizedMemoryStream.Read method

Saat dioverride dalam kelas turunan, membaca urutan byte dari aliran saat ini dan memajukan posisi dalam aliran sebesar jumlah byte yang dibaca.

```csharp
public override int Read(byte[] buffer, int offset, int count)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| buffer | Byte[] | Array byte. Ketika metode ini mengembalikan, buffer berisi array byte yang ditentukan dengan nilai-nilai. |
| offset | Int32 | Offset byte berbasis nol di mana mulai menyimpan data yang dibaca dari aliran saat ini. |
| jumlah | Int32 | Jumlah maksimum byte yang akan dibaca dari aliran saat ini. |

### Nilai Kembalian

Total byte yang dibaca ke dalam buffer. Ini dapat lebih sedikit daripada jumlah byte yang diminta jika byte tersebut tidak tersedia saat ini, atau nol (0) jika akhir aliran telah tercapai.

### Lihat Juga

* class [OptimizedMemoryStream](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


