---
title: "Form.ExportFdf"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form-metod. Exporterar innehållet i pdf-fältens data till fdf-strömmen"
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf method

Exporterar innehållet i pdf-fältens data till fdf-strömmen.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFdfStream | Stream | Den utgående fdf-strömmen. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


