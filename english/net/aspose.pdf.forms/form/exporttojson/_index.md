---
title: "Form.ExportToJson"
linktitle: "ExportToJson"
articleTitle: "ExportToJson"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Exports the PDF form fields to JSON format and writes the result to the provided stream."
type: docs
weight: 160
url: "/net/aspose.pdf.forms/form/exporttojson/"
product_version: "26.9.0"
---
## ExportToJson(Stream, [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)) {#exporttojson}

Exports the PDF form fields to JSON format and writes the result to the provided stream.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(Stream stream, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| stream | Stream | The stream to write the JSON output to. |
| options | ExportFieldsToJsonOptions | Optional settings for exporting the form fields to JSON. |

### Return Value

A collection of [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indicating the result of the export operation for each form field.

### See Also

* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

---

## ExportToJson(string, [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)) {#exporttojson_1}

Exports the PDF form fields to JSON format and writes the result to the specified file.

```csharp
public IEnumerable<FieldSerializationResult> ExportToJson(string fileName, 
    ExportFieldsToJsonOptions options = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fileName | String | The name of the file to write the JSON output to. |
| options | ExportFieldsToJsonOptions | Optional settings for exporting the form fields to JSON. |

### Return Value

A collection of [`FieldSerializationResult`](../../../aspose.pdf/fieldserializationresult/) indicating the result of the export operation for each form field.

### See Also

* class [ExportFieldsToJsonOptions](../../../aspose.pdf/exportfieldstojsonoptions/)
* class [Form](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)

