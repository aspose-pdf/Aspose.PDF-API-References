---
title: "FormEditor.SetSubmitUrl"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode FormEditor. Définit l'URL du bouton"
type: docs
weight: 340
url: /fr/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

Définit l'URL du bouton.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Nom du bouton de soumission. |
| url | String | URL entièrement qualifiée. |

### Valeur de retour

true si l'URL du bouton a été définie avec succès.

## Exemples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### Voir aussi

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


