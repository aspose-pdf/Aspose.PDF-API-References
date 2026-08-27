---
title: "OutputIntents.CopyTo"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "Metode OutputIntents. Menyalin elemen koleksi ke array mulai pada arrayIndex tertentu ke dalam array"
type: docs
weight: 70
url: /id/net/aspose.pdf/outputintents/copyto/
---
## OutputIntents.CopyTo method

Menyalin elemen koleksi ke *array*, mulai pada *arrayIndex* tertentu ke dalam array.

```csharp
public void CopyTo(OutputIntent[] array, int arrayIndex)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| array | OutputIntent[] | Array satu dimensi yang menjadi tujuan output intent yang disalin dari koleksi. Array harus memiliki indeks berbasis nol. |
| arrayIndex | Int32 | Indeks berbasis nol dalam *array* tempat penyalinan dimulai. |

### Pengecualian

| pengecualian | kondisi |
| --- | --- |
| ArgumentNullException | *array* bernilai null. |
| ArgumentOutOfRangeException | *arrayIndex* kurang dari 0. |
| ArgumentException | Jumlah elemen dalam sumber [`OutputIntents`](../) lebih besar daripada ruang yang tersedia dari *arrayIndex* hingga akhir *array* tujuan. |

### Lihat Juga

* class [OutputIntent](../../outputintent/)
* class [OutputIntents](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


