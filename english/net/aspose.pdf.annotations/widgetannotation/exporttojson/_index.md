---
title: "WidgetAnnotation.ExportToJson"
linktitle: "ExportToJson"
articleTitle: "ExportToJson"
second_title: "Aspose.PDF for .NET API Reference"
description: "WidgetAnnotation method. Exports the specified PDF form field to JSON format and writes the result to the provided stream."
type: docs
weight: 40
url: "/net/aspose.pdf.annotations/widgetannotation/exporttojson/"
product_version: "26.9.0"
---
## ExportToJson(Stream, [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)) {#exporttojson}

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

A collection of [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indicating the result of the export operation for the specified form field and its child elements, if present.

### See Also

* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)) {#exporttojson_1}

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

A collection of [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indicating the result of the export operation for the specified form field and its child elements, if present.

### See Also

* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [WidgetAnnotation](../)
* namespace [Aspose.Pdf.Annotations](../../../aspose.pdf.annotations/)
* assembly [Aspose.PDF](../../../)

