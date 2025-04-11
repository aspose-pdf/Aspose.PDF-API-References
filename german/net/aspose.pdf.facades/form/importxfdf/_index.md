---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Formularmethode. Importiert den Inhalt der Felder aus der xfdfxml-Datei und fügt sie in das neue PDF ein.
type: docs
weight: 300
url: /de/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf-Methode

Importiert den Inhalt der Felder aus der xfdf(xml)-Datei und fügt sie in das neue PDF ein.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| inputXfdfStream | Stream | Der Eingabe-xfdf(xml)-Stream. |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)