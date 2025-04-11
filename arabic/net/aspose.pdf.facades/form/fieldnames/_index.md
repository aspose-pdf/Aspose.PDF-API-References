---
title: Form.FieldNames
second_title: Aspose.PDF for .NET API Reference
description: خاصية النموذج. تحصل على قائمة بأسماء الحقول في النموذج
type: docs
weight: 30
url: /ar/net/aspose.pdf.facades/form/fieldnames/
---
## خاصية Form.FieldNames

تحصل على قائمة بأسماء الحقول في النموذج.

```csharp
public string[] FieldNames { get; }
```

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
string[] fields = form.FieldNames;
foreach(string field in fields)
{
  Console.WriteLine(field);
}
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)