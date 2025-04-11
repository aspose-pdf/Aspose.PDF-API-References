---
title: Form.ImportFromJson
second_title: Aspose.PDF for .NET API Reference
description: Formularmethode. Importiert die PDF-Formularfelder aus dem im Stream bereitgestellten JSON-Format
type: docs
weight: 290
url: /de/net/aspose.pdf.forms/form/importfromjson/
---
## ImportFromJson(Stream) {#importfromjson}

Importiert die PDF-Formularfelder aus dem im Stream bereitgestellten JSON-Format.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(Stream stream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, aus dem die JSON-Eingabe gelesen wird. |

### Rückgabewert

Eine Sammlung von [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) die das Ergebnis der Importoperation für jedes Formularfeld angibt.

## Beispiele

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("import.json", FileMode.Open, FileAccess.Read);
document.Form.ImportFormFieldsFromJson(fs);
fs.Close();
document.Save();
```

### Siehe auch

* Klasse [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* Klasse [Form](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)

---

## ImportFromJson(string) {#importfromjson_1}

Importiert die PDF-Formularfelder aus dem im angegebenen Datei bereitgestellten JSON-Format.

```csharp
public IEnumerable<FieldSerializationResult> ImportFromJson(string fileName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der Name der Datei, aus der die JSON-Eingabe gelesen wird. |

### Rückgabewert

Eine Sammlung von [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) die das Ergebnis der Importoperation für jedes Formularfeld angibt.

## Beispiele

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "import.json";
document.Form.ImportFormFieldsFromJson(jsonPath);
document.Save();
```

### Siehe auch

* Klasse [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* Klasse [Form](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)