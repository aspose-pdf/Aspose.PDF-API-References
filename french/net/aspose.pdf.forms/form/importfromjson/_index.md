---
title: Form.ImportFromJson
second_title: Aspose.PDF for .NET API Reference
description: Méthode Form. Importe les champs de formulaire PDF à partir du format JSON fourni dans le flux
type: docs
weight: 290
url: /fr/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

Importe les champs de formulaire PDF à partir du format JSON fourni dans le flux.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| stream | Stream | Le flux à partir duquel lire l'entrée JSON. |

### Valeur de retour

Une collection de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indiquant le résultat de l'opération d'importation pour chaque champ de formulaire.

## Exemples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### Voir aussi

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [Form](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

Importe les champs de formulaire PDF à partir du format JSON fourni dans le fichier spécifié.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| fileName | String | Le nom du fichier à partir duquel lire l'entrée JSON. |

### Valeur de retour

Une collection de [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indiquant le résultat de l'opération d'importation pour chaque champ de formulaire.

## Exemples

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### Voir aussi

* classe [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* classe [Form](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)