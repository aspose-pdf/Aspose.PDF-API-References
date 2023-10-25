---
title: Form.FillFields
second_title: Aspose.PDF for .NET API Reference
description: Form method. Fills the text box fields with a text values and save the document. Relevant for signed documents. Notice Only be applied to Text Box. Both the fields name and values are case sensitive
type: docs
weight: 170
url: /net/aspose.pdf.facades/form/fillfields/
---
## Form.FillFields method

Fills the text box fields with a text values and save the document. Relevant for signed documents. Notice: Only be applied to Text Box. Both the fields' name and values are case sensitive.

```csharp
public bool FillFields(string[] fieldNames, string[] fieldValues, out Stream output)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldNames | String[] | Names of fields. |
| fieldValues | String[] | New values of the fields. |
| output | Stream& | Stream where document will be saved. |

### Return Value

true if fields was found and successfully filled.

## Examples

```csharp
var form = new Form(dataDir + "SignedPdfForm.pdf");
Stream stream; 
form.FillFields(new string[] {"Field1"}, new string[] {"+"}, out stream);
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


