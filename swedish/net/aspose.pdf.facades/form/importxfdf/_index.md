---
title: Form.ImportXfdf
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Importerar innehållet i fälten från xfdfxml-filen och lägger dem i den nya pdf:en
type: docs
weight: 300
url: /sv/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf metod

Importerar innehållet i fälten från xfdf(xml)-filen och lägger dem i den nya pdf:en.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputXfdfStream | Stream | Inmatningsxfdf(xml)-strömmen. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* sammansättning [Aspose.PDF](../../../)