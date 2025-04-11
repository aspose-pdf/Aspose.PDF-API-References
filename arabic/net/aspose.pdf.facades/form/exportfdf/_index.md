---
title: Form.ExportFdf
second_title: Aspose.PDF for .NET API Reference
description: طريقة النموذج. تصدر محتوى حقول pdf إلى تدفق fdf
type: docs
weight: 70
url: /ar/net/aspose.pdf.facades/form/exportfdf/
---
## طريقة Form.ExportFdf

تصدر محتوى حقول pdf إلى تدفق fdf.

```csharp
public void ExportFdf(Stream outputFdfStream)
```

| المعامل | النوع | الوصف |
| --- | --- | --- |
| outputFdfStream | Stream | تدفق fdf الناتج. |

## أمثلة

```csharp
Form form = new Form("PdfForm.pdf");
Stream stream = new FileStream("export.fdf", FileMode.Create, FileAccess.Write);
form.ExportFdf(stream);
stream.Close();
```

### انظر أيضًا

* class [Form](../)
* namespace [Aspose.Pdf.Facades](../../../aspose.pdf.facades/)
* assembly [Aspose.PDF](../../../)