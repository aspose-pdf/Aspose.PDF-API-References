---
title: Form.FillBarcodeField
second_title: Aspose.PDF for .NET API Reference
description: Form method. Fill a barcode field according to its fully qualified field name
type: docs
weight: 120
url: /net/aspose.pdf.facades/form/fillbarcodefield/
---
## Form.FillBarcodeField method

Fill a barcode field according to its fully qualified field name.

```csharp
public bool FillBarcodeField(string fieldName, string data)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The fully qualified field name. |
| data | String | The new barcode value. |

### Return Value

If filling succeed, return true; otherwise, false.

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
form.FillBarcodeField("textField", "42207252");
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


