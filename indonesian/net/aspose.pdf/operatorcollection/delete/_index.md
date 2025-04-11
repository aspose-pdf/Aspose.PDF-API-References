---
title: OperatorCollection.Delete
second_title: Aspose.PDF for .NET API Reference
description: Metode OperatorCollection. Menghapus operator dari koleksi
type: docs
weight: 110
url: /id/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

Menghapus operator dari koleksi.

```csharp
public void Delete(int index)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Indeks operator yang harus dihapus. Penomoran operator dimulai dari 1. |

## Contoh

Contoh menunjukkan cara menghapus operator berdasarkan indeksnya.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### Lihat Juga

* kelas [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

Menghapus operator dari koleksi.

```csharp
public void Delete(Operator[] ops)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ops | Operator[] | Array operator yang akan dihapus |

## Contoh

Contoh menunjukkan cara menghapus operator dari konten halaman.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### Lihat Juga

* kelas [Operator](../../operator/)
* kelas [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

Menghapus operator dari koleksi.

```csharp
public void Delete(IList<Operator> list)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| list | IList`1 | Daftar operator yang akan dihapus |

## Contoh

Contoh menunjukkan cara menghapus operator dari konten halaman.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### Lihat Juga

* kelas [Operator](../../operator/)
* kelas [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)