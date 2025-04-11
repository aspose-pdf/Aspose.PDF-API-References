---
title: OperatorCollection.Delete
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection metodu. Koleksiyondan operatörü siler
type: docs
weight: 110
url: /tr/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

Koleksiyondan operatörü siler.

```csharp
public void Delete(int index)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| index | Int32 | Silinmesi gereken operatörün indeksi. Operatör numaralandırması 1'den başlar. |

## Örnekler

Örnek, operatörü indeksine göre nasıl sileceğinizi gösterir.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### Ayrıca Bakınız

* sınıf [OperatorCollection](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

Koleksiyondan operatörleri siler.

```csharp
public void Delete(Operator[] ops)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| ops | Operator[] | Silinecek operatörlerin dizisi |

## Örnekler

Örnek, sayfa içeriklerinden operatörü nasıl kaldıracağınızı gösterir.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### Ayrıca Bakınız

* sınıf [Operator](../../operator/)
* sınıf [OperatorCollection](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

Koleksiyondan operatörleri siler.

```csharp
public void Delete(IList<Operator> list)
```

| Parametre | Tür | Açıklama |
| --- | --- | --- |
| list | IList`1 | Silinecek operatörlerin listesi |

## Örnekler

Örnek, sayfa içeriklerinden operatörü nasıl kaldıracağınızı gösterir.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### Ayrıca Bakınız

* sınıf [Operator](../../operator/)
* sınıf [OperatorCollection](../)
* ad alanı [Aspose.Pdf](../../../aspose.pdf/)
* derleme [Aspose.PDF](../../../)