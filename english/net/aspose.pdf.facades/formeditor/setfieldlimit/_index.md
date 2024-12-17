---
title: FormEditor.SetFieldLimit
second_title: Aspose.PDF for .NET API Reference
description: FormEditor method. Sets maximum character count of the text field
type: docs
weight: 310
url: /net/aspose.pdf.facades/formeditor/setfieldlimit/
---
## FormEditor.SetFieldLimit method

Sets maximum character count of the text field.

```csharp
public bool SetFieldLimit(string fieldName, int fieldLimit)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of the text field. |
| fieldLimit | Int32 | New value of limit for the field. |

### Return Value

true if field limit was successfully set.

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetFieldLimit.pdf");
formEditor.SetFieldLimit("textField", 15);
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


