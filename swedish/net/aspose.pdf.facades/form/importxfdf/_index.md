---
title: ImportXfdf
second_title: Aspose.PDF för .NET API Referens
description: Importerar innehållet i fälten från xfdfxml-filen och lägger in dem i den nya pdf.
type: docs
weight: 320
url: /sv/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf method

Importerar innehållet i fälten från xfdf(xml)-filen och lägger in dem i den nya pdf.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputXfdfStream | Stream | Ingångsströmmen xfdf(xml). |

### Exempel

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### Se även

* class [Form](../../form)
* namnutrymme [Aspose.Pdf.Facades](../../form)
* hopsättning [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->