---
title: Form.ImportFdf
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Importerar innehållet i fälten från fdf-filen och lägger dem i den nya pdfen
type: docs
weight: 280
url: /sv/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf metod

Importerar innehållet i fälten från fdf-filen och lägger dem i den nya pdf:en.

```csharp
public void ImportFdf(Stream inputFdfStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputFdfStream | Stream | Den inmatade fdf-strömmen. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "PdfForm_imported.pdf");
form.ImportFdf(new FileStream("data.fdf", FileMode.Open, FileAccess.Read));
form.Save();
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)