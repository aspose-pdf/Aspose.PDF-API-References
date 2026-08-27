---
title: "Field.ExportValueToJson"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Field-metod. Exporterar innehållet i det angivna fältet till en JSON-ström. Värden för knappfält exporteras inte"
type: docs
weight: 180
url: /sv/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson method

Exporterar innehållet i det angivna fältet till en JSON‑ström. Värdet för knappfält exporteras inte.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputJsonStream | Stream | Utdata-JSON-strömmen där fältdata kommer att skrivas. |
| indenterad | Boolean | Valfritt. Anger om JSON-utdata ska vara indenterad för bättre läsbarhet. Standardvärdet är true. |

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### Se även

* class [Field](../)
* namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* assembly [Aspose.PDF](../../../)


