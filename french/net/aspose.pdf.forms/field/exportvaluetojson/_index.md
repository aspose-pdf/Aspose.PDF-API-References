---
title: "Field.ExportValueToJson"
second_title: "Référence de l'API Aspose.PDF pour .NET"
description: "Field method. Exporte le contenu du champ spécifié dans un flux JSON. Les valeurs des champs bouton ne sont pas exportées"
type: docs
weight: 180
url: /fr/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson method

Exporte le contenu du champ spécifié dans un flux JSON. Les valeurs des champs bouton ne sont pas exportées.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| outputJsonStream | Stream | Le flux JSON de sortie où les données du champ seront écrites. |
| indenté | Boolean | Optionnel. Spécifie si la sortie JSON doit être indentée pour une meilleure lisibilité. La valeur par défaut est true. |

## Exemples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### Voir aussi

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


