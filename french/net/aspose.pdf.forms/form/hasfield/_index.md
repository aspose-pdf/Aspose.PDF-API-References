---
title: Form.HasField
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Vérifiez si le formulaire a déjà le champ spécifié
type: docs
weight: 280
url: /fr/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Vérifiez si le formulaire a déjà le champ spécifié.

```csharp
public bool HasField(Field field)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| field | Field | Champ à vérifier. |

### Valeur de retour

`true` si le nom de champ spécifié a été ajouté au formulaire ; sinon, `false`.

### Voir aussi

* classe [Field](../../field/)
* classe [Form](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Détermine si le champ avec le nom spécifié a déjà été ajouté au formulaire.

```csharp
public bool HasField(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) ou [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) du champ. |

### Valeur de retour

`true` si le nom de champ spécifié a été ajouté au formulaire ; sinon, `false`.

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Détermine si le champ avec le nom spécifié a déjà été ajouté au formulaire, avec la possibilité de rechercher dans la hiérarchie des champs enfants.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) ou [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) du champ. |
| searchChildren | Boolean | Lorsqu'il est défini sur `true`, toute la hiérarchie des champs de formulaire sera recherchée pour le *fieldName* demandé (notez que dans ce cas, le [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) du champ requis doit être passé comme *fieldName*). |

### Valeur de retour

`true` si le nom de champ spécifié a été ajouté au formulaire ; sinon, `false`.

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)