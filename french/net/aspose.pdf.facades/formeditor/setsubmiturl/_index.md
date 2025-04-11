---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: Méthode FormEditor. Définit l'URL du bouton
type: docs
weight: 340
url: /fr/net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## Méthode FormEditor.SetSubmitUrl

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

* classe [FormEditor](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)