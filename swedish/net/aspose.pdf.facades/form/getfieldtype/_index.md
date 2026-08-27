---
title: "Form.GetFieldType"
second_title: "Aspose.PDF för .NET API‑referens"
description: "Formulärmetod. Returnerar fälttypen"
type: docs
weight: 240
url: /sv/net/aspose.pdf.facades/form/getfieldtype/
---
## Form.GetFieldType method

Returnerar fälttypen.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Fältnamn. |

### Returvärde

Element i FileType‑uppräkning som motsvarar fälttypen.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### Se även

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


