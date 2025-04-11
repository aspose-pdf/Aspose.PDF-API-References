---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Méthode WidgetAnnotation. Exporte le champ de formulaire PDF spécifié au format JSON et écrit le résultat dans le flux fourni
type: docs
weight: 120
url: /fr/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exporte le champ de formulaire PDF spécifié au format JSON et écrit le résultat dans le flux fourni.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux dans lequel écrire la sortie JSON. |
| options | ExportFieldsToJsonOptions | Paramètres optionnels pour l'exportation du champ de formulaire au format JSON. |

### Valeur de retour

Une collection de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indiquant le résultat de l'opération d'exportation pour le champ de formulaire spécifié et ses éléments enfants, le cas échéant.

## Exemples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### Voir aussi

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* classe [WidgetAnnotation](../)
* espace de noms [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exporte le champ de formulaire PDF spécifié au format JSON et écrit le résultat dans le fichier spécifié.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Le nom du fichier dans lequel écrire la sortie JSON. |
| options | ExportFieldsToJsonOptions | Paramètres optionnels pour l'exportation du champ de formulaire au format JSON. |

### Valeur de retour

Une collection de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indiquant le résultat de l'opération d'exportation pour le champ de formulaire spécifié et ses éléments enfants, le cas échéant.

## Exemples

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### Voir aussi

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* classe [WidgetAnnotation](../)
* espace de noms [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)