---
title: OperatorCollection.Delete
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection-Methode. Löscht Operator aus der Sammlung
type: docs
weight: 110
url: /de/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

Löscht Operator aus der Sammlung.

```csharp
public void Delete(int index)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| index | Int32 | Index des Operators, der gelöscht werden muss. Die Nummerierung der Operatoren beginnt bei 1. |

## Beispiele

Das Beispiel zeigt, wie man einen Operator anhand seines Index löscht.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### Siehe auch

* Klasse [OperatorCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

Löscht Operatoren aus der Sammlung.

```csharp
public void Delete(Operator[] ops)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| ops | Operator[] | Array von zu löschenden Operatoren |

## Beispiele

Das Beispiel zeigt, wie man einen Operator aus dem Seiteninhalt entfernt.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### Siehe auch

* Klasse [Operator](../../operator/)
* Klasse [OperatorCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

Löscht Operatoren aus der Sammlung.

```csharp
public void Delete(IList<Operator> list)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| list | IList`1 | Die Liste der zu löschenden Operatoren |

## Beispiele

Das Beispiel zeigt, wie man einen Operator aus dem Seiteninhalt entfernt.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### Siehe auch

* Klasse [Operator](../../operator/)
* Klasse [OperatorCollection](../)
* Namespace [Aspose.Pdf](../../../aspose.pdf/)
* Assembly [Aspose.PDF](../../../)