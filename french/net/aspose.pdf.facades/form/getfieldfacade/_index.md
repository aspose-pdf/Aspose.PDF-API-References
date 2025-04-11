---
title: Form.GetFieldFacade
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Renvoie un objet FrofmFieldFacade contenant tous les attributs d'apparence
type: docs
weight: 210
url: /fr/net/aspose.pdf.facades/form/getfieldfacade/
---
## Méthode Form.GetFieldFacade

Renvoie un objet FrofmFieldFacade contenant tous les attributs d'apparence.

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("form.pdf");
FormFieldFacade field = form.GetFieldFacade("field1");
Console.WriteLine("Color of field border: " + field.BorderColor);
```

```csharp
public FormFieldFacade GetFieldFacade(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du champ à lire. |

### Valeur de retour

Objet FormFieldFacade

### Voir aussi

* classe [FormFieldFacade](../../formfieldfacade/)
* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)