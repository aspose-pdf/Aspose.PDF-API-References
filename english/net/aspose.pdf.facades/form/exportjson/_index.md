---
title: Form.ExportJson
second_title: Aspose.PDF for .NET API Reference
description: Form method. Exports the contents of all fields in the document into a JSON stream. Button field values are not exported
type: docs
weight: 80
url: /net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson method

Exports the contents of all fields in the document into a JSON stream. Button field values are not exported.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputJsonStream | Stream | The output JSON stream where the document's fields data will be written. |
| indented | Boolean | Optional. Specifies whether the JSON output should be indented for better readability. The default value is true. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


