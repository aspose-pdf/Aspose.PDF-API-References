---
title: OperatorCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: Metode OperatorCollection. Menambahkan operator baru ke dalam koleksi
type: docs
weight: 60
url: /id/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

Menambahkan operator baru ke dalam koleksi.

```csharp
public override void Add(Operator op)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| op | Operator | Operator yang harus ditambahkan |

## Contoh

Contoh menunjukkan cara menambahkan operator ke akhir page.contents.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### Lihat Juga

* kelas [Operator](../../operator/)
* kelas [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

Menambahkan operator di akhir operator konten.

```csharp
public void Add(Operator[] ops)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ops | Operator[] | Array operator yang akan ditambahkan. Setiap operator dapat memiliki indeks apa pun (secara default -1) karena mereka datang ke akhir operator konten yaitu indeks ditetapkan secara otomatis. |

## Contoh

Contoh menunjukkan cara menambahkan operator ke akhir konten halaman.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Lihat Juga

* kelas [Operator](../../operator/)
* kelas [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

Menambahkan ke koleksi semua operator dari koleksi lain.

```csharp
public void Add(ICollection<Operator> ops)
```

| Parameter | Tipe | Deskripsi |
| --- | --- | --- |
| ops | ICollection`1 | koleksi yang berisi operator yang akan ditambahkan. |

## Contoh

Contoh menunjukkan cara menambahkan koleksi operator ke konten halaman.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### Lihat Juga

* kelas [Operator](../../operator/)
* kelas [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)