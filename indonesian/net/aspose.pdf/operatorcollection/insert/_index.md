---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: Metode OperatorCollection. Menyisipkan operator ke dalam koleksi
type: docs
weight: 140
url: /id/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

Menyisipkan operator ke dalam koleksi.

```csharp
public override void Insert(int index, Operator op)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| index | Int32 | Indeks di mana operator baru harus ditambahkan |
| op | Operator | Operator yang akan disisipkan |

## Contoh

Contoh menunjukkan cara menyisipkan operator ke dalam konten halaman.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### Lihat Juga

* kelas [Operator](../../operator/)
* kelas [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Sisipkan operator di posisi yang diberikan.

```csharp
public void Insert(int at, Operator[] ops)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| at | Int32 | Indeks dari mana operator mulai disisipkan. |
| ops | Operator[] | Array operator yang akan disisipkan. Setiap operator dapat memiliki indeks apa pun (secara default -1) karena indeks mereka disesuaikan secara otomatis mulai dari *at*. |

## Contoh

Contoh menunjukkan cara menyisipkan operator ke dalam konten halaman.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Lihat Juga

* kelas [Operator](../../operator/)
* kelas [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Sisipkan operator di posisi yang diberikan.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| at | Int32 | Indeks dari mana operator mulai disisipkan. |
| ops | IList`1 | Array operator yang akan disisipkan. |

## Contoh

Contoh menunjukkan cara menyisipkan operator ke dalam konten halaman.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### Lihat Juga

* kelas [Operator](../../operator/)
* kelas [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)