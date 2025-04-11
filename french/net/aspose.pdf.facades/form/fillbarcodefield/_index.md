---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Remplir un champ de code-barres selon son nom de champ entièrement qualifié
type: docs
weight: 120
url: /fr/net/aspose.pdf.facades/form/fillbarcodefield/
---
## Méthode Form.FillBarcodeField

Remplir un champ de code-barres selon son nom de champ entièrement qualifié.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ entièrement qualifié. |
| data | String | La nouvelle valeur du code-barres. |

### Valeur de retour

Si le remplissage réussit, retourne true ; sinon, false.

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)