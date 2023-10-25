---
title: FormEditor.SetFieldAlignment
second_title: Aspose.PDF for .NET API Reference
description: FormEditor method. Set the alignment style of a text field
type: docs
weight: 300
url: /net/aspose.pdf.facades/formeditor/setfieldalignment/
---
## FormEditor.SetFieldAlignment method

Set the alignment style of a text field.

```csharp
public bool SetFieldAlignment(string fieldName, int alignment)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |
| alignment | Int32 | The alignment style definition, including FormFieldFacade.AlignLeft, FormFieldFacade.AlignCenter and FormFieldFacade.AlignRight. |

### Return Value

true if true if field was found and alignment was set.

## Examples

```csharp
FormEditor fe = new FormEditor("PdfStaticForm.pdf", "VerticalAlign.pdf");
fe.SetFieldAlignment("form1[0].TextField[0]", FormFieldFacade.AlignLeft);
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


