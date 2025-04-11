---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: WidgetAnnotation-metod. Exporterar det angivna PDF-formulärfältet till JSON-format och skriver resultatet till den angivna strömmen
type: docs
weight: 120
url: /sv/net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exporterar det angivna PDF-formulärfältet till JSON-format och skriver resultatet till den angivna strömmen.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| stream | Stream | Strömmen att skriva JSON-utdata till. |
| options | ExportFieldsToJsonOptions | Valfria inställningar för att exportera formulärfältet till JSON. |

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

### Se Även

* klass [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* klass [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* klass [WidgetAnnotation](../)
* namnrymd [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exporterar det angivna PDF-formulärfältet till JSON-format och skriver resultatet till den angivna filen.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fileName | String | Namnet på filen att skriva JSON-utdata till. |
| options | ExportFieldsToJsonOptions | Valfria inställningar för att exportera formulärfältet till JSON. |

### Returvärde

En samling av [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) som indikerar resultatet av exportoperationen för det angivna formulärfältet och dess underordnade element, om sådana finns.

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### Se Även

* klass [FieldSerializationResult](../../../aspose.pdf/fieldserializationresult/)
* klass [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* klass [WidgetAnnotation](../)
* namnrymd [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)