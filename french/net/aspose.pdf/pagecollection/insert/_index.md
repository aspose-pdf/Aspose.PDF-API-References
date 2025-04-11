---
title: PageCollection.Insert
second_title: Aspose.PDF for .NET API Reference
description: Méthode PageCollection. Insérer une page vide dans la collection à la position spécifiée. Si le document contient déjà des pages de tailles variées, la taille de la page la plus fréquemment rencontrée sera sélectionnée. Dans le cas où il n'y a que deux pages différentes, la taille de la première page sera utilisée.
type: docs
weight: 160
url: /fr/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Insérer une page vide dans la collection à la position spécifiée. Si le document contient déjà des pages de tailles variées, la taille de la page la plus fréquemment rencontrée sera sélectionnée. Dans le cas où il n'y a que deux pages différentes, la taille de la première page sera utilisée.

```csharp
public Page Insert(int pageNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Position de la nouvelle page. |

### Valeur de retour

Page insérée.

### Voir aussi

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page) {#insert_1}

Insère une page dans la collection de pages à l'endroit spécifié.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Index de page requis dans la collection. |
| entity | Page | Page à insérer. |

### Valeur de retour

Page insérée.

### Voir aussi

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Insère des pages de la collection dans le document.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Position de départ des nouvelles pages. |
| pages | ICollection`1 | Collection de pages. |

### Voir aussi

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, Page[]) {#insert_2}

Insère les pages du tableau dans le document.

```csharp
public void Insert(int pageNumber, Page[] pages)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Numéro de départ des nouvelles pages. |
| pages | Page[] | Tableau de pages qui seront insérées. |

### Voir aussi

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)