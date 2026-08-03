---
title: "Form.ImportFdf"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form-metod. Importerar innehållet i fälten från fdf-filen och placerar dem i den nya pdf-filen."
type: docs
weight: 280
url: /sv/net/aspose.pdf.facades/form/importfdf/
---
## Form.ImportFdf method

Importerar fältens innehåll från fdf-filen och placerar dem i den nya pdf-filen.

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

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


