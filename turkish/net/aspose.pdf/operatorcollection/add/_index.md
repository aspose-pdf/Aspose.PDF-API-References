---
title: OperatorCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection metodu. Koleksiyona yeni operatör ekler
type: docs
weight: 60
url: /tr/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

Koleksiyona yeni operatör ekler.

```csharp
public override void Add(Operator op)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| op | Operator | Eklenmesi gereken operatör |

## Örnekler

Örnek, operatörlerin page.contents'in sonuna nasıl ekleneceğini gösterir.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### Ayrıca Bakınız

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

İçerik operatörlerinin sonuna operatör ekler.

```csharp
public void Add(Operator[] ops)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ops | Operator[] | Eklenmesi gereken operatörler dizisi. Her operatör herhangi bir indekse sahip olabilir (varsayılan -1) çünkü içerik operatörlerinin sonuna gelirler, yani indeksler otomatik olarak atanır. |

## Örnekler

Örnek, operatörün sayfa içeriğinin sonuna nasıl ekleneceğini gösterir.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Ayrıca Bakınız

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

Diğer koleksiyondan tüm operatörleri koleksiyona ekler.

```csharp
public void Add(ICollection<Operator> ops)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ops | ICollection`1 | Eklenmesi gereken operatörleri içeren koleksiyon. |

## Örnekler

Örnek, operatör koleksiyonunun sayfa içeriğine nasıl ekleneceğini gösterir.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### Ayrıca Bakınız

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)