---
title: "OperatorCollection.Insert"
second_title: "Aspose.PDF per .NET - Riferimento API"
description: "Metodo OperatorCollection. Inserisce un operatore nella collezione."
type: docs
weight: 140
url: /it/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

Inserisce l'operatore nella raccolta.

```csharp
public override void Insert(int index, Operator op)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| index | Int32 | Indice dove deve essere aggiunto il nuovo operatore. |
| op | Operator | Operatore che sarà inserito. |

## Esempi

L'esempio dimostra come inserire un operatore nel contenuto della pagina.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### Vedi anche

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Inserisce gli operatori nella posizione indicata.

```csharp
public void Insert(int at, Operator[] ops)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| at | Int32 | Indice da cui gli operatori iniziano ad essere inseriti. |
| ops | Operator[] | Array di operatori da inserire. Ogni operatore può avere qualsiasi indice (per impostazione predefinita -1) perché i loro indici vengono regolati automaticamente a partire da *at*. |

## Esempi

L'esempio dimostra come inserire un operatore nel contenuto della pagina.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Vedi anche

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Inserisce gli operatori nella posizione indicata.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| at | Int32 | Indice da cui gli operatori iniziano ad essere inseriti. |
| ops | IList`1 | Array di operatori da inserire. |

## Esempi

L'esempio dimostra come inserire operatori nel contenuto della pagina.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### Vedi anche

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


