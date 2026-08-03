---
title: "Form.ImportXfdf"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form metod. Importerar innehållet i fälten från xfdfxml-filen och placerar dem i den nya pdf-filen"
type: docs
weight: 300
url: /sv/net/aspose.pdf.facades/form/importxfdf/
---
## Form.ImportXfdf method

Importerar fältens innehåll från xfdf(xml)-filen och placerar dem i den nya pdf-filen.

```csharp
public void ImportXfdf(Stream inputXfdfStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputXfdfStream | Stream | Den inmatade xfdf(xml)-strömmen. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportXfdf.pdf");
Stream fs = new FileStream("export_old.xfdf", FileMode.Open, FileAccess.Read);
form.ImportXfdf(fs);
fs.Close();
form.Save();
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


