---
title: "FormEditor.SetFieldAttribute"
second_title: "Aspose.PDF för .NET API‑referens"
description: "FormEditor-metod. Ställ in attribut för fältet"
type: docs
weight: 290
url: /sv/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## FormEditor.SetFieldAttribute method

Ställ in attribut för fältet.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Parameter | Typ | Beskrivning |
| --- | --- | --- |
| fieldName | String | Namnet på fältet vars attribut ska ställas in. |
| flagga | PropertyFlag | Flag (NoExport/ReadOnly/Required) |

### Returvärde

true om attributet sattes framgångsrikt.

## Exempel

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### Se även

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


