---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection method. Inserts operator into collection
type: docs
weight: 140
url: /it/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

Inserisce l'operatore nella collezione.

```csharp
public override void Insert(int index, Operator op)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Indice in cui il nuovo operatore deve essere aggiunto |
| op | Operator | Operatore che verrà inserito |

## Esempi

L'esempio dimostra come inserire un operatore nei contenuti della pagina.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### Vedi Anche

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Inserisci operatori nella posizione data.

```csharp
public void Insert(int at, Operator[] ops)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| at | Int32 | Indice da cui gli operatori iniziano a essere inseriti. |
| ops | Operator[] | Array di operatori da inserire. Ogni operatore può avere qualsiasi indice (per impostazione predefinita -1) poiché i loro indici vengono regolati automaticamente a partire da *at*. |

## Esempi

L'esempio dimostra come inserire un operatore nei contenuti della pagina.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Vedi Anche

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Inserisci operatori nella posizione data.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| at | Int32 | Indice da cui gli operatori iniziano a essere inseriti. |
| ops | IList`1 | Array di operatori da inserire. |

## Esempi

L'esempio dimostra come inserire operatori nei contenuti della pagina.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### Vedi Anche

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)