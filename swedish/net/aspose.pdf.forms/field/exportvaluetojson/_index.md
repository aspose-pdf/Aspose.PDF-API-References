---
title: Field.ExportValueToJson
second_title: Aspose.PDF for .NET API Reference
description: Fältmetod. Exporterar innehållet i det angivna fältet till en JSON-ström. Värden för knappfält exporteras inte
type: docs
weight: 180
url: /sv/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson metod

Exporterar innehållet i det angivna fältet till en JSON-ström. Värden för knappfält exporteras inte.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputJsonStream | Stream | Den utgående JSON-strömmen där fältdata kommer att skrivas. |
| indented | Boolean | Valfritt. Anger om JSON-utdata ska vara indenterad för bättre läsbarhet. Standardvärdet är sant. |

## Exempel

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### Se Även

* klass [Field](../)
* namnrymd [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* sammansättning [Aspose.PDF](../../../)