---
title: "Form.ExportFdf"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Méthode Form. Exporte le contenu des champs du pdf dans le flux fdf"
type: docs
weight: 70
url: /fr/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf method

Exporte le contenu des champs du pdf vers le flux fdf.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputFdfStream | Stream | Le flux fdf de sortie. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### Voir aussi

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


