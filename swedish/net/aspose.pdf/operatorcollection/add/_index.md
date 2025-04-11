---
title: OperatorCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection metod. Lägger till ny operator i samlingen
type: docs
weight: 60
url: /sv/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

Lägger till ny operator i samlingen.

```csharp
public override void Add(Operator op)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| op | Operator | Operator som måste läggas till |

## Exempel

Exemplet visar hur man lägger till operatörer i slutet av page.contents.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### Se Även

* klass [Operator](../../operator/)
* klass [OperatorCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

Lägg till operatörer i slutet av innehållets operatörer.

```csharp
public void Add(Operator[] ops)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ops | Operator[] | Array av operatörer som ska läggas till. Varje operator kan ha vilket index som helst (som standard -1) eftersom de kommer till slutet av innehållets operatörer dvs. index tilldelas automatiskt. |

## Exempel

Exemplet visar hur man lägger till en operator i slutet av sidinnehållet.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Se Även

* klass [Operator](../../operator/)
* klass [OperatorCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

Lägger till alla operatörer från en annan samling till samlingen.

```csharp
public void Add(ICollection<Operator> ops)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ops | ICollection`1 | samling som innehåller operatörer som ska läggas till. |

## Exempel

Exemplet visar hur man lägger till en operator-samling till sidinnehållet.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### Se Även

* klass [Operator](../../operator/)
* klass [OperatorCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* samling [Aspose.PDF](../../../)