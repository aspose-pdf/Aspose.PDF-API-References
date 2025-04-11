---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection-Methode. Fügt Operator in die Sammlung ein
type: docs
weight: 140
url: /de/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

Fügt Operator in die Sammlung ein.

```csharp
public override void Insert(int index, Operator op)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index, an dem der neue Operator hinzugefügt werden muss |
| op | Operator | Operator, der eingefügt wird |

## Beispiele

Das Beispiel zeigt, wie man einen Operator in den Seiteninhalt einfügt.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### Siehe auch

* Klasse [Operator](../../operator/)
* Klasse [OperatorCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Fügt Operatoren an der angegebenen Position ein.

```csharp
public void Insert(int at, Operator[] ops)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| at | Int32 | Index, ab dem die Operatoren eingefügt werden. |
| ops | Operator[] | Array von Operatoren, die eingefügt werden sollen. Jeder Operator kann einen beliebigen Index haben (standardmäßig -1), da ihre Indizes automatisch ab *at* angepasst werden. |

## Beispiele

Das Beispiel zeigt, wie man einen Operator in den Seiteninhalt einfügt.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Siehe auch

* Klasse [Operator](../../operator/)
* Klasse [OperatorCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Fügt Operatoren an der angegebenen Position ein.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| at | Int32 | Index, ab dem die Operatoren eingefügt werden. |
| ops | IList`1 | Array von Operatoren, die eingefügt werden sollen. |

## Beispiele

Das Beispiel zeigt, wie man Operatoren in den Seiteninhalt einfügt.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### Siehe auch

* Klasse [Operator](../../operator/)
* Klasse [OperatorCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)