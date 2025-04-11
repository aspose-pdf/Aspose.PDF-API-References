---
title: Form.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Exporte les champs de formulaire PDF au format JSON et écrit le résultat dans le flux fourni
type: docs
weight: 240
url: /fr/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exporte les champs de formulaire PDF au format JSON et écrit le résultat dans le flux fourni.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux dans lequel écrire la sortie JSON. |
| options | ExportFieldsToJsonOptions | Paramètres optionnels pour l'exportation des champs de formulaire au format JSON. |

### Valeur de retour

Une collection de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indiquant le résultat de l'opération d'exportation pour chaque champ de formulaire.

## Exemples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### Voir aussi

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* classe [Form](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exporte les champs de formulaire PDF au format JSON et écrit le résultat dans le fichier spécifié.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Le nom du fichier dans lequel écrire la sortie JSON. |
| options | ExportFieldsToJsonOptions | Paramètres optionnels pour l'exportation des champs de formulaire au format JSON. |

### Valeur de retour

Une collection de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indiquant le résultat de l'opération d'exportation pour chaque champ de formulaire.

## Exemples

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### Voir aussi

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* classe [Form](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)