---
title: "Form.FlattenField"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Aplati un champ spécifié avec le nom complet du champ. Tout autre champ restera inchangé. Si le fieldName est invalide, tous les champs resteront inchangés."
type: docs
weight: 170
url: /fr/net/aspose.pdf.facades/form/flattenfield/
---
## Form.FlattenField method

Aplatisse un champ spécifié avec le nom de champ entièrement qualifié. Tout autre champ restera inchangé. Si le fieldName est invalide, tous les champs resteront inchangés.

```csharp
public void FlattenField(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom du champ à aplatir. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
form.FlattenField("textField");
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


