---
title: FormEditor.Single2Multiple
second_title: Aspose.PDF for .NET API Reference
description: FormEditor method. Change a singlelined text field to a multiplelined one
type: docs
weight: 350
url: /net/aspose.pdf.facades/formeditor/single2multiple/
---
## FormEditor.Single2Multiple method

Change a single-lined text field to a multiple-lined one.

```csharp
public bool Single2Multiple(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |

### Return Value

If success, return true;else false.

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "PdfForm_updated.pdf");
formEditor.Single2Multiple("textField");
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


