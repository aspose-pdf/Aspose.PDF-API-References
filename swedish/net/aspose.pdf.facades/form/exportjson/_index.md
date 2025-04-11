---
title: Form.ExportJson
second_title: Aspose.PDF for .NET API Reference
description: Formulärmetod. Exporterar innehållet i alla fält i dokumentet till en JSON-ström. Värden för knappfält exporteras inte
type: docs
weight: 80
url: /sv/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson metod

Exporterar innehållet i alla fält i dokumentet till en JSON-ström. Värden för knappfält exporteras inte.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputJsonStream | Stream | Den utgående JSON-strömmen där dokumentets fältdat kommer att skrivas. |
| indented | Boolean | Valfritt. Anger om JSON-utdata ska vara indenterad för bättre läsbarhet. Standardvärdet är sant. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)