---
title: FormEditor.SetFieldAlignmentV
second_title: Aspose.PDF for .NET API Reference
description: FormEditor method. Set the vertical alignment style of a text field
type: docs
weight: 310
url: /net/aspose.pdf.facades/formeditor/setfieldalignmentv/
---
## FormEditor.SetFieldAlignmentV method

Set the vertical alignment style of a text field.

```csharp
public bool SetFieldAlignmentV(string fieldName, int alignment)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |
| alignment | Int32 | The alignment style definition, including FormFieldFacade.AlignTop, FormFieldFacade.AlignMiddle and FormFieldFacade.AlignRight. |

### Return Value

true if field was found and alignment was successfully filled.

## Examples

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignmentV("form1[0].TextField[0]", FormFieldFacade.AlignBottom);
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


