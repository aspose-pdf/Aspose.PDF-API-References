---
title: Form.ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Exportiert den Inhalt der Felder des PDFs in den XML-Stream. Der Wert der Schaltflächenfelder wird nicht exportiert.
type: docs
weight: 90
url: /de/net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf-Methode

Exportiert den Inhalt der Felder des PDFs in den XML-Stream. Der Wert des Schaltflächenfeldes wird nicht exportiert.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| outputXfdfStream | Stream | Der Ausgabestream im XML-Format. |

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### Siehe auch

* Klasse [Form](../)
* Namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* Assembly [Aspose.PDF](../../../)