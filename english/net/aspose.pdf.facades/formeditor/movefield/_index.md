---
title: FormEditor.MoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor method. Set new position of field
type: docs
weight: 200
url: /net/aspose.pdf.facades/formeditor/movefield/
---
## FormEditor.MoveField method

Set new position of field.

```csharp
public bool MoveField(string fieldName, float llx, float lly, float urx, float ury)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of field which must be moved. |
| llx | Single | Abscissa of the lower-left corner of the field. |
| lly | Single | Ordinate of the lower-left coerner of the field. |
| urx | Single | Abscissa of the upper-right corner of the field. |
| ury | Single | Ordinate of the upper-right corner of the field. |

### Return Value

true if field position was changed successfully.

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_MoveField.pdf");
formEditor.MoveField("textField", 20.5f, 20.3f, 120.6f, 40.8f);
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


