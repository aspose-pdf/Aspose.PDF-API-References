---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: Form method. Imports all field data from a JSON stream into the document fields matching the fields by their full names
type: docs
weight: 290
url: /net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson method

Imports all field data from a JSON stream into the document fields, matching the fields by their full names.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputJsonStream | Stream | The input JSON stream containing the field data to be imported into the document fields. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


