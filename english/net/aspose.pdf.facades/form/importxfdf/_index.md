---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Form method. Imports the content of the fields from the xfdfxml file and put them into the new pdf
type: docs
weight: 320
url: /net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf method

Imports the content of the fields from the xfdf(xml) file and put them into the new pdf.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| inputXfdfStream | Stream | The input xfdf(xml) stream. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


