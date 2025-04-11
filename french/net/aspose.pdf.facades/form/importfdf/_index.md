---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Importe le contenu des champs du fichier fdf et les place dans le nouveau pdf
type: docs
weight: 280
url: /fr/net/aspose.pdf.facades/form/importfdf/
---
## Méthode Form.ImportFdf

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

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)