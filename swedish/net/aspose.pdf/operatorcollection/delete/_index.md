---
title: OperatorCollection.Delete
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection metod. Tar bort operator från samlingen
type: docs
weight: 110
url: /sv/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

Tar bort operator från samlingen.

```csharp
public void Delete(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Index för operatorn som måste tas bort. Operatorernas numrering börjar från 1. |

## Exempel

Exemplet visar hur man tar bort en operator med dess index.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### Se Även

* klass [OperatorCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

Tar bort operatorer från samlingen.

```csharp
public void Delete(Operator[] ops)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ops | Operator[] | Array av operatorer att ta bort |

## Exempel

Exemplet visar hur man tar bort en operator från sidinnehållet.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### Se Även

* klass [Operator](../../operator/)
* klass [OperatorCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

Tar bort operatorer från samlingen.

```csharp
public void Delete(IList<Operator> list)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| list | IList`1 | Listan över operatorer att ta bort |

## Exempel

Exemplet visar hur man tar bort en operator från sidinnehållet.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### Se Även

* klass [Operator](../../operator/)
* klass [OperatorCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)