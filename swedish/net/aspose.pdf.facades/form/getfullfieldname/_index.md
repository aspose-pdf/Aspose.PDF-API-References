---
title: "Form.GetFullFieldName"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Form-metod. Hämtar det fullständiga fältnamnet enligt dess korta fältnamn"
type: docs
weight: 250
url: /sv/net/aspose.pdf.facades/form/getfullfieldname/
---
## Form.GetFullFieldName method

Hämtar det fullständiga fältnamnet enligt dess korta fältnamn.

```csharp
public string GetFullFieldName(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Det fullständigt kvalificerade fältnamnet. |

### Returvärde

Det fullständiga fältnamnet.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
Console.WriteLine("Full field name is : " + form.GetFullFieldName("textField"));
```

### Se även

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


