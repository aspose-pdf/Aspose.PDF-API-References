---
title: "OperatorCollection.Add"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OperatorCollection-metod. Lägger till en ny operator i samlingen"
type: docs
weight: 60
url: /sv/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

Lägger till en ny operator i samlingen.

```csharp
public override void Add(Operator op)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| op | Operator | Operator som måste läggas till |

## Exempel

Exempel visar hur man lägger till operatorer i slutet av page.contents.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### Se även

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

Lägg till operatorer i slutet av innehållsoperatorerna.

```csharp
public void Add(Operator[] ops)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ops | Operator[] | Array av operatorer som ska läggas till. Varje operator kan ha vilket index som helst (standardvärde -1) eftersom de placeras i slutet av innehållsoperatorerna, d.v.s. index tilldelas automatiskt. |

## Exempel

Exempel visar hur man lägger till en operator i slutet av sidans innehåll.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Se även

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

Lägger till alla operatorer från en annan samling i samlingen.

```csharp
public void Add(ICollection<Operator> ops)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ops | ICollection`1 | samling som innehåller operatorer som kommer att läggas till. |

## Exempel

Exempel visar hur man lägger till en operator-samling i sidans innehåll.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### Se även

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


