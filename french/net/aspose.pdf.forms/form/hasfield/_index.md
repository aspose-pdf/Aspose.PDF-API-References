---
title: "Form.HasField"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Vérifie si le formulaire possède déjà le champ spécifié."
type: docs
weight: 300
url: /fr/net/aspose.pdf.forms/form/hasfield/
---
## HasField(Field) {#hasfield}

Vérifie si le formulaire possède déjà le champ spécifié.

```csharp
public bool HasField(Field field)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| champ | Champ | Champ à vérifier. |

### Valeur de retour

`true` si le nom de champ spécifié a été ajouté au Form ; sinon, `false`.

### Voir aussi

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string) {#hasfield_1}

Détermine si le champ portant le nom spécifié a déjà été ajouté au formulaire.

```csharp
public bool HasField(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) ou [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) du champ. |

### Valeur de retour

`true` si le nom de champ spécifié a été ajouté au Form ; sinon, `false`.

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## HasField(string, bool) {#hasfield_2}

Détermine si le champ portant le nom spécifié a déjà été ajouté au formulaire, avec la possibilité d'examiner la hiérarchie des champs enfants.

```csharp
public bool HasField(string fieldName, bool searchChildren)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | [`PartialName`](../../field/partialname/) ou [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) du champ. |
| searchChildren | Boolean | Lorsque réglé sur `true`, toute la hiérarchie des champs de formulaire serait recherchée pour le *fieldName* demandé (notez que dans ce cas le [`FullName`](../../../aspose.pdf.annotations/annotation/fullname/) du champ requis doit être passé comme *fieldName*). |

### Valeur de retour

`true` si le nom de champ spécifié a été ajouté au Form ; sinon, `false`.

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


