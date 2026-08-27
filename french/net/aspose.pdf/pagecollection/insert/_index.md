---
title: "PageCollection.Insert"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode PageCollection. Insère une page vide dans la collection à la position spécifiée. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n'y a que deux pages différentes, la taille de la première page sera utilisée."
type: docs
weight: 160
url: /fr/net/aspose.pdf/pagecollection/insert/
---
## Insert(int) {#insert}

Insère une page vide dans la collection à la position spécifiée. Si le document contient déjà des pages de tailles différentes, la taille de la page la plus fréquente sera sélectionnée. Dans le cas où il n’y a que deux pages différentes, la taille de la première page sera utilisée.

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

Insère une page dans la collection de pages à l'emplacement spécifié.

```csharp
public Page Insert(int pageNumber, Page entity)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Indice de Page requis dans la collection. |
| entité | Page | Page à insérer. |

### Valeur de retour

Page insérée.

### Voir aussi

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)

---

## Insert(int, ICollection&lt;Page&gt;) {#insert_3}

Insère les pages de la collection dans le document.

```csharp
public void Insert(int pageNumber, ICollection<Page> pages)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| pageNumber | Int32 | Position de départ des nouvelles pages. |
| pages | ICollection`1 | Collection de Pages. |

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
| pageNumber | Int32 | Nombre de départ des nouvelles pages. |
| pages | Page[] | Tableau de pages qui seront insérées. |

### Voir aussi

* class [Page](../../page/)
* class [PageCollection](../)
* namespace [Aspose.Pdf](../../../aspose.pdf/)
* assembly [Aspose.PDF](../../../)


