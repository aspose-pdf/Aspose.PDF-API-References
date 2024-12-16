---
title: FormEditor.SetSubmitFlag
second_title: Aspose.PDF for .NET API Reference
description: FormEditor method. Set submit flag of submit button
type: docs
weight: 330
url: /net/aspose.pdf.facades/formeditor/setsubmitflag/
---
## FormEditor.SetSubmitFlag method

Set submit flag of submit button.

```csharp
public bool SetSubmitFlag(string fieldName, SubmitFormFlag submitFormFlag)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Name of submit button. |
| submitFormFlag | SubmitFormFlag | Submit flag. |

### Return Value

true if field was found and submit flag was successfully set.

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitFlag.pdf");
formEditor.SetSubmitFlag("btnSubmit", SubmitFormFlag.Fdf);
```

### See Also

* enum [SubmitFormFlag](../../submitformflag/)
* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


