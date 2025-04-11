---
title: OutputIntents.CopyTo
second_title: Aspose.PDF for .NET API Reference
description: Metode OutputIntents. Menyalin elemen koleksi ke *array* mulai dari *arrayIndex* tertentu ke dalam array
type: docs
weight: 70
url: /id/net/aspose.pdf/outputintents/copyto/
---
## Metode OutputIntents.CopyTo

Menyalin elemen koleksi ke dalam *array*, mulai dari *arrayIndex* tertentu ke dalam array.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | OutputIntent[] | Array satu dimensi yang merupakan tujuan dari output intents yang disalin dari koleksi. Array harus memiliki pengindeksan berbasis nol. |
| arrayIndex | Int32 | Indeks berbasis nol di *array* di mana penyalinan dimulai. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *array* adalah null. |
| ArgumentOutOfRangeException | *arrayIndex* kurang dari 0. |
| ArgumentException | Jumlah elemen dalam sumber [`OutputIntents`](../) lebih besar dari ruang yang tersedia dari *arrayIndex* hingga akhir *array* tujuan. |

### Lihat Juga

* kelas [OutputIntent](../../outputintent/)
* kelas [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)