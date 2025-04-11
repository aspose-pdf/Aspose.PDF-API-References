---
title: Field.ImportValueFromJson
second_title: Aspose.PDF for .NET API Reference
description: Méthode de champ. Importe des données dans les champs spécifiés à partir d'un flux JSON basé sur une correspondance exacte des noms complets des champs
type: docs
weight: 210
url: /fr/net/aspose.pdf.forms/field/importvaluefromjson/
---
## ImportValueFromJson(Stream) {#importvaluefromjson}

Importe des données dans les champs spécifiés à partir d'un flux JSON, basé sur une correspondance exacte des noms complets des champs.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputJsonStream | Stream | Le flux JSON d'entrée contenant les données du champ à importer dans le champ. |

### Valeur de retour

Vrai si le champ a été trouvé dans le flux JSON ; sinon - faux

## Exemples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs);
fs.Close();
document.Save();
```

### Voir aussi

* classe [Field](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ImportValueFromJson(Stream, string) {#importvaluefromjson_1}

Importe des données dans le champ spécifié à partir d'un flux JSON, en utilisant le nom complet spécifié dans la variable 'fieldFullNameInJSON' pour la correspondance.

```csharp
public bool ImportValueFromJson(Stream inputJsonStream, string fieldFullNameInJSON)
```

| Paramètre | Type | Description |
| --- | --- | --- |
| inputJsonStream | Stream | Le flux JSON d'entrée contenant les données du champ à importer dans le champ. |
| fieldFullNameInJSON | String | Le nom des données dans le flux JSON pour la correspondance. Si les données dans le flux JSON ont une structure imbriquée, le nom complet doit être spécifié avec tous les éléments parents et enfants séparés par '.' |

### Valeur de retour

Vrai si le champ a été trouvé dans le fichier json ; sinon - faux

## Exemples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
Field field = document.Form.Fields[0];
field.ImportValueFromJson(fs, "GroupName.AnotherFieldName");
fs.Close();
document.Save();
```

### Voir aussi

* classe [Field](../)
* espace de noms [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)