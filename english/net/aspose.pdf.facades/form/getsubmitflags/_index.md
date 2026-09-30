---
title: "Form.GetSubmitFlags"
linktitle: "GetSubmitFlags"
articleTitle: "GetSubmitFlags"
second_title: "Aspose.PDF for .NET API Reference"
description: "Form method. Returns the submit button's submission flags"
type: docs
weight: 340
url: "/net/aspose.pdf.facades/form/getsubmitflags/"
product_version: "26.9.0"
---
## Form.GetSubmitFlags method

Returns the submit button's submission flags

```csharp
public SubmitFormFlag GetSubmitFlags(string fieldName)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | The qualified field name. |

### Return Value

Submission flags of the button.

## Examples

```csharp
Aspose.Pdf.Facades.Form form = new Aspose.Pdf.Facades.Form("PdfForm.pdf");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Xfdf )!= 0 ? " XFDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Fdf )!= 0 ? " FDF" : " ");
System.Console.WriteLine((form.GetSubmitFlags("btnSubmit") | Aspose.Pdf.Facades.SubmitFormFlag.Pdf )!= 0 ? " PDF" : " ");
```

### See Also

* enum [SubmitFormFlag](../../../aspose.pdf.facades/submitformflag/)
* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)

