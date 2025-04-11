---
title: OperatorCollection.Delete
second_title: Aspose.PDF for .NET API Reference
description: Méthode OperatorCollection. Supprime l'opérateur de la collection
type: docs
weight: 110
url: /fr/net/aspose.pdf/operatorcollection/delete/
---
## Delete(int) {#delete_1}

Supprime l'opérateur de la collection.

```csharp
public void Delete(int index)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| index | Int32 | Index de l'opérateur qui doit être supprimé. La numérotation des opérateurs commence à 1. |

## Exemples

L'exemple démontre comment supprimer un opérateur par son index.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(3);
```

### Voir aussi

* classe [OperatorCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(Operator[]) {#delete}

Supprime les opérateurs de la collection.

```csharp
public void Delete(Operator[] ops)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| ops | Operator[] | Tableau des opérateurs à supprimer |

## Exemples

L'exemple démontre comment retirer un opérateur du contenu de la page.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
oc.Delete(new Operator[] { oc[1] } );
```

### Voir aussi

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Delete(IList&lt;Operator&gt;) {#delete_2}

Supprime les opérateurs de la collection.

```csharp
public void Delete(IList<Operator> list)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| list | IList`1 | La liste des opérateurs à supprimer |

## Exemples

L'exemple démontre comment retirer un opérateur du contenu de la page.

```csharp
Document doc = new Document("input.pdf");
OperatorCollection oc = doc.Pages[1].Contents;
List<Operator> opList = new List<Operator>();
opList.Add(oc[1]);
oc.Delete(opList);
```

### Voir aussi

* classe [Operator](../../operator/)
* classe [OperatorCollection](../)
* espace de noms [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)