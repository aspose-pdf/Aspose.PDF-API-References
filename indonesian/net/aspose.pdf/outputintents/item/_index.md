---
title: OutputIntents.Item
second_title: Aspose.PDF for .NET API Reference
description: Properti OutputIntents. Mendapatkan niat keluaran pada indeks yang ditentukan
type: docs
weight: 30
url: /id/net/aspose.pdf/outputintents/item/
---
## Indeks OutputIntents

Mendapatkan niat keluaran pada *indeks* yang ditentukan.

```csharp
public OutputIntent this[int index] { get; }
```

| Parameter | Deskripsi |
| --- | --- |
| index | Indeks berbasis nol dari niat keluaran yang akan diambil. |

### Nilai Kembali

Niat keluaran pada *indeks* yang ditentukan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *index* kurang dari 0 atau *index* sama dengan atau lebih besar dari [`Count`](../count/). |
| InvalidOperationException | Dokumen yang berisi koleksi tidak memiliki katalog untuk mengakses OutputIntents. |

### Lihat Juga

* kelas [OutputIntent](../../outputintent/)
* kelas [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)