---
title: "Form.ExportXfdf"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Formulärmetod. Exporterar innehållet i fälten i pdf-filen till xml‑strömmen. Värdet för knappraderna exporteras inte."
type: docs
weight: 90
url: /sv/net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf method

Exporterar innehållet i pdf-fältens data till xml-strömmen. Värdet för knappfältet exporteras inte.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputXfdfStream | Stream | Utdata‑xml‑strömmen. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


