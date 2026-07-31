---
title: "OperatorCollection.Delete"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OperatorCollection. Elimina l'operatore dalla collezione"
type: docs
weight: 110
url: /it/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

Elimina l'operatore dalla collezione.

```csharp
public void Delete(int index)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Indice dell'operatore da eliminare. La numerazione degli operatori inizia da 1. |

## Esempi

L'esempio dimostra come eliminare l'operatore tramite il suo indice.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### Vedi anche

* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

Elimina gli operatori dalla collezione.

```csharp
public void Delete(Operator[] ops)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ops | Operator[] | Array di operatori da eliminare |

## Esempi

L'esempio dimostra come rimuovere l'operatore dal contenuto della pagina.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### Vedi anche

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

Elimina gli operatori dalla collezione.

```csharp
public void Delete(IList<Operator> list)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| elenco | IList`1 | L'elenco degli operatori da eliminare |

## Esempi

L'esempio dimostra come rimuovere l'operatore dal contenuto della pagina.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### Vedi anche

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


