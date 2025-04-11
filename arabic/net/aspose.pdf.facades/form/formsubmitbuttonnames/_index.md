---
title: Form.FormSubmitButtonNames
second_title: Aspose.PDF for .NET API Reference
description: خاصية النموذج. تحصل على جميع أسماء أزرار إرسال النموذج
type: docs
weight: 40
url: /ar/net/aspose.pdf.facades/form/formsubmitbuttonnames/
---
## خاصية Form.FormSubmitButtonNames

تحصل على جميع أسماء أزرار إرسال النموذج.

```csharp
public string[] FormSubmitButtonNames { get; }
```

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
string[] submits = form.FormSubmitButtonNames;
foreach(string btn in submits)
{
  Console.WriteLine(btn);
}
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)