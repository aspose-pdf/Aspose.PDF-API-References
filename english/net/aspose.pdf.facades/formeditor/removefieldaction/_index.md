---
title: "FormEditor.RemoveFieldAction"
linktitle: "RemoveFieldAction"
articleTitle: "RemoveFieldAction"
second_title: "Aspose.PDF for .NET API Reference"
description: "FormEditor method. Remove submit action of the field."
type: docs
weight: 250
url: "/net/aspose.pdf.facades/formeditor/removefieldaction/"
product_version: "26.9"
---
## FormEditor.RemoveFieldAction method

Remove submit action of the field.

```csharp
public void RemoveFieldAction(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of the field. |

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_RemoveFieldAction.pdf");
formEditor.RemoveFieldAction("btnSubmit");
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

