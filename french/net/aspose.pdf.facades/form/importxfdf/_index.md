---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Importe le contenu des champs du fichier xfdfxml et les place dans le nouveau pdf
type: docs
weight: 300
url: /fr/net/aspose.pdf.facades/form/importxfdf/
---
## Méthode Form.ImportXfdf

Importe le contenu des champs du fichier xfdf(xml) et les place dans le nouveau pdf.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputXfdfStream | Stream | Le flux xfdf(xml) d'entrée. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)