---
title: FormEditor.SetSubmitUrl
second_title: Aspose.PDF for .NET API Reference
description: FormEditor method. Sets URL of the button
type: docs
weight: 380
url: /net/aspose.pdf.facades/formeditor/setsubmiturl/
---
## FormEditor.SetSubmitUrl method

Sets URL of the button.

```csharp
public bool SetSubmitUrl(string fieldName, string url)
```

| Parameter | Type | Description |
| --- | --- | --- |
| fieldName | String | Submit button name. |
| url | String | Fully qualified URL. |

### Return Value

true if URL for button was successfully set.

## Examples

```csharp
FormEditor formEditor = new FormEditor("PdfForm.pdf", "FormEditor_SetSubmitUrl.pdf");
formEditor.SetSubmitUrl("btnSubmit", "www.mysite.com");
```

### See Also

* class [FormEditor](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)


