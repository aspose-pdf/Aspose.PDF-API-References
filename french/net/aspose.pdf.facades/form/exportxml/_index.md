---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Exporte le contenu des champs du pdf dans le flux xml. La valeur des champs de bouton ne sera pas exportée
type: docs
weight: 100
url: /fr/net/aspose.pdf.facades/form/exportxml/
---
## Méthode Form.ExportXml

Exporte le contenu des champs du pdf dans le flux xml. La valeur du champ de bouton ne sera pas exportée.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputXmlStream | Stream | Flux Xml de sortie. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)