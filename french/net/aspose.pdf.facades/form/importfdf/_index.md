---
title: "Form.ImportFdf"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Importe le contenu des champs depuis le fichier fdf et les place dans le nouveau pdf."
type: docs
weight: 280
url: /fr/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf method

Importe le contenu des champs du fichier fdf et les place dans le nouveau pdf.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputFdfStream | Stream | Le flux fdf d'entrée. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


