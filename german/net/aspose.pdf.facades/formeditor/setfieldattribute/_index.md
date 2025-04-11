---
title: FormEditor.SetFieldAttribute
second_title: Aspose.PDF for .NET API Reference
description: FormEditor-Methode. Setze Attribute des Feldes
type: docs
weight: 290
url: /de/net/aspose.pdf.facades/formeditor/setfieldattribute/
---
## FormEditor.SetFieldAttribute-Methode

Setze Attribute des Feldes.

```csharp
public bool SetFieldAttribute(string fieldName, PropertyFlag flag)
```

| Parameter | Typ | Beschreibung |
| --- | --- | --- |
| fieldName | String | Name des Feldes, dessen Attribute gesetzt werden sollen. |
| flag | PropertyFlag | Flag (NoExport/ReadOnly/Required) |

### Rückgabewert

true, wenn das Attribut erfolgreich gesetzt wurde.

## Beispiele

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf",  "PdfForm_SetFieldAttribute.pdf");
formEditor.SetFieldAttribute("listboxField", PropertyFlag.ReadOnly);
formEditor.SetFieldAttribute("textField", PropertyFlag.NoExport);
```

### Siehe auch

* enum [PropertyFlag](../../propertyflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)