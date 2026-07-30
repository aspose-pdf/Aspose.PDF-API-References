---
title: "Form.GetSubmitFlags"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Retourne les indicateurs de soumission des boutons"
type: docs
weight: 270
url: /fr/net/aspose.pdf.facades/form/getsubmitflags/
---
## Form.GetSubmitFlags method

Renvoie les indicateurs de soumission du bouton d'envoi

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fieldName | String | Le nom de champ qualifié. |

### Valeur de retour

Indicateurs de soumission du bouton.

## Exemples

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");        
```

### Voir aussi

* enum [SubmitFormFlag](../../submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


