---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Exporterar innehållet i fälten i pdf:en till fdf-strömmen
type: docs
weight: 70
url: /sv/net/aspose.pdf.facades/form/exportfdf/
---
## Form.ExportFdf metod

Exporterar innehållet i fälten i pdf:en till fdf-strömmen.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| outputFdfStream | Stream | Den utgående fdf-strömmen. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)