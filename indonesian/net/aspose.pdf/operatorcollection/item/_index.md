---
title: OperatorCollection.Item
second_title: Aspose.PDF for .NET API Reference
description: Properti OperatorCollection. Mendapatkan operator berdasarkan indeksnya
type: docs
weight: 40
url: /id/net/aspose.pdf/operatorcollection/item/
---
## Indeks OperatorCollection

Mendapatkan operator berdasarkan indeksnya.

```csharp
public override Operator this[int index] { get; set; }
```

| Parameter | Deskripsi |
| --- | --- |
| index | Indeks operator. Penomoran dimulai dari 1. |

### Nilai Kembali

Operator dari indeks yang diminta

## Contoh

Contoh menunjukkan cara mendapatkan operator dari konten halaman berdasarkan indeks.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Lihat Juga

* kelas [Operator](../../operator/)
* kelas [OperatorCollection](../)
* ruang nama [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)