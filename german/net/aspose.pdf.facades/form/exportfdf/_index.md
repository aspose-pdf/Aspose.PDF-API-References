---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Exportiert den Inhalt der Felder des PDFs in den FDF-Stream
type: docs
weight: 70
url: /de/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf-Methode

Exportiert den Inhalt der Felder des PDFs in den FDF-Stream.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputFdfStream | Stream | Der Ausgabefdf-Stream. |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)