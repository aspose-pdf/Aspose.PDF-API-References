---
title: RenameField
second_title: Aspose.PDF for .NET API Reference
description: Change name of the field.
type: docs
weight: 270
url: /net/aspose.pdf.facades/formeditor/renamefield/
---
## FormEditor.RenameField method

Change name of the field.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Old name of the field. |
| newFieldName | String | New name of the field. |

### Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.RenameField("textField", "textField_Renamed");
```

### See Also

* class [FormEditor](../../formeditor)
* namespace [Aspose.Pdf.Facades](../../formeditor)
* assembly [Aspose.PDF](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.PDF.dll -->