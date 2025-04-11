---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: Formmetod. Returnerar typ av fält
type: docs
weight: 240
url: /sv/net/aspose.pdf.facades/form/getfieldtype/
---
## Form.GetFieldType metod

Returnerar typ av fält.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | Sträng | Fältnamn. |

### Returvärde

Element av FileType-uppräkning som motsvarar fälttyp.

## Exempel

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### Se Även

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)