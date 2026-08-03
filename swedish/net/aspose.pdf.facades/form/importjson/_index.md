---
title: "Form.ImportJson"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Formulärmetod. Importerar all fältdata från en JSON‑ström till dokumentfälten som matchar fälten efter deras fullständiga namn"
type: docs
weight: 290
url: /sv/net/aspose.pdf.facades/form/importjson/
---
## Form.ImportJson method

Importerar all fältdata från en JSON-ström till dokumentets fält, genom att matcha fälten efter deras fullständiga namn.

```csharp
public void ImportJson(Stream inputJsonStream)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| inputJsonStream | Stream | Ingångs‑JSON‑strömmen som innehåller fältdata som ska importeras till dokumentfälten. |

## Exempel

```csharp
Form form = new Form("PdfForm.pdf", "Form_ImportJson.pdf");
Stream fs = new FileStream("export_old.json", FileMode.Open, FileAccess.Read);
form.ImportJson(fs);
fs.Close();
form.Save();
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


