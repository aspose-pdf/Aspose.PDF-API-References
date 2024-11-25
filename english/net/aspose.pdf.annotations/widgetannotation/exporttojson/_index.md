---
title: WidgetAnnotation.ExportToJson
second_title: Aspose.PDF for .NET API Reference
description: WidgetAnnotation method. Exports the specified PDF form field to JSON format and writes the result to the provided stream
type: docs
weight: 120
url: /net/aspose.pdf.annotations/widgetannotation/exporttojson/
---
## ExportToJson(Stream, ExportFieldsToJsonOptions) {#exporttojson}

Exports the specified PDF form field to JSON format and writes the result to the provided stream.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write the JSON output to. |
| options | ExportFieldsToJsonOptions | Optional settings for exporting the form field to JSON. |

### Return Value

A collection of [`FieldSerializationResult`](../../../aspose.pdf.engine.io.convertstrategies.converthelpers/fieldserializationresult/) indicating the result of the export operation for the specified form field and its child elements, if present.

## Examples

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(fs);
fs.Close();
```

### See Also

* class [FieldSerializationResult](../../../aspose.pdf.engine.io.convertstrategies.converthelpers/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf.engine.io.convertstrategies.converthelpers/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, ExportFieldsToJsonOptions) {#exporttojson_1}

Exports the specified PDF form field to JSON format and writes the result to the specified file.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The name of the file to write the JSON output to. |
| options | ExportFieldsToJsonOptions | Optional settings for exporting the form field to JSON. |

### Return Value

A collection of [`FieldSerializationResult`](../../../aspose.pdf.engine.io.convertstrategies.converthelpers/fieldserializationresult/) indicating the result of the export operation for the specified form field and its child elements, if present.

## Examples

```csharp
Document document = new Document("PdfDoc.pdf");
string jsonPath = "export.json";
WidgetAnnotation annotation = document.Form[1];
annotation.ExportToJson(jsonPath);
```

### See Also

* class [FieldSerializationResult](../../../aspose.pdf.engine.io.convertstrategies.converthelpers/fieldserializationresult/)
* class [ExportFieldsToJsonOptions](../../../aspose.pdf.engine.io.convertstrategies.converthelpers/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)


