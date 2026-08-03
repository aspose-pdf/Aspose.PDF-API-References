---
title: "Form.GetFieldFlag"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Formulärmetod. Returnerar flaggor för fältet"
type: docs
weight: 220
url: /sv/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag method

Returnerar fältets flaggor.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Fältnamn |

### Returvärde

Egenskapsflagga (ReadOnly/ Required/NoExport

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### Se även

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


