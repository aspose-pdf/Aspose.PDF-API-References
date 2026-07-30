---
title: "OperatorCollection.Insert"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode OperatorCollection. Insère un opérateur dans la collection."
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
| index | Int32 | Indice où le nouvel opérateur doit être ajouté. |
| op | Operator | Opérateur qui sera inséré. |

## Exemples

L'exemple montre comment insérer un opérateur dans le contenu de la page.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Aspose.Pdf.Operators.q());
oc.Add(new Aspose.Pdf.Operators.Q());
```

### Voir aussi

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Operator[]) {#insert_1}

Insérer les opérateurs à la position donnée.

```csharp
public void Insert(int at, Operator[] ops)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| at | Int32 | Indice à partir duquel les opérateurs commencent à être insérés. |
| ops | Operator[] | Tableau d'opérateurs à insérer. Chaque opérateur peut avoir n'importe quel indice (par défaut -1) car leurs indices sont ajustés automatiquement à partir de *at*. |

## Exemples

L'exemple montre comment insérer un opérateur dans le contenu de la page.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Insert(1, new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Voir aussi

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, IList&lt;Operator&gt;) {#insert_2}

Insérer les opérateurs à la position donnée.

```csharp
public void Insert(int at, IList<Operator> ops)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| at | Int32 | Indice à partir duquel les opérateurs commencent à être insérés. |
| ops | IList`1 | Tableau d'opérateurs à insérer. |

## Exemples

L'exemple montre comment insérer des opérateurs dans le contenu de la page.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new Operators.q());
opList.Add(new Operators.Q());
oc.Insert(1, opList);
```

### Voir aussi

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


