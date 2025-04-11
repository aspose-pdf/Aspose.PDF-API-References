---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection metod. Infogar operator i samlingen
type: docs
weight: 140
url: /sv/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

Infogar operator i samlingen.

```csharp
public override void Insert(int index, Operator op)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Index där ny operator måste läggas till |
| op | Operator | Operator som kommer att infogas |

## Exempel

Exemplet visar hur man infogar en operator i sidinnehållet.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### Se Även

* klass [Operator](../../operator/)
* klass [OperatorCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Infoga operatorer på den angivna positionen.

```csharp
public void Insert(int at, Operator[] ops)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| at | Int32 | Index från vilket operatorer börjar infogas. |
| ops | Operator[] | Array av operatorer som ska infogas. Varje operator kan ha vilket index som helst (som standard -1) eftersom deras index justeras automatiskt från *at*. |

## Exempel

Exemplet visar hur man infogar en operator i sidinnehållet.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Se Även

* klass [Operator](../../operator/)
* klass [OperatorCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Infoga operatorer på den angivna positionen.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| at | Int32 | Index från vilket operatorer börjar infogas. |
| ops | IList`1 | Array av operatorer som ska infogas. |

## Exempel

Exemplet visar hur man infogar operatorer i sidinnehållet.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### Se Även

* klass [Operator](../../operator/)
* klass [OperatorCollection](../)
* namnrymd [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)