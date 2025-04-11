---
title: OperatorCollection.Delete
second_title: Aspose.PDF for .NET API Reference
description: Metodo OperatorCollection. Elimina l'operatore dalla collezione
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
| index | Int32 | Indice dell'operatore che deve essere eliminato. La numerazione degli operatori inizia da 1. |

## Esempi

L'esempio dimostra come eliminare un operatore in base al suo indice.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### Vedi Anche

* classe [OperatorCollection](../)
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

L'esempio dimostra come rimuovere un operatore dai contenuti della pagina.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### Vedi Anche

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
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
| list | IList`1 | La lista degli operatori da eliminare |

## Esempi

L'esempio dimostra come rimuovere un operatore dai contenuti della pagina.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### Vedi Anche

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)