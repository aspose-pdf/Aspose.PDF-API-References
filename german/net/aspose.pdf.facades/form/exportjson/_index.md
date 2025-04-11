---
title: Form.ExportJson
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Exportiert den Inhalt aller Felder im Dokument in einen JSON-Stream. Werte von Schaltflächenfeldern werden nicht exportiert
type: docs
weight: 80
url: /de/net/aspose.pdf.facades/form/exportjson/
---
## Form.ExportJson-Methode

Exportiert den Inhalt aller Felder im Dokument in einen JSON-Stream. Werte von Schaltflächenfeldern werden nicht exportiert.

```csharp
public void ExportJson(Stream outputJsonStream, bool indented = true)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputJsonStream | Stream | Der Ausgabestream für JSON, in den die Felddaten des Dokuments geschrieben werden. |
| indented | Boolean | Optional. Gibt an, ob die JSON-Ausgabe für eine bessere Lesbarkeit eingerückt werden soll. Der Standardwert ist true. |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.json", FileMode.Create, FileAccess.Write);
form.ExportJson(fs);
fs.Close();
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)