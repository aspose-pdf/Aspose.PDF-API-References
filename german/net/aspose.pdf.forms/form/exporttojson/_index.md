---
title: Form.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Exportiert die PDF-Formularfelder in das JSON-Format und schreibt das Ergebnis in den bereitgestellten Stream
type: docs
weight: 240
url: /de/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exportiert die PDF-Formularfelder in das JSON-Format und schreibt das Ergebnis in den bereitgestellten Stream.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| stream | Stream | Der Stream, in den die JSON-Ausgabe geschrieben wird. |
| options | ExportFieldsToJsonOptions | Optionale Einstellungen für den Export der Formularfelder nach JSON. |

### Rückgabewert

Eine Sammlung von [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) die das Ergebnis der Exportoperation für jedes Formularfeld angibt.

## Beispiele

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### Siehe auch

* Klasse [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* Klasse [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* Klasse [Form](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exportiert die PDF-Formularfelder in das JSON-Format und schreibt das Ergebnis in die angegebene Datei.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fileName | String | Der Name der Datei, in die die JSON-Ausgabe geschrieben wird. |
| options | ExportFieldsToJsonOptions | Optionale Einstellungen für den Export der Formularfelder nach JSON. |

### Rückgabewert

Eine Sammlung von [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) die das Ergebnis der Exportoperation für jedes Formularfeld angibt.

## Beispiele

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### Siehe auch

* Klasse [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* Klasse [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* Klasse [Form](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)