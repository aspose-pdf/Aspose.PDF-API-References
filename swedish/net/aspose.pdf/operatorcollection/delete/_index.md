---
title: "OperatorCollection.Delete"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OperatorCollection-metod. Raderar en operator från samlingen"
type: docs
weight: 110
url: /sv/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

Raderar operatorn från samlingen.

```csharp
public void Delete(int index)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Index för operator som måste raderas. Operatorernas numrering börjar från 1. |

## Exempel

Exempel visar hur man raderar en operator med dess index.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### Se även

* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

Raderar operatorer från samlingen.

```csharp
public void Delete(Operator[] ops)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ops | Operator[] | Array av operatorer att radera |

## Exempel

Exemplet visar hur man tar bort en operator från sidinnehållet.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### Se även

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

Raderar operatorer från samlingen.

```csharp
public void Delete(IList<Operator> list)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| lista | IList`1 | Listan över operatorer att ta bort |

## Exempel

Exemplet visar hur man tar bort en operator från sidinnehållet.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### Se även

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


