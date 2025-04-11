---
title: Field.ExportValueToJson
second_title: Aspose.PDF for .NET API Reference
description: Feldmethode. Exportiert den Inhalt des angegebenen Feldes in einen JSON-Stream. Werte von Schaltflächenfeldern werden nicht exportiert
type: docs
weight: 180
url: /de/net/aspose.pdf.forms/field/exportvaluetojson/
---
## Field.ExportValueToJson-Methode

Exportiert den Inhalt des angegebenen Feldes in einen JSON-Stream. Werte von Schaltflächenfeldern werden nicht exportiert.

```csharp
public void ExportValueToJson(Stream outputJsonStream, bool indented = true)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputJsonStream | Stream | Der Ausgabestream für JSON, in den die Felddaten geschrieben werden. |
| indented | Boolean | Optional. Gibt an, ob die JSON-Ausgabe zur besseren Lesbarkeit eingerückt werden soll. Der Standardwert ist true. |

## Beispiele

```csharp
Document document = new Document("PdfDoc.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
Field field = document.Form.Fields[0];
field.ExportValueToJson(fs);
fs.Close();
```

### Siehe auch

* Klasse [Field](../)
* Namespace [Aspose.Pdf.Forms](../../../aspose.pdf.forms/)
* Assembly [Aspose.PDF](../../../)