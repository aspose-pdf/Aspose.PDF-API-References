---
title: Form.GetFieldType
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Gibt den Typ des Feldes zurück
type: docs
weight: 240
url: /de/net/aspose.pdf.facades/form/getfieldtype/
---
## Form.GetFieldType-Methode

Gibt den Typ des Feldes zurück.

```csharp
public FieldType GetFieldType(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Feldname. |

### Rückgabewert

Element der FileType-Enumeration, das dem Feldtyp entspricht.

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldType("textField") == FieldType.Text)
{
   Console.WriteLine("Type of field is text");
}
```

### Siehe auch

* enum [FieldType](../../fieldtype/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)