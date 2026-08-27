---
title: "Form.ExportXml"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Formulärmetod. Exporterar innehållet i fälten i pdf-filen till xml‑strömmen. Värdet för knappraderna exporteras inte."
type: docs
weight: 100
url: /sv/net/aspose.pdf.facades/form/exportxml/
---
## Form.ExportXml method

Exporterar innehållet i pdf-fältens data till xml-strömmen. Värdet för knappfältet exporteras inte.

```csharp
public void ExportXml(Stream outputXmlStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputXmlStream | Stream | Utdata Xml‑ström. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf"));
FileStream fs = new FileStream("export.xml", FileMode.Create, FileAccess.Write);
form.ExportXml(fs);
fs.Close();
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


