---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Importe toutes les données de champ d'un flux JSON dans les champs du document en faisant correspondre les champs par leurs noms complets
type: docs
weight: 290
url: /fr/net/aspose.pdf.facades/form/importjson/
---
## Méthode Form.ImportJson

Importe toutes les données de champ d'un flux JSON dans les champs du document, en faisant correspondre les champs par leurs noms complets.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputJsonStream | Stream | Le flux JSON d'entrée contenant les données de champ à importer dans les champs du document. |

## Exemples

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### Voir aussi

* classe [Form](../)
* espace de noms [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)