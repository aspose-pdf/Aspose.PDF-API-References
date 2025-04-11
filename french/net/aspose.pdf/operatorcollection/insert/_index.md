---
title: OperatorCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: Méthode OperatorCollection. Insère un opérateur dans la collection
type: docs
weight: 140
url: /fr/net/aspose.pdf/operatorcollection/insert/
---
## Insert(int, Operator) {#insert}

Insère un opérateur dans la collection.

```csharp
public override void Insert(int index, Operator op)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Index où le nouvel opérateur doit être ajouté |
| op | Operator | Opérateur qui sera inséré |

## Exemples

L'exemple démontre comment insérer un opérateur dans le contenu de la page.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### Voir aussi

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Insérer des opérateurs à la position donnée.

```csharp
public void Insert(int at, Operator[] ops)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| at | Int32 | Index à partir duquel les opérateurs commencent à être insérés. |
| ops | Operator[] | Tableau d'opérateurs à insérer. Chaque opérateur peut avoir n'importe quel index (par défaut -1) car leurs indices sont ajustés automatiquement à partir de *at*. |

## Exemples

L'exemple démontre comment insérer un opérateur dans le contenu de la page.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Voir aussi

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Insérer des opérateurs à la position donnée.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| at | Int32 | Index à partir duquel les opérateurs commencent à être insérés. |
| ops | IList`1 | Tableau d'opérateurs à insérer. |

## Exemples

L'exemple démontre comment insérer des opérateurs dans le contenu de la page.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### Voir aussi

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)