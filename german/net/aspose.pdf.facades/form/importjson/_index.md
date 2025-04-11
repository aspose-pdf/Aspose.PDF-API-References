---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Importiert alle Felddaten aus einem JSON-Stream in die Dokumentfelder, indem die Felder anhand ihrer vollständigen Namen zugeordnet werden.
type: docs
weight: 290
url: /de/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson-Methode

Importiert alle Felddaten aus einem JSON-Stream in die Dokumentfelder, indem die Felder anhand ihrer vollständigen Namen zugeordnet werden.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputJsonStream | Stream | Der Eingabe-JSON-Stream, der die Felddaten enthält, die in die Dokumentfelder importiert werden sollen. |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)