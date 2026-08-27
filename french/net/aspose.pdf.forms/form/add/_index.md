---
title: "Form.Add"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Ajoute un champ sur le formulaire"
type: docs
weight: 210
url: /fr/net/aspose.pdf.forms/form/add/
---
## Add(Field, int) {#add_2}

Ajoute un champ au formulaire.

```csharp
public void Add(Field field, int pageNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| champ | Champ | Champ qui doit être ajouté. |
| pageNumber | Int32 | Index de la page où le champ ajouté sera placé. |

### Voir aussi

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field) {#add_1}

Ajoute un champ au formulaire.

```csharp
public void Add(Field field)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| champ | Champ | Champ qui doit être ajouté. |

### Voir aussi

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## Add(Field, string, int) {#add}

Ajoute un nouveau champ au formulaire ; si ce champ est déjà placé sur un autre formulaire ou sur celui-ci, une copie du champ est créée.

```csharp
public Field Add(Field field, string partialName, int pageNumber)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| champ | Champ | Nom du champ. |
| partialName | String | Nom du champ sur le formulaire. |
| pageNumber | Int32 | Numéro de page où le champ sera ajouté. |

### Valeur de retour

Champ ajouté renvoyé. Si une copie du champ a été créée, elle sera renvoyée.

### Voir aussi

* class [Field](../../field/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


