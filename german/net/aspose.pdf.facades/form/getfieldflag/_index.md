---
title: Form.GetFieldFlag
second_title: Aspose.PDF for .NET API Reference
description: Form-Methode. Gibt die Flags des Feldes zurück
type: docs
weight: 220
url: /de/net/aspose.pdf.facades/form/getfieldflag/
---
## Form.GetFieldFlag-Methode

Gibt die Flags des Feldes zurück.

```csharp
public PropertyFlag GetFieldFlag(string fieldName)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Feldname |

### Rückgabewert

Eigenschaftsflag (ReadOnly/ Required/NoExport

## Beispiele

```csharp
Form form = new Form("PdfForm.pdf");
if (form.GetFieldFlag("textField") == PropertyFlag.ReadOnly)
{
   Console.WriteLine("Field is read-only");
}
```

### Siehe auch

* enum [PropertyFlag](../../propertyflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)