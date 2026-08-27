---
title: "OperatorCollection.Insert"
second_title: "Aspose.PDF för .NET API‑referens"
description: "OperatorCollection-metod. Infogar en operator i samlingen"
type: docs
weight: 140
url: /sv/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

Infogar operatorn i samlingen.

```csharp
public override void Insert(int index, Operator op)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| index | Int32 | Index där ny operator måste läggas till |
| op | Operator | Operator som kommer att infogas |

## Exempel

Exempel visar hur man infogar en operator i sidans innehåll.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### Se även

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Infoga operatorer på den angivna positionen.

```csharp
public void Insert(int at, Operator[] ops)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vid | Int32 | Index från vilket operatorer påbörjas att infogas. |
| ops | Operator[] | Array av operatorer som ska infogas. Varje operator kan ha vilket index som helst (standardvärde -1) eftersom deras index justeras automatiskt med början från *at*. |

## Exempel

Exempel visar hur man infogar en operator i sidans innehåll.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Se även

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Infoga operatorer på den angivna positionen.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| vid | Int32 | Index från vilket operatorer påbörjas att infogas. |
| ops | IList`1 | Array av operatorer som ska infogas. |

## Exempel

Exempel visar hur man infogar operatorer i sidans innehåll.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### Se även

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


