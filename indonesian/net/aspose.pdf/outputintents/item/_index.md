---
title: "OutputIntents.Item"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Properti OutputIntents. Mendapatkan output intent pada indeks yang ditentukan."
type: docs
weight: 30
url: /id/net/aspose.pdf/outputintents/item/
---
## OutputIntents indexer

Mendapatkan output intent pada *index* yang ditentukan.

```csharp
public OutputIntent this[int index] { get; }
```

| Parameter | Deskripsi |
| --- | --- |
| index | Indeks berbasis nol dari output intent yang akan diambil. |

### Nilai Kembalian

Output intent pada *index* yang ditentukan.

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentOutOfRangeException | *index* kurang dari 0 atau *index* sama dengan atau lebih besar dari [`Count`](../count/). |
| InvalidOperationException | Dokumen yang berisi koleksi tidak memiliki katalog untuk mengakses OutputIntents. |

### Lihat Juga

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


