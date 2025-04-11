---
title: Form.ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Exporte le contenu des champs du pdf dans le flux xml. La valeur des champs de bouton ne sera pas exportée
type: docs
weight: 90
url: /fr/net/aspose.pdf.facades/form/exportxfdf/
---
## Méthode Form.ExportXfdf

Exporte le contenu des champs du pdf dans le flux xml. La valeur du champ de bouton ne sera pas exportée.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputXfdfStream | Stream | Le flux xml de sortie. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)