---
title: "Form.FillBarcodeField"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Remplit un champ code-barres selon son nom de champ entièrement qualifié"
type: docs
weight: 120
url: /fr/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

Remplit un champ de code-barres selon son nom de champ entièrement qualifié.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom complet du champ. |
| data | String | La nouvelle valeur du code-barres. |

### Valeur de retour

Si le remplissage réussit, retourne true; sinon, false.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


