---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: Form method. Exports the content of the fields of the pdf into the fdf stream
type: docs
weight: 110
url: /net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf method

Exports the content of the fields of the pdf into the fdf stream.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputFdfStream | Stream | The output fdf stream. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


