---
title: OperatorCollection.Add
second_title: Aspose.PDF for .NET API Reference
description: OperatorCollection metodo. Aggiunge un nuovo operatore nella collezione.
type: docs
weight: 60
url: /it/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

Aggiunge un nuovo operatore nella collezione.

```csharp
public override void Add(Operator op)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| op | Operatore | Operatore che deve essere aggiunto |

## Esempi

L'esempio dimostra come aggiungere operatori alla fine di page.contents.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### Vedi Anche

* classe [Operatore](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

Aggiunge operatori alla fine degli operatori dei contenuti.

```csharp
public void Add(Operator[] ops)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ops | Operatore[] | Array di operatori da aggiungere. Ogni operatore può avere qualsiasi indice (per impostazione predefinita -1) perché vengono aggiunti alla fine degli operatori dei contenuti, cioè gli indici vengono assegnati automaticamente. |

## Esempi

L'esempio dimostra come aggiungere un operatore alla fine dei contenuti della pagina.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Vedi Anche

* classe [Operatore](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

Aggiunge alla collezione tutti gli operatori da un'altra collezione.

```csharp
public void Add(ICollection<Operator> ops)
```

| Parametro | Tipo | Descrizione |
| --- | --- | --- |
| ops | ICollection`1 | collezione che contiene operatori che verranno aggiunti. |

## Esempi

L'esempio dimostra come aggiungere una collezione di operatori ai contenuti della pagina.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### Vedi Anche

* classe [Operatore](../../operator/)
* classe [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)