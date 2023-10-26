---
title: Form.ExportXml
second_title: Aspose.PDF for .NET API Reference
description: Form method. Exports the content of the fields of the pdf into the xml stream. The button fields value will not be exported
type: docs
weight: 130
url: /net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml method

Exports the content of the fields of the pdf into the xml stream. The button field's value will not be exported.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Parameter | Type | Description |
| --- | --- | --- |
| outputXmlStream | Stream | Output Xml stream. |

## Examples

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


