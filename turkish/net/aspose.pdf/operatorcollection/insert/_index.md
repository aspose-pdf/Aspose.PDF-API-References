---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection metodu. Operatörü koleksiyona ekler
type: docs
weight: 140
url: /tr/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

Operatörü koleksiyona ekler.

```csharp
public override void Insert(int index, Operator op)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | Int32 | Yeni operatörün eklenmesi gereken indeks |
| op | Operator | Eklenecek operatör |

## Örnekler

Örnek, operatörün sayfa içeriğine nasıl ekleneceğini gösterir.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### Ayrıca Bakınız

* sınıf [Operator](../../operator/)
* sınıf [OperatorCollection](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Verilen konumda operatörleri ekler.

```csharp
public void Insert(int at, Operator[] ops)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| at | Int32 | Operatörlerin eklenmeye başlandığı indeks. |
| ops | Operator[] | Eklenecek operatörlerin dizisi. Her operatör herhangi bir indekse sahip olabilir (varsayılan -1) çünkü indeksleri *at*'dan itibaren otomatik olarak ayarlanır. |

## Örnekler

Örnek, operatörün sayfa içeriğine nasıl ekleneceğini gösterir.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Ayrıca Bakınız

* sınıf [Operator](../../operator/)
* sınıf [OperatorCollection](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Verilen konumda operatörleri ekler.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| at | Int32 | Operatörlerin eklenmeye başlandığı indeks. |
| ops | IList`1 | Eklenecek operatörlerin dizisi. |

## Örnekler

Örnek, operatörlerin sayfa içeriğine nasıl ekleneceğini gösterir.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### Ayrıca Bakınız

* sınıf [Operator](../../operator/)
* sınıf [OperatorCollection](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)