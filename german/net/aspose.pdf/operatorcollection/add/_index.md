---
title: OperatorCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection-Methode. Fügt neuen Operator zur Sammlung hinzu
type: docs
weight: 60
url: /de/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

Fügt neuen Operator zur Sammlung hinzu.

```csharp
public override void Add(Operator op)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| op | Operator | Operator, der hinzugefügt werden muss |

## Beispiele

Das Beispiel zeigt, wie man Operatoren am Ende von page.contents hinzufügt.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### Siehe auch

* Klasse [Operator](../../operator/)
* Klasse [OperatorCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

Fügt Operatoren am Ende der Inhaltsoperatoren hinzu.

```csharp
public void Add(Operator[] ops)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ops | Operator[] | Array von Operatoren, die hinzugefügt werden sollen. Jeder Operator kann einen beliebigen Index haben (standardmäßig -1), da sie am Ende der Inhaltsoperatoren kommen, d.h. Indizes werden automatisch zugewiesen. |

## Beispiele

Das Beispiel zeigt, wie man einen Operator am Ende des Seiteninhalts hinzufügt.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Siehe auch

* Klasse [Operator](../../operator/)
* Klasse [OperatorCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

Fügt der Sammlung alle Operatoren aus einer anderen Sammlung hinzu.

```csharp
public void Add(ICollection<Operator> ops)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ops | ICollection`1 | Sammlung, die Operatoren enthält, die hinzugefügt werden sollen. |

## Beispiele

Das Beispiel zeigt, wie man eine Operatorensammlung zu den Seiteninhalten hinzufügt.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### Siehe auch

* Klasse [Operator](../../operator/)
* Klasse [OperatorCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)