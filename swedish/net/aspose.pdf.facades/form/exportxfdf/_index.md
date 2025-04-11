---
title: Form.ExportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Exporterar innehållet i fälten i pdf:en till xml-strömmen. Värdet av knappfälten kommer inte att exporteras
type: docs
weight: 90
url: /sv/net/aspose.pdf.facades/form/exportxfdf/
---
## Form.ExportXfdf metod

Exporterar innehållet i fälten i pdf:en till xml-strömmen. Värdet av knappfältet kommer inte att exporteras.

```csharp
public void ExportXfdf(Stream outputXfdfStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputXfdfStream | Stream | Den utgående xml-strömmen. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
FileStream fs = new FileStream("export.xfdf", FileMode.Create, FileAccess.Write);
form.ExportXfdf(fs);
fs.Close();
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)