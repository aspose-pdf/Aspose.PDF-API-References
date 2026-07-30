---
title: "Form.ExportJson"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Form méthode. Exporte le contenu de tous les champs du document dans un flux JSON. Les valeurs des champs de bouton ne sont pas exportées"
type: docs
weight: 80
url: /fr/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson method

Exporte le contenu de tous les champs du document vers un flux JSON. Les valeurs des champs bouton ne sont pas exportées.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputJsonStream | Stream | Le flux JSON de sortie où les données des champs du document seront écrites. |
| indenté | Boolean | Optionnel. Spécifie si la sortie JSON doit être indentée pour une meilleure lisibilité. La valeur par défaut est true. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


