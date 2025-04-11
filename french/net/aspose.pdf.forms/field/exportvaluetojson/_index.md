---
title: Field.ExportValueToJson
second_title: Aspose.PDF for .NET API Reference
description: Méthode Field. Exporte le contenu du champ spécifié dans un flux JSON. Les valeurs des champs de bouton ne sont pas exportées
type: docs
weight: 180
url: /fr/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Méthode Field.ExportValueToJson

Exporte le contenu du champ spécifié dans un flux JSON. Les valeurs des champs de bouton ne sont pas exportées.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputJsonStream | Stream | Le flux JSON de sortie où les données du champ seront écrites. |
| indented | Boolean | Optionnel. Spécifie si la sortie JSON doit être indentée pour une meilleure lisibilité. La valeur par défaut est true. |

## Exemples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### Voir aussi

* classe [Field](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)