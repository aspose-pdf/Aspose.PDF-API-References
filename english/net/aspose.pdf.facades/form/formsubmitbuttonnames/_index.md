---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: Form property. Gets all form submit button names
type: docs
weight: 60
url: /net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## Form.FormSubmitButtonNames property

Gets all form submit button names.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## Examples

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### See Also

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


