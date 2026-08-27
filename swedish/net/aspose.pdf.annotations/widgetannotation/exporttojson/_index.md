---
title: "WidgetAnnotation.ExportToJson"
second_title: "Aspose.PDF för .NET API‑referens"
description: "WidgetAnnotation-metod. Exporterar det angivna PDF-formulärfältet till JSON-format och skriver resultatet till den angivna strömmen"
type: docs
weight: 120
url: /sv/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exporterar det angivna PDF‑formulärfältet till JSON‑format och skriver resultatet till den angivna strömmen.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| ström | Stream | Strömmen att skriva JSON-utdata till. |
| options | ExportFieldsToJsonOptions | Valfria inställningar för export av formulärfältet till JSON. |

### Returvärde

En samling av [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) som indikerar resultatet av exportoperationen för det angivna formulärfältet och dess underordnade element, om sådana finns.

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### Se även

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exporterar det angivna PDF‑formulärfältet till JSON‑format och skriver resultatet till den angivna filen.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| `fileName` | String | Namnet på filen att skriva JSON-utdata till. |
| options | ExportFieldsToJsonOptions | Valfria inställningar för export av formulärfältet till JSON. |

### Returvärde

En samling av [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) som indikerar resultatet av exportoperationen för det angivna formulärfältet och dess underordnade element, om sådana finns.

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### Se även

* class [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


