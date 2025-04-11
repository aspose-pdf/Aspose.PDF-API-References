---
title: Form.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Exporterar PDF-formulärfält till JSON-format och skriver resultatet till den angivna strömmen
type: docs
weight: 240
url: /sv/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exporterar PDF-formulärfält till JSON-format och skriver resultatet till den angivna strömmen.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att skriva JSON-utdata till. |
| options | ExportFieldsToJsonOptions | Valfria inställningar för att exportera formulärfälten till JSON. |

### Returvärde

En samling av [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) som indikerar resultatet av exportoperationen för varje formulärfält.

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### Se Även

* klass [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* klass [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* klass [Form](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exporterar PDF-formulärfält till JSON-format och skriver resultatet till den angivna filen.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | Namnet på filen att skriva JSON-utdata till. |
| options | ExportFieldsToJsonOptions | Valfria inställningar för att exportera formulärfälten till JSON. |

### Returvärde

En samling av [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) som indikerar resultatet av exportoperationen för varje formulärfält.

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### Se Även

* klass [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* klass [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* klass [Form](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)