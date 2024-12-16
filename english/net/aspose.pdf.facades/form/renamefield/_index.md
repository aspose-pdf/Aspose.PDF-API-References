---
title: Form.RenameField
second_title: Aspose.PDF for .NET API Reference
description: Form method. Renames a field. Either AcroForm field or XFA field is OK
type: docs
weight: 330
url: /net/aspose.pdf.facades/form/renamefield/
---
## Form.RenameField method

Renames a field. Either AcroForm field or XFA field is OK.

```csharp
public void RenameField(string fieldName, string newFieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | the old field name |
| newFieldName | String | the new field name |

## Examples

```csharp
Form form = new Form("PdfForm.pdf", "PdfFormUpdated.pdf");
form.RenameField("field", "field1");
form.Save();
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


