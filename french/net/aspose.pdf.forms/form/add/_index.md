---
title: Form.Add
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Ajoute un champ sur le formulaire
type: docs
weight: 190
url: /fr/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

Ajoute un champ sur le formulaire.

```csharp
public void Add(Field field, int pageNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| field | Field | Champ qui doit être ajouté. |
| pageNumber | Int32 | Index de la page où le champ ajouté sera placé. |

### Voir aussi

* classe [Field](../../field/)
* classe [Form](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

Ajoute un champ sur le formulaire.

```csharp
public void Add(Field field)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| field | Field | Champ qui doit être ajouté. |

### Voir aussi

* classe [Field](../../field/)
* classe [Form](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

Ajoute un nouveau champ au formulaire ; Si ce champ est déjà placé sur un autre formulaire ou celui-ci, une copie du champ est créée.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| field | Field | Nom du champ. |
| partialName | String | Nom du champ sur le formulaire. |
| pageNumber | Int32 | Numéro de la page où le champ sera ajouté. |

### Valeur de retour

Champ ajouté retourné. Si une copie du champ a été créée, elle sera retournée.

### Voir aussi

* classe [Field](../../field/)
* classe [Form](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)