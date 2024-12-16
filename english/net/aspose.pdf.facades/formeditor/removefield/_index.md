---
title: FormEditor.RemoveField
second_title: Aspose.PDF for .NET API Reference
description: FormEditor method. Remove field from the form
type: docs
weight: 210
url: /net/aspose.pdf.facades/formeditor/removefield/
---
## FormEditor.RemoveField method

Remove field from the form.

```csharp
public void RemoveField(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of the field which must be removed. |

## Examples

```csharp
FormEditr formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveField.pdf");
formEditor.RemoveField("listboxField");
formEditor.RemoveField("textField");
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


