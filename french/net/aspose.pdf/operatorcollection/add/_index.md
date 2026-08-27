---
title: "OperatorCollection.Add"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode OperatorCollection. Ajoute un nouvel opérateur dans la collection."
type: docs
weight: 60
url: /fr/net/aspose.pdf/operatorcollection/add/
---
## Add(Operator) {#add}

Ajoute un nouvel opérateur dans la collection.

```csharp
public override void Add(Operator op)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| op | Operator | Opérateur qui doit être ajouté. |

## Exemples

L'exemple montre comment ajouter des opérateurs à la fin de page.contents.

```csharp
Document doc = new Document("input.pdf");
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.q());
doc.Pages[1].Contents.Add(new Aspose.Pdf.Operators.Q());
```

### Voir aussi

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(Operator[]) {#add_1}

Ajoute des opérateurs à la fin des opérateurs de contenu.

```csharp
public void Add(Operator[] ops)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| ops | Operator[] | Tableau d'opérateurs à ajouter. Chaque opérateur peut avoir n'importe quel indice (par défaut -1) car ils sont placés à la fin des opérateurs de contenu, c'est‑à‑dire que les indices sont attribués automatiquement. |

## Exemples

L'exemple montre comment ajouter un opérateur à la fin du contenu de la page.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Add(new Operator[] { new Aspose.Pdf.Operators.q(), new Aspose.Pdf.Operators.Q() } );
```

### Voir aussi

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Add(ICollection&lt;Operator&gt;) {#add_2}

Ajoute à la collection tous les opérateurs d’une autre collection.

```csharp
public void Add(ICollection<Operator> ops)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| ops | ICollection`1 | collection qui contient les opérateurs qui seront ajoutés. |

## Exemples

L'exemple montre comment ajouter la collection d'opérateurs au contenu de la page.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(new AOperator.q());
opList.Add(new Operators.Q());
oc.Add(opList);
```

### Voir aussi

* class [Operator](../../operator/)
* class [OperatorCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


