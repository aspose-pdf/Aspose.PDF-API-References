---
title: FormEditor.SetFieldCombNumber
second_title: Aspose.PDF for .NET API Reference
description: FormEditor method. Sets number of combs for a regular singleline text field the field is automatically divided into as many equally spaced positions or combs as the value of combNumber parameter
type: docs
weight: 300
url: /net/aspose.pdf.facades/formeditor/setfieldcombnumber/
---
## FormEditor.SetFieldCombNumber method

Sets number of combs for a regular single-line text field (the field is automatically divided into as many equally spaced positions, or combs, as the value of combNumber parameter).

```csharp
public bool SetFieldCombNumber(string fieldName, int combNumber)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |
| combNumber | Int32 | The number of combs to divide the field into. |

### Return Value

If success, return true;else false.

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfWithAcroForm.pdf", "FormEditor_SetFieldComb.pdf"));
formEditor.SetFieldCombNumber("textCombField", 5);
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


