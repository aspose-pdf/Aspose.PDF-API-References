---
title: "Form.ExportJson"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form metod. Exporterar innehållet i alla fält i dokumentet till en JSON-ström. Värden för knappfält exporteras inte."
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson method

Exporterar innehållet i alla fält i dokumentet till en JSON-ström. Värden för knappfält exporteras inte.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputJsonStream | Stream | Den utgående JSON-strömmen där dokumentets fältdata kommer att skrivas. |
| indenterad | Boolean | Valfritt. Anger om JSON-utdata ska vara indenterad för bättre läsbarhet. Standardvärdet är true. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


