---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Importiert den Inhalt der Felder aus der fdf-Datei und fügt sie in das neue pdf ein.
type: docs
weight: 280
url: /de/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf-Methode

Importiert den Inhalt der Felder aus der fdf-Datei und fügt sie in das neue pdf ein.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputFdfStream | Stream | Der Eingabe-fdf-Stream. |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)