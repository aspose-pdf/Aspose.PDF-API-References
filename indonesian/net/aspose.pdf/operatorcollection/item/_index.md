---
title: "OperatorCollection.Item"
second_title: "Referensi API Aspose.PDF untuk .NET"
description: "OperatorCollection properti. Mendapatkan operator berdasarkan indeksnya"
type: docs
weight: 40
url: /id/net/aspose.pdf/operatorcollection/item/
---
## OperatorCollection indexer

Mendapatkan operator berdasarkan indeksnya.

```csharp
public override Operator this[int index] { get; set; }
```

| Parameter | Deskripsi |
| --- | --- |
| index | Indeks operator. Penomoran dimulai dari 1. |

### Nilai Kembalian

Operator dari indeks yang diminta

## Contoh

Contoh menunjukkan cara mendapatkan operator dari konten halaman berdasarkan indeks.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
Operator first = oc[1];
```

### Lihat Juga

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


