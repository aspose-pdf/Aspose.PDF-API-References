---
title: "Form.ExportXfdf"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Exporte le contenu des champs du PDF vers le flux XML. La valeur des champs bouton ne sera pas exportée"
type: docs
weight: 90
url: /fr/net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf method

Exporte le contenu des champs du pdf vers le flux xml. La valeur du champ bouton ne sera pas exportée.

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

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


