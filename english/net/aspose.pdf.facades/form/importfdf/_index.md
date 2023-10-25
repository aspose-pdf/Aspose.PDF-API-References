---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: Form method. Imports the content of the fields from the fdf file and put them into the new pdf
type: docs
weight: 310
url: /net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf method

Imports the content of the fields from the fdf file and put them into the new pdf.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputFdfStream | Stream | The input fdf stream. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


