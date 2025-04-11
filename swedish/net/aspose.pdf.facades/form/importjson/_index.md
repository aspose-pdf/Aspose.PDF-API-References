---
title: Form.ImportJson
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Importerar all fältdatainformation från en JSON-ström till dokumentfälten som matchar fälten efter deras fullständiga namn
type: docs
weight: 290
url: /sv/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson metod

Importerar all fältdatainformation från en JSON-ström till dokumentfälten, och matchar fälten efter deras fullständiga namn.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputJsonStream | Stream | Den inmatade JSON-strömmen som innehåller fältdatainformationen som ska importeras till dokumentfälten. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### Se Även

* klass [Form](../)
* namnrymd [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* samling [Aspose.PDF](../../../)