---
title: FormEditor.SetFieldAttribute
second_title: Aspose.PDF for .NET API Reference
description: FormEditor metod. Ställ in attribut för fält
type: docs
weight: 290
url: /sv/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## FormEditor.SetFieldAttribute metod

Ställ in attribut för fält.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namn på fältet vars attribut ska ställas in. |
| flag | PropertyFlag | Flagga (NoExport/ReadOnly/Required) |

### Returvärde

true om attributet ställdes in framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### Se Även

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)