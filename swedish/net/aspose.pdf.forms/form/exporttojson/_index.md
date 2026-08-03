---
title: "Form.ExportToJson"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form method. Exporterar PDF-formulärfält till JSON-format och skriver resultatet till den angivna strömmen"
type: docs
weight: 260
url: /sv/net/aspose.pdf.forms/form/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exporterar PDF‑formulärfält till JSON‑format och skriver resultatet till den angivna strömmen.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Strömmen att skriva JSON-utdata till. |
| options | ExportFieldsToJsonOptions | Valfria inställningar för export av formulärfält till JSON. |

### Returvärde

En samling av [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) som indikerar resultatet av exportoperationen för varje formulärfält.

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
document.Form.ExportFormFieldsToJson(fs);
fs.Close();
```

### Se även

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exporterar PDF‑formulärfält till JSON‑format och skriver resultatet till den specificerade filen.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| `fileName` | String | Namnet på filen att skriva JSON-utdata till. |
| options | ExportFieldsToJsonOptions | Valfria inställningar för export av formulärfält till JSON. |

### Returvärde

En samling av [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) som indikerar resultatet av exportoperationen för varje formulärfält.

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
document.Form..ExportFormFieldsToJson(jsonPath);
```

### Se även

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


